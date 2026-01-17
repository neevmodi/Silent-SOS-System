# Silent SOS – Emergency Alert Android App

## About the Project
Silent SOS is a personal safety Android application designed to help users send emergency alerts without making calls or drawing attention.

The app allows users to:
- Save trusted contact numbers
- Set a custom SOS message
- Trigger emergency alerts by shaking the phone or holding a button for 3 seconds

Once triggered, the app fetches the user’s live location and sends an SOS message via SMS.

## Features
- Hard shake detection (tuned to avoid false triggers)
- Long-press emergency button
- Real-time GPS location sharing
- SMS alert to trusted contacts
- Strong vibration feedback
- Works without unlocking the phone

## Technologies Used
- Android (Kotlin)
- Accelerometer Sensor
- GPS / Location Services
- SMS Manager
- SharedPreferences (Firebase simulation)
- Python & C (logic prototyping and explanation)

## Use Case
Designed for emergency situations such as harassment, accidents, or medical emergencies where the user cannot openly use their phone.

## Future Improvements
- Firebase real-time database integration
- Background service for screen-off detection
- Auto-call feature
- Guardian dashboard

## Developed By
Team NUTS
