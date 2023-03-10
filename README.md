# DamnOverSharp

## An easy to use library for creating in-app overlays for different games and programs.

![image](targetProcessWPFdemo.png)

### Features:
- Works in both windowed and fullscreen mode
- DirectX 9, 10 and 11 support (DirectX 12 and Vulkan coming soon!)

### 3 Renderers:
- WpfRenderer: Allows the user to host WPF controls with mouse events and keyboard input
- ChromiumRenderer: Allows the user to host a Chromium instance with full input passtrough (also supports transparency!)
- GraphicRenderer: Allows the user to Draw a Bitmap on the screen (can be updated every frame)

## Example

A simple sample project can be found in the project repo, which contains samples for the usage of all 3 renderers.

#### Screenshot of the target app (in this case Muck lol) rendering the WPF control
![image](targetProcessWPFdemo.png)

#### Screenshot of the example's UI
![image](exampleApp.png)

#### The control being hosted in game in the WPF designer
![image](designerWPFdemo.png)
