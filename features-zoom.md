# Zoom Features
AVStudio's AV features like playing media and showing them on a second screen can be used without joining a Zoom meeting. 
But AVStudios full potential is leveraged when combined with Zoom.

![image](https://github.com/avstudiojw/avstudio/assets/166111109/cae2f8b7-5802-4e3c-baaa-2c8ebff8867b)

- Basic
  - mute/unmute self
  - video on/off self

- Toast Notifications in vibrant colors with quick actions, when ..
  - AVStudio has no co-host privilages
  - someone entered the waiting room, QUICK ACTION-> admit
  - active speaker changed
  - spotlighted users changed, QUICK ACTION-> spotlight off
  - chat message has arrived
  - someone is unmuted, QUICK ACTION-> mute / mute all
  - someone raised hand, QUICK ACTION-> lower hand 

- Participants Pane
  - search for participants
  - automatic participant count (real participants not tiles)
  - ordered by categories
    -  waiting room
    -  spotlighted
    -  unmuted
    -  raised hand
    -  participants
  - actions
    -  mute/unmute
    -  video on/off
    -  rename
    -  admit, put to waiting room
    -  spotlight on/off

- Chat Pane
  - receive and send messages from and to other participants

- Views
  - change how tiles are beeing displayed how and whenever you want, with one click
  - active speaker view
  - spotlighted users view (automatic activation)
  - screen share view (automatic activation)
  - gallery view with popup actions  
  - second full screen window with active speaker shown on second screen


### Join a Meeting
Enter your Meeting Id, User Name and Password to join a meeting

![image](https://github.com/avstudiojw/avstudio/assets/166111109/70240200-6d69-43e5-b04e-db278c0e7186)

### Add Meeting
If you have recurring meetings, you can add a meeting to your settings. It than will be shown in your combobox.

![image](https://github.com/avstudiojw/avstudio/assets/166111109/cff4c9f0-fd9d-4d02-b7c9-d1955eccb7b0)

### YOU NEED CO-HOST privilages
With AVStudio you can not log in as host and start a meeting. 
You can only share media, and administring participants when having Co-Host privilages.

A toast notification is shown, if you have not such privilages.

!IMPORTANT 
If you use AVStudio on the same computer as the host, the host has to "leave to computer audio"!

![image](https://github.com/avstudiojw/avstudio/assets/166111109/16107ad0-b0df-4c19-9b7e-0fee423287b6)

### Control Bar
With the control bar you have direct access to all the main functions of AVStudio.
The buttons are big and colored so your eyes can easily see if yor audio or video is on or off.

![image](https://github.com/avstudiojw/avstudio/assets/166111109/92d0627a-0ec2-4803-83ab-1f7e2442b8dd)

### Screen Sharing
If any media is anywhere clicked in AVStudio, it will automaticly start screen sharing. No further action required.
- images do not share computer sound
- songs and videos do share computer sound

The View switches to the screen share view.
You can switch to active speaker or gallery view anytime and come back to screen share view.

A toast notification will popup with text "... is sharing screen". This is helpfull if someone else is sharing his screen. It either way you can stop your or his screen sharing by clicking the quick action: stop.

The button "share" in the control bar turns green.
You can than stop the screen sharing by clicking the button. The media does not stop, though. Only the screen share within Zoom stops!

![image](https://github.com/avstudiojw/avstudio/assets/166111109/7f5eb48a-5f21-4c70-b0b1-d9b2dd1cfd3c)

### Menu Bar
You can switch views back and forth
- Active Speaker or spotlighted participants
- Gallery
- Screen Share (only available when someone is sharing its screen)
- maximize Zoom in a seperate independent window

![image](https://github.com/avstudiojw/avstudio/assets/166111109/a2e6421c-fa3f-493e-8714-9972567ddab3)

### Maximize Zoom in a seperate Window
You can maximize the Zoom active speaker view in a seperate window independent from your Zoom panel.
The window will show the active speaker or other participants when spotlighted. If someone shares its screen it will then show the shared screen.

### Chat
A toast notification will popup if a message as been sent. It will automatically disappear after 1 minute.

Chat messages can be send via the chat pane. It can be activated by the control bar.
The chat pane will automatically activated when a message has been received.

![image](https://github.com/avstudiojw/avstudio/assets/166111109/122f80c2-17b5-458d-a01b-26bc5d0a259f)

## Participants
With AVStudio you can administring the participants in your Zoom meeting

### Participants Pane
The Participants Pane can be activated by the button User in the control bar.

Unlike the Zoom client, participants are grouped by categories.
- Waiting Room
- Spotlighted
- Unmuted
- Raised Hand
- Participants (all, joined)

Within each category you have quick action, like mute/mute all in the "Unmuted" category.

Participants can appear multiple times
You also can filter Participants in the search bar.

### Waiting Room
If someone enters the waiting room, a toast notification will appear. You are now are able to use a quick action to admit the participant to the meeting.

You also will see a category apear in the participants pane, and will also be able to admit the participant or admit all waiting in the room to the meeting. 

![image](https://github.com/avstudiojw/avstudio/assets/166111109/2915e8c4-1ff1-4df8-853f-aebcd7c33a9a)

### Automatic admit Participants
Under meeting setting you have the option to automatic admit all to the meeting.

NEW: You can define a whitelist, with all named (wildcarded) participant name that should be admitted automatically.

![image](https://github.com/avstudiojw/avstudio/assets/166111109/19c30eb5-bfa0-4d92-ab29-a42b0fcf5f36)

### Unmuted Participants
If someone unmutes itsself, it will be noticed by a toast notification als well as a category in the participants pane. 
You then have quick actions to unmute those participants.

![image](https://github.com/avstudiojw/avstudio/assets/166111109/1b5d1a61-d29a-4f75-a190-188a93a7e5aa)

### Raised Hand
If someone raised his hand, it will be noticed by a toast notification. You then have quick actions to lower its hand.

![image](https://github.com/avstudiojw/avstudio/assets/166111109/77869c3c-d026-4acf-8cf8-7cb7f5a0d246)

### Spotlight
You can spotlight multiple participants. They will appear as the active speaker. Because no one else can speak besides the spotlighted ones.
A toast notification will popup. You then have a quick action to turn the participants spotlight off. Additonally a new category will apear in the participants pane.

The speakers view will switch and will show the spotlighted participants.

![image](https://github.com/avstudiojw/avstudio/assets/166111109/e41c9061-a65c-44bc-a9ff-62b0192f9363)

### Participants
#### Automatic Participant Count
Participants are now counted by numbers not by tiles!
Any apearing number up to two digits but maximum 9 will be added to the total participants count.
Examples
- Smith -> 1
- (2) Johnson -> 2
- Brown -4- -> 4

#### Other Action
Other actions regarding participants are available via context menu.

![image](https://github.com/avstudiojw/avstudio/assets/166111109/e201e91a-ad62-47c9-95f5-8278a9d8a000)




