# NoX_Gate
Simple noise gate light weight application using python 3.0+ (README and use .EXE file if python not installed)

NOX GATE - Noise Gate Software
==============================

What it does:
- Removes background noise from your microphone
- Works with Discord, games, and all voice apps
- Professional audio quality

Installation:
1. Run INSTALL.bat as Administrator
2. Install VB-Cable from the other ZipFile
3. Restart your computer
4. Run NoX Gate from Desktop

Setting up NOX GATE 
1. INSIDE NOX_GATE APP: SELECT USE VB-CABLE (should be default anyway)
2. START NOX GATE
3. ADJUST YOUR THRESHOLD AND KEEP IT RUNNING 
4. disable - 'Enable Audio Monitoring'; this is only for adjusting your threshold.

SETUP YOUR GAMES AND DISCORD
1. Keep your Mic as default in windows setting (bottom right corner)
2. In your GAMES or Discords settings go to Audio - Voice
3. Input Device: Select "CABLE OUTPUT"
4= now the NoX Gate will work through the CABLE OUTPUT in your games or discord

That's it! No Python or technical knowledge needed.

README++++
========================================================================
                     NOX GATE - COMPLETE PACKAGE
========================================================================

WHAT'S INCLUDED:
---------------
1. NoX_Gate.exe - Complete noise gate application
   - Includes Python runtime
   - Includes SoundDevice audio library
   - Includes NumPy mathematical library
   - Includes Tkinter GUI framework
   - ALL dependencies included

2. INSTALL.bat - Easy installer
3. This README file

WHAT'S NOT INCLUDED (but needed for Discord):
--------------------------------------------
• VB-Cable Virtual Audio Device (separate ZIP)
  Required for Discord/voice chat applications

========================================================================
                    INSTALLATION INSTRUCTIONS
========================================================================

STEP 1: INSTALL NOX GATE
-----------------------
1. Run "INSTALL.bat"
   - If asked, run as Administrator
   - No additional software needed

2. After installation:
   - Desktop shortcut will be created
   - Start Menu entry will be added
   - README file will be on Desktop

STEP 2: INSTALL VB-CABLE (For Discord)
--------------------------------------
1. Extract the separate VB-Cable ZIP file
2. Run "VBCABLE_Setup_x64.exe"
3. Follow installation prompts
4. RESTART your computer

STEP 3: CONFIGURE DISCORD
-------------------------
1. Open Discord
2. Settings → Voice & Video
3. Input Device: Select "CABLE Output (VB-Audio Virtual Cable)"
4. Test your microphone

========================================================================
                    USING NOX GATE
========================================================================

QUICK START:
1. Launch "NoX Gate" from Desktop
2. Click "START NOX GATE"
3. Speak into microphone
4. Adjust threshold slider until:
   - Gate opens (green) when you speak
   - Gate closes (red) when silent

SETTINGS:
• Threshold: Controls sensitivity (lower = more sensitive)
• Attack Time: How quickly gate opens (10-30ms recommended)
• Release Time: How slowly gate closes (100-200ms recommended)

========================================================================
                    TECHNICAL INFORMATION
========================================================================

NOX GATE INCLUDES:
• Python 3.x runtime (embedded)
• SoundDevice 0.5.x audio library
• NumPy 2.x mathematical library
• Tkinter GUI toolkit
• All required dependencies

NO ADDITIONAL INSTALLS NEEDED:
• No Python installation required
• No pip install commands
• No separate library downloads
• Everything is self-contained

FILE INFORMATION:
• NoX_Gate.exe: ~30-50MB (contains everything)
• Portable: Can be copied to any Windows computer
• Works offline: No internet connection required

========================================================================
                    TROUBLESHOOTING
========================================================================

COMMON ISSUES:

1. "NoX Gate won't start"
   • Try running as Administrator
   • Check Windows Defender isn't blocking it
   • Ensure enough disk space (50MB free)

2. "No audio input"
   • Check microphone is connected
   • Test microphone in Windows Sound Settings
   • Make sure correct input device is selected

3. "For Discord: No CABLE Output option"
   • Install VB-Cable from separate ZIP
   • Restart computer after installing VB-Cable
   • Check Device Manager for VB-Audio device

4. "Application closes unexpectedly"
   • Try running from installation folder
   • Check event viewer for errors
   • Re-run INSTALL.bat

========================================================================
                    SUPPORT
========================================================================

This package includes everything needed to run NoX Gate.
No additional software, libraries, or Python installations required.

For VB-Cable issues, refer to VB-Audio documentation.

========================================================================
