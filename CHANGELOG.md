# Changelog

All notable changes to Atmosfär will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [4.4.0] - 2025-10-19

### 🎨 New Feature
- Added desktop widget that can be placed on your desktop for quick weather access

<div align="center">
  <img src="https://raw.githubusercontent.com/SahalMoh/AtmosfarReleases/refs/heads/main/assets/WidgetShowcase.png" alt="Desktop Widget Showcase" style="width:320px; max-width:90%; border-radius:0px; box-shadow: 0 12px 30px rgba(0,0,0,0.35), 0 0 24px rgba(0,150,255,0.12); filter: drop-shadow(0 8px 24px rgba(0,0,0,0.25));">
</div>

<!--### 📦 Distribution
- Added Flatpak support - Install using: `flatpak install sahal.atmosfar.desktop`-->

### ✨ UI Improvements
- Settings page revamped with improved layout and visual design
- Enhanced overall settings experience for better usability

### 🐛 Bug Fixes
- Fixed issue where location/IP-based weather data was showing inaccurate information

### 🔧 Under The Hood
- Backend code improvements and optimizations
- Enhanced code structure for better maintainability

---

## [4.3.3] - 2025-10-15

### 🐧 Linux Fixes
- Fixed missing/broken icons on Linux systems
- Fixed AppImage not launching properly on some distributions

### 🐛 Bug Fixes
- Fixed location/IP access issues preventing weather data from loading correctly

### ✨ Added
- Added credits section to acknowledge contributors and libraries

---

## [4.3.2] - 2025-10-10

### 🚀 New Feature
- Added autostart on system boot option
- App can now launch automatically when your PC starts
- Starts minimized in the background for seamless experience
- Easily toggle autostart on/off in settings

### ⚙️ Convenience
- Set it once and always have weather ready when you need it
- No more manually launching the app after restart
- Minimal system impact with background startup

### 🔧 Under The Hood
- Major code refactoring for better performance and reliability
- Improved error handling and app stability
- Enhanced caching and resource management
- Better API communication with automatic retry logic
- Overall code quality improvements for smoother experience

---

## [4.3.1] - 2025-10-10

### ✨ Visual Polish
- Settings, AQI, and changelog modals now feature smooth animations
- Added icons beside weather details for better visual clarity
- Enhanced modal transitions and effects

### 🔧 Improvements
- Check for Updates button in tray menu now opens settings page directly
- Update checking now displays inline instead of separate window
- More streamlined update experience

### 🎨 UI Enhancements
- Improved settings page layout and accessibility
- Better visual feedback throughout the app
- *Version number is now more... interactive* 🤔

---

## [4.3.0] - 2025-10-09

### 🌍 Multi-Language Support
- Added support for multiple languages
- Users can now view weather information in their preferred language
- Seamless language switching from settings

### 🎯 Improved User Experience
- Changelog now opens in a modal instead of web browser
- Air Quality Index information opens in a modal instead of web browser
- Better in-app experience without leaving the application

---

## [4.2.3] - 2025-10-05

### 🔧 Backend Improvements
- Backend system optimizations and stability improvements
- Enhanced error handling and logging
- Code refactoring for better maintainability

### 🐛 Fixes
- Various backend bug fixes
- Improved application stability
- Performance optimizations

---

## [4.2.2] - 2025-09-30

# 🐧 LINUX VERSION NOW AVAILABLE! 🎉

**Atmosfär is now cross-platform! Download for both Windows and Linux.**

### 🎨 Visual Improvements
- Enhanced download button with Windows and Linux platform icons
- Wider weather boxes (30% increase) for better text readability
- High-quality 128x128 weather icons from WeatherAPI CDN
- Improved mobile responsiveness with larger weather boxes

### 🌤️ Weather Features
- Hourly forecast now shows next 24 hours from current time (not past hours)
- Sharper, always up-to-date weather icons
- Better readability for long weather conditions like "PATCHY RAIN NEARBY"

### 📱 Cross-Platform Support
- Clear platform support indication with Windows and Linux icons
- Better mobile experience with improved sizing
- Professional hover effects and spacing

### ⚡ Performance
- Faster icon loading via global CDN
- More relevant forecast data for better weather planning
- Enhanced design consistency throughout the app

---

## [4.2.1] - 2025-09-29

### 🕐 Time Display Fixes
- Fixed unwanted date showing in 24-hour mode
- Both 12-hour (1:00 PM) and 24-hour (13:00) modes now show only time
- Consistent time format across web and desktop versions

### 🎨 Dark Mode Improvements
- Enhanced dark mode color scheme throughout the app
- Fixed jarring white search button hover in dark mode
- Better search input styling with proper accent colors
- Improved visual consistency across all dark mode elements

### 🎯 User Experience
- Improved button styling and link appearance
- Cleaner, more organized interface
- Enhanced visual hierarchy

---

## [4.2.0] - 2025-09-29

### 📸 Before & After

<div align="center">
  <table>
    <tr>
      <td align="center"><strong>Before (v4.0.x)</strong></td>
      <td align="center"><strong>After (v4.2.0)</strong></td>
    </tr>
    <tr>
      <td><img src="https://raw.githubusercontent.com/SahalMoh/AtmosfarReleases/refs/heads/main/assets/AppScreenshotOld.png" alt="Old Design" width="400"></td>
      <td><img src="https://raw.githubusercontent.com/SahalMoh/AtmosfarReleases/refs/heads/main/assets/AppScreenshot.png" alt="New Design" width="400"></td>
    </tr>
  </table>
</div>

### ✨ Added
- Modern glassmorphism design throughout the app
- New weather data: Windchill, Heat Index, and Dew Point
- Web installer and offline installer options
- Enhanced loading screen with improved animation

### 🔄 Changed
- Redesigned weather display with cleaner, compact layout
- Search now only triggers on button click or Enter key
- Removed automatic search while typing for better performance
- Polished weather cards and hourly forecast styling

### 🐛 Fixed
- Loading screen positioning issues
- Weather display layout problems
- Improved app stability and reliability
- Better responsiveness across devices

---

## [4.0.1] - 2025-09-25

### ✨ Added
- Dark mode support with theme switcher
- Wind direction arrows and moon phase icons
- Redesigned settings modal

### 🔄 Changed
- Stylized "Atmosfär" wordmark header
- Improved weather visuals and layout
- Enhanced external link handling

### � Fixed
- Better performance with cached weather data
- Streamlined update indicators

---

## [4.0.0] - 2025-09-25

### 🎉 Added
- Initial release of Atmosfär weather application
- Real-time weather information display
- Clean and intuitive user interface
- Native desktop experience powered by ElectronJS
- Windows platform support

### 📋 Notes
- First stable release
- Windows only compatibility