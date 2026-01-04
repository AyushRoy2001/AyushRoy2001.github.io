<link rel="stylesheet" href="style.css">
<button class="theme-switcher" onclick="toggleTheme()" title="Toggle Dark/Light Mode">🌓</button>

**[News](news.md)** | **[Experience](experience.md)** | **[Publications](publications.md)** | **[Hackathons](hackathons.md)** |

## News 👀 <a id="news"></a>

<div class="news-container">
  <div class="news-item">
    📳 **<code style="color: #FC465B">One papers have been accepted for presentation at AAAI Workshop 2026 to be held in Singapore on January 26, 2025.</code>**
  </div>
  
  <div class="news-item">
    📳 **<code style="color: Green">Started my PhD on August 17, 2024 under the supervision of Prof. Vishnu Lokhande at the University of Buffalo (SUNY).</code>**
  </div>
  
  <div class="news-item">
    📳 **<code style="color: #FC465B">Three papers have been accepted for presentation at the ICPR 2024 to be held in Kolkata, India on December 01 – 05, 2024.</code>**
  </div>
  
  <div class="news-item">
    📳 **<code style="color: Green">Completed by Bachelor's in Electrical Engineering from Jadavpur University.</code>**
  </div>
  
  <div class="news-item">
    📳 **<code style="color: #FC465B">Three papers have been accepted for presentation at ICPR 2024 to be held in Kolkata, India on December 01 – 05, 2024.</code>**
  </div>
  
  <div class="news-item">
    📳 **<code style="color: #FC465B">One paper has been accepted for presentation at MIUA 2024 to be held in Manchester, England on July 24 – 26, 2024.</code>**
  </div>
  
  <div class="news-item">
    📳 **<code style="color: #FC465B">Two papers have been accepted for presentation at ISBI 2024 to be held in Athens, Greece on May 27 – 30, 2024.</code>**
  </div>
  
  <div class="news-item">
    📳 **<code style="color: #FC465B">One paper has been accepted for presentation at IEEE CBMS 2024 to be held in Guadalajara, Mexico on June 26 – 28, 2024.</code>**
  </div>
</div>

<script>
// Theme toggle functionality
function toggleTheme() {
  const body = document.body;
  if (body.classList.contains('dark-theme')) {
    body.classList.remove('dark-theme');
    body.classList.add('light-theme');
    localStorage.setItem('theme', 'light');
  } else {
    body.classList.remove('light-theme');
    body.classList.add('dark-theme');
    localStorage.setItem('theme', 'dark');
  }
}

// Load saved theme on page load
document.addEventListener('DOMContentLoaded', function() {
  const savedTheme = localStorage.getItem('theme') || 'light';
  document.body.classList.add(savedTheme + '-theme');
});
</script>



