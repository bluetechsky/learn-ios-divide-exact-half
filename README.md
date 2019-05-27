# learn-ios-divide-exact-half
## How to format 2 elements fit each into exact 1/2 of iOS device (iPhone, iPad...)

See how it look like:
## iPhone
### Portrait
<img width="50%" alt="iPhone Portait screenshot" src="screenshots/Image-7.png">


### Landscape
<img width="50%" alt="iPhone Lanscape screenshot" src="screenshots/Image-6.png">


## iPad Pro
### Portrait
<img width="50%" alt="iPad Pro Portait screenshot" src="screenshots/SimulatorScreenShot-iPadPro12.9-inch-2019-05-27_0911.png">

### Landscape
<img width="50%" alt="iPad Pro Lanscape screenshot" src="screenshots/SimulatorScreenShot-iPadPro12.9-inch-2019-05-27_0912.png">


## How to
- Add 2 Views: namely GreenView + BlueView
- Control + drag GreenView to its parent in Document Outline
- Add constraint : Equal Height
- Then edit Proportional Height "multiply: 1:2" in Size Inspector
- Set Left + Top + Right constraint to 0

Next
- Control + drag BlueView to GreenView in Storyboard
- Add constraint: Equal Height
- set Left + Bottom + Right constraint to 0

Done
