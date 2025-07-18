document.getElementById('chat-popup').addEventListener('click', function() {
  const chatButtons = document.getElementById('chat-buttons');
  chatButtons.style.display = chatButtons.style.display === 'flex' ? 'none' : 'flex';
});

// Optional auto-popup after 10s
setTimeout(() => {
  document.getElementById('chat-popup').style.display = 'block';
}, 10000);
