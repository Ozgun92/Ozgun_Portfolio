## [Project 1: HugMeApp](https://github.com/oezguenY/HugMeApp)

This is a social app created by me that enables you to send hugs to your loved ones.

![](https://github.com/oezguenY/Ozguns_Portfolio/blob/6922fc529561951c4830a4892eabc93d0c2c7340/images/HugNew1.png)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/0d6129efea7803ce36bcae71ee87b1d7eff60508/images/HugNew2.png)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/7b15dd50ba4069936ead1a46c0f9366f6730c8df/images/HugNew3.png)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/7b15dd50ba4069936ead1a46c0f9366f6730c8df/images/HugNew4.png)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/7b15dd50ba4069936ead1a46c0f9366f6730c8df/images/HugNew5.png)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/7b15dd50ba4069936ead1a46c0f9366f6730c8df/images/HugNew6.png)

Functionality
- Authentication (Sign Up&Log In)
- Apple Sign In
- Google Sign In
- Push Notifications
- Account and Profile Deletion
- Realtime Capabilities
- Paginated Posts Feed (20 posts per fetch)
- Making/Posting pictures & exchanging text & pictures (like Snapchat)
- Deleting Posts

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

Task Tracker is an app that I created for a small business. It enables employees to write down their tasks for the day, how long they took them and add additional information. They also can inspect those tasks. Synchronizing sends data to a server of the company, that documents this data of every employee. Core Data was implemented so data of the user is being saved on the device.

![](https://github.com/oezguenY/Ozguns_Portfolio/blob/a42e6989c9df9cfef8814f663f83b3fb1b314b3b/images/TaskTracker1.png)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/d1459a2c6c2780f69be1b02cb40c598dc3126c5b/images/TaskTracker2.png)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/d1459a2c6c2780f69be1b02cb40c598dc3126c5b/images/TaskTracker3.png)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/d1459a2c6c2780f69be1b02cb40c598dc3126c5b/images/TaskTracker4.png)

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
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/a51c168da7f9e882f0d31938cf78a795e543f90c/images/Art2.png)
![](https://github.com/oezguenY/Ozguns_Portfolio/blob/a51c168da7f9e882f0d31938cf78a795e543f90c/images/Art3.png)

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

## [Project 5: Star Wars Lexicon](https://github.com/Ozgun92/StarWars-Lexicon)

StarWars-Lexicon is an MVC practice project. Users can press on a button which triggers a web request. This web request gets a random StarWars character in JSON.

![](https://github.com/oezguenY/Ozgun_Portfolio/blob/main/images/SWL1.png?raw=true)
![](https://github.com/oezguenY/Ozgun_Portfolio/blob/main/images/SWL2.png?raw=true)
![](https://github.com/oezguenY/Ozgun_Portfolio/blob/main/images/SWL3.png?raw=true)
![](https://github.com/oezguenY/Ozgun_Portfolio/blob/main/images/SWL4.png?raw=true)

Framework:
* UIKit

Language: 
* Swift

Architecture:
* Model-View-Controller

Third-Party Libraries:
* Alamofire
* SwiftyJSON

Things I learned:
* Use different methods for web requests: Alamofire with Codable, Alamofire with SwiftyJSON, just Alamofire, and conventional URLSession


## Project 6: STONKS

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



