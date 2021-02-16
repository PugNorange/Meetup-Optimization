# Meetup-Optimization
Web/iOS app that optimize individual meetups
This is the client-side application. When the user(sender) sets their destination, traveling mode, and contact info, the information will be send via text message to the client. When the client opens up the url, it will start subscribe to the specific uuid topic mqtt messages.
The sender-side(iOS app) will keep updating the gps current location every 5-10ft change. 
Using the Google Map JavaScript Library, it can get the estimated time arrival. In addition, when the route changes, it will automatically update on the web app side so the client can know exactly where, how, when the sender arrives.

![Architecture Overview](https://github.com/PugNorange/Meetup-Optimization/blob/main/documentation/architecture_overview.png)
