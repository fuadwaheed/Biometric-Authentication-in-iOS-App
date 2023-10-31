# Biometric-Authentication-in-iOS-App

In today's digital age, security is paramount. Users expect their personal information to be kept safe. Biometric authentication is a powerful way to enhance the security of your iOS app. 
In this blog post, we'll guide you through the process of implementing biometric authentication using Face ID and Touch ID in your iOS application.

We'll create a Singleton class that handles this authentication and explain how to request the necessary permissions, useage of default images for all three types of biometric Authentication (i.e. touchID, faceID and the new opticID), where to save login information, and what to do if the user denies permission.

Mostly, biometric authentication being used to do login. This code shows other way to use biometeric authentication as well.
This project have 
Singleton Classes 
1. 'KeychainManager'
2. 'BiometricAuthManager'
    
Controllers
1. LoginVC in it you will see Authentication using Biometric Authentication and also storying user credentials in KeychainManager.
2. BalanceVC in it you will see balance being hidden then you will unhide balance using biometric authentication
3. SettingsVC in it you will see switch to turn on/off Biometric Authentication
   
Views
1. Main Storyboard contains all views
2. LaunchScreen Storyboard contains Launch View
