Create a complete Tic Tac Toe game as a single-file Progressive Web App (PWA) designed for TWA (Trusted Web Activity / TriWeb Application) deployment. The app must load from a web URL, work offline, and stay under 500KB.

REQUIREMENTS:

1. SINGLE FILE STRUCTURE:
   - One complete HTML file containing embedded CSS and JavaScript
   - No external dependencies (all code inline)
   - Total size target: &lt;100KB (well under 500KB limit)

2. CORE GAME FEATURES:
   - Classic 3x3 Tic Tac Toe grid
   - Two modes: Player vs Player (local) and Player vs AI
   - AI must use Minimax algorithm (unbeatable difficulty)
   - Score tracking (X wins, O wins, Draws)
   - Move history with undo functionality
   - Game state persistence (localStorage)

3. UI/UX SPECIFICATIONS:
   - Modern glassmorphism design with CSS backdrop-filter
   - Smooth animations (cell marking, winning line, transitions)
   - Responsive layout (mobile-first, works on all screen sizes)
   - Touch-optimized (large tap targets, no hover dependencies)
   - Dark/Light theme toggle
   - Sound effects (Web Audio API, optional mute toggle)

4. TWA/PWA REQUIREMENTS:
   - Include complete manifest.json content as a comment block
   - Service worker code for offline functionality
   - App icons (SVG data URIs for scalability)
   - Theme color meta tags
   - Standalone display mode optimization

5. CODE QUALITY:
   - Vanilla JavaScript (no frameworks)
   - CSS Grid for game board layout
   - ES6+ classes for game logic
   - Comprehensive comments
   - Error handling and input validation

6. PERFORMANCE:
   - 60fps animations using CSS transforms
   - Passive event listeners for touch
   - requestAnimationFrame for game loop
   - Lazy load non-critical resources

DELIVERABLE:
Provide the complete, production-ready HTML file that can be saved as index.html, uploaded to any static host (GitHub Pages, Netlify, etc.), and immediately deployed as a TWA to Google Play Store or used as a TriWeb Application.

Include setup instructions for TWA deployment using Bubblewrap or PWA Builder.