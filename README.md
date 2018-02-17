# Moriya Shrine
#### An intelligent embedded mood-lighting system

Project involves:
- Onion Omega2 Linux SoC
- Logitech C170 Webcam
- Shell Scripting
- C++ Code
- Cross-Compilation

There are three modes of operation for control of the RGB LED

1. Image Colour Averaging: Simply weighs averages the colour of every pixel within the image taken
2. Facial Recognition: Determines position of face within image and weighs colour from pixels surrounding it (i.e. the colour of the background behind the person)
3. Laser Pointer Recognition: Determines position of laser pointer and weighs colour from surrounding area
