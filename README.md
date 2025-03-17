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
📦 **Package:** io.th.mathflowers.mathflowers
💾 **Size:** 22.48 KB
📱 **Minimum API Level:** 7
📅 **Updated On:** [date=2025-03-17 timezone="Asia/Calcutta"]
💻 **Built & documented using:** [FAST-CLI](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel) `v2.7.0`

## <kbd>Events:</kbd>
**MathFlowers** has total 6 events.

### 💛 FlowerCompleted
Event triggered when flower drawing is completed

### 💛 FlowerStarted
Event triggered when flower drawing starts

### 💛 FlowerProgress
Event triggered when flower drawing progress changes

| Parameter | Type
| - | - |
| percentComplete | number

### 💛 FlowerError
Event triggered when an error occurs

| Parameter | Type
| - | - |
| errorMessage | text

### 💛 FlowerCleanedUp
Event triggered when flower resources are cleaned up

### 💛 ImageSaved
Event triggered when an image is successfully saved

| Parameter | Type
| - | - |
| filePath | text

## <kbd>Methods:</kbd>
**MathFlowers** has total 17 methods.

### 💜 Initialize
Initialize the flower drawing with a canvas

| Parameter | Type
| - | - |
| canvas | component

### 💜 BackgroundColorRGB
Set background color using RGB values

| Parameter | Type
| - | - |
| red | number
| green | number
| blue | number

### 💜 BackgroundColorARGB
Set background color using ARGB values (with alpha transparency)

| Parameter | Type
| - | - |
| alpha | number
| red | number
| green | number
| blue | number

### 💜 TransparentBackground
Set transparent background

### 💜 GradientBackground
Set gradient background. Example: SetGradientBackground(Color.RED, Color.BLUE, true)

| Parameter | Type
| - | - |
| startColor | number
| endColor | number
| isVertical | boolean

### 💜 GenerateRandomFlower
Generate a new random flower

### 💜 DrawFlower
Draw a flower with specific n and d values. For example, DrawFlower(5, 2) creates a 5-petaled flower, while DrawFlower(7, 3) creates a more complex pattern. The ratio n/d determines the flower's shape.

| Parameter | Type
| - | - |
| numerator | number
| denominator | number

### 💜 PauseDrawing
Pause the current drawing

### 💜 ResumeDrawing
Resume the paused drawing

### 💜 RotateFlower
Rotate the flower by specified degrees

| Parameter | Type
| - | - |
| degrees | number

### 💜 ExportFlowerParameters
Export current flower parameters as a list containing n, d, and rotation values. Example: ExportFlowerParameters() might return a list like [5, 3, 45] for a flower with n=5, d=3, and 45 degree rotation

### 💜 ImportFlowerParameters
Import and apply flower parameters from a YailList. Example: ImportFlowerParameters(list(5, 3, "#FF0000", 2, 45)) to create a flower with n=5, d=3, red color, thickness 2, and 45 degree rotation

| Parameter | Type
| - | - |
| params | list

### 💜 Cleanup
Clean up resources and stop drawing

### 💜 SaveAsPNG
Save the current flower drawing as a PNG image file. Triggers ImageSaved event with the file path if successful.

| Parameter | Type
| - | - |
| fileName | text

### 💜 SaveAsJPEG
Save the current flower drawing as a JPEG image file with specified quality (1-100). Triggers ImageSaved event with the file path if successful.

| Parameter | Type
| - | - |
| fileName | text
| quality | number

### 💜 IsStorageAvailable
Check if external storage is available for saving images

### 💜 SetDashedLine
Set dashed line properties (enable, dash length, gap length)

| Parameter | Type
| - | - |
| enable | boolean
| dashLength | number
| gapLength | number

## <kbd>Setters:</kbd>
**MathFlowers** has total 12 setter properties.

### 💚 BackgroundColor
Set background color of the pattern view

* Input type: `number`

### 💚 BackgroundAlpha
Set background alpha (transparency) value (0-255)

* Input type: `number`

### 💚 Numerator
Get the current n value

* Input type: `number`

### 💚 Denominator
Get the current d value

* Input type: `number`

### 💚 AnimationSpeed
Set the animation speed (milliseconds between frames)

* Input type: `number`

### 💚 OilPaintEffect
Enable or disable oil paint effect

* Input type: `boolean`

### 💚 OilPaintRadius
Set the oil paint effect radius (1-10)

* Input type: `number`

### 💚 RoundedEdges
Enable or disable rounded edges for lines

* Input type: `boolean`

### 💚 CornerRadius
Set the corner radius for rounded edges (1-20)

* Input type: `number`

### 💚 DashedLine
Enable or disable dashed line effect

* Input type: `boolean`

### 💚 DashLength
Set the dash length for dashed lines (1-50)

* Input type: `number`

### 💚 DashGap
Set the gap between dashes (1-50)

* Input type: `number`

## <kbd>Getters:</kbd>
**MathFlowers** has total 16 getter properties.

### 🟢 White
Returns the color White

* Return type: `number`

### 🟢 Black
Returns the color Black

* Return type: `number`

### 🟢 Red
Returns the color Red

* Return type: `number`

### 🟢 Green
Returns the color Green

* Return type: `number`

### 🟢 Blue
Returns the color Blue

* Return type: `number`

### 🟢 Transparent
Returns a transparent color

* Return type: `number`

### 🟢 Numerator
Get the current n value

* Return type: `number`

### 🟢 Denominator
Get the current d value

* Return type: `number`

### 🟢 AnimationSpeed
Set the animation speed (milliseconds between frames)

* Return type: `number`

### 🟢 OilPaintEffect
Enable or disable oil paint effect

* Return type: `boolean`

### 🟢 OilPaintRadius
Set the oil paint effect radius (1-10)

* Return type: `number`

### 🟢 RoundedEdges
Enable or disable rounded edges for lines

* Return type: `boolean`

### 🟢 CornerRadius
Set the corner radius for rounded edges (1-20)

* Return type: `number`

### 🟢 DashedLine
Enable or disable dashed line effect

* Return type: `boolean`

### 🟢 DashLength
Set the dash length for dashed lines (1-50)

* Return type: `number`

### 🟢 DashGap
Set the gap between dashes (1-50)

* Return type: `number`

