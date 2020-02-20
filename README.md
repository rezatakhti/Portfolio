# Portfolio






## Bookie - Session Tracker 
### On the [App Store](https://apps.apple.com/us/app/bookie-session-tracker/id1493326511?ls=1)

Bookie is an app that allows you to track each time you read, so you can track both how much you read and how fast you read over a period of time.

<img src="https://user-images.githubusercontent.com/36284798/71433420-ee670b80-2693-11ea-8aa8-f419360eded7.png" width="190">  <img src="https://github.com/rezatakhti/Bookie---Session-Tracker/blob/master/Bookie%20-%20Session%20Tracker/Assets.xcassets/01MainScreen_framed.imageset/01MainScreen_framed.png" width="190">  <img src="https://github.com/rezatakhti/Bookie---Session-Tracker/blob/master/Bookie%20-%20Session%20Tracker/Assets.xcassets/02NewSession_framed.imageset/02NewSession_framed.png" width="190">  <img src="https://github.com/rezatakhti/Bookie---Session-Tracker/blob/master/Bookie%20-%20Session%20Tracker/Assets.xcassets/03PastSessions_framed.imageset/03PastSessions_framed.png" width="190">

#### Few Concepts Used and Learned
* Storing small bits of data using User Defaults 
* Persisting larger data using a Singleton Core Data 
* Passing data between view controllers using Delegates and Protocols 
* Creating custom view by subclassing existing UIKit classes
* Constraints using Autolayout and NSLayoutAnchor






## CryptoTracker

<img src="https://user-images.githubusercontent.com/36284798/74476913-310cbf00-4e5f-11ea-8861-1833d3c7d6da.png" width="250"> <img src="https://user-images.githubusercontent.com/36284798/74476915-323dec00-4e5f-11ea-815e-c28e0d69e4c2.png" width="250"> 

This application uses CoinGecko API to display cryptocurrency prices. It was created using a purely programmtic UI, and I'm overall very happy about the look and feel of the app. I wanted to go for a simple yet professional design while gaining more experience with URL Session. 

#### Important Concepts Used
 - Designed application from scratch in Sketch
 - Used Charts framework to create, animate, and allow user interaction with a line chart 
 - Used URL session to make API calls and created a JSON with received data using Swift's Codable protocol
 - Used collection view flow layout for main page, and created card view for second page using a child view controller 
 - Layed out all constraints programmatically using NSLayoutAnchor
 - Used UIView.animate to create constraint animations and CADisplayLink for text animations
