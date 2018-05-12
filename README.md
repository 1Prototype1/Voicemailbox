# Voicemailbox
An offline voicemail service that answers incoming call automatically if not answered by the user, tells caller to leave a message,records it and then notifies the user when the screen is unlocked.

<b>Basic Idea:</b><br>
- Answer call after timeout.
- Play recorded message.
- Record voicecall.
 <br> 
<b>Approach:</b><br>
  I am first going to try this on Tasker and then try to create a standalone app.
  <br><br><br>
  <b>Progress:</b><br>


```diff
+ Answer Call
+ Greetings mp3[Customized][Thanks to Julie]
+ Play mp3 through speaker
+ Mute microphone
+ Record Call
- Notify user when screen unlocked
- Play mp3 silently(Speaker ATM)~~Skipped[Maybe not possible]
```
Above steps are working **without Root**  which is great!:wink:<br>
**Testing Device:**
Redmi 4x Android Oreo 8.1 [SDK 27]
<br><br><br>
# Why to pay when you can get it for free!:smiling_imp:
