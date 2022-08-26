## Why
This is a clone of the google-voice-desktop app, except I've replaced voice.google.com with chat.google.com.
This way I can run both voice.google.com and chat.google.com with 2 separate accounts and 2 separate notifications.

I've also changed the icon to the old Hangouts icon to differentiate between the two.

Unfortunately, I have no way to detect when new messages appear or when the page attempts to send a notification.

When new messages appear, the exact phrase "1 new message" appears in the page source.  Once you read the message, that goes away.
This could trigger the taskbar icon change if I could read that change in the source.
I cannot figure out how to read the source and search for that variable.

However, for some reason, when notifications are turned on in Google Chat settings they seem to last longer although this seems to be random.
Typical Windows notifications can only be displayed for a maximum of 5 minutes.  This includes the official Google Chat app.
Addtionally, the timeoutType in notificationShim doesn't seem to work.

## Current Differences from the Official Google Chat App
Shows a taskbar icon (official app needs a third party app, RBTray, to minimize to taskbar).
Clicking on the message opens Google Chat (like the Google Voice app this is forked from), which the official app does not.

## Features that do not work
Cannot detect when a new message is sent as I have no idea how to capture and search the page code (although I know what should be searched for).

Without a way to detect when new messages are received, this app has limited usefulness.

Project abandoned.
