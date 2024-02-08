# SmellDC

## Description
SmellDC is an app that allows users to report smells about areas within Washington DC. Users can use the map to select a location within DC to use as the location for their 
smell report on or simply view the daily smell reports submitted by other users of the app (the map only shows user reports submitted on the current day). 
The map uses markers to represent an individual user report that was submitted that day. A pink marker represents a report submitted by another user, while a red marker 
represents a report submitted by the currently logged in user. Clicking on these markers allows the user to view detailed information within that report.

Users are also able to view a quick summary of the submitted reports so far for that day separated by region (Northwest, Northeast, Southwest, and Southeast). 
This summary, or 'Quick Stats', includes the total number of reports for each region, number of each report rating, and number of reported health issues.

In addition to creating and viewing daily smell reports, users can view their history of submitted reports.

User authentication and report related data is stored through the Google Firebase platform.

## Demo 
https://youtu.be/QpzEfbjMJ7k

## Images
### Login page

<img src="images/1.png" width="400" height="700">

### Creating account

<img src="images/2.png" width="400" height="700">

### Welcome page

<img src="images/3.png" width="400" height="700">

### User's history of submitted reports

<img src="images/4.png" width="400" height="700">

### Interactive map

<img src="images/5.png" width="400" height="700">

### All submitted user reports (represented by map markers)

<img src="images/6.1.png" width="400" height="700">

### Clicking on a user report marker reveals details of that individual report

<img src="images/6.2.png" width="400" height="700">

### Creating a report by first selecting a location on the map

<img src="images/7.png" width="400" height="700">

### Smell report form 

<img src="images/8.png" width="400" height="700">

### Summary of all submitted user reports by region

<img src="images/9.png" width="400" height="700">



## List of external libraries and code used in this project

Icons from Freepik.com

com.google.firebase.FirebaseApp

com.google.firebase.auth.FirebaseAuth

com.google.firebase.auth.FirebaseUser

com.google.firebase.database.FirebaseDatabase

com.google.firebase.database.DatabaseReference

com.google.firebase.database.DataSnapshot

com.google.firebase.database.DatabaseError

com.google.firebase.database.ValueEventListener

com.google.android.gms.maps.GoogleMap

com.google.android.gms.maps.CameraUpdateFactory

com.google.android.gms.maps.OnMapReadyCallback

com.google.android.gms.maps.SupportMapFragment

com.google.android.gms.maps.model.BitmapDescriptorFactory

com.google.android.gms.maps.model.LatLng

com.google.android.gms.maps.model.LatLngBounds

com.google.android.gms.maps.model.Marker

com.google.android.gms.maps.model.MarkerOptions
