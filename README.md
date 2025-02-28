
## [Project 1: HugMeApp](https://github.com/oezguenY/HugMeApp)

This is a social app created by me that enables you to send hugs to your loved ones. This app is on TestFlight. Join the Beta: https://testflight.apple.com/join/pjvv0zGQ

![](https://github.com/oezguenY/Ozguns_Portfolio/blob/main/images/HugNew1.png?raw=true)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/main/images/HugNew2.png?raw=true)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/main/images/HugNew3.png?raw=true)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/main/images/HugNew4.png?raw=true)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/main/images/HugNew5.png?raw=true)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/main/images/HugNew6.png?raw=true)

Functionality
- Authentication (Sign Up&Log In)
- Apple Sign In
- Google Sign In
- Email
- Password Forgotten - Change Password
- Push Notifications for friend requests and hug requests
- Account and Profile Deletion
- Realtime Capabilities
- Paginated Posts Feed (20 posts per fetch)
- Making/Posting pictures & exchanging text & pictures (like Snapchat)
- Deleting Posts
- Search for users either via username or full name
- Animate GIFS

Architecture
- MVC (in hindsight, I should have picked MVVM since some VCs are just too large. For instance, the ProfileViewVC is at 2.2k lines of code)

Backend
- Firebase

Apple Frameworks Used
- Combine (SignUp VC)
- Vision (Functionality for recognizing human faces is commented out at the moment)
- AVFoundation
- UIKit

Libraries
- FirebaseAuth
- FirebaseMessaging
- FirebaseStorage
- GoogleSignIn
- AuthenticationServices
- Kingfisher
- TOCropViewController
- ImageIO

NOTE: This app is on TestFlight for Beta-Testing.
TestFlight Link: https://testflight.apple.com/join/pjvv0zGQ

## Project 2: Task Tracker

Task Tracker is an app that I created for a small business. It enables employees to write down their tasks for the day and add additional information. They also can inspect those tasks. Synchronizing sends data to a server of the company, that documents this data of every employee. Core Data was implemented so data of the user is being saved on the device.

![](https://github.com/oezguenY/Ozguns_Portfolio/blob/main/images/TaskTracker1.png?raw=true)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/main/images/TaskTracker2.png?raw=true)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/main/images/TaskTracker3.png?raw=true)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/main/images/TaskTracker4.png?raw=true)

Framework:
* UIKit

Language: 
* Swift

Architecture:
* MVVM

Apple Frameworks Used
* Combine
* Core Data

Third-Party Libraries:
* IQKeyboardManagerSwift


## [Project 3: ART](https://github.com/Ozgun92/ART)

ART is an MVC practice project. Users can either sign up/sign in or continue as guest (no authentication required). If users forget their password, they can retrieve it by clicking "Forgot password?" button and entering their mail address. The app consists of two different versions: One is the admin version, where categories can be created/edited and new pictures can be added to categories. The other is the user version, where users can enjoy these pictures and favorite them. Favorited pictures are saved and stored in a seperate Table View.

![](https://github.com/oezguenY/Ozgun_Portfolio/blob/main/images/Apple%20iPhone%2011%20Pro%20Max%20Screenshot%200.png?raw=true)
![](https://github.com/oezguenY/Ozgun_Portfolio/blob/main/images/Apple%20iPhone%2011%20Pro%20Max%20Screenshot%201.png?raw=true)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/main/images/Art2.png?raw=true)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/main/images/Art3.png?raw=true)

Backend:
* Implemented Firebase Authentication
* Monitor changes/events in database
* Upload images to Firebase Storage
* Communication with Firebase database (read/write)

Framework:
* UIKit

Language: 
* Swift

Architecture:
* Model-View-Controller

Third-Party Libraries:
* Firebase
* IQKeyboardManagerSwift
* Kingfisher

Things I learned:
* Create custom XIB Table View Cells
* Practiced backend

What I plan to implement:
* Stripe SDK for payments

## [Project 4: Uber Clone](https://github.com/Ozgun92/Uber-Clone)

Uber-Clone is an MVC practice project. Users are asked for their current location and also where they want to be dropped off. Based on the distance between pick-up and drop-off location, a quota is being calculated which varies for the three types of rides available.

![](https://github.com/oezguenY/Ozgun_Portfolio/blob/main/images/Uber1.png?raw=true)
![](https://github.com/oezguenY/Ozgun_Portfolio/blob/main/images/Uber2.png?raw=true)
![](https://github.com/oezguenY/Ozgun_Portfolio/blob/main/images/Uber3.png?raw=true)
![](https://github.com/oezguenY/Ozgun_Portfolio/blob/main/images/Uber4.png?raw=true)

Frameworks:
* UIKit 
* MapKit

Language:
* Swift

Architecture:
* Model-View-Controller

Third-Party Libraries:
* None

Things I learned:
* Feed the app dummy JSON data for testing purposes
* Work with CLLocationManager
* Create MapView Annotations

What I plan to implement:
* Possibility to tip drivers

## Project 5: STONKS

STONKS is an MVC practice project. Users can search for any US based stocks, equities & ETFs. They can calculate and project potential returns from these assets. Main features of the app were Unit Tested.

![](https://github.com/oezguenY/Ozgun_Portfolio/blob/main/images/F1.png?raw=true)
![](https://github.com/oezguenY/Ozgun_Portfolio/blob/main/images/F2.png?raw=true)
![](https://github.com/oezguenY/Ozgun_Portfolio/blob/main/images/F3.png?raw=true)

Frameworks:
* UIKit 
* Combine

Language:
* Swift

Architecture:
* Model-View-Controller

Third-Party Libraries:
* MBProgressHUD
* Loaf

Things I learned:
* Pass data with Combine
* Write Unit Tests



