# Reasons to Root
## Add Power Management Exceptions to Google Play Services and Google Framework Services to allow notifications to pass through apps
https://www.reddit.com/r/Onyx_Boox/comments/1qxgdfh/comment/o3zo8k7/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button

# Not receiving calls, not able to place calls
https://www.reddit.com/r/Onyx_Boox/comments/1qlzbwz/comment/o2qvwkd/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button
> Update: phone dialing is no longer working. I ditched Good2Go because it was spotty reception in my area and picked up Tello. With Tello SMS works but phone calls both incoming and outgoing do not work. It's the same symptoms that I outlined above. When I try to dial a number, the interface resets to a blank state without the phone number.

> I got it working by debugging with Gemini. Tried scores of adb commands and finally the last step I did was to enable the app to be on top of other apps.
> 1. Long press the Phone App
> 2. Manage
> 3. Switch to "On" the "Display on top of other Apps" setting.

> Now dialing is working. Incoming calls also work, including the ringer and haptics. To enable the ringer:

> 1. BOOX Settings app
> 2. Sound
> 3. Select "Sound Mode" to "Sound". Mine was on "Mute"
