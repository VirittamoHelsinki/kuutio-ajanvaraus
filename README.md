# kuutio-ajanvaraus
Kuutio is an application for booking a conference room located in Virittämö Helsinki. The front-end is made with React and the back-end uses Google Firebase services. 

The user can book a conference room by selecting the time of day and stating the subject of the booking.

<img src="public/kuutio_booking.png" alt="drawing" width="66%"/>

The user can view the bookings made and delete them as needed. The admin user can view and delete all bookings.

<img src="public/kuutio_manage.png" alt="drawing" width="66%"/>

# How to run the project

1. Clone the project from https://github.com/VirittamoHelsinki/tyoaikakirjaus.git
2. Run "npm install"
3. Copy your own Firebase config settings from your own Firebase project and replace settings in src/firebase/firebase.js file
4. Start the project "npm run dev"
