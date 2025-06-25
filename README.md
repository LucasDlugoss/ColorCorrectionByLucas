🎨 Color Correction by Lucas to Comfy UI

A custom ComfyUI node that offers advanced controls for color correction, noise, and blur.

✨ Features

This node allows you to adjust the following parameters of an image:

•
🌈 Hue: Adjusts the color tone (-180° to +180°)

•
💧 Saturation: Controls the intensity of colors (0 to 3x)

•
💡 Brightness: Adjusts the overall image brightness (0 to 3x)

•
🔆 Contrast: Controls the difference between light and dark areas (0 to 3x)

•
⚡ Gamma: Adjusts mid-tone brightness (0.1 to 3.0)

•
📺 Noise: Adds random noise to the image (0 to 1)

•
🌫️ Blur: Applies Gaussian blur (0 to 10 pixels)

📦 Installation

Method 1: Manual Installation

1.
Download the color_correction_by_lucas.zip file.

2.
Extract its contents into your ComfyUI's custom_nodes folder:

3.
Restart ComfyUI.

Method 2: Via ComfyUI Manager (if available)

1.
Open ComfyUI Manager.

2.
Search for "Color Correction by Lucas".

3.
Click "Install".

4.
Restart ComfyUI.

🚀 How to Use

1.
In ComfyUI, search for "Color Correction by Lucas" in the image/color category.

2.
Add the node to your workflow.

3.
Connect an image to the node's input.

4.
Adjust the parameters using the sliders:

•
Hue: Negative values shift towards red, positive towards blue.

•
Saturation: 0 = black and white, 1 = normal, >1 = more saturated.

•
Brightness: 0 = black, 1 = normal, >1 = brighter.

•
Contrast: 0 = uniform gray, 1 = normal, >1 = more contrast.

•
Gamma: <1 = darker, 1 = normal, >1 = lighter.

•
Noise: 0 = no noise, >0 = adds random noise.

•
Blur: 0 = no blur, >0 = applies Gaussian blur.



5.
The corrected image will be available at the output.

🎯 Included Presets

The node includes pre-configured presets accessible via the right-click context menu:

•
🔄 Reset All Values: Restores all parameters to their default values.

•
🎯 Enhance Colors: Improves colors and contrast.

•
🌙 Vintage Look: Applies a subtle vintage look with noise and blur.

🎨 Visual Interface

•
Colorful Sliders: Enhanced visual interface with gradients.

•
Visual Icons: Each parameter has an identifying icon.

•
Context Menu: Quick access to presets and information.

•
Author Signature: "by Lucas" visible on the node.

🔧 Interface Features

•
Reset All Values: Right-click on the node and select "🔄 Reset All Values".

•
About: Right-click and select "ℹ️ About Color Correction".

•
Presets: Access pre-defined settings via the context menu.

📋 Requirements

•
ComfyUI

•
Python 3.8+

•
PyTorch 2.0+

•
PIL (Pillow)

•
OpenCV (cv2)

•
NumPy

🐛 Troubleshooting

Node does not appear in the list

•
Verify that the folder was extracted correctly into custom_nodes.

•
Fully restart ComfyUI.

•
Check the console for error messages.

Error "module 'cv2' has no attribute..."

•
Install OpenCV: python -m pip install opencv-python.

•
Use the specific Python environment of ComfyUI for installation.

Slow performance

•
For very large images, consider resizing before correction.

•
Gamma and blur adjustments might be slower on high-resolution images.

💡 Usage Tips

•
For dark photos: Increase brightness and adjust gamma.

•
For faded photos: Increase contrast and saturation.

•
For color correction: Adjust hue subtly.

•
For artistic effects: Combine multiple adjustments.

•
For vintage look: Use the "Vintage Look" preset or manually adjust noise and blur.

📝 Changelog

v1.0.0

•
Initial release.

•
Support for HUE, Saturation, Brightness, Contrast, Gamma, Noise, and Blur.

•
Custom visual interface with colorful sliders.

•
Pre-configured presets.

•
Batch processing support.

👨‍💻 Author

Created with ❤️ by Lucas

📄 License

This project is distributed under the MIT License. See the LICENSE file for more details.

🤝 Contributions

Contributions are welcome! Feel free to:

•
Report bugs

•
Suggest new features

•
Submit pull requests

📞 Support

If you encounter any issues or have questions, please:

1.
Check the troubleshooting section above.

2.
Look for similar issues in the repository.

3.
Create a new issue with problem details.





Enjoy color correcting! 🎨

