MARIONA — FULL APPLICATION SPECIFICATION
1. Product Overview
App Name: Mariona
Category: Intent-based private matching platform
Platforms (future): Android (first), iOS (later)
Core Idea:
Mariona connects people to relationships or opportunities through declared intent, silent matching, and consent-based visibility. No public profiles. No browsing. No performance.
2. Core Principles (Non‑Negotiable)
1. Private by Default — User information is never public.
2. Intent First — Every interaction starts with what the user wants now.
3. Match ≠ Exposure — Matching happens silently.
4. Consent Unlocks Visibility — Nothing is revealed without permission.
5. No Popularity Mechanics — No likes, followers, views, or rankings.
These principles guide every feature decision.
3. User Roles
Standard User — Any person using Mariona to connect (relationship or opportunity).
(No public roles, no influencers, no recruiters with special power.)
4. Complete User Journey
Open App → Login → Declare Intent → Private Profile → Silent Matching → Anonymous Suggestion → Mutual Consent → Messaging → Optional External Exchange
5. Screen‑by‑Screen Specification (WITH SKETCHES)
SCREEN 1: Login / Sign Up
Purpose: Secure access to the app.
Inputs:
Email or Phone Number
Password / OTP
Actions:
Sign Up
Log In
Rules:
No profile browsing before login.
Sketch:
+----------------------+
|      MARIONA         |
|----------------------|
| Email / Phone        |
| [______________]    |
| Password / OTP      |
| [______________]    |
|                      |
| [ Log In ]           |
| [ Sign Up ]          |
+----------------------+
SCREEN 2: Intent Declaration (MANDATORY)
Purpose: Capture the user’s current intention.
Question:
“What are you looking for at the moment?”
Options:
Relationship
Friendship
Job Opportunity
Collaboration
Mentorship
Just Exploring
Rules:
User cannot continue without selecting one.
Intent can be changed later, but resets matching.
Sketch:
+----------------------+
| What are you looking |
| for right now?       |
|----------------------|
| ( ) Relationship     |
| ( ) Friendship       |
| ( ) Job Opportunity  |
| ( ) Collaboration    |
| ( ) Mentorship       |
| ( ) Just Exploring   |
|                      |
| [ Continue ]         |
+----------------------+
SCREEN 3: Private Profile (System‑Only)
Purpose: Collect honest information for matching.
Fields:
Who I am (short text)
What I want
What I offer
What I’m not open to
Visibility:
Invisible to other users
Used only by matching system
Sketch:

+----------------------+
| Tell us about you    |
|----------------------|
| Who I am             |
| [______________]    |
| What I want          |
| [______________]    |
| What I offer         |
| [______________]    |
| Not open to          |
| [______________]    |
|                      |
| [ Save & Continue ]  |
+----------------------+
SCREEN 4: Anonymous Match Suggestion

Purpose: Notify user of aligned matches without exposure.

What is shown:

Notification text

Intent type only

Optional minimal tags (e.g. “Work”, “Long‑term”)


Actions:

Allow Connection

Pass


Rules:

No names

No photos

No profile viewing yet


Sketch:

+----------------------+
| A Match is Available |
|----------------------|
| Someone matching     |
| your intent is here. |
|                      |
| Intent: Collaboration|
|                      |
| [ Allow ]   [ Pass ] |
+----------------------+
SCREEN 5: Consent Waiting State

Purpose: Prevent pressure or rejection.

Behavior:

If user allows, system waits silently.

No notification if the other user declines.


Sketch:

+----------------------+
| Waiting for consent  |
|----------------------|
| If both agree,       |
| messaging will open. |
|                      |
| [ Back ]             |
+----------------------+

SCREEN 6: Messaging (Unlocked Only After Mutual Consent)

Purpose: Enable intentional communication.

Features:

Secure chat

No unsolicited messages

Optional profile reveal (user‑controlled)


Sketch:

+----------------------+
| Chat                 |
|----------------------|
| [Hello…]             |
|                      |
| [Type message...]    |
| [ Send ]             |
+----------------------+

6. Matching Logic (Plain‑Language Specification)

1. Compare user intents


2. If intents compatible → continue


3. Check preference overlap


4. Assign match score


5. If score ≥ threshold → potential match


6. Do NOT expose identities


7. Trigger anonymous suggestion


8. Unlock chat ONLY if both consent

7. Data & Privacy Levels

Level 0: Invisible (matching only)

Level 1: Intent only

Level 2: Profile + messaging

Level 3: External contact (optional)


User controls level at all times.

8. What Mariona Will Never Add

Public profiles

Feeds

Likes / hearts

Followers

View counts

Trending users

9. Success Definition

Mariona is successful if:

Silence is reduced

Pressure is reduced

Users feel safe being honest

Fewer but clearer connections happen

10. Core Statement

“Mariona matches intention silently, and reveals people only by choice.”

End of Specification# Mariona
A social and connection app.
