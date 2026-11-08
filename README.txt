EcoChain keychain ad - source files

HOW TO OPEN IN VS CODE
1. Download this whole folder (EcoChain_Ad_Source) to your computer.
2. Open VS Code > File > Open Folder... and choose this folder.
3. Open render_ad.py to read the script.

HOW TO RE-RUN IT (optional)
1. Install Python 3 from python.org (on Windows tick "Add Python to PATH").
2. Install ffmpeg:
   - Windows: open a terminal and run  winget install ffmpeg
   - Mac: install Homebrew, then run  brew install ffmpeg
3. In VS Code open the Terminal (Terminal > New Terminal) and run:
      pip install pillow numpy
4. Still in the terminal, run:
      python render_ad.py
5. Wait about 2 to 3 minutes. The video is saved in this folder as
   EcoChain_Keychain_Ad_30PHP_Landscape_v2.mp4

Files in this folder
- render_ad.py: draws every frame and builds the video
- Eco__1_.png, Eco__2_.png, Eco__3_.png: product photos
- merged_seamless_upscaled.png: the banner (reference only, not used by the script)
- snaptik_com_lc_-_7704136954870304001.mp3: the audio track
- Poppins-Regular.ttf, Poppins-Bold.ttf: fonts used for the text (OFL licence)
