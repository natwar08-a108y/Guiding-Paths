# 🧭 Guiding Paths
### Intelligent Tourist Safety & Emergency Response Platform

<p align="center">
  <strong>Explore Freely. Travel Safely. Get Help When It Matters.</strong>
  <br/>
  An AI-powered safety ecosystem connecting tourists, nearby helpers, and emergency responders—even when connectivity fails.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/AI-On--Device%20Intelligence-7C3AED?style=flat-square" />
  <img src="https://img.shields.io/badge/Navigation-Augmented%20Reality-0284C7?style=flat-square" />
  <img src="https://img.shields.io/badge/Emergency-Offline%20Resilience-DC2626?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Privacy%20%26%20Safety-059669?style=flat-square" />
</p>

---

## 📍 The Idea Behind Guiding Paths

Travel should be about discovering new places—not worrying about what might go wrong.

Traditional safety applications often depend on an active internet connection, manual emergency reporting, and conventional navigation. But what happens when a traveler gets separated from their group in a crowded bazaar, encounters danger in an unfamiliar street, loses connectivity during a trek, or needs to report an incident in a language they do not understand?

**Guiding Paths is designed to address these gaps through a unified, intelligent safety platform.**

By combining on-device machine learning, Bluetooth-based peer-to-peer communication, augmented-reality navigation, emergency intelligence, and tamper-evident evidence records, the project aims to move tourist safety from reactive assistance toward proactive, resilient protection.

## 🗺️ Navigate the Project

| Section | What's inside |
|---|---|
| [Core Innovations](#-three-innovations-that-define-guiding-paths) | Offline mesh, predictive safety, AR navigation |
| [Complete Feature Set](#-the-complete-safety-ecosystem) | All 10 major capabilities |
| [Journey Workflow](#-from-journey-to-emergency-response) | How the safety system works |
| [Technology Architecture](#️-technology-architecture) | Technologies and integrations |
| [Privacy & Security](#-privacy-security--trust) | Data protection and accountability |
| [Development Roadmap](#-implementation-roadmap) | Suggested implementation stages |

---

# 🚀 Three Innovations That Define Guiding Paths

## 01. 📡 A Safety Network That Can Survive Without the Internet

<sub>OFFLINE COMMUNICATION · BLUETOOTH · DECENTRALIZED ASSISTANCE</sub>

Imagine a tourist losing contact with their group inside a crowded marketplace where mobile connectivity is unavailable. A conventional application may no longer be able to deliver location updates or emergency messages.

Guiding Paths proposes a **Bluetooth-based Peer-to-Peer (P2P) relay network** that can forward encrypted emergency packets through nearby participating devices.

**How the offline safety network is intended to work:**

- **Group reunification:** Share encrypted location packets to help separated travelers reconnect with their group.
- **Hyperlocal SOS:** Broadcast a distress message to compatible participating devices within a target radius of **200–300 metres**, enabling nearby tourists or locals to offer assistance.
- **Multi-hop message relay:** Forward emergency packets through intermediate devices when a direct connection is unavailable.
- **Internet-assisted escalation:** When a packet reaches an internet-connected device in the relay chain, forward the SOS to the configured emergency service.
- **Offline escape guidance:** Use pre-downloaded maps and landmarks to help travelers navigate when connectivity is unavailable.

The aim is to create a decentralized safety layer that can continue operating in situations where conventional cloud-dependent applications struggle.

> **Engineering challenge:** Reliable multi-hop delivery requires device discovery, message authentication, duplicate suppression, packet expiry, battery-aware operation, and Android background-execution handling. Bluetooth relay does not guarantee that an SOS will reach authorities.

---

## 02. 🛡️ Predictive Safety With On-Device Machine Learning

<sub>WOMEN'S SAFETY · EDGE AI · MOTION & AUDIO ANALYSIS</sub>

A person facing danger may not have enough time—or the ability—to unlock their phone and press an emergency button.

The Women's Safety ML Engine aims to identify potentially dangerous situations by analyzing relevant sensor signals during an explicitly activated journey.

| Signal | What the model looks for |
|---|---|
| Accelerometer data | Unusual movement, sudden falls, abrupt acceleration, or other configured anomalies |
| Ambient audio | Potential distress signatures such as screams |
| Trigger phrases | Supported emergency words or phrases, where speech recognition is implemented |
| Inactivity | Prolonged inactivity under configured conditions |
| Location context | Relevant geofence breaches or configured hazard conditions |

When a configured risk threshold is met, the system can initiate an SOS workflow, subject to the selected safeguards and trigger configuration.

**Privacy comes first:** Supported audio and motion inference is intended to happen locally on the device. Raw microphone recordings should not be uploaded to the cloud by this monitoring feature.

The engine should account for false positives, environmental noise, different movement patterns, and the limitations of automated inference. A model's prediction is a warning signal—not definitive proof of an emergency.

---

## 03. 🥽 Augmented Reality That Guides You Toward Safety

<sub>ARCORE · SAFE-ROUTE NAVIGATION · HAZARD AVOIDANCE</sub>

In an unfamiliar area at night, repeatedly looking down at a 2D map can distract a traveler from their surroundings.

Guiding Paths proposes an **AR Green Path** that overlays directional navigation onto a live camera view using Google ARCore on compatible Android devices.

**The experience combines three elements:**

- **Green Path Guidance:** Display a virtual directional path through the camera view.
- **Verified Safe Havens:** Identify mapped police stations and designated safe locations.
- **Dynamic Danger Avoidance:** Use available hazard geofences to help exclude unsafe or restricted areas from recommended routes.

The goal is straightforward: help users maintain awareness of their surroundings while finding an appropriate route toward safety.

AR guidance depends on device compatibility, location accuracy, mapping data, and reliable information about safe locations and hazards. A route must not be presented as guaranteed safe simply because it is visually highlighted.

---

# 🌐 The Complete Safety Ecosystem

Beyond its three core innovations, Guiding Paths brings together seven additional capabilities covering emergency exits, incident accountability, crowd safety, legal documentation, disaster awareness, and communication.

## 04 — 🚪 Smart Exit Intelligence

**For crowded venues, parks, reserves, temples, and large public spaces.**

A tourist in a large venue may know that an exit exists without knowing which exit is closest or whether it falls within a reasonable distance.

Guiding Paths introduces a constrained exit-selection system:

- Users can select up to **five potential exit gates**.
- The system evaluates the candidate gates and identifies the nearest eligible exit using available route data.
- A strict **1.5 km safety-radius constraint** classifies gates beyond the configured distance as **Out of Range**.
- Route-aware ranking can account for navigable distance instead of relying exclusively on straight-line proximity.
- The interface can distinguish eligible exits from distant or unavailable alternatives.

**Important distinction:** The 1.5 km rule is a configurable proximity constraint. It does not establish that an exit within the radius is safe, accessible, or reachable.

## 05 — 🚨 Multi-Modal SOS & Transparent Emergency Ledger

A single emergency button is not sufficient for every situation. Guiding Paths is designed to support multiple trigger mechanisms
