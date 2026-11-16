---
title: Tarmach Privacy Policy
---

**Effective date:** 16 November 2026

## The short version

Tarmach records your journeys using your iPhone's own sensors and keeps them
on your iPhone. There is no Tarmach account, server or analytics service. The
app does not upload your journeys, photos or vehicle records to the developer.

BMW sync and fuel-price lookups contact other services when you enable them.
The app also uses Apple Maps for some maps and nearby searches. The details
are below.

## Who is responsible

Tarmach is developed by **Harry Salt**, a sole trader based in London,
United Kingdom, who is the data controller for the limited purposes
described here.

**Contact:** <tarmach.spill850@passmail.net>

[Tarmach support](support/)

## What the app collects, and where it goes

### Stored on your device

The app keeps the following in its storage area on your iPhone:

- **Location while recording a journey** — approximately one position per
  second while a journey is running, including speed, heading and altitude,
  forming the route you see on the map.
- **Motion data** — the app uses accelerometer and gyroscope readings to
  estimate braking, acceleration and cornering. It normally saves the events
  detected from them. If you switch on **Capture raw motion** in Settings, it
  also saves the sensor readings in a separate file that you can export or
  delete.
- **Journey records** — start and end times, distance, duration, and the
  places you start and finish at.
- **Vehicle records** — anything you enter yourself: cars, registrations,
  service history, modifications, documents and photographs.
- **Fuel and charging records** — fills, charges, prices, odometer readings
  and any receipt photographs you scan or attach.
- **App settings** — your preferences, stored in the iPhone's standard app
  settings area.

Receipt scanning is performed **on your device**, by iOS itself. Receipt
images are not uploaded for processing.

### Sent to third parties, only when you use the relevant feature

**1. BMW CarData** — if, and only if, you connect a BMW.
Connecting exchanges an approval code with BMW's servers; the resulting access
tokens are stored on your iPhone. When you sync, your vehicle's identifier is
sent to BMW and odometer, fuel, tyre and service readings are returned and
stored locally. This never happens unless you have connected a car.
BMW's handling of that data is governed by BMW's own privacy policy.

**2. DVSA MOT History** — registration lookup is unavailable in the public
App Store build. In development builds with the integration configured, the
app can send a registration to the UK Driver and Vehicle Standards Agency's
MOT History API to return make, model and MOT history. Adding a registration
to the Garage in the App Store build keeps it in the app's records.

**3. Fuel prices** — if, and only if, you agree to it. Your precise location is
sent to `checkfuelprices.co.uk` to find nearby stations and their prices.
The request includes the coordinates and search radius. Tarmach does not add
an account or an app user identifier to it. **The app asks before the first
such lookup**, on the fuel map, and the fuel-price provider receives no lookup
requests from the app unless you agree.

Once you have agreed, three parts of the app use it:

- the **fuel map**, while you are looking at it;
- the **add-refill form**, to fill in the station you are standing at;
- and the **forecourt reminder**, which checks the location of a stop the app
  has noticed — a few minutes, somewhere you do not usually stop — so it can
  ask whether you have just filled up. **This one happens in the background**,
  while a journey is being recorded, rather than while you are looking at a
  screen. It is the only lookup that does. You can turn it off on its own in
  Settings › At the pump, and it is off entirely unless you have agreed to the
  lookup above.

**4. Apple Maps** — some map screens use Apple Maps for the basemap or for
nearby places such as charging stations. Requests can include the area you
are viewing or the location used for the search. Apple explains how it handles
such requests in [Apple Maps & Privacy](https://www.apple.com/uk/legal/privacy/data/en/apple-maps/).

If you export or share data, you choose where it goes. Your iPhone backup
settings determine whether iOS includes app data in a device backup.

### While Tarmach is in beta (TestFlight)

Beta builds are distributed through Apple's TestFlight. If you have enabled
sharing in iOS, Apple may provide the developer with **crash reports and basic
usage statistics** for this app, and any feedback or screenshots you choose to
submit through TestFlight. This is handled by Apple, is not part of the app
itself, and stops when the beta ends. You can turn it off in
iOS Settings › Privacy & Security › Analytics & Improvements.

## What is never collected

- You can use the app's journey and vehicle features without creating a
  Tarmach account. BMW sign-in is managed by BMW for that optional feature.
- No advertising, no advertising identifiers, no tracking across apps or
  websites, and no data sold or shared with data brokers. The app's privacy
  manifest declares tracking as `false`.
- The app does not include an analytics service.
- The app does not read your contacts, calendars or health data. If you attach
  a photo, the app receives the photo you select.

## Why the app asks for location access

With **While Using** access, you can start a journey in Tarmach and it can
continue recording when the screen is locked. **Always** access is needed for
a journey started by an automation while the app is in the background and for
iOS to relaunch the app in the background to recover an interrupted journey.
The app asks for it when you set up automatic starts.

You can change or revoke this at any time in
iOS Settings › Privacy & Security › Location Services › Tarmach.

## How long data is kept, and how to delete it

Data stays on your device until **you** remove it. There is no expiry, because
there is no server holding a copy.

You can:

- **Delete individual records** — any journey, refill, service entry or
  photograph, from the screen it appears on.
- **Delete everything** — Settings › About › What leaves the phone ›
  **Delete all data**. This erases saved journeys, places, vehicles, service
  and modification records, fills, charges, their photos and motion captures.
  It also clears any connected BMW sign-in and readings. Copies you exported
  or shared are managed at their destination.
- **Delete the app** — removing Tarmach from your iPhone removes its database
  and all photographs with it.

To withdraw consent for the optional lookups: disconnect the BMW account in the
Garage; stop refreshing MOT data; or, for fuel prices, tap **Not now** when the
fuel map asks — which switches the lookup off everywhere in the app, including
the forecourt reminder, and not merely on that screen. If you have already
agreed and want to undo it, **Delete all data** (below) returns the app to
never having asked.

Deleting all data also clears the app's list of forecourt stops it has already
asked you about, which is kept outside the journey database and would otherwise
survive the deletion.

## Your rights

Because your data stays on your device and the developer holds no copy, you
exercise most rights — access, correction, erasure, portability — directly
within the app. The export feature (Settings › Export and share) produces your
journeys as GPX, CSV or GeoJSON files, which covers portability.

If you are in the UK or EU, you have rights under the UK GDPR and GDPR
including access, rectification, erasure, restriction, objection and
portability. Where the developer genuinely holds no personal data about you,
there may be nothing to respond to — but you are welcome to ask, at the contact
address above.

You may also complain to the UK Information Commissioner's Office
(`ico.org.uk`) if you believe your data has been mishandled.

## Children

Tarmach is not directed at children and does not knowingly collect data from
them. It is intended for licensed drivers.

## A note on accuracy

Speed, distance, braking, cornering and G-force figures are estimates based
on the phone's sensors. They are unsuitable as evidence for an insurance claim
or dispute. Set up recording before setting off and use the app while parked.

## Changes to this policy

Material changes will be noted by the "Last updated" date above, and, where
they affect what leaves your device, described in the app's "What's new"
screen.
