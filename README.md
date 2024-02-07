This sample code uses TFT_eSPI and SPIFFS to read bitmaps from the flash filesystem and display them in sequence.
Each bitmap must be uncompressed, same dimensions as the screen (296*240 in my case) and use 16-bit colors (5R, 6G, 5B)

I also tried the exact same code with tft.pushImage() but that doesn't seem to work
