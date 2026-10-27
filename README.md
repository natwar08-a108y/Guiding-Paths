<div align="center">

# 🧭 GUIDING PATHS

### Safety that moves with you.

**An intelligent tourist safety platform built for the moments when ordinary navigation and emergency systems fall short.**

AI-powered protection · Offline emergency communication · AR navigation · Accountable response

<br/>

![Android](https://img.shields.io/badge/Platform-Android-101828?style=flat-square&logo=android&logoColor=3DDC84)
![AI](https://img.shields.io/badge/Intelligence-On--Device%20AI-101828?style=flat-square&logo=tensorflow&logoColor=FF6F00)
![Navigation](https://img.shields.io/badge/Navigation-AR%20Powered-101828?style=flat-square&logo=googlemaps&logoColor=4285F4)
![Privacy](https://img.shields.io/badge/Design-Privacy--First-101828?style=flat-square&logo=shieldsdotio&logoColor=FFFFFF)

<br/>

**Explore freely. Travel safely. Get help when it matters.**

</div>

---

## The problem isn't always knowing where you are.

Sometimes, it's being unable to reach your group.
Sometimes, it's facing danger without time to press an SOS button.
Sometimes, there's no internet, no familiar language, and no clear way out.

Conventional safety applications often depend on connectivity, manual intervention, and traditional maps. Guiding Paths takes a different approach: bringing intelligent threat detection, resilient communication, safety-aware navigation, and emergency accountability into one connected experience.

**Our goal:** make tourist safety more proactive, accessible, and resilient—even in challenging environments.

---

## Three capabilities. One safety ecosystem.

<table>
<tr>
<td width="33%" valign="top">

### 01 / Stay Connected

**Emergency communication beyond network coverage.**

A proposed Bluetooth-based peer-to-peer relay network forwards encrypted SOS and location packets through nearby participating devices.

- Group reunification
- Hyperlocal emergency broadcasts
- Multi-hop message relaying
- Internet-assisted SOS delivery

</td>
<td width="33%" valign="top">

### 02 / Detect Danger

**AI that looks for signs of distress.**

On-device machine learning analyzes supported audio and motion signals during an explicitly activated journey.

- Scream and distress detection
- Motion anomaly recognition
- Configurable emergency triggers
- Privacy-conscious local inference

</td>
<td width="33%" valign="top">

### 03 / Find Safety

**Navigation designed around the situation.**

Augmented reality and hazard-aware routing help travelers find suitable safe locations without constantly looking down at a map.

- AR Green Path
- Verified safe havens
- Hazard-geofence avoidance
- Offline landmark guidance

</td>
</tr>
</table>

---

## The safety experience

### 01 — Journey-aware protection

Monitoring should be a choice, not a permanent background activity.

A tourist manually starts a journey. During that session, supported on-device AI processes microphone audio and motion data for configured safety signals. Raw microphone recordings are not uploaded to the cloud by the local monitoring engine.

When the tourist ends the journey, monitoring stops and temporary session data is cleared according to the application's retention policy.

**Start when needed. Monitor locally. Stop when finished.**

### 02 — An offline safety network

A lost connection should not automatically mean a lost opportunity to get help.

Guiding Paths proposes a Bluetooth-based P2P relay system for forwarding encrypted emergency packets between nearby compatible devices.

| Capability | Intended behavior |
|---|---|
| Group reunification | Relay location packets to help separated travelers reconnect with their group. |
| Hyperlocal SOS | Broadcast distress messages to compatible participating devices within a target radius of **200–300 metres**. |
| Multi-hop relay | Forward packets through intermediate devices when direct connectivity is unavailable. |
| Emergency escalation | When a packet reaches an internet-connected relay device, forward the SOS to the configured emergency service. |
| Offline guidance | Use pre-downloaded maps and landmarks to help the traveler navigate without internet access. |

The network is intended to support nearby assistance from participating tourists or locals and improve the chances of emergency delivery in connectivity dead zones.

*Bluetooth relaying cannot guarantee delivery. Multi-hop routing, device discovery, message authentication, packet expiry, duplicate suppression, encryption, and Android background execution require implementation and real-device testing.*

### 03 — Women's safety ML engine

An emergency may unfold faster than a person can unlock their phone.

The proposed on-device anomaly detection engine evaluates relevant sensor signals during an active journey to identify potential distress.

- **Audio intelligence:** Recognize supported distress signatures, including screams, and configurable trigger phrases where speech recognition is implemented.
- **Motion intelligence:** Detect unusual movement patterns, including sudden falls, abrupt acceleration, or other configured anomalies.
- **Inactivity monitoring:** Support prolonged-inactivity triggers when the required conditions and safeguards are satisfied.
- **Automated SOS:** Initiate an emergency workflow when defined model-confidence and risk thresholds are met.

The system must account for environmental noise, unusual but harmless movement, model uncertainty, and false alarms. Automated detection indicates potential danger; it does not prove that an assault or emergency has occurred.

### 04 — AR safe-route evasion

**Look ahead, not just down.**

Using Google ARCore on compatible Android devices, Guiding Paths aims to overlay a glowing virtual **Green Path** on the live camera feed.

The navigation experience combines:

- Directional AR guidance toward a mapped police station or verified safe haven.
- Route selection informed by available hazard geofences.
- Alternative-route guidance when reliable danger-zone information is available.
- Offline landmark support when map data has been downloaded in advance.

AR guidance depends on device compatibility, positioning accuracy, available maps, and trustworthy safe-location information. No route can be guaranteed safe solely because it is displayed in green.

---

## Beyond navigation: the complete safety layer

The remaining capabilities extend protection from finding an exit to documenting incidents and anticipating hazards.

<details>
<summary><strong>05 / Smart Exit — five gates, one nearest eligible exit</strong></summary>

Designed for large reserves, parks, crowded venues, temples, and other complex public spaces.

- Allow users to select up to **five potential exit gates**.
- Calculate the nearest eligible exit using available route information.
- Enforce a strict **1.5 km safety-radius constraint**.
- Automatically mark gates beyond that configured distance as **Out of Range**.
- Distinguish proximity from actual route accessibility and safety.

The 1.5 km constraint is a configurable product rule. A gate within range is not necessarily safe, accessible, or reachable.

</details>

<details>
<summary><strong>06 / Multi-modal SOS & transparent emergency ledger</strong></summary>

Emergency workflows can be initiated through:

- Manual SOS activation.
- Supported scream or distress-sound detection.
- Prolonged inactivity when configured conditions are met.
- Configured geofence breaches.

The system is designed to capture available GPS coordinates, timestamps, trigger types, delivery status, and subsequent authority-response information where available.

A blockchain-compatible, tamper-evident ledger can maintain an auditable record of SOS events and response timelines to help evaluate emergency handling and accountability.

Sensitive personal information must remain protected. Public ledger records should not expose identities, precise location histories, recordings, or confidential evidence.

</details>

<details>
<summary><strong>07 / Early-warning crowd & stampede risk detection</strong></summary>

Large gatherings can become dangerous when crowd density increases or movement turns chaotic.

The proposed crowd-risk system combines permitted, aggregated crowd-density indicators with movement-anomaly analysis to:

- Identify unusual crowd concentration.
- Detect validated patterns associated with sudden surges or chaotic movement.
- Send **High Crowd Alerts** to tourists near affected areas.
- Notify connected local authorities or crowd-management services.
- Suggest alternative routes when reliable navigation data is available.

Crowd density alone cannot reliably predict an imminent stampede. Useful alerts require validated data sources, suitable thresholds, and false-positive management.

</details>

<details>
<summary><strong>08 / AI-powered e-FIR & tamper-evident evidence</strong></summary>

Turn a natural-language incident description into a structured report while preserving the ability to verify whether its recorded contents have changed.

- Organize incident descriptions into structured fields.
- Capture relevant facts, locations, timestamps, and supporting multimedia.
- Suggest potentially relevant **Bharatiya Nyaya Sanhita (BNS)** provisions, subject to legal verification.
- Generate **SHA-256 cryptographic hashes** of the e-FIR draft and supporting evidence.
- Record hashes and suitable audit metadata in a protected ledger.
- Allow users to review the report before submission through an authorized channel.

A matching hash helps verify file consistency against the recorded hash; it does not independently prove that evidence is genuine or that its contents are truthful.

An AI-generated draft is not an officially registered FIR. Registration depends on the applicable legal procedure and authorized channels.

</details>

<details>
<summary><strong>09 / Real-time disaster alerts — NDMA SACHET</strong></summary>

Guiding Paths aims to integrate with the National Disaster Management Authority's **SACHET** alert platform.

- Parse supported **Common Alerting Protocol (CAP)** messages from an accessible SACHET RSS or other supported feed.
- Match warnings against the user's location and affected geographical area.
- Present relevant alerts for floods, cyclones, earthquakes, and other supported hazards.
- Display available severity, affected locations, timing, and official safety instructions.
- Help travelers reconsider routes or destinations affected by active warnings.

Feed availability, update frequency, location matching, and delivery depend on the actual integration. Previously downloaded alerts cannot guarantee notification of new disasters while offline.

</details>

<details>
<summary><strong>10 / AI safety assistant & real-time translator</strong></summary>

An integrated conversational assistant aims to reduce uncertainty and language barriers in unfamiliar environments.

- Answer travel-safety questions and explain emergency procedures.
- Provide context-aware guidance using permitted journey information.
- Translate between supported languages.
- Help users communicate essential emergency phrases.
- Support voice interaction where implemented.
- Prioritize verified information and official instructions in critical situations.

AI-generated guidance should complement, not replace, emergency services or authoritative disaster warnings.

</details>

---

## How the system works

```mermaid
flowchart TD
    A["Start Journey"] --> B["Enable Selected Safety Features"]
    B --> C["On-Device AI and Context Monitoring"]
    C --> D{"Potential Emergency?"}

    D -- No --> C
    D -- Yes --> E["Initiate SOS Workflow"]

    E --> F["Capture Available Location and Event Details"]
    F --> G{"Internet Available?"}

    G -- Yes --> H["Send Through Configured Network"]
    G -- No --> I["Attempt Bluetooth P2P Relay"]

    I --> J{"Internet-Connected Relay Reached?"}
    J -- Yes --> H
    J -- No --> K["Continue Eligible Relay Attempts and Offline Guidance"]

    H --> L["Configured Emergency Service"]
    L --> M["Record Available Delivery and Response Events"]
    K --> M

    C --> N["End Journey"]
    N --> O["Stop Monitoring and Clear Temporary Session Data"]
