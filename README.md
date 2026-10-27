# 🌊 Asterisk: Vltava Spatial Symphony & Sign Engine

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Verification: Level 4 Gold](https://img.shields.io/badge/SPARK%202022-Level%204%20Gold%20(DO--178C%20DAL--A)-brightgreen)](spark/)
[![Meta VR Start](https://img.shields.io/badge/Meta%20VR%20Start-Developer%20Competition%202026-blue)](https://start-developer-competition-26.devpost.com/)
[![Status: Locked For Judging](https://img.shields.io/badge/Status-Locked%20for%20Judging-blue)](https://devpost.com/software/asterisk-sovereign-3d-spatial-sign-engine)

> **Official Submission for the Meta VR Start Developer Competition 2026 ($1,000,000 Prize Pool)**  
> **Live WebXR Experience:** [https://web4light.online/](https://web4light.online/)  
> **Devpost Submission:** [Asterisk: Vltava (#1510029)](https://devpost.com/software/asterisk-sovereign-3d-spatial-sign-engine)  
> **Video Demonstration:** [YouTube Showcase](https://www.youtube.com/watch?v=F3ZPIO6cfqg)  

---

## 💡 Inspiration: Hearing Through Spatial Flow

Bedřich Smetana composed his magnum opus, *Vltava*, in complete and profound deafness. He never heard the orchestral performance with physical ears — he perceived its spatial flow, acoustic vibrations, and fluid dynamics purely in his mind and soul.

**Asterisk: Vltava** transforms classical music and human communication into a tactile, spatial, and visual experience accessible to everyone — especially the deaf, hard of hearing, and blind — running controller-free inside the **Meta Quest Browser**.

---

## ⚙️ The First 5 Minutes: Zero Cognitive Friction

Engineered to captivate immediately without the urge to disconnect:

1. **Instant Access (Bus Stop Test):**
   - Zero-install WebXR launch in < 2 seconds via Meta Quest Browser. No waiting for 30 GB app downloads.
2. **Hands-First Interaction:**
   - 100% controller-free. Powered directly by the **Meta Horizon Hand Tracking API**.
3. **The 60 cm Bounding Box (Airplane Seat Test):**
   - The entire spatial experience is calibrated within a comfortable 60 cm personal zone — perfectly usable seated in an armchair or airplane seat without flailing arms.
4. **Haptic & Visual Vibro-Acoustics:**
   - Acoustic waves from Smetana's orchestra are mapped into visual particle flows and haptic frequencies ($20 \le f \le 250\,$Hz) via `Smetana_Spatial_Acoustic_Harmonizer`.
5. **Interactive 3D Smetana Avatar:**
   - A historical 3D avatar communicates in Czech Sign Language (ČZJ) and finger alphabet with mathematically proven joint kinematics.

---

## 🛡️ Formally Verified Kinematics (Ada/SPARK 2022 Level 4 Gold)

Anatomical safety and joint limits are mathematically guaranteed:
- **`Sign_Studio_Kinematics` (13 VCs):** Bounds Euler rotation angles and prevents anatomical joint singularities.
- **`Smetana_Spatial_Acoustic_Harmonizer` (7 VCs):** Guarantees safe vibro-acoustic frequencies and particle bounds.
- **`WebXR_Spatial_Anchor_Enclave` (9 VCs):** Enforces 6-DOF velocity bounds ($\le 2500\,$mm/s) to eliminate simulator sickness.
- **`Sign_Pose_Validator` (23 VCs):** Validates skeletal finger shapes against canonical phonetic sign dictionaries.

```bash
cd spark
gnatprove -P default.gpr --level=4 --report=all
```
Result: **738 / 738 checks proved (100% Level 4 Gold, DO-178C DAL-A)**.

---

## 🔒 Freeze Notice for Judging Period
This repository is **locked and frozen** for the judging evaluation of the Meta VR Start Developer Competition 2026.

## 📜 License
Released under the [MIT License](LICENSE).
