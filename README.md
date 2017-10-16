# ARCore test 

#### Install Android Studio version 2.3 or higher with Android SDK Platform version 7.0 (API level 24) or higher.
* You will need a supported Android device.
* You will need to get the ARCore SDK for Android Studio. You can either:

Download the SDK preview for Android Studio and extract it.

-or-
Clone the repository: `git clone https://github.com/google-ar/arcore-android-sdk.git`



#### You must use a supported, physical device. ARCore does not support virtual devices such as the Android Emulator. To prepare your device:

* Enable developer options
* Enable USB debugging
* Install the ARCore Service on the device:
* Download the ARCore Service
* Connect your Android device to the development machine with a USB cable

Install the service by running the following adb command:

`adb install -r -d arcore-preview.apk`

In Android Studio, open the HelloAR sample project in `<ARCore SDK Folder> /samples/java_arcore_hello_ar`
