# learn-ios-divide-exact-half
## How to format 2 elements fit each into exact 1/2 of iOS device (iPhone, iPad...)

See how it look like:
## iPhone
<table>
	<tr><th>Portrait</th><th>Landscape</th></tr>
	<tr>
		<td><img width="200" alt="iPhone Portait screenshot" src="screenshots/Image-7.png"></td>
		<td><img width="250" alt="iPhone Lanscape screenshot" src="screenshots/Image-6.png"></td>
	</tr>
</table>

## iPad Pro
<table>
	<tr><th>Portrait</th><th>Landscape</th></tr>
	<tr>
		<td><img width="300" alt="iPad Pro Portait screenshot" src="screenshots/SimulatorScreenShot-iPadPro12.9-inch-2019-05-27_0911.png"></td>
		<td><img width="350" alt="iPad Pro Lanscape screenshot" src="screenshots/SimulatorScreenShot-iPadPro12.9-inch-2019-05-27_0912.png"></td>
	</tr>
</table>


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
