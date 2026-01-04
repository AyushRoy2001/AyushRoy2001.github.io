**[News](news.md)** | **[Experience](experience.md)** | **[Publications](publications.md)** | **[Hackathons](hackathons.md)** |

<style>
/* Force override Jekyll theme styles */
body {
    transition: background-color 0.3s ease, color 0.3s ease !important;
}

body.dark-mode {
    background-color: #222 !important;
    color: #ddd !important;
}

body.dark-mode a {
    color: #add8e6 !important;
}

body.dark-mode h1, 
body.dark-mode h2, 
body.dark-mode h3, 
body.dark-mode h4, 
body.dark-mode h5, 
body.dark-mode h6 {
    color: #F3F606 !important;
}

body.dark-mode code {
    background-color: #333 !important;
    color: #eee !important;
}

.theme-toggle-btn {
    position: fixed !important;
    top: 20px !important;
    right: 20px !important;
    z-index: 9999 !important;
    background: #333 !important;
    color: white !important;
    border: 2px solid #666 !important;
    padding: 10px 15px !important;
    border-radius: 50px !important;
    cursor: pointer !important;
    font-size: 20px !important;
    box-shadow: 0 4px 6px rgba(0,0,0,0.3) !important;
    transition: all 0.3s ease !important;
}

.theme-toggle-btn:hover {
    transform: scale(1.1) !important;
    box-shadow: 0 6px 8px rgba(0,0,0,0.4) !important;
}

body.dark-mode .theme-toggle-btn {
    background: #F3F606 !important;
    color: #222 !important;
    border-color: #F3F606 !important;
}

.news-scroll-container {
    max-height: 500px !important;
    overflow-y: auto !important;
    padding: 20px !important;
    border: 2px solid #333 !important;
    border-radius: 8px !important;
    margin: 20px 0 !important;
    background: #f8f9fa !important;
}

body.dark-mode .news-scroll-container {
    background: #1a1a1a !important;
    border-color: #F3F606 !important;
}

.news-scroll-container::-webkit-scrollbar {
    width: 12px !important;
}

.news-scroll-container::-webkit-scrollbar-track {
    background: #e0e0e0 !important;
    border-radius: 10px !important;
}

body.dark-mode .news-scroll-container::-webkit-scrollbar-track {
    background: #333 !important;
}

.news-scroll-container::-webkit-scrollbar-thumb {
    background: #888 !important;
    border-radius: 10px !important;
}

.news-scroll-container::-webkit-scrollbar-thumb:hover {
    background: #555 !important;
}

body.dark-mode .news-scroll-container::-webkit-scrollbar-thumb {
    background: #F3F606 !important;
}

.news-item-div {
    padding: 12px 0 !important;
    border-bottom: 1px solid rgba(128,128,128,0.3) !important;
}

.news-item-div:last-child {
    border-bottom: none !important;
}
</style>

## News 👀 <a id="news"></a>

<div class="news-scroll-container">
  <div class="news-item-div">
    📳 <strong><code style="color: #FC465B">One papers have been accepted for presentation at AAAI Workshop 2026 to be held in Singapore on January 26, 2025.</code></strong>
  </div>
  
  <div class="news-item-div">
    📳 <strong><code style="color: Green">Started my PhD on August 17, 2024 under the supervision of Prof. Vishnu Lokhande at the University of Buffalo (SUNY).</code></strong>
  </div>
  
  <div class="news-item-div">
    📳 <strong><code style="color: #FC465B">Three papers have been accepted for presentation at the ICPR 2024 to be held in Kolkata, India on December 01 – 05, 2024.</code></strong>
  </div>
  
  <div class="news-item-div">
    📳 <strong><code style="color: Green">Completed by Bachelor's in Electrical Engineering from Jadavpur University.</code></strong>
  </div>
  
  <div class="news-item-div">
    📳 <strong><code style="color: #FC465B">Three papers have been accepted for presentation at ICPR 2024 to be held in Kolkata, India on December 01 – 05, 2024.</code></strong>
  </div>
  
  <div class="news-item-div">
    📳 <strong><code style="color: #FC465B">One paper has been accepted for presentation at MIUA 2024 to be held in Manchester, England on July 24 – 26, 2024.</code></strong>
  </div>
  
  <div class="news-item-div">
    📳 <strong><code style="color: #FC465B">Two papers have been accepted for presentation at ISBI 2024 to be held in Athens, Greece on May 27 – 30, 2024.</code></strong>
  </div>
  
  <div class="news-item-div">
    📳 <strong><code style="color: #FC465B">One paper has been accepted for presentation at IEEE CBMS 2024 to be held in Guadalajara, Mexico on June 26 – 28, 2024.</code></strong>
  </div>
</div>

<script>
// Create toggle button
(function() {
    // Create button element
    var btn = document.createElement('button');
    btn.className = 'theme-toggle-btn';
    btn.innerHTML = '🌓';
    btn.title = 'Toggle Dark/Light Mode';
    btn.onclick = toggleTheme;
    
    // Append to body
    document.body.appendChild(btn);
    
    // Load saved theme
    var savedTheme = localStorage.getItem('theme');
    if (savedTheme === 'dark') {
        document.body.classList.add('dark-mode');
    }
})();

function toggleTheme() {
    var body = document.body;
    if (body.classList.contains('dark-mode')) {
        body.classList.remove('dark-mode');
        localStorage.setItem('theme', 'light');
    } else {
        body.classList.add('dark-mode');
        localStorage.setItem('theme', 'dark');
    }
}
</script>




