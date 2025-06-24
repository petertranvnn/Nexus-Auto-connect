# Nexus-Auto-connect
Guide: F12 => console = Paste => enter ok


setInterval(() => {
  const toggleButton = document.getElementById('connect-toggle-button');
  if (toggleButton) {
    const isOff = toggleButton.classList.contains('border-[#79747E]');
    if (isOff) {
      toggleButton.click();
      console.log('⛏️ Mining OFF terdeteksi — tombol otomatis diklik untuk ON.');
    } else {
      console.log('✅ Mining masih aktif.');
    }
  } else {
    console.warn('❌ Tombol tidak ditemukan di halaman.');
  }
}, 1000); // cek setiap 1 detik
