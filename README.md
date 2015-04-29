# November Strategy data collection tool
November Wire-frame design for app collecting strategy meeting data

##Wireframe only demonstrates end user specs
The behavior is like what a typical user now sees on their iPad only solution

##Backend is reason for switch
Back end is technically owned by November, however is a great concept
Reason for moving away from here is a fixed license fee.
Looking to host this in a cloud based on temporal assignment and availability

##security
Security should be enabled by a short key-word which locks the unique token a client has collected
All client data is now tied into the group, the user only needs to supply his name for validation against an unknown list

##configuration
Most visible data is dynamic edited by the November team and subject to change from one strategy session to the other.
The list of meeting members and keywords can separate the different members of that team.
There needs to be a near real time monitoring feature displaying who entered what.

##HTML/ReactiveExtensions/Rest
I believe a light weight client over a secure channel with tiny real time updates to make sure the progress is monitored

##screenshots
Concept of the default screen:
![default](images/screenshot1.jpg)

Concept of the details entry screen:
![data entry](images/screenshot2.jpg)