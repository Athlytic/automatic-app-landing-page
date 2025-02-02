---
layout: page
title: Troubleshooting
include_in_header: false
---

## First! 
Note that most of the time whether on iPhone or Apple Watch, force closing the app, powering down the device and back on, or uninstalling and reinstalling Athlytic (you will not lose any of your data if you do this) will solve 90% of all issues! 

## Recovery

### Why Hasn't Recovery updated since this morning?

Athlytic (and many others’) concept of Recovery is that it reads either your sleeping HRV or HRV derived from a morning Mindfulness Ap session along with Resting Heart Rate to give you a Recovery score for the day you should base your training on. (Note that because Apple updates RHR throughout the day you may see further adjustments in your Recovery score however usually they don’t swing as wildly given that RHR is a bit more stable than HRV)

If you want your Recovery to update every time a new HRV sample is taken, then you would turn off sleep prioritization in Settings. However studies have shown that waking HRV is less accurate to rely on given that it could be influenced by external stressors like work etc., so for this reason Athlytic ships with sleep prioritization turned on.

So long story short, waking up and having 1 Recovery pretty similar throughout the day is expected behavior.

### Why does Recovery Change Throughout the Day?
Athlytic will use your your average sleeping HRV or an HRV that was sampled during a morning Mindfulness App Session for your Recovery each day.  However, Apple treats resting heart rate (RHR) differently.  The Apple Watch will save 1 single RHR each day and update it throughout the day (as opposed to saving multiple samples like it does with HRV, you can see this yourself by going into the Apple Health App then Browse then Heart).  Because of this there may be slight variations in Recovery throughout the day, e.g. you wake up and your RHR is 55, then at 2pm, it’s 53, Recovery will increase slightly.  To address this issue, Athlytic now can save its own RHR sample into Apple Health based on your average HR during sleep.  To enable this go into the More Tab and tap on Recovery Customization and turn on Enable Athlytic to Save Resting Heart Rates.  Provided you wear your watch to sleep, this will prevent Recovery from updating throughout the day.

### Recovery Always Seems Low
First are you wearing your watch to bed or doing a Breathe App session immediately after waking? Remember Recovery is derived from your HRV and resting heart rate against your baseline of each.  So even though we may get a full night’s rest and feel great, if HRV and RHR are well below/above baseline then our body is signaling that it feels stressed, which might not be only from a hard workout but could be related to many things like alcohol from the previous night or just normal everyday life stress.   Also if you recently got your Apple Watch, then you don’t have a 60 day baseline of HRV and RHR data to compare against, so the more you wear your watch this will not be an issue. 

### Recovery says 0
Check if you might not have an HRV reading from the past day.  You can see your HRV samples by going into the Apple Health App (white icon with a heart) then Browse -> Heart Rate Variability -> scroll to the bottom and tap on Show All Data, and see if you have an HRV from today. 

### Recovery on iPhone different than on the watch
First be aware that Apple Watch complications are only permitted by Apple to be updated 4 times per hour, so sometimes Recovery may not match on the iPhone’s Widget, App, and Apple Watch App’s complication if a recent HRV or RHR has been observed. 

If you find that they are constantly different, look closely at the 60 day baseline HRV and RHR under recovery (the small number in parenthesis), now compare this to the same numbers on the Apple Watch under Recovery.  

If they are different, this may be an iCloud or Background Task issue.  Because Apple limits queries on the Apple Watch to no more than 7 days, Athlytic uses a background task and iCloud to post the 60 day HRV and RHR baselines so the Watch App can read them.  To trouble shoot this issue try these steps: 

(1) Go to Settings on the iPhone, then tap on your name at the top, then tap on iCloud and turn off iCloud for Athlytic, then turn it back on.  (It should always be turned on).  Then Power the watch down and on again.

(2) If go back to Settings on the iPhone and then General then Background App Refresh, check that you have Background App Refresh turned on at the top, and then that Athlytic's switch turned on.


### Recovery High when Use the Breathe App
Because the Apple Watch only gives us a few HRV samples during sleep, for a most accurate and consistent measure of Recovery we recommend that you use the Apple Watch’s Mindfulness App (formerly “Breathe App”) immediately upon waking (before picking up your iPhone and seeing any notifications (texts, emails etc.) so there are no external stressors).  During the Mindful Minute or however long you choose, most of the time the Apple Watch will also take a new HRV sample.  For reasons stated above, Athlytic will default to this single Mindfulness HRV to base Recovery on. See here for instructions on using the Mindfulness App <https://support.apple.com/en-us/HT212718>

However when you use the Mindfulness App you will notice that the app prompts you to breathe very deeply in and out.  We recommend that you do not follow the app’s prompting and just breathe normally.  The reason for this is what while breath work has been shown to improve HRV, when you are essentially doing this same breath work while trying to sample your HRV (and measure the state of your CNS) you are sort of “hacking” your HRV to be higher than it might otherwise be if you breathe normally.  If you just breathe normally as you would,  your resulting HRV sample should be much within range of your normal ranges.  Note that it can be difficult to ignore the Mindfulness App’s haptics, so we also recommend that you go into the Apple Watch app on your iPhone, then find the Mindfulness App, scroll to the bottom and set Haptics to “None.”

We also recommend that you are consistent with whether you chose to (1) do a morning Mindfulness Session every morning for your daily Recovery HRV or (2) you wear your watch to bed and  let Athlytic use your sleeping HRV for Recovery.  The reason for this is typically, even when breathing normally, HRV during the Mindfulness Session is likely going to be higher than the average of your sleeping HRV.  So to compare apples to apples, it is best to have a 60 day baseline of the same type of HRV.  

On last tip, to remind yourself to perform Mindfulness in the morning, open the Watch app on your iPhone and go to Mindfulness. Select Allow Notifications, and then, under Mindfulness Reminders, enable Start of Day. You can also tap Add Reminder to set a custom time.

### Recovery is high but my muscles are sore and I feel tired 
Recovery in Athlytic is 100% physiological based on your HRV and resting heart rate.  Athlytic does not use sleep to factor into Recovery.  The reason for this is that even if you were to get only 5 hours of sleep last night, if your body is signaling that is has fully recovered from yesterday’s workout, we don’t feel we should artificially reduce recovery just because you didn’t sleep well.  Recovery cannot however factor in soreness from a workout.  At this point there is simply no good technical way to measure muscle soreness from your wrist.  So our best advice is always listen to your body first when deciding how to train and then use a Recovery tool like Athlytic.

### Recovery Days are Missing 
You could be missing Recovery from a day if the Apple Watch didn’t take an HRV for a given day.  You can see your HRV samples by going into the Apple Health App (white icon with a heart) then Browse -> Heart Rate Variability -> scroll to the bottom and tap on Show All Data, and see if you have an HRV from the day that is missing.  If you are missing an HRV from the given day, you may have not worn your Apple Watch long enough to receive an HRV reading.

## Sleep

### Not Seeing Any Sleep Data
Athlytic reads sleep data that was saved by either your Apple Watch or another app or device and saved into Apple Health.  So you either need to set up your Apple Watch or some other app or hardware advice to track your sleep. 

To double check whether you are getting sleep data at all, go into the Apple Health App (white icon with a heart) then tap browse, then sleep and see if you have any data there. Make sure you see both “in bed” (saved by the iPhone) and “asleep” samples (saved by the Apple Watch) in the Health App, both of which Athlytic relies on for its Sleep tab.   

If you don’t see Asleep samples then your Apple Watch still isn’t set up properly to track your sleep and you need to set it up (see here: <https://support.apple.com/guide/watch/sleep-apd830528336/watchos>) or use another app like Pillow to track.  If you use another app or device other than native Apple Watch Sleep Tracking, you can select it as your preferred sleep tracker in Settings in Athlytic.  If it is not listed please let me know.  Selecting the app you use as your preferred sleep tracker usually fixes issues like seeing duplicate sleep data - however I have also seen apps like Pillow save duplicate sleep samples which uninstalling and reinstalling the app usually fixes.   

If you do see both asleep and in bed samples in the Health App, then it might be something else so please screen shot and email me what the asleep samples look like in Apple Health so that I can see the “source” listed.  

Ps if you are having trouble getting the Apple Watch’s native sleep tracking to track your sleep correctly, this has been my routine and seems to work well (1) I do have a sleep schedule set for everyday that is around the time i normally go to bed and wake up (2) if i go to bed earlier I will toggle sleep mode on, on my watch (3) as soon as I wake up in the am, usually before my sleep end/alarm time, i open my iPhone and go to the controls screen and turn off sleep mode on it.  This has consistently worked for me counting my sleep correctly. 

### Double Counting Sleep?
This usually occurs because you are using a 3rd party app or hardware device for sleep tracking, and the app or device writes duplicate sleep data into Apple Health.  Try going into Settings and setting your preferred Sleep Tracker, then go back to the sleep tab and pull down to refresh.  Please let us know if this does not fix this issue or if you are using another 3rd party app or device that is not listed.  If it doesn’t fix the issue, we may need to dig a little deeper to diagnose why your sleep is being double counted. 

## Exertion/Effort

### What is Exertion and What Affects It
Exertion is measured on a 0-10 scale using your 30-day average max heart rate (or you can set a customized max heart rate) along with your 60-day average resting heart rate. Your body accumulates Exertion for time spent above a heart rate threshold that is personalized to you.

Exertion is an indication of your cardiovascular load over a course of a day. There are many daily factors that can affect exertion other than just physical activity. These include but are not limited to stress, alcohol, your job, and even simple everyday tasks. So, yes, a long day can cause a higher Exertion, even if you have not worked out.

Athlytic also suggests a Target Exertion Zone based on your Recovery.  Note however, that, unlike Apple's Move Goal, this is not something you need to consistently hit everyday.  The Target Exertion Zone is just a recommended Zone if you are training where it is likely safer to remain in.  Avoiding going over is more important than worrying about being below.  Note also that you can set a Training Goal in Settings which will impact the bottom of the Target Exertion Zone.

### What is Effort 
Closely related to Exertion, Effort is a per workout measure of cardiovascular load during a workout.  The longer and more intense a workout is, the higher Effort will be.  Like Exertion, Effort is also based on your heart rate threshold that is personalized to you.
 
Understand that Effort is only a measure of cardiovascular load, i.e. your heart rates during a workout.  So for example if you weightlifting without a cardio component and your heart rate is not elevated you may score a lower Effort even though you are lifting heavy weight.

### Exertion Complication Not Updating
To save battery life, Apple limits apps to only being able to update complications 4 times per hour (or every 15 minutes).  Because of this, sometimes it is necessary to tap on the complication to open the app which will force a complication update.  You can see this same behavior with Apple’s Weather app where the temperature might not update until you tap on it.  However if you are noticing the complication isn’t updating even after an hour or so please let me know.  

### Heart Rate Sensor Not Reading.  
Check that you do not have power save set to on (go to the Apple Watch app on the iPhone (black icon), then general, then look for Workout Power Saving Mode).  When you turn power save on, it will disable the heart rate sensor from reading.  I personally somehow set this to on by accident and couldn’t figure out why I was only getting 3 or 4 heart rate samples per workout until I figured it out and turned it off and all is good.   If that doesn’t solve it, it might be something else so please let me know. 

### Exertion or Effort Too Low
First check that your max heart rate is correct.  Athlytic will use your max heart rate from the last 30 days by default, but you can set a custom max in Settings.  If your max is based on an anomalous HR (e.g. above 200 and your real max is 185) then your numbers might be skewing lower. 

If that doesn't solve the issue are you using a 3rd party app or device other than the Apple Watch to track heart rate?  The problem with many third party apps/devices is that they don't write data correctly to Apple Health.  Your heart rates during a workout should look like the below (logged with an Apple Watch).  For example Garmin writes HR data every 2 minutes to Apple Health, and Polar every minute (contrast this with the Apple Watch which writes HR data almost every second during a workout.  You will either need to use your Apple Watch to track heart rate or try using an app like RunGap or FitnessSyncer to try and import these other apps/devices HR data into Apple Health.  

![image](https://user-images.githubusercontent.com/78270566/150047554-23b2053a-9c31-4163-bf9f-e69083143400.png)


### Exertion or Effort Too High
First check that your max heart rate is correct.  Athlytic will use your max heart rate from the last 30 days by default, but you can set a custom max in Settings.  So if you haven't had a very high heart rate in the past 30 days, your max might be too low.  A good rule of thumb is 220 - age to start with.  Once you set your custom max, pull to refresh on any tab to refresh the data.  

## Energy (Calories burned and consumed)

### Not seeing Calories from MyFitnessPal
Make sure that MyFitnessPal is sync’d with Apple Health.  Here is how 👉 <https://support.myfitnesspal.com/hc/en-us/articles/360032271092-Apple-Health-FAQ-and-Troubleshooting> Also note that once you do sync MFP with Apple Health, MFP will only write nutrition data going forward (i.e. it will not go back and sync past days nutrition info.  To make sure that MFP is writing data to Apple Health, open the Apple Health App (White Icon with Heart) and then Browse then Nutrition.  If your nutrition data isn’t there then MFP isn’t properly writing data to Apple Health (and Athlytic cannot read it). 

### Not seeing Calories from Other App
It sounds like this app isn’t syncing properly to Apple Health since all Athlytic is doing is querying Apple Health for this data and it isn’t returning anything.  Try this:  go to the Apple Health App (white app icon with red heart), then Nutrition -> Dietary Energy then scroll down to the Bottom to “Show All Data” and screenshot the list of calories as well as tap on one of the samples so that we can see it as well.  If there is nothing here then there isn’t any data for Athlytic to read and the problem is on the other app’s end syncing to Apple Health.  Please let us know! 

## Apple Watch Issues

### App Won’t Install on Watch
The Watch app requires WatchOS 7, an update Apple shipped in September 2020.  Apple has dropped  support for Apple Watches Series 0, 1, and 2 and so those watches cannot run Watch OS 7 If you're still running an earlier version of Watch OS you'll need to update to install the free update through the Watch app on your phone (you can check this by going to the Watch app on your iPhone and then General -> Software Update).

If you're running a recent version of watchOS but Athlytic isn't showing on the Watch, there are steps to try:
1. Do you have auto-install enabled for Watch apps? Did it maybe not auto-install? Is it in the middle of installing? Head into the Watch app on your phone and scroll down to see if Athlytic is available for install. As you scroll down you'll pass Apple's apps first, then currently installed third party Watch apps, then third party apps that have yet to be installed (and those in the middle of being installed). You should see Athlytic in one of those last two sections and that'll give you a clue as to what is going on.
2. I hate the cliched answer, but have you rebooted your phone and Watch? Many users say this solves the issue.
3. If Athlytic isn't anywhere in those lists, try deleting and reinstalling the Athlytic iOS app from the App Store.


If you already knew that, sometimes getting apps to load on the Apple Watch can be buggy, I tried to get an app to install on my Series 6 last week and it took many tries.  What you want to do is go to the Watch app on your iPhone (black app icon), from there scroll down to "available apps", you'll see Athlytic ....tap install.  (This is where I had to try multiple times before it seemed to "stick") and finally install.  Also doing this in different WIFI or cellular environments seems to help.  

If you still cannot get it to install, try searching for Athlytic on the Apple Watch’s App Store App, this should get it to finally install. 

## Not seeing any data at all
This is usually an Apple Health  permission issue, can you try this:  uninstall the app and reinstall which will bring up the screen that asks for Apple Health permissions and make sure you check them all. 


## Watch subscription not unlocked
Thanks for reaching out.  After you subscribe on the iPhone it will sometimes take a new launch of the iPhone and watch app to pick up the subscription. First try force quitting the iPhone app and reopening.  This should send your active subscription to the watch.  

If that alone doesn’t help the watch pick up the subscription, can you please try powering off the watch and then on and tell me if it detects the subscription?  If it still doesn’t unlock Athlytic Pro on your watch, can you go into Settings, then tap on your name at the top, then tap on iCloud and scroll down and make sure Athlytic is turned on for iCloud.  Athlytic on the watch requires iCloud to communicate your subscription status from the iPhone to the watch.  

Finally if nothing else seems to work please try these steps: (1) go back to Settings, then tap on your name at the top, then tap on iCloud and turn off iCloud for Athlytic, then turn it back on.  Then (2) Power the watch down and on again.  👈 This usually solves most sync issues with subscriptions on the watch.  

Also try this: If you go to Settings on the iPhone and then General then Background App Refresh, do you have Background App Refresh turned on at the top, and then is Athlytic's switch turned on? 

## Complication Not Updating
To save battery life, Apple limits apps to only being able to update complications 4 times per hour (or every 15 minutes).  Because of this, sometimes it is necessary to tap on the complication to open the app which will force a complication update.  You can see this same behavior with Apple’s Weather app where the temperature might not update until you tap on it.  However if you are noticing the complication isn’t updating even after an hour or so please let me know.  

## Getting Recovery HRV RHR on IPHONE BUT NOT WATCH
Check that you do not have Wrist Detection turned off on the watch.  Open the settings app on the Apple Watch, tap Passcode and see if Wrist Detection is off.  Turning off Wrist Detection will prevent the Apple Watch from tracking Heart Rate so turn it back on. See more here: 

Turning off wrist detection affects these Apple Watch features:

When you use Apple Pay on your Apple Watch, you’ll be prompted to enter your passcode when you double-click the side button to authorize the payment.
	Some Activity measurements are unavailable.
	Heart rate tracking and notifications are turned off
	<https://support.apple.com/guide/watch/lock-or-unlock-apple-watch-apd0e1e73b6f/watchos>

## Miscellaneous Issues

### Why Vo2 Max Doesn’t Show Up for non Athlytic workouts on Trends Tab
This was a design decision...right now when you tap on a workout and see the workout detail page you will always see a Vo2 Max as it calculates it on the fly.  However, on the trends Vo2 Max chart it is a little too CPU expensive to calculate it for every workout (since you have to query for all the workouts, then do a separate query for heart rates for each workout) and this would cause too big of a performance hit, so this chart is just asking Apple Health for Vo2 Max which only the Apple Fitness App and Athlytic save, so if it was logged with another app or the Apple Fitness App but not a running, walking, or hiking workout, there won't be a Vo2 Max returned from the query.  If you want to see Vo2 Max for every workout then you either need to log it with the Athlytic watch app or it the Apple Fitness App (and again has to be running, walking, or hiking).  

### Family Sharing
Yes Athlytic is available for family sharing!  At some point down the road we may introduce a higher subscription tier with family sharing but you would be grandfathered in.  Right now there is no extra cost for a pro subscription (either annual or monthly).  To set up family sharing see here: <https://support.apple.com/en-us/HT201088>.  To see how to share subscriptions with family members see here: <https://support.apple.com/guide/iphone/share-subscriptions-and-icloud-storage-iph6e7917d3f/ios#:~:text=Share%20Apple%20subscriptions%20and%20an,then%20follow%20the%20onscreen%20instructions>.  Please note that I have also heard that it can take over an hour on Apple’s end from the time you purchase on 1 device until the app is available on the other device.  

### How to cancel Subscription
To cancel your subscription go to the App Store App and tap on your profile on the top right.  Then tap on subscriptions. From here you can review your active subscriptions and cancel any so they will not automatically renew.  If you don’t mind me asking, is there something in Athlytic that could be improved that would make you subscribe again? 

### Strava Workouts Not Syncing to Apple Health
Athlytic relies on data being saved to Apple Health, so it sounds like your Strava workouts are not being imported into Apple Health.  You can double check whether the workouts are there or not by going into the Apple Health App (White App Icon with Red Heart), then Browse -> Activity -> Workouts then scroll to the bottom and tap on show all data.  If the workouts are not listed here, there is no way Athlytic can pull them.  See here for how to get Strava to sync to Apple Health 👉 <https://support.strava.com/hc/en-us/articles/216917527-Health-App-and-Strava>.   

### Strava Via Run Gap Heart Rates Not Syncing to Apple Health
Athlytic relies on data being saved to Apple Health, so it sounds like your Strava Heart Rate data is not being imported into Apple Health.  If the data isn't being saved into Apple Health then Athlytic has no way to get it to use it.  See here for how to get Strava to sync to Apple Health 👉 <https://support.strava.com/hc/en-us/articles/216917527-Health-App-and-Strava>.  

You can double check whether your heart rate data is in Apple Health by going to the Apple Health App (white icon with red heart) then tap on Browse then Heart Rate then scroll to the bottom and tap on show all data and see if they are there.  Again if they aren't present here then there isn't anything for Athlytic to read. If there is nothing else that works, anecdotally I have heard (from Garmin Users) that a 3rd party app FitnessSyncer might work to try and get the data sync'd I can't vouch for it though since I only use Apple Watch myself. 

### How to make Garmin or Oura Ring sync to Apple Health
Athlytic relies on integration with Apple Health, so primarily its going to work best on an Apple Watch, however we do have a few users who also use Garmin/Oura in addition to their Apple Watch and they have told me its kind of a hack but possible to push the Garmin/Oura data to RunGap or FitnessSyncer (3rd party apps) and then let then write the workout to Apple Health.  I can’t attest to how well this works though.

If your issue or question isn't listed here, please email us at <athlytic@gmail.com>

