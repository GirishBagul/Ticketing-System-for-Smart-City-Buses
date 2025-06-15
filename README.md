# Ticketing System for Smart City Buses

A smart mobile-based ticketing and passenger tracking system designed to improve public transportation management using IoT and app development technologies. The project combines a bidirectional visitor counter and mobile application to ensure accurate fare collection, crowd control, and passenger safety.

## 🔧 Components & Technologies Used
- Arduino Uno
- Bidirectional IR Sensor Module
- NodeMCU / ESP8266 (optional for Wi-Fi)
- Flutter (for mobile app)
- Firebase (real-time database)
- QR Code Scanner (in-app)

## 📋 Features
- Real-time crowd tracking using bidirectional sensors
- QR-based ticket scanning via mobile app
- Live data sync with Firebase
- User registration and bus pass generation
- Entry/exit detection using IR sensors
- Reduces manual ticketing and improves safety

## 🛠️ Tools
- Arduino IDE (sensor-side logic)
- Firebase Console (database management)
- Flutter (cross-platform app development)

## 📂 How It Works
1. Passengers register through the mobile app.
2. Upon boarding, they scan a QR to log their entry.
3. IR sensors count in/out movement to validate physical presence.
4. Fare and movement data is synced to Firebase in real time.
5. Upon exit, passengers scan the QR again to mark trip completion.

## 🎯 Benefits
- Enhances passenger management and reduces overloading.
- Promotes digital fare systems and ecological sustainability.
- Suitable for buses, public events, and crowded venues.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
