Fact Check Insight is a high-performance, AI-driven Windows application designed to be a personal guardian
against misinformation. It provides real-time, global verification of factual claims and news media with zero
effort from the user.

  🛡️ The Product Vision
  In an era of rapid information flow, Fact Check Insight bridges the gap between encountering a claim and
  knowing its truth. By living silently in the Windows taskbar, it transforms the simple act of "copying text"
  into a powerful investigative tool, delivering a precision credibility score (0–100%) based on a global
  consensus of international news, official records, and verified data.

  🚀 Core Features
   * Active Clipboard Monitoring: Uses robust browser detection (Brave, Chrome, Edge, etc.) to watch your
     clipboard and trigger only when you copy factual claims or news URLs.
   * Global Truth Engine: Powered by Gemini 3.1 Flash Lite (optimized for speed and logic), the app generates
     multiple diverse search queries to cross-reference claims against over 50 international sources.
   * Granular Credibility Scoring: Moves beyond simple "True/False" labels. It provides a detailed 0–100% score
     for the overall claim and individual reliability ratings for every site it accesses.
   * Deep Media Analysis: Capable of analyzing images for context and manipulation, ensuring that visual
     misinformation is caught as effectively as text.
   * Blazing Speed: Features a parallelized search architecture (ThreadPoolExecutor) that fetches results from
     across the web simultaneously, reducing analysis time by 70%.
  🛠️ Technical Excellence & Branding
   * Deterministic Logic: Uses a low model temperature (0.1) to ensure consistent, reliable scoring for the same claim every time.
   * Single-Instance Safety: Implements Windows Named Mutexes to prevent process conflicts, ensuring only one
     monitor and one installer can run at a time.
   * Persistent Profile Storage: Automatically manages all results and history within the user's %APPDATA%
     folder for centralized, persistent data.
   * Full Branded UI: A modern, dark-themed interface utilizing a Charcoal and Teal palette, complete with
     custom taskbar icons, window icons, and high-DPI logo integration.

  📦 Deployment & Distribution
   * Professional Installer: A standalone FactCheckInstaller.exe that bundles the entire application. It
     features an interactive setup with Reinstall/Delete/Cancel logic and automatic uninstallation of registry
     keys and files.
   * Startup Persistence: Seamlessly integrates with the Windows Registry to launch automatically upon login,
     keeping the user protected from the moment they boot their PC.
   * Landing Page: A modern, responsive website featuring a high-impact hero section, feature breakdown, and direct download link, ready for global distribution.
     
Fact Check Insight is not just an app; it is a comprehensive, production-ready ecosystem for empowering truth
in the digital age.
