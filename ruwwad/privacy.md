# Ruwwad — Privacy Policy

*Version 2 · updated 20 October 2026*

**The Ruwwad phone app does not send your activity to us.** Prayer times and the Qibla direction are calculated on your device, and
the app works without an internet connection.

This policy covers the phone app and the optional Ruwwad Prayer Times skill for Alexa.
The phone sections below describe data kept on your device. The Alexa section explains
the separate server data needed for voice requests and automatic routines.

## Your location

Prayer times and the Qibla depend on where you are, so the app needs a location. It
gets one of two ways, and **both stay on your device**:

- **Your device's location**, if you grant permission. It is used on your device to
  calculate times and the Qibla bearing. **It is never sent to us.** To show you the
  name of the town you are in, iOS looks that name up using Apple's own service, which
  means your approximate location goes to Apple in the same way it would for Maps or
  the weather. It goes nowhere else, and we never see it.
- **A city you choose from a list**, if you would rather not grant permission.

**Location permission is optional.** The app is fully usable without it — the city
picker covers every function. If you have granted it and change your mind, iOS
Settings will revoke it and the app keeps working.

## What else the app stores

On your device only:

- Your chosen calculation method, madhab, high-latitude rule and any manual
  adjustments to prayer times.
- Your notification preferences.
- Your dhikr counts and streaks.
- Your chosen or detected location.

Some of this is written to a shared container so the widgets can read it. That
container is on your device and is readable only by these apps.

## The phone app: no account, no sign-in

There is nothing to sign in to. The app has no accounts, asks for no name or email
address, and has no server of ours to hold one. Everything it knows about you is on
your device, and deleting the app deletes it.

## Finding a mosque

If you search for a nearby mosque, that search is carried out by **Apple Maps**, the
same as searching in the Maps app. The search text and the area you are looking in go
to Apple. Nothing goes to us and no search is recorded on your device.

## Checking for a new version

From version 1.1, Ruwwad checks once a day whether a newer version is on the App Store,
so it can tell you when one is out. It asks **Apple's App Store**, not us. The request
contains only Ruwwad's App Store number. It carries **nothing about you**: not your
location, not anything you did in the app, and no cookies are kept. Apple sees it the way
it sees any request to the App Store. Nothing goes to us.

If a newer version is out, the app shows a notice and, if you allow notifications, sends
one. You can switch the check off in **Settings → About → Check for updates**; then no
request is made at all.

## Notifications

Prayer reminders are **local notifications**, scheduled on your device in advance.
There is no push server, and no notification passes through anyone else's system. The
notice about a new version is a local notification too. From version 1.1 the app may wake
briefly in the background to keep your reminders scheduled and to run the version check.

## Ruwwad Prayer Times on Alexa

Alexa is an optional, separate service. Amazon handles your voice under its own privacy
notice. Ruwwad receives the recognized command and its details (such as a city or surah), and a skill-specific user code, not a voice
recording, your home address, your name or your email. Requests can contain the city or
recitation you ask for. The phone app and Alexa do not share your settings.

**What we store:** your chosen city, Asr calculation choice, whether the UK Asr explanation
has been given, prayer switches, listening position and completed recitations, and monthly
reading-plan progress. Optional morning/night recitation also stores whether each schedule
is enabled, its selected recitation, its delay after Fajr or Isha, and the last sensor signal
and open/closed state. These are used to answer you, resume listening, and run the routines
you choose. They are not used for advertising or behavioural tracking.

**Optional Amazon linking:** Login with Amazon requests only your Amazon user ID. We store
that ID, the link to the voice user code, Alexa's service region, and the access/refresh
credentials Amazon issues for sensor events. We do not request your name or email. These
credentials are used only to send the Adhan, Morning Recitation and Night Recitation signals.
They are not included in our application logs or public files.

**Where:** settings and linking data are held in our AWS database in Ireland. Skill requests
can be processed by our AWS functions in Ireland or Northern Virginia, USA, according to
Amazon's regional routing. Amazon also handles requests and routine data under its own terms.

**Playback:** your Echo downloads Qur'an recordings directly from cdn.islamic.network.
It downloads full adhan recordings from our CloudFront audio hosting. Like any internet
audio request, the serving provider receives connection details such as the device's public
IP address. Fajr is Besim Azemi / Islamic Center Malmö, CC BY 3.0; other prayers use
Beautiful adhan, CC0. Recitation is Sheikh Muhammad Ayyub / King Fahd Complex, via Islamic
Network. Our skill does not send the audio providers your voice user code or linking credentials.

**Routines and reminders:** automatic playback requires routines you create in Alexa.
Morning and night recitation schedules are off until enabled. Spoken reminders you request
are created in your Amazon account only after you grant reminders permission. We keep no
separate copy of those reminders; manage them in Alexa.

**Deletion and stopping:** say **“Alexa, ask Prayer Times to forget my city”** to delete your
saved voice settings, listening progress, account mapping and event credentials. Disabling
the skill also triggers deletion when Amazon delivers the skill-disabled event. Revoked
credentials are removed when Amazon rejects their use. Unlinking alone does not guarantee
an immediate notification to us. To stop playback immediately, disable the routines in Alexa;
you may also turn off the adhan, morning recitation and night recitation by voice before
unlinking. Amazon's copies of routines, reminders and voice history are managed in Alexa.

Your Alexa settings and progress are kept until you request deletion or Amazon delivers a skill-disabled event.

Technical logs from our Irish AWS function contain running times and errors and are retained for 30 days. We do not deliberately
log request bodies, event credentials or your recitation history. No server settings are
shared with the phone app.

## What is not in the phone app

- **No advertising.**
- **No analytics of any kind.**
- **No tracking**, across apps or websites.
- **No account of any kind** — nothing to create, nothing to sign in to, and no
  password.

## What Apple sees

If you have agreed in your iOS settings to share analytics with developers, Apple
gives us **aggregate, anonymous** figures — installs, sessions, crash reports. We
cannot see individuals in that. You can turn it off in **Settings → Privacy &
Security → Analytics & Improvements**.

## Deleting everything

Deleting the phone app removes its local settings. It does not delete the separate Alexa
settings: use the Alexa deletion command above for those.

## Changes

Version 2 adds the optional Alexa skill, full adhan hosting, listening progress, linked
Amazon sensor events and optional prayer-relative recitation. The phone app and Alexa data are described separately.


If the app ever gains a feature that changes any of this, this policy will be updated
before that feature ships, and the date at the top will change.

## Contact

**boltontechnicalsupplies@gmail.com**
