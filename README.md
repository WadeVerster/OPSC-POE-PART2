# OPSC-POE-PART2
OPSC POE PART 2
# MoveMindSA
**youtube video link:** https://youtube.com/shorts/7mypBo0hJWM?feature=share

# MoveMindSA 🧠🏃‍♂️🌿

**MoveMindSA** is a comprehensive wellness and fitness tracking mobile application developed for Android devices. It is designed to support individuals on their journey to better mental and physical health by providing tools for movement tracking, wellness monitoring, and mindful living.

## 🧩 What is MoveMindSA?

MoveMindSA stands for "Move Mind South Africa" — an initiative to encourage healthier lifestyles by promoting **physical activity**, **nutritional awareness**, and **mental wellness** through daily engagement.

In today’s fast-paced and often stressful world, it's easy to neglect both physical movement and mental well-being. MoveMindSA provides a simple and user-friendly platform that helps users become more aware of their daily habits, set personal goals, and track their progress across multiple dimensions of wellness.

---

## 📱 Key Functionalities

### 🏃 Workout Tracking
Users can log different types of physical activities and track their workouts over time. This includes viewing progress, setting goals, and analyzing past performance to stay motivated.

### 🧠 Wellness Logging
MoveMindSA encourages mindfulness and mental well-being by allowing users to log wellness activities such as sleep, mood, meditation, or rest. This helps build a more holistic view of overall health beyond just physical metrics.

### 🍎 Food Logging
Users can input meals and snacks to track their daily nutritional intake. This supports healthy eating habits and raises awareness of food choices.

### 📍 Location-based Features
The app uses GPS and location services to enhance fitness experiences, such as tracking walking or running routes, or enabling context-aware features based on where the user is.

### 🔔 Smart Notifications
MoveMindSA sends personalized reminders to encourage activity, wellness check-ins, hydration, or rest. It also integrates with Android's notification and scheduling systems to deliver helpful nudges throughout the day.

### ⚙️ Background Services
The app includes background services such as a battery-aware broadcast receiver and location tracking services to continue monitoring activity and sending alerts, even when the app is not in the foreground.

---

## 🎯 Why Use MoveMindSA?

- **All-in-One Wellness Tool** – Combines fitness, food, and mental health tracking in one app.
- **User-Centric Design** – Focuses on simplicity, ease of use, and daily engagement.
- **Motivational Features** – Helps build consistent habits through tracking, reminders, and progress visualization.
- **Locally Relevant** – Designed with the South African user in mind, but applicable globally.

---

## 🌐 Vision

The goal of MoveMindSA is to **bridge the gap between physical and mental health** by empowering users with simple tools to take charge of their well-being — one mindful move at a time.

Whether you're starting a fitness journey, trying to eat healthier, or just want to be more present in your daily life, MoveMindSA is here to support you.

---

## 💡 Future Enhancements (Planned)

- Integration with wearable devices (e.g., smartwatches)
- Mood analytics and wellness insights
- Community features and wellness challenges
- Data export and cloud syncing

---

> MoveMindSA is more than a fitness tracker — it's a companion for a healthier, more balanced lifestyle.


## ✨ Features

- ✅ User Authentication (Login/Register)
- 🏃 Workout Progress Tracking
- 🍎 Log Daily Meals
- 🧠 Wellness Activity Logging
- 📍 Location-based Services using Google Maps
- 🔋 Background Service & BroadcastReceiver (e.g. Battery Low Detection)
- 🔔 Notification Support
- 🌐 Internet & Network State Monitoring


## 🛠️ Tech Stack

- **Language:** Kotlin
- **Architecture:** MVVM (or your architecture, if different)
- **Build System:** Gradle
- **Libraries:**
  - AndroidX
  - Google Maps SDK
  - Google Services
  - JUnit & AndroidX Test for Unit & Instrumentation Testing

## 📦 Project Structure
app/
├── activities/
├── dashboard/
├── services/
├── res/
├── AndroidManifest.xml


## 🔧 Setup & Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/movemindsa.git
   cd movemindsa

🔐 Permissions Required

This app requires the following permissions:

INTERNET

ACCESS_FINE_LOCATION

ACCESS_COARSE_LOCATION

ACTIVITY_RECOGNITION

POST_NOTIFICATIONS

RECEIVE_BOOT_COMPLETED

ACCESS_NOTIFICATION_POLICY

ACCESS_NETWORK_STATE

Make sure to handle runtime permission requests in newer Android versions.

🧪 Testing

Unit and Instrumented tests are available under:

src/test/java/.../ExampleUnitTest.kt

src/androidTest/java/.../ExampleInstrumentedTest.kt





