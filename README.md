# Firebase Push Notifications Handler

A comprehensive Dart class for handling **Firebase Push Notifications** in a Flutter app. This service manages notifications seamlessly in all states:

- **Foreground**: Notifications are displayed while the app is active.
- **Background**: Notifications are handled when the app is minimized.
- **Terminated**: Notifications work even when the app is completely closed.

Additionally, it integrates **Local Notifications** to display alerts while the app is in use, making the implementation straightforward and reusable for any Flutter project. 🛠️

---

## 🚀 Features

- **Handles All Notification States**:
  - Foreground
  - Background
  - Terminated
- **Local Notifications**: Displays notifications inside the app using `flutter_local_notifications`.
- **Easy Integration**: Modular and reusable for any Flutter project.
- **FCM Token Support**: Fetches and prints the Firebase Cloud Messaging token for device-specific notifications.
