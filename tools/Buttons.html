Reusable Runtipi Button Components

These components rely on Tailwind CSS (for utility classes) and Font Awesome (for the GitHub/Star icons). The custom styling for the gradient border and tooltips is included below under Custom CSS.

1. Required Dependencies (Add to your new project's <head>)
You must include these script and link tags in the <head> of your new HTML project:

<!-- Load Tailwind CSS -->
<script src="[https://cdn.tailwindcss.com](https://cdn.tailwindcss.com)"></script>
<!-- Load Font Awesome for icons -->
<link rel="stylesheet" href="[https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css)">

2. Essential Custom CSS (Add to your project's <style> block)
These CSS variables and rules are absolutely essential for the buttons and their hover effects/tooltips to display correctly, especially with the dark/light mode theming.

/* --- Custom Color Variables (Critical for Button Styling) --- */
:root {
    /* General Dark Theme Colors */
    --bg-body: #131313;
    --bg-card: #1F1F1F;
    --color-text-primary: #E2E8F0;
    --color-text-secondary: #94A3B8;
    --color-border: #2D2D2D;

    /* Accents (Used for the gradient border) */
    --color-runtipi-red: #FF66A3;
    --color-runtipi-blue: #6495ED;
}

/* --- Light Theme Overrides (Optional, but needed for proper color transitions) --- */
html[data-theme='light'] {
    --bg-body: #F7F7F7;
    --bg-card: #FFFFFF;
    --color-text-primary: #1F2937;
    --color-text-secondary: #6B7280;
    --color-border: #E5E7EB;
}

/* Apply variables to ensure colors work */
.bg-card-dark { background-color: var(--bg-card); }
.border-dark { border-color: var(--color-border); }

/* --- Gradient Border Button Style (Reusable Class) --- */
.icon-btn-gradient {
    /* Ensures border doesn't shrink on hover */
    border: 1px solid transparent !important; 
    background-color: var(--bg-card);
    color: var(--color-text-primary);
    transition: all 0.2s ease-in-out;
    position: relative;
    box-shadow: none !important;
}

.icon-btn-gradient:hover {
    /* Creates the gradient border effect using border-image */
    border: 1px solid transparent; 
    border-image: linear-gradient(to right, var(--color-runtipi-red), var(--color-runtipi-blue)) 1;
    transform: translateY(-1px);
}

/* --- General Tooltip Style --- */
.icon-btn-gradient .tooltip { 
    visibility: hidden;
    background-color: var(--color-runtipi-red);
    color: #fff;
    text-align: center;
    border-radius: 0.375rem;
    padding: 0.375rem 0.625rem; 
    position: absolute;
    z-index: 20; 
    opacity: 0;
    white-space: nowrap;
    font-size: 0.75rem; 
    font-weight: 500;
    pointer-events: none;
    transition: opacity 0.2s, transform 0.2s;
}

/* Tooltip Arrow */
.icon-btn-gradient .tooltip::after { 
    content: "";
    position: absolute;
    top: 100%;
    left: 50%;
    margin-left: -5px;
    border-width: 5px;
    border-style: solid;
    border-color: var(--color-runtipi-red) transparent transparent transparent;
}

/* Tooltip Visibility on Hover */
.icon-btn-gradient:hover .tooltip { 
    visibility: visible;
    opacity: 1;
}

/* Specific positioning for HEADER elements (Top Button) */
.header-github-btn .tooltip { 
    bottom: auto; 
    top: 100%;
    left: 50%;
    transform: translateX(-50%) translateY(0.5rem);
}

.header-github-btn:hover .tooltip {
    transform: translateX(-50%) translateY(0);
}

/* Specific Arrow direction for HEADER elements */
.header-github-btn .tooltip::after { 
    top: auto;
    bottom: 100%;
    border-color: transparent transparent var(--color-runtipi-red) transparent; 
}

/* Specific positioning for FOOTER elements (Bottom 3 Buttons) */
.footer-link-group .icon-btn-gradient .tooltip {
    top: auto;
    bottom: 100%; 
    left: 50%;
    transform: translateX(-50%) translateY(10px); 
}

.footer-link-group .icon-btn-gradient:hover .tooltip {
    transform: translateX(-50%) translateY(0); 
}

/* Specific Arrow direction for FOOTER elements */
.footer-link-group .icon-btn-gradient .tooltip::after {
    top: 100%; 
    bottom: auto; 
    border-color: var(--color-runtipi-red) transparent transparent transparent; 
}

3. Extracted HTML Components
A. The "Star This Project" Header Button
<!-- You can place this wherever you need a single CTA button -->
<a href="[https://github.com/acidgreenservers/runtipi-homelab-appstore/tree/master/Tools](https://github.com/acidgreenservers/runtipi-homelab-appstore/tree/master/Tools)" target="_blank" 
   class="icon-btn-gradient flex items-center text-color-primary font-medium py-2 px-4 rounded-lg header-github-btn" 
   data-tooltip="Star This Project">
    <i class="fas fa-star text-yellow-400 mr-2"></i>
    Star This Project
    <i class="fab fa-github ml-2"></i> 
    <span class="tooltip">Star This Project</span>
</a>

B. The Three Footer Buttons
These three buttons are contained within a parent div that handles their alignment and spacing, so it's best to copy the whole block.

<!-- Wrapper div for spacing and alignment -->
<div class="flex justify-center space-x-4 footer-link-group"> 
    
    <!-- 1. GitHub (Tools Directory) -->
    <a href="[https://github.com/acidgreenservers/runtipi-homelab-appstore/tree/master/Tools](https://github.com/acidgreenservers/runtipi-homelab-appstore/tree/master/Tools)" target="_blank" 
       class="icon-btn-gradient flex items-center text-color-primary font-medium py-2 px-4 rounded-lg"
       data-tooltip="View Generator Tools Directory">
        <i class="fab fa-github text-lg mr-2"></i>
        GitHub
        <span class="tooltip">View Generator Tools Directory</span>
    </a>
    
    <!-- 2. My GitHub Profile (Includes the custom SVG logo) -->
    <a href="[https://github.com/acidgreenservers](https://github.com/acidgreenservers)" target="_blank" 
       class="icon-btn-gradient flex items-center text-color-primary font-medium py-2 px-4 rounded-lg"
       data-tooltip="View My GitHub Profile">
        <!-- SVG Tipi Logo Snippet -->
        <svg width="20" height="20" viewBox="0 0 30 30" fill="none" class="mr-2" xmlns="[http://www.w3.org/2000/svg](http://www.w3.org/2000/svg)">
            <path d="M15 4L27 26H3L15 4Z" fill="#F4511E"/>
            <!-- NOTE: The 'fill' here should be adjusted based on the new project's background color -->
            <path d="M15 7L24 24H6L15 7Z" fill="var(--bg-body)"/> 
            <path d="M15 4L27 26" stroke="#FF66A3" stroke-width="2" stroke-linecap="round"/>
            <path d="M3 26L15 4" stroke="#FF66A3" stroke-width="2" stroke-linecap="round"/>
            <line x1="10" y1="12" x2="20" y2="12" stroke="#FFD180" stroke-width="1.5" stroke-linecap="round"/>
            <line x1="8" y1="18" x2="22" y2="18" stroke="#FFD180" stroke-width="1.5" stroke-linecap="round"/>
            <line x1="6" y1="24" x2="24" y2="24" stroke="#FFD180" stroke-width="1.5" stroke-linecap="round"/>
        </svg>
        GitHub Profile
        <span class="tooltip">View My GitHub Profile</span>
    </a>

    <!-- 3. Official Store -->
    <a href="[https://github.com/runtipi/runtipi-appstore/tree/master](https://github.com/runtipi/runtipi-appstore/tree/master)" target="_blank" 
       class="icon-btn-gradient flex items-center text-color-primary font-medium py-2 px-4 rounded-lg"
       data-tooltip="View Official Store">
        <i class="fab fa-github text-lg mr-2"></i>
        Official Store
        <span class="tooltip">View Official Store</span>
    </a>
</div>
