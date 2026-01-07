# ☕️ Prendiamo Un Caffè Insieme!

## Simple coffee spending web app
Got a new coffee machine for Christmas - lucky me. Decided to build a web app to track our spending (or more importantly, **saving**) when we use it. Used the opportunity to play around with Firebase hosting for the first time.

* Frontend: Vanilla JS, HTML5, CSS3
* Backend: Firebase (Auth, Realtime Database)

Site can be seen at https://caffe-insieme.web.app/

Basic functionality of inputting to a user in database everytime a coffee is submitted. Checks for if entry has been provided when trying to submit "Out".
Firebase auth checks for particular users to be logged in, and if so, they can commit. Regular users (guest or logged in but not matching email permissions) are in read only so can still see the amounts and where, but can't contribute.