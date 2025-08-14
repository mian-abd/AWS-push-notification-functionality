# AWS Push Notification System

A full-stack mobile push notification solution built with **AWS**, **Firebase**, and **Android** that demonstrates cloud architecture and mobile development expertise.

## 🚀 Key Features

- **Real-time Push Notifications** via Firebase Cloud Messaging
- **AWS Lambda Functions** for serverless notification processing  
- **AWS SNS** for scalable message delivery
- **Android Application** with modern Kotlin architecture
- **Cross-platform Notification Support** (Android/GCM)

## 🛠️ Technology Stack

**Backend & Cloud:**
- AWS Lambda (Node.js)
- AWS SNS (Simple Notification Service)
- AWS SQS (Simple Queue Service)
- Firebase Cloud Messaging

**Mobile:**
- Android Studio
- Kotlin
- Firebase SDK
- Android Fragments & Lifecycle Management

## 📋 Architecture Overview

1. **Android App** generates unique device tokens upon registration
2. **Firebase** manages device token registration and message routing
3. **AWS SNS** creates endpoints for each device and manages subscriptions
4. **AWS Lambda** triggers notification delivery via SNS topics
5. **Firebase Cloud Messaging** delivers notifications to target devices

## 🏗️ Project Structure

```
├── Source-Code/
│   ├── Android-Source-Code/     # Complete Android application
│   ├── Lambda-Function/         # AWS Lambda notification handler
│   └── google-services.json     # Firebase configuration
```

## 💡 Technical Highlights

- **Serverless Architecture**: Leverages AWS Lambda for cost-effective, scalable processing
- **Real-time Messaging**: Implements Firebase FCM for instant notification delivery
- **Modern Android Development**: Uses Kotlin, Fragments, and Android best practices
- **Cloud Integration**: Seamlessly connects AWS services with Firebase ecosystem
- **Production-Ready**: Includes proper error handling and lifecycle management

## 🔧 Setup & Configuration

1. **AWS Setup**: Configure SNS topics and Lambda functions
2. **Firebase Setup**: Add google-services.json to Android project
3. **Android Build**: Import project in Android Studio and build
4. **Testing**: Use provided Lambda test function for notification validation

---

**Skills Demonstrated:** Cloud Architecture • Mobile Development • Serverless Computing • Real-time Systems • AWS Services • Firebase Integration • Kotlin • Node.js