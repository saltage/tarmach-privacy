---
title: Tarmach Privacy Policy
---

# Tarmach — Privacy Policy

>
>

**Last updated:** 2 September 2026

## The short version

Tarmach records your journeys using your iPhone's own sensors and keeps them
on your iPhone. There is no Tarmach account, no Tarmach server, and no
analytics. The developer never receives your journeys, your locations, your
photographs or your vehicle records — there is nowhere for them to be sent.

Three optional features contact someone else's server, and only when you
choose to use them. They are named individually below.

## Who is responsible

Tarmach is developed by *Harry Salt, trading as Harry Salt*, a sole
trader based in London, United Kingdom, who is the data controller for the
limited purposes described here.

**Contact:** `tarmach@spill850@passmail.net` 

## What the app collects, and where it goes

### Stored on your device only

All of the following is written to a database inside the app's own storage
area on your iPhone. It is not transmitted anywhere:

- **Location while recording a journey** — approximately one position per
  second while a journey is running, including speed, heading and altitude,
  forming the route you see on the map.
- **Motion data** — accelerometer and gyroscope readings used to detect
  braking, acceleration and cornering. Individual readings are not kept; only
  the events detected from them.
- **Journey records** — start and end times, distance, duration, and the
  places you start and finish at.
- **Vehicle records** — anything you enter yourself: cars, registrations,
  service history, modifications, documents and photographs.
- **Fuel records** — refills, prices, odometer readings, and any receipt
  photographs you scan or attach.
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

**2. DVSA MOT History** — if, and only if, you enrol a car with a registration
plate. The registration is sent to the UK Driver and Vehicle Standards Agency's
MOT History API to retrieve the car's make, model and MOT test history. This
happens once at enrolment, and again whenever you manually refresh MOT data.

**3. Fuel price map** — if, and only if, you open the fuel map or the
add-refill form. Your current precise location is sent to
`checkfuelprices.co.uk` to find nearby stations and their prices. Nothing else
about you is sent with it, and it happens only while that screen is open. The
app asks before the first such lookup.

Each of these is optional. The app records journeys perfectly well without any
of them.

### While Tarmach is in beta (TestFlight)

Beta builds are distributed through Apple's TestFlight. If you have enabled
sharing in iOS, Apple may provide the developer with **crash reports and basic
usage statistics** for this app, and any feedback or screenshots you choose to
submit through TestFlight. This is handled by Apple, is not part of the app
itself, and stops when the beta ends. You can turn it off in
iOS Settings › Privacy & Security › Analytics & Improvements.

## What is never collected

- No account, sign-up, name or email address is required or requested.
- No advertising, no advertising identifiers, no tracking across apps or
  websites, and no data sold or shared with data brokers. The app's privacy
  manifest declares tracking as `false`.
- No analytics or telemetry of any kind is sent to the developer.
- Your contacts, photos library, calendars and health data are not accessed.

## Why the app asks for location "Always"

Journeys need to keep recording when your screen is off and the app is in the
background — that is the entire function of the app. "Always" permission is
what allows iOS to keep the recording alive while you drive. If you grant only
"While Using", journeys can still be recorded, but only while the app is open
on screen.

You can change or revoke this at any time in
iOS Settings › Privacy & Security › Location Services › Tarmach.

## How long data is kept, and how to delete it

Data stays on your device until **you** remove it. There is no expiry, because
there is no server holding a copy.

You can:

- **Delete individual records** — any journey, refill, service entry or
  photograph, from the screen it appears on.
- **Delete everything** — Settings › About › What leaves the phone ›
  **Delete all data**. This permanently erases every journey, place, vehicle,
  service and modification record, fuel refill and photograph, and clears any
  connected BMW sign-in and readings. It cannot be undone.
- **Delete the app** — removing Tarmach from your iPhone removes its database
  and all photographs with it.

To withdraw consent for the optional lookups: disconnect the BMW account in the
Garage, stop refreshing MOT data, or decline the location prompt on the fuel
map. Each is independent of the others.

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

Speed, distance, braking, cornering and G-force figures come from the phone's
own sensors, not from the car. The thresholds behind "harsh" events are still
being validated against real driving. Treat every figure as an estimate, not as
evidence for an insurance claim, a dispute, or anyone else's records. Tarmach
is not navigation or driver assistance — do not interact with the phone while
driving.

## Changes to this policy

Material changes will be noted by the "Last updated" date above, and, where
they affect what leaves your device, described in the app's "What's new"
screen.
