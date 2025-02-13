# Stitching On VERSA - Troubleshooting
## 1. Calibrating at 1000 PPI
- Calibration Limits
    - The BC-100 calibration system is designed for resolutions up to **600 PPI**.
    - Calibrating at higher resolutions (like **1000 PPI**) can cause difficulties, particularly with **10% SFR** and **50% SFR**. These values get affected by high resolution, potentially leading to oversharpening.
- SFR (Spatial Frequency Response)
    - **10% SFR** is affected by system factors that are uncontrollable, such as **aperture, lens, and vibration**.
    - **50% SFR** is related to **focus and alignment** of the camera, which are **controllable**. If resolution is too high, it can reduce the effectiveness of these controllable factors.
- Note:
    - Closer Camera Distance → Lower SFR
        - Moving the camera closer to the target decreases the SFR, which can impact the sharpness of the resulting image.

## 2. Colour Registration
- What it Measures
    - Colour registration measures the **alignment of RGB values (red, green, and blue)** in the image.
    - This is a **software measurement issue**, not an image problem.
- Ignore Colour Registration
    - If colour registration shows **100%**, yet you're experiencing resolution issues, the problem is more likely due to **pixel alignment** (not sharpness or colour itself).
- Pixel Alignment
When pixels don't align properly, it can result in **less sharp images**, even with good colour registration.

## 3. Error Checking (Lightness Tab)
- Lightness Tab Overview
    - The **Lightness Tab** in Capture One provides a **visual representation** of your image's sharpness and alignment.
    - The **traces** (lines) in various colours (red, blue, green, brown, purple) correspond to **slant edge squares** in the image.
- Interpreting Traces (Lines)
    - Oversharpened Areas:\
    If the traces (lines) **exceed the bounds of the 4-star gates**, the area is **oversharpened**.
    - Less Sharp Areas:\
    If the traces (lines) **fall below the bounds of the 4-star gates**, the area is less **sharp**.
- Adjusting Sharpness Using Capture One Settings
    - Increase Sharpness:\
    Increasing settings in Capture One will move the traces (lines) to the **right**.
    - Decrease Sharpness:\
    Decreasing settings will move the traces (lines) to the **left**.

## 4. Additional Checks
- Zoom In on Slant Edge Squares
    - Zoom in on the **slant edge squares** to check for the presence of colour traces (red, blue, green, brown, purple).
    - If **no traces** are visible, the software is likely working correctly.
- Adjusting the Rectangular Green Boxes
    - The **rectangular green boxes** around the slant edge squares can be adjusted to **increase or decrease** the trace (line) positioning in the **resolution tab**. This adjustment helps fine-tune the sharpness and alignment.

## Key Points To NOTE!:
1. **Resolution Impact**: Calibrating above 600 PPI can cause oversharpening. The closer the camera is, the lower the SFR (sharpness).
2. **Colour Registration**: Don’t worry about it if it’s 100%. Pixel misalignment is likely the cause of poor resolution.
3. **Error Checking**: The Lightness Tab helps you visually identify oversharpening or areas that are less sharp.
4. **Adjusting Sharpness**: Modify Capture One's settings to adjust the sharpness and trace lines to improve your image quality.