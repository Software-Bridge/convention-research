# Convention Research - Claude Instructions

## Project Overview
This repository contains research and analysis for conventions and trade shows relevant to Pacific Volt (PacVolt). PacVolt manufactures software-driven Low Voltage Regulators (LVR30, LVR50) for electric utilities, cooperatives, and edge-of-grid applications.

## About Pacific Volt's LVR Products

### Technical Capabilities
- **Software-enabled voltage regulation** — not mechanical tap changers
- **100-600V AC operating range** — secondary/service level (NOT medium/primary voltage)
- **Boost AND buck** — ramps voltage up or down to a target setpoint
- **Bidirectional power flow** — handles grid-to-user AND user-to-grid (e.g., solar farms feeding back)
- **Autonomous operation** — software-controlled with firmware that can be updated remotely
- **Communication** — DNP3 protocol for SCADA integration

### Key Market Context
- Pacific Volt has proven success in **outback Australia** deployments — edge-of-grid, long feeders, SWER lines, high solar penetration
- The strategic focus is **building the American cooperative market** from Australian lessons learned, primarily with the **LVR50**
- PacVolt's LVR is NOT a traditional step voltage regulator — it is a different product category (software-controlled power electronics at LV/secondary level)
- The LVR complements (rather than competes with) primary-side medium-voltage regulators like Eaton VR-32

### Key Use Cases
- Remote/edge-of-grid users without three-phase power who pull heavy single-phase loads (farming, irrigation, cold storage)
- Solar farm interconnection points where bidirectional voltage regulation is needed
- End-of-line voltage management on long distribution feeders
- Conservation Voltage Reduction (CVR) programs at the service level

## Repository Structure
- `TechAdvantage/` — Research for TechAdvantage 2026 conference (Nashville, March 9-11, 2026)
  - `Exhibitor_Research_*.md` — Detailed profiles of 460 exhibitors (alphabetical batches)
  - `tech-advantage-2026-survey.md` — Original exhibitor survey (grouped PacVolt with traditional VRs)
  - `tech-advantage-2026-survey-take2.md` — **Updated survey** with corrected PacVolt positioning
  - `tech-advantage-2026-jobs.md` — Job openings at exhibitor companies
- Additional convention folders may be added over time

## Research Conventions
- When researching exhibitors, always evaluate relevance through the lens of PacVolt's specific LVR capabilities (software-driven, bidirectional, LV, edge-of-grid)
- Distinguish between true direct competitors (LV power electronics) and adjacent market players (MV step voltage regulators)
- The #1 identified direct competitor is **Hitachi Energy C-LVR** (low voltage regulator)
- DERMS, VVO, and SCADA integration partners are critical — PacVolt's software-driven architecture makes integration more capable than traditional regulators
- Australian market experience is a key differentiator to highlight in all positioning

## Working Directories
- Primary: `/Users/gameraman/dev/dev_pacvolt/convention-research`
- Related planning: `/Users/gameraman/dev/dev_pacvolt/pacvolt-planning/research/TechAdvantage`
