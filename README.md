# Geocoding/Mapping with Unity Mapbox
![unity maps](https://user-images.githubusercontent.com/18353476/28991456-c8952bc8-793c-11e7-9e15-42da3ad593e8.png)

Create and Style the tile layers of your map(2d or 3d) for any augmented reality and virtual reality applications.

![map style](https://user-images.githubusercontent.com/18353476/28952342-5d2ab572-7885-11e7-8030-2c1017f9172a.PNG)
![map4](https://user-images.githubusercontent.com/18353476/28952494-6aef7c8c-7886-11e7-98ff-167490a6623b.gif)
![sf map](https://user-images.githubusercontent.com/18353476/29289910-273357a0-80f3-11e7-93ba-9ba40aae97be.gif)

# Vulkan Support 
Vulkan is a new generation graphics and compute API that provides high-efficiency, cross-platform access to modern GPUs in both PCs and on mobile platforms. Android Nougat version 7.0 from Google brings official support for the Vulkan API.The main benefit of Vulkan over older mobile rendering APIs such as OpenGL ES 3.x is speed. Vulkan is designed to take advantage of multiple CPU cores by allowing the application to build command lists in multiple threads in parallel. This allows the application to take advantage of all of the CPU cores on the device, improving performance.

To enable Vulkan support, open “Player Settings”, go to the “Other Settings” pane and clear the “Auto Graphics API” checkbox. You are presented with an ordered list of graphics APIs to choose from. If Vulkan is not on that list, click the ‘+’ sign at the bottom of the list to add it. Then drag Vulkan to be the first item on the list so that it’ll be used whenever supported, and you’re done! All your existing shaders will get translated to Vulkan SPIR-V.
![vulkan](https://user-images.githubusercontent.com/18353476/28993201-7543d586-7965-11e7-8e9c-f93b7079e2bf.PNG)

# Requirements and installation
![mapbox-unity](https://user-images.githubusercontent.com/18353476/28955677-13871fce-789d-11e7-8899-4f1917ba6336.PNG)

Mac OS
Coming soon.
Xamarin Studio is the recommended IDE.

Linux
Coming soon.

Getting started: https://www.mapbox.com/mapbox-unity-sdk/docs/00-getting-started.html

Configuring your API token: https://www.mapbox.com/mapbox-unity-sdk/docs/01-mapbox-api-token.html

Known Issues: https://www.mapbox.com/mapbox-unity-sdk/docs/02-known-issues.html

Built-in Examples: https://www.mapbox.com/mapbox-unity-sdk/docs/03-examples.html

Attribution: https://www.mapbox.com/mapbox-unity-sdk/docs/04-attribution.html

API: https://www.mapbox.com/mapbox-unity-sdk/api/

Changelog: https://www.mapbox.com/mapbox-unity-sdk/docs/05-changelog.html

IMPORTANT: If you intend to deploay for Android, please set your minimum version to 15 in PlayerSettings.
For iOS, please set your minimum version to 8.
