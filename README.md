# GPS Spoof

Simulate your iOS location with GPS coordinates. 


## Requirements

 1. Download/Update **[Xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12)** from the Mac App Store
 2. Download [this](https://github.com/Lukejb14/GPS-Spoof/archive/master.zip) repository


## Setup

 3. Open [GPS Spoof.xcodeproj](https://github.com/Lukejb14/GPS-Spoof/tree/master/GPS%20Spoof.xcodeproj "GPS Spoof.xcodeproj") with Xcode
 4. Open **Location.gpx** in the Xcode project
 5. Edit **line 37** in Location.gpx to the GPS coordinates of your choice

 Example Line 37: `<wpt lat="25.197204"  lon="55.274283">`


## Run GPS-Spoof

6. Select your device
7. Press '**Play**' button in top left. (Wait for 'Build Succeeded' to pop up)
8. Select **Debug** > **Simulate Location** > **Location**
9. Done! *Check if it worked by going to your maps application.*

![Video demo on how to run GPS-Spoof](https://i.imgur.com/GCP8oqA.gif)
