FocusProof Beta Chrome Extension Privacy Policy

Last updated: 16 July 2026

## Purpose

FocusProof Beta is a Google Chrome companion extension for the FocusProof macOS
study tracker. Its single purpose is to connect Chrome to the FocusProof Mac app
and provide the current website domain during an active study session when
browser tracking is enabled.

## Information handled

During an eligible active study session, the extension accesses the active
Chrome tab URL and immediately reduces it to the website domain, such as
`example.com`. It sends that domain, a temporary tab identifier, the event time
and type, and technical version/browser identifiers to the FocusProof app on the
same Mac.

When there is no active study session, a readiness check sends only connection,
version and browser-identity information. The readiness check does not access a
tab or create a study activity record.

FocusProof Beta does not collect full URLs, URL paths, query strings, searches,
page titles, page contents, typed text, form entries, keystrokes, screenshots,
clipboard contents, local files, or Incognito browsing activity.

## Local processing and disclosure

The extension communicates with the FocusProof Mac app through Chrome native
messaging on the same device. The extension contains no analytics, advertising,
cloud API or external data endpoint. Website-domain activity is not sold and is 
not transmitted by the extension to any external server or third party.

A user may separately choose to export or back up FocusProof data using the Mac
app's existing controls.

## Limited use

FocusProof uses website-domain activity only to provide its disclosed
study-session tracking feature. It does not use or transfer this information
for advertising, profiling, creditworthiness, or any purpose unrelated to
FocusProof's study-session tracking features.

## Storage and retention

The extension does not use Chrome storage. Its current domain and tab state are
held temporarily in service-worker memory and cleared when tracking is no longer
eligible or the native connection closes.

The FocusProof Mac app may store the website domain as part of a local study
session record. It replaces the raw Chrome tab identifier with a random,
session-scoped alias before persistence. Local domain activity remains until the
user deletes the relevant session or resets FocusProof data.

## Permissions

FocusProof Beta uses:

- **Native messaging** to connect to the local FocusProof Mac helper.
- **Tabs** to read the active tab URL only during an authorised study session
  and immediately derive the website domain.

The extension does not request host permissions, content-script access,
browsing-history permission, Chrome storage, web-request access, cookies, or
Incognito access.

## User controls

Users can disable browser tracking globally in FocusProof, pause it for the
current session from the extension, end a study session, delete individual
sessions, or reset all FocusProof data.

## Diagnostics

Connection and version status are processed locally. FocusProof Beta does not
automatically transmit diagnostic or activity data to an external service.

## Beta status and contact

FocusProof Beta is available only to approved closed-beta testers. Questions may
be submitted through the FocusProof downloads repository issue tracker:

https://github.com/kevinantoun1/focusproof-downloads/issues

Users should not include sensitive personal information in public issues.
