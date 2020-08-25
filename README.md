# Dts-Overlays
Several dts overlays for raspberrypi0-wifi:
1. gpio-keys.dts, through the kernel module gpio-keys, it can simulate keyboard buttons with gpios

2. i2s-only-output.dts, since i2s definition include both the input (ex.microphone) and the output(ex.speaker), with this overlay the the input pin is free to be                     used for other purposes

3. tft24-resistive.dts, it consists of a tft2.4 display which use fb_ili9341 kernel module plus a touchscreen based on ads7846

4. waveshare3.5-resistive.dts, the well known Waveshare tft3.5 display
