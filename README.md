# Sample NFC Kit  

A simple Flutter app to read and write NFC tags using `flutter_nfc_kit`.  

## Getting Started  

### 1️⃣ Install Dependencies  

Run the following command to install required packages:  

```sh
flutter pub get
```


### 2️⃣ Platform-Specific Setup

#### 📱 Android
Ensure your device has NFC enabled.
Uses Android 19 (KitKat) and above.

#### 🍏 iOS
Only works on iPhone 7 and later with iOS 13+.



### 4️⃣ Running the App
To run the app on a physical device (NFC is not supported on emulators):

```sh
flutter run
```


### 5️⃣ Features
📖 Read NFC tags

✍️ Write custom data to NFC tags

🔄 Erase NFC tag content


### 6️⃣ Troubleshooting
Ensure your phone supports NFC and is turned on.
If you face build issues, try:

```sh
flutter clean
flutter pub get
```


## 🚀 Contributing
Feel free to fork and submit descriptive pull requests!
