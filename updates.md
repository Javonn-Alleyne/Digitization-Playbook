# Step-by-Step Guide: Editing Lightness and Tone 
**Lightness and Tone** are terms that relate to the brightness, contrast, and overall appearance of an image, and they are often adjusted to achieve a more balanced or visually pleasing result.
This process is primarily evaluated based on the neutral patches, ranging from white to black. When calibrating from scratch, we will have to adjust these tones. The aim is to reach four golden thread stars on all these patches.

`The aim is to reach a 4 star on golden thread on all these patches`

We can get a four star score (or close to one) across the board by adjusting the following mechanical variables:

1. Exposure
adjusts the overall brightness of an image, making it lighter or darker

2. Shutter speed
controls how long the camera's shutter is open, affecting motion and light exposure

3. Aperture
controls the size of the lens opening, affecting how much light enters and the depth of field (how much of the image is in focus) (must stay at 8.0)

4. Lighting bank rig (this is especially important with the new Nexus/Gemini rigs)
setups of lights used to control the intensity, direction, and quality of light

A near perfect score based on changing mechanical settings only would look like this:
![image1](images/update_images/Patch20&21fix.png)

The near perfect score shows the patches that scored 4 stars on Golden Thread as well as the darker patches
![iamge2](images/update_images/FADGI_score_99.png)

The 6% means that some neutral patches were not 4 star compliant. 


## WHAT IF MY IMAGE IS ALL TOO DARK OR BRIGHT?

![image3](images/update_images/remaining_images/bright.png) missing

WAY TOO BRIGHT  

![image4](images/update_images/remaining_images/dark.png) missing

WAY TOO DARK

If your images are too dark or too bright in Capture One, you can adjust the Exposure, Shutter Speed and Aperture settings to correct the brightness as well as the Lighting rig:

### Adjusting Exposure in Capture One
In Capture One, the primary way to adjust exposure is by using the exposure slider in the exposure tool tab. Ensure that before you start your calibration that your exposure is set to 0. Increasing the exposure will brighten the image and decreasing the exposure will darken the image. If the image is too dark, you can drag the exposure slider to the right until the image is bright enough. If you want to preserve some tonal details, avoid pushing it too far (pass 0.3). If the image is too bright, lower the exposure slider to reduce the overall brightness of the image. This controls the amount of light captured during the shot, so reducing it will tone down the exposure without affecting other aspects of the image. However when adjusting the exposure ensure that it doesn’t fall into a negative range (e.g -1.31) (**we do not calibrate in negatives**)


### Adjusting shutter speed in Capture One 
While in calibration after the LCC step ensure that you adjust the shutter speed back either **1/8** or **1/6** seconds. A high shutter speed results in an image being too dark ( e.g 1/20). However, to fix an image that's too bright in Capture One using shutter speed, simply increase the shutter speed (e.g from ⅛ to 1/13)  in your camera settings before re-taking the shot. A faster shutter speed (shorter exposure time) allows less light to hit the sensor, reducing overexposure.

### Adjust Aperture in Capture One 
If your image is too dark or too bright, ensure that the aperture is locked at f/8.0 as this is the set aperture setting that is used for our type of imaging. ( Revisit the system's Preflight section under 'Camera Settings' and verify the configuration.) 

### Adjust Lighting Rig 
Always ensure that the light rigs are on **“continuous”** for BC- 100 by toggling the control on the lighting power supply and that both LED lights are on. For Versa ensure that the Nexus software is open and the Stella Gemini lights are set to **“Computer Control”** by going to the back of the light and toggling the switch to the correct setting.

![image5](images/update_images/remaining_images/backofstation_1.jpg) missing

BC-100 Lighting Rig

![image6](images/update_images/remaining_images/backofstation_2.jpg) missing

Versa Lighting Rig 

## WHAT IF MY SCORES ARE MOSTLY GOOD AND A FEW ARE OFF?
If your scores are mostly good, but there are a few issues, especially at the darker end of the neutrals, you can fix them by tweaking the luma curve a bit towards the lower end. We'll know which patches to adjust since Golden Thread shows a dropdown for each patch, along with its desired value.

![image7](images/update_images/I11_J11.png)

The Image above shows that Patch I11 and J11 was too dark and did not hit the 4 star compliant Therefore we would need to adjust the **Luma curve**.

The Image below shows that Patch I11 and J11 was too dark and did not hit the 4 star compliant Therefore we would need to adjust the **Luma curve**.

See figures below

![image8](<images/update_images/H11_I11_J11.png>)

The patch readouts should read values of  
I11:lower limit 8.74 to upper limit 11.74 with an aim of (10.24)  
J11:lower limit 4.18 to upper limit 7.18 with an aim of (5.68)

### WHAT IS THE LUMA CURVE?
The luma curve allows you to adjust the brightness (luminance) of specific tonal ranges in your image. 
The example below shows the luma curve before any adjustments were made on the FADGI target. 

![image9](<images/update_images/Screenshot curve2025-02-05 at 16.40.04.png>)

The example below shows a bad luma curve affecting patch I11 and J11 based on the generated Golden Thread values shown from the photo above.

![image10](<images/update_images/Screenshot FADGI patch j11 too low curve needs to go up 2025-02-04 at 15.35.48.png>)

#### Adjusting the luma curve 
When the last patch is moved **UP** on the curve, it carries **up** the value of patches H11, I11 and carries down the value of J11. When the patch is moved **DOWN** on the curve , the value of patches H11 and I11 drops and the values of J11 goes **up**.

![image11](<images/update_images/Screenshot FADGI with corrected curve with values given to hit 4 star for patches h11 to j11 when the curve patched m,ove it affects the values of h11 to j11 when the last curve patch is moved up  2025-02-04 at 15.43.20.png>)

When the Second last patch on the curve is moved **UP** it carries **up** the value of all three patches, when it is carried **DOWN** it carries down the value of all three patches.

![image12](<images/update_images/Screenshot middle 2025-02-05 at 15.25.42.png>)

When the middle patch is moved **UP** on the curve, it carries **up** the value of patches H11, I11 and carries **down** the value of J11. When the patch is moved **DOWN** on the curve the value of patches H11 and I11 drops and the values of J11 goes **up**

![image13](<images/update_images/Screenshot middle 2025-02-05 at 15.25.42.png>)

When the fourth patch on the curve is carried **UP** patch H11 **drops** and the values of I11 and J11 goes **up**. When it is carried **DOWN** the values of patch H11 goes up and the values of I11 and J11 goes **down**.

![image14](<images/update_images/Screenshot 4th 2025-02-05 at 15.27.34.png>)

**_Note: To determine which patches on the curve you will move and adjust will be  based on the readout values. These values give the feedback needed to change the patches' positions, helping the curve stay in line with the data._**

After correcting the curve and sending the image to be tested in Golden Thread you should attain almost the perfect score. 

## The Perfect Score 

![image15](images/update_images/GoldenThread_Perfect_score.png)

### The Perfect Luma Curve
After you adjusted the curve you should get almost the perfect score 
The patch readouts should read values of

H11:lower limit 17.98 to upper limit 20.98 with an aim of (**19.48**)\
I11:lower limit 8.46 to upper limit 11.46 with an aim of (**9.96**)  
J11:lower limit 2.91 to upper limit 5.91 with an aim of (**4.41**)\
( Congratulations you hit a 4 star compliant based on the values given in the Golden Thread assessment. )

![image16](<images/update_images/Screenshot 2025-02-05 144141.png>)

Values of full 4 star compliant

## WHAT IF I ADJUST MY LUMA CURVE TOO MUCH?
Excessive bumps, lifts, or dips in the luma curve suggest underlying issues and the curve should be kept as straight as possible for optimal results. Any humps should be corrected before relying on curve adjustments. (This requires patience and a steady hand)

![image17](<images/update_images/Screenshot FADGI curve ith humps and bumps  2025-02-04 at 15.40.44.png>)

# Step-by-Step Guide: Creating an LCC Profile in Capture One
## What is LCC?
The **Lens Cast Correction (LCC)** ensures neutrality and color accuracy by providing even exposure and brightness across the frame, avoiding ‘light falloff.’ Light falloff refers to the gradual decrease in brightness from the center of the image towards the edges and corners.
### How to Create an LCC Profile
#### 1. Capture an LCC Reference Image
- Place a white board in front of the lens to cover the entire field of view.

![image18](images/update_images/remaining_images/whiteboard_1.jpg) missing

The image above shows how to position your white board. 

By opening Capture One Live View you can reference if your board covers the entire field and it is shown perfectly below:

![image19](<images/update_images/Shanice/Screenshot 2025-02-06 at 10.58.57.png>)

- Adjust the **Shutter Speed** to a value between **1/8** and **1/20** before capturing the image.

- Add Color **Readouts** in the **middle**, **upper**, **and lower edges** of the frame.
In this case, Shutter speed of 1/15 was used and Readouts placed at 5 different positions. Using the red guide to place the middle readout to get an accurate value.

![image20](<images/update_images/Shanice/Screenshot 2025-02-06 at 11.00.05.png>)
- Ensure the **Color Readout values fall within the 65-70 range** before creating the LCC.

![image21](<images/update_images/Shanice/Screenshot 2025-02-06 at 11.00.31.png>)

After capturing again at 1/20 the readout values are good enough to go ahead and create the LCC Profile.

#### 2. Import the LCC Image into Capture One
- Open **Capture One** and create a **new session** or open an existing one.
- Import your LCC reference image by clicking **File > Import Images**, then navigate to your LCC shot and click **Open**.

#### 3. Apply the LCC Profile
- Select the LCC reference image in the ***Browser** panel.
- Open the **LCC Tool** by navigating to **Lens > LCC** in the toolbar.
- Click **Create LCC Profile** to analyze and generate the LCC correction.
- Ensure the options for **Dust Removal, Color Cast, and Light Falloff Correction** are checked.
- Click **Apply** to save the LCC profile.

![image22](<images/update_images/Shanice/Screenshot 2025-02-06 at 11.01.38.png>)

After the LCC is created and the values are good, always change back to 1/8 shutter speed and capture the target and proceed to exposure and dropping color readouts on the patches. **You made it this far, Well Done!**

![iamge23](<images/update_images/Shanice/Screenshot 2025-02-06 at 11.01.47.png>)

#### 4. Apply the LCC Profile to Your Images
- Select all images shot under the same conditions as the LCC reference image.
- Click the **Copy & Apply** button in the **LCC Tool**.
- Check the LCC profile in the **Adjustments Clipboard**, then click **Apply**.

#### 5. Verify and Adjust (If Needed)
- Zoom into your images and check for any unwanted color shifts or artifacts.
- If necessary, tweak the **Light Falloff** or **Color Cast** settings in the **LCC Tool**.

### What If My Lightness Uniformity is Off in Golden Thread?
If Lightness Uniformity is off, this indicates an issue in key LCC creation. Here’s what you can do:

![image24](images/update_images/Lightness_Uniformity_OFF.png)

The image above shows a Golden thread score of Lightness Uniformity being off

#### Troubleshooting Steps:
##### 1. Check the White Board
- If the board is **damaged, creased, or dirty**, it can affect the color reading.
- Replace it with a **clean, flat white board**.

##### 2. Ensure Proper Positioning
- The white board must be held **parallel to the glass** to avoid uneven brightness.
- It should cover the **entire field of view** to prevent inaccurate color readings.

`Perfect examples of positioning the white board correctly and incorrectly:`

![image25](images/update_images/remaining_images/whiteboard_2.jpg) missing

![image26](images/update_images/remaining_images/whiteboard_3.jpg) missing

![image27](images/update_images/remaining_images/whiteboard_4.jpg) missing

##### 3. Adjust Shutter Speed
- If the LCC is created out of range:
    - If the image is **too dark**, reduce the shutter speed between **1/13** and **1/15**.
    - If the image is **too bright**, increase the shutter speed between **1/20** and **1/25**.
- **Recapture** the image after adjustments.

### Tips for Best Results
- Always shoot an LCC reference image whenever you change **lenses, apertures, or camera setups**.
- Keep the **white panel clean** to avoid introducing dust artifacts.
- **Store** your LCC profiles for future use when shooting in similar conditions.

By following these steps, you’ll ensure cleaner and more color-accurate images in Capture One. **Happy editing!**

# Step-by-Step Guide: Editing SFR 10% AND 50%

## What is the SFR? 
A numerical value that describes how a camera changes contrast as a function of spatial frequency response. It's a measure of how well a camera's lens and sensor can resolve details in an image. In golden thread there are 2 types of SFR measurements.

![image28](images/update_images/remaining_images/perfect_score.jpg) missing

### 50% SFR 
In Golden Thread the 50% SFR provides guidance on whether adjustments should be made to either increase or decrease the radius levels in the sharpening tab. This determination is based on the results of the corresponding graph below.

![image29](images/update_images/SFR_CURVES_FIX.png)

This image depicts what we aim our SFR graph to look like. If what is on your golden thread graph is similar to this you are on the correct track, however if not follow these troubleshooting steps below.

#### Troubleshooting 50%SFR
After completing the calibration within the Golden Thread, in the event the 50% SFR is off by approximately 60% with a 3 star complaint it becomes necessary to analyze and adjust the position curves on the SFR graph and bring it within an acceptable range. The key objective is to refine the settings and correct the difference to align with golden thread.  

On the SFR graph there are 3 distinct colored markers on the x and y axis and the position of your curves within these markers determines a star compliant level. 
- Between the Red markers indicates a 2 star compliant level 
- Between the Blue markers indicates a 3 star compliant level 
- Between the Yellow markers indicates a 4 star compliment level 

![image30](images/update_images/remaining_images/shapening.jpg)

Our aim is to place our curves on the golden thread graph between the yellow markers. This is done by increasing or decreasing the radius so that our curves are positioned between the yellow color markers on the graph. As you can see in the image above the curves are not passing through our yellow markers on the graph, therefore we have not achieved a 4 star compliant level.

##### How to increase or decrease your radius?
The radius is found in the system's check heading under the sharpening tab. See image below. 

![image31](images/update_images/remaining_images/fadgi.jpg)

Select one of the values ranging 0.3 - 0.5 (preferably moving up or down by the value 0.1) depending on your system and this should rectify your 50% SFR issues.

##### How do you know if you have to increase or decrease your Radius?
If your curves are positioned more to the **left** on the outside of your yellow colored vertical lines you should **increase** your radius preferably to a maximum of 0.5. 

![image32](images/update_images/remaining_images/move_to_the_right.jpg)

In the image above our curves are located more to the **left** of our yellow markers, therefore we need to **increase** our radius.
 
If your curves are positioned more to the **right** on the outside of your yellow colored vertical lines you should **decrease** your radius preferably to a minimum of 0.3.

![image33](images/update_images/remaining_images/move_to_the_left.jpg)

The image above shows our curves located more to the **right** of our yellow markers therefore we have to **decrease** our radius. 

If you have correctly followed the troubleshooting steps you should have a SFR graph resembling the image below. 

![image34](images/update_images/SFR_CURVES_FIX.png)

### 10% SFR - Sampling Efficiency 
Is a metric used in digital imaging to assess how well a camera captures fine details, specifically by measuring the spatial frequency. Essentially, it indicates how much of the potential detail in an image a camera can actually capture at a given resolution, with a higher percentage signifying better detail capturing ability.

#### Troubleshooting 10% SFR - Sampling Efficiency
When undergoing the process of calibration the numerical values in your Noise reduction tab should be as follows:
- Details - 50 
- Color - 40
- Single Pixel - 0 

![image35](images/update_images/remaining_images/fadgi_2.jpg)

These are the settings that are used to produce the best possible score within the golden thread, however you may notice that the luminance is missing. In the event that you encounter an issue in golden thread where the 10% SFR is producing a 3 star or lower compliant level, you proceed to undergo the following process found below to rectify your issue: 

![image36](images/update_images/remaining_images/sfr_10.jpg)

The image above shows an example of a 10% SFR - Sampling Efficiency that needs adjusting. 
To rectify this issue you follow the process below.
- Change the luminance numerical value of the Luminance found in the Noise Reduction Tab. The most reliable values to use are 0, 40 or 50. It is important to note every time you make a change in the systems check tab you **MUST** capture again after all changes are made. 

![image37](images/update_images/remaining_images/fadgi_3.jpg)

After you have changed your value and captured your image, run your image through a Golden Thread and your issue should be resolved.