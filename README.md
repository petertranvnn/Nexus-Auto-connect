# Nexus-Auto-connect
Guide: F12 => console = Paste => enter ok

```
setInterval(() => {
  const toggleButton = document.getElementById('connect-toggle-button');
  if (toggleButton) {
    const isOff = toggleButton.classList.contains('border-[#79747E]');
    if (isOff) {
      toggleButton.click();
      console.log('ON - OFF Connect');
    } else {
      console.log('active');
    }
  } else {
    console.warn('OFF');
  }
}, 1000); // Check ERR
```
