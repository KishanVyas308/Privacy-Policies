# Privacy Policy for AptiCore

*Last updated: July 4, 2026*

We respect your privacy and are committed to protecting the personal data of our users. This Privacy Policy describes how we handle information in the AptiCore mobile application (the "App").

---

## 1. Complete Offline Architecture (No External Data Collection)

The App is built with an offline-first architecture. This means your study data is kept private to your device.
* **SQLite Local Database:** All learning progress, subject/topic practice attempts, quiz answers, bookmark logs, incorrect answer logs, and study session timers are stored locally on your device in a secure SQLite database.
* **Local Settings and Profile Storage:** Your profile information (such as your chosen nickname and avatar emoji), along with app settings (your custom target exams and dates), is stored locally using `AsyncStorage`.
* **No Cloud Synchronization:** The App does not synchronize, mirror, or upload your data to external servers, cloud providers, or databases.
* **No Analytics or Tracker SDKs:** We do not collect, monitor, or transmit usage statistics, crash logs, or behavioral analytics to third-party services.

---

## 2. Home Screen Widgets and Local Shared Preferences

To support the App's home screen widget functionality:
* **Shared Preferences:** Your active target exam goal, exam date, and selected widget style are written to a secure local key-value store (`SharedPreferences` on Android).
* **Local Widget Rendering:** The native home screen widgets read this local storage directly to render your countdown progress on your home screen launcher. 
* **Zero Network Traffic:** No widget configuration or countdown data is transmitted over the network.

---

## 3. Permissions Requested by the App

The App may request the following device permissions to operate:
* **Notifications:** Used to deliver periodic study reminders and target milestones. These notifications are scheduled and triggered entirely locally on your device by the operating system, with no push notification server involved. You can disable this permission at any time in your device settings.

---

## 4. Data Retention and Deletion

* **App Uninstallation:** Because all progress and configuration data is stored locally, uninstalling the App will permanently delete all of your SQLite databases, AsyncStorage configurations, and widget preferences. This action is irreversible.
* **Clearing App Storage:** If you wish to wipe all data without uninstalling the App, you can select "Clear Storage" or "Clear Data" under the App's settings menu inside your device's system settings.

---

## 5. Changes to This Privacy Policy

We may update this Privacy Policy to reflect future changes to the App. If we introduce cloud synchronization, backup solutions, or authentication features in future releases, we will request your explicit consent and update this policy to detail the data collection, transmission, and processing policies before any features are activated.

---

## 6. Contact Us

If you have any questions or feedback regarding this Privacy Policy or the App's offline architecture, please reach out to us via our local support channels or repository contact methods.
