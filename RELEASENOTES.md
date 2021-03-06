![](images/adsmall.png)

# ACE Direct

## Release Tag: v2.0 (11/01/2017)

* Identity and Access Management implementation
* NGINX implementation
* Videomail recording
* Videomail retrieval
* BusyLight integration
* BusyLight customization page
* 508-Compliance for BusyLight default color scheme
* Agent WebRTC for incoming calls
* Improved WebRTC for customer complaints
* Migrate to Chrome
* Agent portal screen enhancements
* Management Portal UI enhancements
* Consumer portal screen enhancements
* Consumer portal landing entry page: Email (future), Phone (future), and Video Call
* Configurable Consumer portal redirect URL (specify and enable/disable)
* Upgrade to latest JSSIP library
* Integration of Sorenson client devices and apps
* Installer enhancements
* Secure code review resolutions

## Release Tag: v1.1 (02.10.2017)

* Increased character limit in WebRTC RTT implementation
* Call transfer functionality from one agent to another
* A new Agent Status window
* Acceptance of inbound PSTN calls
* The use of a secure protocol (HTTPS) during web transmissions
* Encoding of userids and passwords
* Enhanced documentation in the README files and in the source code
* Segmentation of application servers to increase system scalability 
* Additional software changes to improve scalability and reliability

## Release Tag: v1.0 (11.02.2016)
Release v1.0 of ACE Direct (initial public release)

* This ACE Direct public release software was demonstrated to the FCC.

## Release Tag: v0.0

* The version of code just before creating the develop branch.

## Release Tag: 20161102qa

* Implemented Zphone consumer Option #4 logic
* Implemented Zphone consumer Option #5 logic
* Implemented Linphone consumer Option #4 logic
* Implemented Linphone consumer Option #5 logic

## Release Tag: 20161101qa

* Resolved issue where unanswered call caused CSR to go "in use"

## Release Tag: 20161031qa

* logo changes
* Cosmetic 
* new AD logo (image)
* new AD logo on login page
* new AD logo on complaint form


## Release Tag: 20161028qa

* Implement "in call" icons for both queues
* Assistance URL for CSR portal is configurable
* Node handles hangups in Linphone Consumer use case; properly transitions to call wrapup

## Release Tag: 20161027qa

* Fixed duration label wrapping
* Added in scripts box to main content area and made vrs and ticket info tabs on call details container
* Updated the Zendesk URL to use the hostname for the ESB rather thanthe IP address
* Implemented Assistance button from CSR Portal to Management Portal
* Implemented Linphone Consumer USE case
* Implemented update of existing Zendesk ticket
* Enhancements to "in call" status indicator
* Can update Zendesk subject and problem description (comment)

## Release Tag: 20161025qa

### CSR Portal

* Can now update problem description (in Zendesk, this is a new comment field from the CSR)
* Now handling Consumer calling in on Linphone
* CSR must ask the Consumer, calling in on Linphone, for VRS number
* Ticket Save button now CREATES a ticket for Consumer calling in on Linphone
* Fixed Call Duration
* Added "in call" indicator next to the CSR queue name

## Release Tag: 20161024qa

### CSR Portal

* Display queues that agent belongs to
* RTT is now character-by-character
* Call duration is implemented
* Register/unregister complaints and general info. queues
* Pause/unpause complaints queue and general info. queue together
* Dynamically change Tab title based on agent role
* Call Agent Information in Gear Settings tab is now hidden
* Zendesk ticket update is now working (for modifying subject field only)
* Alert added for Zendesk ticket update
* Clicking agent queue toggles script (brings into focus) in script tab

### Complaint Form

* RTT is now character-by-character

## Release Tag: 20161019qa

* Complaint Form: subject is bounded at length 80
* Complaint Form: new character counter for Complaint Description
* Complaint Form: chat message is bounded at length 140
* Complaint Form: new phone and email icons
* Complaint Form: fixed general button style that was conflicting with AdminLTE style
* Complaint Form: disable Submit button after consumer creates a ticket
* Complaint Form: disable Call button after consumer makes a call
* Complaint Form: enable Call button after ticket creation
* Complaint_form: added error class for invalid phone number format
* Complaint_form: phone number validation
* CSR Portal: new script logic function
