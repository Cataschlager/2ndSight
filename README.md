# 2ndSight
**Empowering blind and low-vision people with affordable, real-time scene understanding.**

---

## 🌟 Mission
Give every blind or low-vision individual the **agency and independence** to navigate, identify objects, and read text in the physical world—without spending thousands of dollars or relying on sighted assistance.

---

## 🔬 Methodology
| Layer | What We Do | Why It Matters |
|-------|------------|----------------|
| **Edge AI** | Run lightweight object- and text-recognition models on a Raspberry Pi Zero 2 W | Keeps latency < 200 ms and works offline |
| **Human-centred Design** | Large tactile buttons, audio feedback, haptic cues | Built *for* accessibility, not retro-fitted |
| **Open Hardware Guides** | Publish STL files, wiring diagrams, BOM | Anyone can print, solder, and iterate |
| **Community Testing** | Recruit blind beta-testers via GitHub Issues & Discord | Real-world feedback drives sprints |
| **Fair-Source Licensing** | Non-commercial use is free; commercial rights remain with core team | Enables wide collaboration while sustaining the project  [oai_citation:0‡IT Pro](https://www.itpro.com/software/what-is-fair-source-the-new-software-licensing-structure?utm_source=chatgpt.com) |

---

## 🌱 Principles
1. **Accessibility-First** – UX decisions begin with the needs of blind users, not sighted developers.  
2. **Affordability** – Target retail price \< \$500, thousands below legacy aids.  
3. **Transparency** – Every pull request must explain *why* a change benefits end-users.  
4. **Community-Ownership** – Code, docs, and roadmap are open for discussion; decisions are logged publicly.  
5. **Sustainability** – Fair-Source model balances open collaboration with a viable path to keep core maintainers funded  [oai_citation:1‡fair.io](https://fair.io/?utm_source=chatgpt.com).

---

## 📂 Purpose of This Repository
* **Firmware & Software** – Source for the on-device Python/C++ stack, model configs, and CLI utilities.  
* **Hardware Reference** – CAD files, wiring schematics, and bill-of-materials for the wearable housing.  
* **Docs & Tutorials** – Step-by-step guides so makers and researchers can replicate or extend the prototype.  
* **Issue Tracker** – Central hub for bug reports, feature requests, and user-testing feedback.  

> **Goal:** ship an MVP by *end of summer 2025* and iterate toward a production-ready v1.0 with the help of community contributors.

---

## 🤝 Fair-Source Community Project
2ndSight adopts a **Non-Commercial Fair-Source License (v1.1)**:  
* **Free for personal, research, and accessibility-advocacy use.**  
* **Commercial use requires a separate agreement**—ensuring sustainability for long-term development while still sharing the codebase openly.  
* License converts to a standard OSI-approved license after a future “sunset” period, guaranteeing eventual full open-source release  [oai_citation:2‡fair.io](https://fair.io/licenses/?utm_source=chatgpt.com).

_Read the full license in [`LICENSE.md`](./LICENSE.md)._  

---

## 🚀 Getting Started
```bash
# 1. Clone the repo
git clone https://github.com/2ndSight/2ndSight-Prototype.git
cd 2ndSight-Prototype

# 2. Flash our pre-built image (or install deps)
bash setup/install.sh

# 3. Run demo
python run_demo.py