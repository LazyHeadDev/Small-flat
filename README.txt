========================================================================
360° VIRTUAL TOUR - WEBSITE EXPORT PACKAGE
========================================================================
Tour Title : Modern Minimalist Coastal Villa & Penthouse
Created At : 2026-10-30T20:04:15.581Z
Format     : 100% Self-Contained Static Website (No Node.js/SQLite required)

This export package contains a complete, production-ready virtual tour that
can be hosted on any web server (Namecheap, cPanel, WordPress, Apache, Nginx,
Cloudflare Pages, AWS S3, etc.) without requiring a database, backend, or
external cloud dependencies.

------------------------------------------------------------------------
STEP-BY-STEP: HOW TO UPLOAD TO NAMECHEAP / CPANEL
------------------------------------------------------------------------
1. Log in to your Namecheap cPanel dashboard.
2. Open "File Manager" from the Files section.
3. Navigate to your website public directory (usually "public_html").
4. Create a new subfolder for this tour, for example:
   public_html/tours/amalfi-coastal-villa-tour/
5. Upload all extracted files and subdirectories directly into that folder:
   - index.html
   - tour-data.json
   - assets/
     ├── three.module.min.js
     └── three.core.min.js
   - panoramas/
     └── (all panoramic images)
   - README.txt
6. Your virtual tour is now live! Open it in your web browser:
   https://salman3dspace.com/tours/amalfi-coastal-villa-tour/

------------------------------------------------------------------------
HOW TO EMBED THIS TOUR IN WORDPRESS
------------------------------------------------------------------------
To display this tour inside any WordPress page or blog post:
1. Edit the WordPress page where you want the virtual tour to appear.
2. Add a "Custom HTML" block (or Elementor "HTML" widget).
3. Paste the following responsive iframe embed code:

<div style="position: relative; width: 100%; max-width: 1200px; margin: 0 auto; border-radius: 16px; overflow: hidden; box-shadow: 0 20px 40px rgba(0,0,0,0.4);">
  <iframe 
    src="https://salman3dspace.com/tours/amalfi-coastal-villa-tour/" 
    width="100%" 
    height="650" 
    style="border: 0; display: block;" 
    allow="accelerometer; magnetometer; gyroscope; fullscreen" 
    loading="lazy"
    allowfullscreen>
  </iframe>
</div>

------------------------------------------------------------------------
LOCAL TESTING BEFORE UPLOAD
------------------------------------------------------------------------
Because modern web browsers restrict loading local files and WebGL textures
over the file:// protocol (CORS restriction), test your exported tour using
a simple local web server:

Option A (Node.js):
  Run: npx serve .
  Then open: http://localhost:3000

Option B (Python 3):
  Run: python3 -m http.server 8080
  Then open: http://localhost:8080

Option C (VS Code):
  Right-click index.html -> "Open with Live Server".

------------------------------------------------------------------------
WHAT IS INCLUDED IN THIS EXPORT
------------------------------------------------------------------------
- High-Performance WebGL 360° Spherical Canvas
- Lossless Panorama Images at Original Quality
- Smooth Direct Portal Navigation between Scenes
- Informational Hotspot Popups with Detail Badges
- Responsive Room / Scene Navigation Drawer
- Natural Exposure / Brightness Control with Instant Reset
- Interactive Compass with Real-Time Heading Tracking
- Touch & Mobile Friendly (Drag Orbit, Pinch-to-Zoom, Tap Navigation)
- Native Fullscreen Mode Support
- Visible Error Overlay with Diagnostics and Retry
========================================================================
