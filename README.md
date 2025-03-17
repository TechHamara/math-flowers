# math-flowers
MathFlowers An extension for MIT App Inventor 2 by th
-----
<div align="center">
<h1><kbd>🧩 MathFlowers</kbd></h1>
An extension for MIT App Inventor 2.<br>
MathFlowers lets you create beautiful mathematical flower patterns on a canvas. Set numerator and denominator values to create different patterns, customize colors, line thickness, and special effects like oil paint or dashed lines. Animate your flowers with adjustable speed and rotation.
</div>

## 📝 Specifications
* **
📦 **Package:** io.th.mathflowers.mathflowers<br>
💾 **Size:** 22.48 KB<br>
📱 **Minimum API Level:** 7<br>
📅 **Updated On:** [date=2025-03-17 timezone="Asia/Calcutta"]<br>
💻 **Built & documented using:** [FAST-CLI](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel) `v2.7.0`<br>
<br><br>

## Screen Shots

![MathFlowers-1742112908565](https://github.com/user-attachments/assets/d0857979-e66f-410b-8d29-e5a2f8763ade)
<br>
![MathFlowers-1742114416462](https://github.com/user-attachments/assets/524e5c23-25ec-4ab7-95be-3718a18c2f20)
<br>
![MathFlowers-1742115988552](https://github.com/user-attachments/assets/2ec3a3f1-4820-48b2-9cb6-85809279aab1)
<br>
![MathFlowers-1742117306305 png](https://github.com/user-attachments/assets/8caa1ca8-143b-407f-a2a6-a48b726ebf42)
<br>
![photo_2025-03-17_16-40-48](https://github.com/user-attachments/assets/340b1a25-42d7-463f-a667-8fad49690011)
<br>

## <kbd>Events:</kbd>
**MathFlowers** has total 6 events.

![FlowerCompleted_Event](https://github.com/user-attachments/assets/3dad4aaa-a9c5-4875-81e6-8e161f528bd3)
### 💛 FlowerCompleted
Event triggered when flower drawing is completed

![FlowerStarted_Event](https://github.com/user-attachments/assets/285d045f-4f77-42e0-9162-eed2bbd93434)
### 💛 FlowerStarted
Event triggered when flower drawing starts

![FlowerProgress_Event](https://github.com/user-attachments/assets/46a395e5-95a5-47b1-9863-61a6e52c343c)
### 💛 FlowerProgress
Event triggered when flower drawing progress changes

| Parameter | Type
| - | - |
| percentComplete | number

![FlowerError_Event](https://github.com/user-attachments/assets/8369b527-0c47-48ab-89b7-2d79d98731f5)
### 💛 FlowerError
Event triggered when an error occurs

| Parameter | Type
| - | - |
| errorMessage | text

![FlowerCleanedUp_Event](https://github.com/user-attachments/assets/5258a49d-a12b-4833-88a3-92ccb334a103)
### 💛 FlowerCleanedUp
Event triggered when flower resources are cleaned up

![ImageSaved_Event](https://github.com/user-attachments/assets/d3a6b0a9-4781-4d56-8436-9b3cacb13e6c)
### 💛 ImageSaved
Event triggered when an image is successfully saved

| Parameter | Type
| - | - |
| filePath | text

## <kbd>Methods:</kbd>
**MathFlowers** has total 17 methods.

![Initialize_Method](https://github.com/user-attachments/assets/34961b4f-ca1e-4371-acca-8d9fa0e15a95)
### 💜 Initialize
Initialize the flower drawing with a canvas

| Parameter | Type
| - | - |
| canvas | component

![BackgroundColorRGB_Method](https://github.com/user-attachments/assets/d7ed2342-e92d-436f-b624-db59c18acbf3)
### 💜 BackgroundColorRGB
Set background color using RGB values

| Parameter | Type
| - | - |
| red | number
| green | number
| blue | number

![BackgroundColorARGB_Method](https://github.com/user-attachments/assets/887de141-6bad-483a-aa4e-d25308f2860b)
### 💜 BackgroundColorARGB
Set background color using ARGB values (with alpha transparency)

| Parameter | Type
| - | - |
| alpha | number
| red | number
| green | number
| blue | number

![TransparentBackground_Method](https://github.com/user-attachments/assets/c06c13a3-cb88-4b6d-ad24-24752444f3ec)
### 💜 TransparentBackground
Set transparent background

![GradientBackground_Method](https://github.com/user-attachments/assets/25f18b1b-dc9b-42f4-9959-e75d047dbb90)
### 💜 GradientBackground
Set gradient background. Example: SetGradientBackground(Color.RED, Color.BLUE, true)

| Parameter | Type
| - | - |
| startColor | number
| endColor | number
| isVertical | boolean

![GenerateRandomFlower_Method](https://github.com/user-attachments/assets/197cc7f6-26f8-47d0-955e-fd03e5277ae0)
### 💜 GenerateRandomFlower
Generate a new random flower

![DrawFlower_Method](https://github.com/user-attachments/assets/2ec6f663-d033-4c06-bed2-a997cb2d91ba)
### 💜 DrawFlower
Draw a flower with specific n and d values. For example, DrawFlower(5, 2) creates a 5-petaled flower, while DrawFlower(7, 3) creates a more complex pattern. The ratio n/d determines the flower's shape.

| Parameter | Type
| - | - |
| numerator | number
| denominator | number

![PauseDrawing_Method](https://github.com/user-attachments/assets/3c6ffbdb-ea87-4c4c-a7e7-0ac98fd86d5f)
### 💜 PauseDrawing
Pause the current drawing

![ResumeDrawing_Method](https://github.com/user-attachments/assets/879177e3-2357-40a3-91a9-d14cc71790a0)
### 💜 ResumeDrawing
Resume the paused drawing

![RotateFlower_Method](https://github.com/user-attachments/assets/6da83ec5-a75b-4646-8758-03011b4dfcb8)
### 💜 RotateFlower
Rotate the flower by specified degrees

| Parameter | Type
| - | - |
| degrees | number

![ExportFlowerParameters_Method](https://github.com/user-attachments/assets/6d92d4ab-36c3-4e28-a682-ef95826951b4)
### 💜 ExportFlowerParameters
Export current flower parameters as a list containing n, d, and rotation values. Example: ExportFlowerParameters() might return a list like [5, 3, 45] for a flower with n=5, d=3, and 45 degree rotation

![ImportFlowerParameters_Method](https://github.com/user-attachments/assets/44ecc7ed-b518-4005-9ce7-1702b1a9f33f)
### 💜 ImportFlowerParameters
Import and apply flower parameters from a YailList. Example: ImportFlowerParameters(list(5, 3, "#FF0000", 2, 45)) to create a flower with n=5, d=3, red color, thickness 2, and 45 degree rotation

| Parameter | Type
| - | - |
| params | list

![Cleanup_Method](https://github.com/user-attachments/assets/047bdb20-a758-49dc-bebd-bb720fbe88d6)
### 💜 Cleanup
Clean up resources and stop drawing

![SaveAsPNG_Method](https://github.com/user-attachments/assets/33398f32-8a8e-4c6f-bfdf-753a00301185)
### 💜 SaveAsPNG
Save the current flower drawing as a PNG image file. Triggers ImageSaved event with the file path if successful.

| Parameter | Type
| - | - |
| fileName | text

![SaveAsJPEG_Method](https://github.com/user-attachments/assets/d2a841bf-9af2-497b-b82f-2898d2cdcb34)
### 💜 SaveAsJPEG
Save the current flower drawing as a JPEG image file with specified quality (1-100). Triggers ImageSaved event with the file path if successful.

| Parameter | Type
| - | - |
| fileName | text
| quality | number

![IsStorageAvailable_Method](https://github.com/user-attachments/assets/58d6c54f-dbdb-4951-a8b6-bf4a22a2088f)
### 💜 IsStorageAvailable
Check if external storage is available for saving images

![SetDashedLine_Method](https://github.com/user-attachments/assets/37fca7d9-373b-42b1-b8dc-20d3690563b4)
### 💜 SetDashedLine
Set dashed line properties (enable, dash length, gap length)

| Parameter | Type
| - | - |
| enable | boolean
| dashLength | number
| gapLength | number

## <kbd>Setters:</kbd>
**MathFlowers** has total 12 setter properties.


![BackgroundColor_Set_Property](https://github.com/user-attachments/assets/ccdc5a58-23a9-4d36-95c2-bb08ea75b6dc)
### 💚 BackgroundColor
Set background color of the pattern view

* Input type: `number`

![BackgroundAlpha_Set_Property](https://github.com/user-attachments/assets/349a717e-40a2-4a6a-a916-2c13fd99726d)
### 💚 BackgroundAlpha
Set background alpha (transparency) value (0-255)

* Input type: `number`

![Numerator_Set_Property](https://github.com/user-attachments/assets/133ef3da-807d-4982-91b7-785d682f0232)
### 💚 Numerator

Get the current n value

* Input type: `number`

![Denominator_Set_Property](https://github.com/user-attachments/assets/29e7ff5a-7424-4725-a212-95e4d478dd3e)
### 💚 Denominator
Get the current d value

* Input type: `number`


![AnimationSpeed_Set_Property](https://github.com/user-attachments/assets/d7b8742f-1fca-451e-ad12-e4c483507278)
### 💚 AnimationSpeed
Set the animation speed (milliseconds between frames)

* Input type: `number`

![OilPaintEffect_Set_Property](https://github.com/user-attachments/assets/f0e05a26-235a-415c-b47b-3e28dbadda4a)
### 💚 OilPaintEffect
Enable or disable oil paint effect

* Input type: `boolean`

![OilPaintRadius_Set_Property](https://github.com/user-attachments/assets/899f833b-4d15-444c-a9ed-d95fe6605065)
### 💚 OilPaintRadius
Set the oil paint effect radius (1-10)

* Input type: `number`

![RoundedEdges_Set_Property](https://github.com/user-attachments/assets/0692152f-7971-416c-822a-5bdddb7636ea)
### 💚 RoundedEdges
Enable or disable rounded edges for lines

* Input type: `boolean`

![CornerRadius_Set_Property](https://github.com/user-attachments/assets/85e6e6e5-421a-4aea-95bb-d1a5fdea6397)
### 💚 CornerRadius
Set the corner radius for rounded edges (1-20)

* Input type: `number`

![DashedLine_Set_Property](https://github.com/user-attachments/assets/8af87b55-1c47-446e-8fa1-80daf9d1b121)
### 💚 DashedLine
Enable or disable dashed line effect

* Input type: `boolean`

![DashLength_Set_Property](https://github.com/user-attachments/assets/a905fb8b-4ee1-422f-971d-862029508e18)
### 💚 DashLength
Set the dash length for dashed lines (1-50)

* Input type: `number`

![DashGap_Set_Property](https://github.com/user-attachments/assets/9b7bcd93-384f-4cd8-9c82-113f93ef9a59)
### 💚 DashGap
Set the gap between dashes (1-50)

* Input type: `number`

## <kbd>Getters:</kbd>
**MathFlowers** has total 16 getter properties.

![White_Get_Property](https://github.com/user-attachments/assets/bfbc9588-cfee-4c01-b925-e0e8c134a383)
### 🟢 White
Returns the color White

* Return type: `number`

![Black_Get_Property](https://github.com/user-attachments/assets/1c8aee31-09ea-40ce-b689-35b6017d39fe)
### 🟢 Black
Returns the color Black

* Return type: `number`

![Red_Get_Property](https://github.com/user-attachments/assets/b18fc72f-5b1b-4e26-80d2-1b4af45c88fa)
### 🟢 Red
Returns the color Red

* Return type: `number`

![Green_Get_Property](https://github.com/user-attachments/assets/204dbab4-b1f1-43ea-b109-25ef3e981646)
### 🟢 Green
Returns the color Green

* Return type: `number`

![Blue_Get_Property](https://github.com/user-attachments/assets/55526ffb-fdba-433d-8f0b-9298377aeba0)
### 🟢 Blue
Returns the color Blue

* Return type: `number`

![Transparent_Get_Property](https://github.com/user-attachments/assets/add1e9c9-bffe-4ddb-ba4b-ccda069df775)
### 🟢 Transparent
Returns a transparent color

* Return type: `number`

![Numerator_Get_Property](https://github.com/user-attachments/assets/df0af2b3-9027-4c9f-add4-4f1fba793469)
### 🟢 Numerator
Get the current n value

* Return type: `number`

![Denominator_Get_Property](https://github.com/user-attachments/assets/a036301d-2740-4d28-b5e8-fe795c9a4655)
### 🟢 Denominator
Get the current d value

* Return type: `number`
  
![AnimationSpeed_Get_Property](https://github.com/user-attachments/assets/f16bf5fc-a39d-4c81-99d7-32f0cf38c491)
### 🟢 AnimationSpeed
Set the animation speed (milliseconds between frames)

* Return type: `number`

![OilPaintEffect_Get_Property](https://github.com/user-attachments/assets/c0491731-b636-41da-bad8-890fae5ed67d)
### 🟢 OilPaintEffect
Enable or disable oil paint effect

* Return type: `boolean`

![OilPaintRadius_Get_Property](https://github.com/user-attachments/assets/5c469e20-309d-42cd-af6c-efa4b5cecfe6)
### 🟢 OilPaintRadius
Set the oil paint effect radius (1-10)

* Return type: `number`

![RoundedEdges_Get_Property](https://github.com/user-attachments/assets/f2890f89-6b9e-478e-89b6-372a9fed1da5)
### 🟢 RoundedEdges
Enable or disable rounded edges for lines

* Return type: `boolean`

![CornerRadius_Get_Property](https://github.com/user-attachments/assets/fd2fb0a3-c866-40eb-a22c-2769387d913c)
### 🟢 CornerRadius
Set the corner radius for rounded edges (1-20)

* Return type: `number`

![DashedLine_Get_Property](https://github.com/user-attachments/assets/2b821547-22ea-4ff4-835b-17bfe66e3042)
### 🟢 DashedLine
Enable or disable dashed line effect

* Return type: `boolean`

![DashLength_Get_Property](https://github.com/user-attachments/assets/7d138eb1-a996-4164-b2a5-9f1e72a0f6cf)
### 🟢 DashLength
Set the dash length for dashed lines (1-50)

* Return type: `number`

![DashGap_Get_Property](https://github.com/user-attachments/assets/9bcc1ae4-2104-4be1-866d-d1ee5d2ea35c)
### 🟢 DashGap
Set the gap between dashes (1-50)

* Return type: `number`

## Thanks 
  TechHamara
  
