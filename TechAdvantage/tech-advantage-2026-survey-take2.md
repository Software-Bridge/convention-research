# TechAdvantage 2026 — Updated Survey Report (Take 2)
## Prepared for Pacific Volt (Booth 404)
### Conference: March 9-11, 2026 | Nashville, TN | 460 Exhibitors

> **Revision Context**: This is a revised version of the original exhibitor survey, updated to reflect a more specific and accurate understanding of Pacific Volt's software-driven Low Voltage Regulators (LVRs). The original survey grouped PacVolt with traditional mechanical step voltage regulators. This revision corrects that framing and re-evaluates the competitive landscape, use cases, and partnership opportunities accordingly.

> **Pacific Volt's Strategic Focus**: Building from proven success in outback Australia deployments, Pacific Volt is entering the American market with the LVR50 — targeting edge-of-grid cooperatives and rural utilities facing the same voltage challenges that PacVolt has already solved in Australia's remote networks.

---

# TABLE OF CONTENTS

1. [What Makes Pacific Volt Different](#what-makes-pacvolt-different)
2. [The Problem Pacific Volt Solves](#the-problem)
3. [Re-Evaluated Competitive Landscape](#competitive-landscape)
4. [Tier 1: True Direct Competitors (LV, Software-Controlled)](#tier-1-direct-competitors)
5. [Tier 2: Adjacent Competitors (MV/Primary-Side)](#tier-2-adjacent-competitors)
6. [Tier 3: Emerging Competitive Forces (Smart Inverters)](#tier-3-smart-inverters)
7. [Tier 4: Critical Integration & Software Partners](#tier-4-integration-partners)
8. [Tier 5: "Monitor + Fix" Partnership Opportunities](#tier-5-monitor-fix)
9. [Tier 6: Renewable Energy & DER Companies](#tier-6-renewable-energy)
10. [Tier 7: Channel & Distribution Partners](#tier-7-channel-partners)
11. [Tier 8: Engineering Firms That Specify Equipment](#tier-8-engineering)
12. [Australian Market Context & Lessons Learned](#australian-context)
13. [US Market Opportunity: The Australia Parallel](#us-market-opportunity)
14. [Updated Conference Strategy](#conference-strategy)
15. [Key Talking Points for Booth 404](#talking-points)

---

<a id="what-makes-pacvolt-different"></a>
# 1. WHAT MAKES PACIFIC VOLT DIFFERENT

The original survey positioned PacVolt's LVR30/LVR50 alongside traditional step voltage regulators (Eaton VR-32, Howard Industries SVRs, etc.). **This was fundamentally wrong.** Pacific Volt's LVRs are a different class of product:

### Pacific Volt LVR — Key Technical Differentiators

| Feature | Pacific Volt LVR | Traditional Step Voltage Regulators |
|---------|-----------------|-------------------------------------|
| **Voltage Level** | 100-600V AC (secondary/service level) | 4kV-35kV (primary/medium voltage) |
| **Control Method** | Software-driven, autonomous | Hardware/mechanical tap changers |
| **Regulation Type** | Boost AND buck to setpoint | Typically boost only (some buck) |
| **Power Flow** | **Bidirectional** (grid-to-user AND user-to-grid) | Unidirectional (grid-to-user only) |
| **Switching Technology** | Power electronics (solid-state) | Mechanical tap changers (motor-driven contacts) |
| **Response Time** | Fast (power electronics switching) | Slow (mechanical tap change, seconds) |
| **Maintenance** | Low (no moving parts in power path) | High (mechanical wear, oil, contact maintenance) |
| **Remote Management** | Software-controlled, firmware-updatable | Limited (basic SCADA point monitoring) |
| **Grid Position** | Last-mile, near the customer | Upstream, at substation or feeder head |
| **DER Compatibility** | Built for bidirectional solar/DER flow | Struggles with reverse power flow |
| **Deployment Model** | Edge-of-grid, distributed | Centralized at substations |

### Why This Distinction Matters

1. **PacVolt's LVRs solve the LAST-MILE voltage problem** — the voltage sag (and solar-driven voltage rise) that occurs between the distribution transformer and the customer premises, especially on long service runs at the end of the grid.

2. **Traditional step regulators cannot reach this problem** — they operate at medium voltage on the primary side. By the time power reaches the customer through a distribution transformer and long service wire, the voltage may still be out of range.

3. **Bidirectional capability is a critical differentiator** — as solar farms and rooftop solar feed power back through the grid, traditional unidirectional regulators cannot manage the reverse voltage rise. PacVolt's LVRs handle both directions natively.

4. **Software-driven autonomy means the LVR manages itself** — adaptive algorithms, remote monitoring, firmware updates, and data analytics. This is closer to a smart grid device than a traditional regulator.

---

<a id="the-problem"></a>
# 2. THE PROBLEM PACIFIC VOLT SOLVES

## Edge-of-Grid Voltage Issues

### The Physics
Voltage drops along distribution lines proportionally to distance, load, and conductor impedance. On long rural feeders:
- Voltage at the substation: ~120V nominal (US) / ~240V (Australia)
- Voltage at the end of a 30km+ feeder: can drop to 108V or below (US) / 216V or below (Australia)
- **This is below equipment operating range** and violates utility service standards (ANSI C84.1 Range A: 114V-126V)

### The Users Affected
- **Remote farming operations** — large properties at the end of long distribution lines
- **Heavy single-phase loads without three-phase access** — irrigation pumps, grain dryers, cold storage, dairy milking equipment, shearing sheds, welding equipment
- **Edge-of-grid communities** — small towns and settlements at the extremities of the distribution network
- **Solar farm interconnection points** — where distributed generation feeds back into weak grid infrastructure

### The Bidirectional Problem (Solar Backfeed)
When solar installations (particularly larger farm-scale arrays) export power back through long, high-impedance lines:
- **Voltage RISES** at the point of generation (the reverse of the drop problem)
- Traditional regulators designed only for voltage boost cannot handle this
- The same feeder may need voltage BOOST during peak demand AND voltage BUCK during peak solar generation
- **PacVolt's boost/buck bidirectional LVR handles both directions in a single device**

### Why This Problem Is Growing
1. **Increasing rural solar adoption** — cooperatives are seeing rapid DER growth on their weakest feeders
2. **Electrification of agriculture** — electric irrigation pumps, EV charging for farm vehicles, cold storage expansion
3. **Grid infrastructure aging** — distribution infrastructure in rural areas is often decades old
4. **Climate adaptation** — increased cooling loads (HVAC) in traditionally mild-climate rural areas
5. **Remote work migration** — rural properties now supporting home offices with higher power quality expectations

---

<a id="competitive-landscape"></a>
# 3. RE-EVALUATED COMPETITIVE LANDSCAPE

## Key Correction from Original Survey

The original survey identified 9 "direct competitors" — all of which are actually **medium-voltage, primary-side step voltage regulator manufacturers**. While they operate in the broader voltage regulation market, they are NOT direct competitors to PacVolt's low-voltage, software-driven, bidirectional LVR.

### Original "Direct Competitors" — Reclassified

| Company | Original Classification | **Revised Classification** | Reason |
|---------|------------------------|---------------------------|--------|
| Eaton (Cooper Power) | CRITICAL competitor | **Adjacent market** (MV/primary) | VR-32 operates at 7.2-19.9kV, mechanical tap-changer, unidirectional |
| Reinhausen Manufacturing | CRITICAL competitor | **Adjacent market + Watch** | MV on-load tap-changers; ETOS platform could move downstream |
| Hitachi Energy | CRITICAL competitor | **CRITICAL (C-LVR product only)** | C-LVR competes directly at LV; rest of portfolio is MV/HV |
| Howard Industries | HIGH competitor | **Adjacent market** (MV/primary) | Step VRs at primary distribution level |
| Prolec GE Waukesha | HIGH competitor | **Adjacent market** (MV/primary) | SVRs at primary distribution level |
| ABB Electrification | HIGH competitor | **Adjacent market** (MV/primary) | Step VRs focused on larger kVA units |
| Schneider Electric | MODERATE competitor | **Software platform** (not hardware) | ADMS/VVO software — integration target, not competitor |
| Southern States | MODERATE competitor | **Adjacent market** (higher voltage) | Higher voltage classes entirely |
| Sieyuan Electric | MODERATE competitor | **Emerging — monitor** | Chinese MV equipment entering US; no LV products identified |

### The Actual Competitive Landscape for PacVolt's LVR

```
DIRECT COMPETITORS (LV, software-controlled, bidirectional)
    |
    |- Hitachi Energy C-LVR     [At TechAdvantage - Booth 1625]
    |- EDGE Electrons (AU)      [NOT at TechAdvantage]
    |- Gridco Systems (MV, but  [At TechAdvantage - Booth 504]
    |  closest technology match)
    |
ADJACENT COMPETITORS (MV step regulators — different product, same customer)
    |
    |- Eaton VR-32 / EVER-Tap   [Booth 1825]
    |- Reinhausen VACUTAP        [Booth 209]
    |- Prolec GE Waukesha SVR   [Booth 418]
    |- Howard Industries SVR     [Booth 615]
    |- ABB Step VRs              [Booth 1734]
    |- T&R Electric              [Booth 1749]
    |
EMERGING COMPETITION (smart inverters with voltage regulation features)
    |
    |- Enphase IQ8 (grid-forming microinverter)
    |- SMA Solar (Volt-VAR, Volt-Watt)
    |- Fronius (grid-support functions)
    |- Selectronic SP PRO (AU market)
    |- Redback Technologies (AU market)
    |
ABSORBED / UNCERTAIN STATUS
    |
    |- Varentec ENGO (acquired by Koch → Sentient Energy; product status unclear)
    |- GridBridge (acquired by Eaton; technology absorbed)
```

---

<a id="tier-1-direct-competitors"></a>
# 4. TIER 1: TRUE DIRECT COMPETITORS

These companies make or have made products that compete directly in PacVolt's niche: software-controlled, low-voltage voltage regulation.

---

## Hitachi Energy — C-LVR (Compact Low Voltage Regulator) — Booth 1625

**THE #1 COMPETITIVE THREAT**

### Why Critical
Hitachi Energy's C-LVR is the only product from a major global manufacturer that directly competes at the low-voltage (secondary/service) level with PacVolt's LVR products.

### What We Know
- **Product**: C-LVR — Compact Low Voltage Regulator
- **Voltage Range**: Low voltage, secondary/service level — directly overlapping with PacVolt
- **Parent Company**: Hitachi Energy (formerly ABB Power Grids), ~$13B revenue
- **Technology Platform**: Lumada IoT platform, AI/ML-based grid analytics, TXpert digital monitoring
- **Protocols**: IEC 61850, DNP3.0
- **Scale**: Massive — Hitachi Energy invested $4.1B in new US transformer manufacturing (2024)
- **Cooperative Market**: Actively gaining traction, leveraging legacy ABB relationships

### What We Need to Find Out (Intelligence Targets)
1. **Exact specifications**: Voltage range, kVA ratings, phase configurations
2. **Bidirectional capability**: Does the C-LVR support user-to-grid power flow for solar backfeed?
3. **Software/firmware architecture**: How autonomous is it? Remote management? OTA updates?
4. **Pricing**: Enterprise/project-based? Per-unit cost?
5. **Installed base**: How many units deployed? Which cooperatives?
6. **Australian presence**: Hitachi Energy has significant AU operations — are they deploying C-LVR in outback applications?
7. **Roadmap**: What's next for the C-LVR product line?

### PacVolt's Potential Advantages over C-LVR
- **Software-first architecture**: If PacVolt's firmware is more sophisticated and field-updatable
- **Proven outback Australia deployments**: Real-world edge-of-grid track record
- **Bidirectional from the ground up**: If C-LVR was designed as unidirectional and backfeed is an afterthought
- **Price**: If PacVolt can undercut Hitachi Energy's enterprise pricing
- **Agility**: Small company can iterate faster than a $13B division of Hitachi
- **Specialization**: PacVolt does ONE thing (LV voltage regulation) vs. Hitachi's sprawling portfolio

### Conference Action
**MANDATORY VISIT — Day 1 priority.** Send team members to Booth 1625 to gather intelligence on C-LVR specifications, pricing, and market positioning. This is the single most important competitive intelligence opportunity at the conference.

---

## Gridco Systems — Booth 504

### Why Relevant
Gridco makes **solid-state, power-electronics-based voltage regulators** — the closest technology paradigm to PacVolt's approach, though primarily at medium voltage.

### What We Know
- **Product**: InlineRegulator (ILPR), Empower Platform
- **Voltage Range**: Primarily medium voltage (4kV-35kV) — NOT directly competing at 100-600V
- **Technology**: IGBT/SiC-based power electronics, continuous (stepless) regulation, sub-cycle response time
- **Software**: Real-time embedded control, grid-edge computing, SCADA/DNP3 integration
- **Bidirectional**: Likely yes — power electronics architecture supports bidirectional flow
- **Key Selling Point**: "No mechanical parts, no oil, no maintenance" — same pitch as PacVolt

### PacVolt's Position vs. Gridco
- Gridco is MV, PacVolt is LV — **complementary rather than competitive** in most deployments
- Gridco validates the market thesis that **solid-state/software-controlled is the future** of voltage regulation
- Potential for a "primary (Gridco) + secondary (PacVolt) solid-state regulation" story
- Gridco's pricing reportedly higher than traditional — if they move down to LV, PacVolt needs to be established

### Conference Action
Visit Booth 504 to understand their technology roadmap. Key question: **Are they developing an LV product?** If not, explore positioning PacVolt as the LV complement to Gridco's MV solution.

---

## EDGE Electrons (Australia) — NOT at TechAdvantage

### Why Relevant
EDGE Electrons is potentially the most closely aligned competitor globally — an Australian company making software-defined power electronics for edge-of-grid applications.

### What We Know [NEEDS LIVE VERIFICATION]
- **Product**: Power electronics platform for edge-of-grid
- **Voltage Range**: Low voltage (240V/415V AC — Australian standard) — **directly in PacVolt's range**
- **Software Controlled**: Yes — software-defined power electronics is their core proposition
- **Bidirectional**: Yes — designed for solar feed-in on remote/edge-of-grid networks
- **Target Market**: Edge-of-grid, remote communities, mining, agriculture in Australia
- **Market Position**: Australian market focused

### PacVolt's Position vs. EDGE Electrons
- Both address the same fundamental problem (last-mile voltage at edge-of-grid)
- PacVolt has the advantage of proven Australian deployments AND a US market strategy
- EDGE Electrons appears Australia-focused without US market presence
- Not a factor at TechAdvantage, but a key competitor for any Australian business

### Conference Action
No booth visit needed (not present). However, PacVolt should reference Australian edge-of-grid experience in conversations to establish credibility.

---

## Varentec ENGO (Now Sentient Energy / Koch) — Status Uncertain

### Background
Varentec developed the ENGO V10 solid-state voltage regulator — a power-electronics-based device designed for high-DER feeders with bidirectional flow. Koch Industries acquired the technology.

### Current Status
Sentient Energy (the Koch subsidiary that absorbed Varentec) is at **Booth 934** — but the exhibitor research shows they are displaying **line sensors (MM3, UM3)**, NOT the ENGO voltage regulator. The ENGO product line appears to have been deprioritized or shelved.

### Conference Action
Low priority but worth a quick walk-by of Booth 934 to ask: "Whatever happened to the ENGO voltage regulator?" The answer will confirm whether this technology is truly dead or potentially coming back.

---

<a id="tier-2-adjacent-competitors"></a>
# 5. TIER 2: ADJACENT COMPETITORS (MV / Primary-Side)

These companies make traditional step voltage regulators at medium voltage. They serve the same cooperative customers but operate at a different point on the grid. They are NOT direct competitors but share the customer relationship.

**Key Insight**: PacVolt's LVR complements these products rather than competing with them. A cooperative with Eaton VR-32s on its feeders still needs PacVolt LVRs at the service level for last-mile voltage management.

### Reframed Messaging Opportunity
Instead of positioning against these companies, PacVolt should position **alongside** them:
> "Your Eaton VR-32 handles voltage regulation at the feeder level. Pacific Volt's LVR50 handles what happens AFTER the distribution transformer — the last-mile voltage problem that your VR-32 can't reach."

---

| Company | Booth | Product | Why Adjacent (Not Direct) | Partnership Angle |
|---------|-------|---------|--------------------------|-------------------|
| **Eaton (Cooper Power)** | 1825 | VR-32, EVER-Tap, CL-7 | MV (7.2-19.9kV), mechanical, unidirectional. Market leader (~40-50% cooperative market share, $15K-$30K+ per unit). EVER-Tap is their solid-state move. | PacVolt solves the problem that persists AFTER the VR-32 regulates at feeder level. |
| **Reinhausen Mfg** | 209 | VACUTAP, TAPCON, ETOS | Global leader in MV on-load tap-changers. ETOS digital platform showing distribution interest. | ETOS platform could potentially integrate with PacVolt's LVR data. Watch for downstream moves. |
| **Prolec GE Waukesha** | 418 | SVRs (single/three-phase) | MV step regulators. **Just steps from PacVolt at Booth 404!** | Proximity makes this a natural conversation. "We solve the last mile that your SVR can't reach." |
| **Howard Industries** | 615 | Step VRs, distribution transformers | MV step regulators. Strong cooperative relationships. Domestic manufacturer. | Potential OEM/distribution partner — Howard's cooperative relationships + PacVolt's LVR technology. |
| **ABB Electrification** | 1734 | Step VRs, switchgear | MV focus, larger kVA units. ABB Ability IoT platform. Revenue ~$15B. | ABB's IoT platform sets technology expectations PacVolt should match. |
| **T&R Electric Supply** | 1749 | Step VRs (new and remanufactured) | Primary-side VRs. Colman, SD. Manufacturer and remanufacturer. | "Primary (T&R) + secondary (PacVolt)" story. T&R handles primary-side, PacVolt handles secondary. |
| **Southern States** | 235 | Voltage regulators, switching | Higher voltage classes entirely. Hampton, GA. Employee-owned. | Different market segment. Low priority. |
| **Sieyuan Electric** | 127 | Substation equipment | Chinese MV equipment entering US. No LV products identified. | Monitor for LV product introductions. |

---

<a id="tier-3-smart-inverters"></a>
# 6. TIER 3: EMERGING COMPETITIVE FORCES — SMART INVERTERS

### The Long-Term Threat

As IEEE 1547-2018 (US) and AS 4777.2 (Australia) increasingly mandate voltage regulation functions (Volt-VAR, Volt-Watt) in grid-connected inverters, there is a growing argument that distributed smart inverters can provide aggregate voltage regulation, reducing the need for dedicated LVR devices.

### Why PacVolt Still Wins

1. **Inverters only regulate at the point of generation/consumption** — PacVolt's LVR regulates at ANY point on the secondary network
2. **Inverters provide reactive, not proactive regulation** — they respond to voltage deviations per programmed curves, not actively managing to a setpoint
3. **On feeders without solar (or with variable solar)**, there may be no inverters to provide regulation, but the voltage problem persists
4. **PacVolt's LVR is always active** — it doesn't depend on solar generation or battery state
5. **Regulation at the service entrance is more reliable** than hoping distributed inverters collectively manage voltage

### Smart Inverter Companies to Be Aware Of

| Company | Key Product | Voltage Regulation Features | TechAdvantage? |
|---------|------------|---------------------------|----------------|
| **Enphase Energy** | IQ8 microinverter | Grid-forming, Volt-VAR, Volt-Watt. Per-panel control. | Not exhibiting |
| **SMA Solar** | Sunny Boy/Tripower | Volt-VAR, Volt-Watt, SMA Data Manager for fleet control | Not exhibiting |
| **Fronius** | Symo GEN24 Plus | Volt-VAR, Volt-Watt, active power curtailment | Not exhibiting |
| **Selectronic** (AU) | SP PRO | Bidirectional inverter/charger, voltage regulation. Dominant in AU off-grid. | Not exhibiting |
| **Redback Technologies** (AU) | Smart Hybrid System | Cloud-connected, Volt-Watt/Volt-VAR per AS4777.2. Brisbane-based. | Not exhibiting |

**None of these companies are at TechAdvantage 2026** — their primary market is solar/residential, not the cooperative utility market that TechAdvantage serves. This is important: **the cooperative market is PacVolt's defensible beachhead** before smart inverters become ubiquitous.

---

<a id="tier-4-integration-partners"></a>
# 7. TIER 4: CRITICAL INTEGRATION & SOFTWARE PARTNERS

These companies provide the SCADA, ADMS, VVO, and IT platforms that PacVolt's LVR must integrate with. **With PacVolt being software-driven, these integration partnerships become even MORE important** — the LVR's software control capability is only as valuable as its ability to talk to the systems cooperative engineers already use.

---

## NISC (National Information Solutions Cooperative) — Booth 901

**The dominant IT platform for cooperatives.** NISC's iVUE, MDM, and mapping systems are where LVR telemetry data needs to flow. Integration with NISC means visibility at every cooperative using the platform.

**PacVolt Software Advantage**: A software-driven LVR can expose richer data to NISC's platform — not just voltage readings, but regulation events, power flow direction, energy throughput, firmware status, and operational analytics.

---

## OATI — Booth 945

**Volt/VAR Optimization and DERMS.** OATI's webSmartEnergy platform is precisely the system that would dispatch and optimize LVR operation. For a software-controlled LVR, OATI integration means the LVR can participate in automated grid optimization — a capability traditional mechanical regulators cannot match.

**Key Discussion**: Can PacVolt's LVR accept real-time setpoint commands from OATI's VVO engine?

---

## Survalent Technology — Booth 1934

**Cooperative-focused SCADA/ADMS with VVO.** Widely deployed at cooperatives. LVR integration with Survalent's VVO extends voltage optimization to the secondary/service level — a capability most VVO systems currently lack because they only have visibility/control at the primary level.

**PacVolt Pitch**: "Survalent's VVO optimizes voltage at the feeder level. Add PacVolt's LVR and extend that optimization all the way to the customer meter."

---

## Milsoft Utility Solutions — Booth 1424

**WindMil is THE tool cooperative engineers use to model voltage profiles and plan regulator placement.** If PacVolt's LVR is properly modeled as a library component in WindMil, every cooperative engineer doing a voltage study will see it as an option.

**Action Item**: Discuss getting LVR30/LVR50 performance data and models into WindMil's component library.

---

## ETAP — Booth 1700

**Gold standard for power systems engineering studies.** Used by engineering consultants who recommend equipment to cooperatives. LVR models in ETAP's library provide engineering credibility.

---

## NovaTech Automation — Booth 2445

**OrionLX substation automation.** Widely deployed at cooperative substations. LVR must communicate via DNP3 to these systems. PacVolt's software-driven approach makes protocol integration more flexible than hardwired traditional regulators.

---

## Schweitzer Engineering (SEL) — Booth 1201

**Dominant protective relaying at cooperatives.** SEL relays and RTACs are the most commonly deployed protection/automation devices. LVR DNP3 compatibility with SEL equipment is essential. The SEL-2411 programmable controller is sometimes used for voltage regulation control schemes.

---

## S&C Electric — Booth 1919

**Distribution automation and IntelliCap capacitor control.** S&C's IntelliCap does VAR compensation (reactive power) while PacVolt's LVR does voltage regulation (real power). These are complementary functions that together provide complete voltage/VAR management at the distribution level.

---

## Schneider Electric — Booth 2112

**ADMS/VVO software platform.** Not a hardware competitor. Schneider's EcoStruxure ADMS and VVO modules could integrate PacVolt's software-driven LVR as a controllable grid asset. Their microgrid controller is also relevant for edge-of-grid scenarios.

---

<a id="tier-5-monitor-fix"></a>
# 8. TIER 5: "MONITOR + FIX" PARTNERSHIP OPPORTUNITIES

These companies identify voltage problems. PacVolt fixes them. Together, they create a complete solution.

**This tier is ELEVATED from the original survey** because PacVolt's software-driven architecture makes data integration and coordinated response much more feasible than with traditional regulators.

---

## Virtual Peaker — Booth 400

**LITERALLY NEXT DOOR (Booth 400 vs. PacVolt's 404).** This is the single most convenient and potentially most valuable partnership at the conference.

### The Partnership Story
- Virtual Peaker's DERMS manages DERs (solar, batteries, EVs, flexible loads) at cooperatives
- Those DERs cause the voltage fluctuations that PacVolt's LVRs correct
- Virtual Peaker identifies where DER-driven voltage issues occur
- PacVolt's LVR corrects them
- **Integrated solution**: "DER management + voltage correction" offered jointly to cooperatives

### Bidirectional Relevance
Virtual Peaker's platform explicitly manages **bidirectional power flow** from DERs. PacVolt's LVR is designed for **bidirectional voltage regulation**. This is a natural technical fit.

### Conference Action
**Highest priority meeting.** Walk next door on Day 1. Propose a joint solution exploration.

---

## Tantalus Systems — Booth 735

### TRUVolt — Voltage Monitoring on the Distribution Grid
Tantalus's TRUVolt product specifically monitors voltage at points on the distribution grid. This is the data that tells cooperatives WHERE they need LVR deployment.

**The Story**: "Tantalus TRUVolt tells you where voltage is out of range. Pacific Volt LVR50 fixes it."

**Bidirectional Relevance**: TRUVolt can detect both low voltage (load-driven sag) AND high voltage (solar-driven rise) — both problems PacVolt's LVR addresses.

---

## Ubicquia — Booth 2245

### UbiVolt / UbiGrid — Streetlight-Based Voltage Monitoring
Ubicquia deploys grid sensors through existing streetlight infrastructure, providing low-cost, widespread voltage visibility. Their UbiVolt product specifically measures voltage.

**The Story**: "Ubicquia's sensors on every streetlight show you the voltage map. Pacific Volt LVR50 corrects the problem areas."

---

## MICATU — Booth 554

### GridSight — Fiber-Optic Voltage Sensors
Precision voltage measurement purpose-built for CVR/VVO programs. Drift-free, highly accurate.

**The Story**: "MICATU measures the voltage with laboratory precision. Pacific Volt regulates it to the setpoint."

---

## Itron — Booth 625

### Distributed Intelligence — Edge Computing at the Meter
Itron's OpenWay Riva AMI platform with Distributed Intelligence enables edge computing at every smart meter. Meters already measure voltage at every customer premises — this data drives targeted LVR deployment.

**The Story**: "Your Itron meters already know where voltage is low. Deploy Pacific Volt LVR50s at those locations."

---

## Landis+Gyr — Booth 1035

### Revelo Smart Meters — Voltage Data at Every Customer
Same story as Itron: smart meters provide voltage readings that identify LVR deployment opportunities. Landis+Gyr's Gridstream Connect platform could integrate LVR feedback data.

---

## Power Monitors, Inc. — Booth 362

Power quality monitors used to validate voltage regulation performance. Their Scout series can be used to measure and verify LVR effectiveness before and after deployment.

---

## Sentient Energy — Booth 934

Line sensors (MM3, UM3) providing real-time voltage and current visibility on distribution feeders. Note: Sentient absorbed Varentec's ENGO voltage regulator technology, which appears to have been shelved. Worth asking about the ENGO status.

---

<a id="tier-6-renewable-energy"></a>
# 9. TIER 6: RENEWABLE ENERGY & DER COMPANIES

**Renewable energy integration is the key growth driver for PacVolt's LVR.** Every solar installation on a weak feeder creates a bidirectional voltage management challenge that PacVolt's boost/buck bidirectional LVR is uniquely positioned to solve.

---

## High-Priority Renewable Companies at TechAdvantage

| Company | Booth | Why Relevant to PacVolt |
|---------|-------|------------------------|
| **Silicon Ranch** | 1545 | Nashville-based, subsidiary of Shell. Pioneered cooperative community solar. Their projects inject power into distribution systems requiring voltage regulation at interconnection. **Direct driver of LVR demand.** |
| **RWE Clean Energy** | 708 | Largest onshore wind operator in US (9+ GW). Cooperatives partnering for solar/wind. Renewable generation creates voltage fluctuations that require regulation. |
| **FlexGen** | 827 | Battery energy storage (BESS). HybridOS platform for solar+storage. BESS can both cause and mitigate voltage issues. Coordinating BESS with LVR is an advanced grid management scenario. |
| **Virtual Peaker** | 400 | DERMS platform. Already covered in Tier 5 above. |
| **Clean Power Research** | 853 | SolarAnywhere and PowerClerk platforms help utilities evaluate solar integration impacts including voltage impacts. Their analysis tools can identify where LVRs are needed. |
| **ELM Microgrid** | 2350 | Microgrid design and control. Microgrids at edge-of-grid are a core PacVolt use case. |
| **Ameresco** | 515 | Energy services for cooperatives. Revenue ~$1.4B. Works on cooperative solar projects. |

### The Pitch to Renewable Companies
> "Every solar farm you connect to a weak cooperative feeder creates a voltage management problem. Pacific Volt's LVR50 solves it — bidirectional regulation that handles both import AND export power flow."

---

<a id="tier-7-channel-partners"></a>
# 10. TIER 7: CHANNEL & DISTRIBUTION PARTNERS

These companies distribute equipment to cooperatives. Getting PacVolt LVRs into their catalogs and warehouses accelerates market access.

| Company | Booth | Relevance |
|---------|-------|-----------|
| **NRECA National Discounts** | 1348 | **CRITICAL**: Getting LVRs listed in NRECA's national purchasing program = access to 900+ cooperatives |
| **Irby** | 1045 | Major cooperative equipment distributor (Sonepar subsidiary). Southeast US and cooperative territories. |
| **Border States** | 1411 | Employee-owned, 130+ branches, strong Upper Midwest cooperative presence. $3.7B revenue. |
| **Graybar** | 2019 | Fortune 500 electrical distributor, $10B revenue. Strong utility division. |
| **RESCO** | 922 | Cooperative-owned supply organization. Natural channel. |
| **Wesco Distribution** | 1211 | Major distributor, $22B revenue. |
| **United Utility Supply** | 1117 | Utility distributor serving cooperatives. |
| **KGPCo** | 1404 | Supply chain management for utilities. |
| **NexGen Utility Sales** | 217 | Manufacturers' rep firm. Potential PacVolt sales rep in certain territories. |

---

<a id="tier-8-engineering"></a>
# 11. TIER 8: ENGINEERING FIRMS THAT SPECIFY EQUIPMENT

These firms consult for cooperatives and specify/recommend voltage regulation equipment. Winning their endorsement means they recommend PacVolt LVRs in their studies.

| Company | Booth | Why Important |
|---------|-------|---------------|
| **PSE (Power Systems Engineering)** | 1740 | Primary engineering consultant for cooperatives. They specify voltage regulation equipment. |
| **Finley Engineering** | 718 | Long-established, employee-owned, deeply trusted by cooperatives. |
| **1898 & Co. (Burns & McDonnell)** | 320 | Technology and management consulting for utilities. Grid modernization strategy. |
| **ENTRUST Solutions Group** | 2219 | Growing utility engineering firm. |
| **GDS Associates** | 714 | Energy consulting including rate studies and power supply planning. |
| **DNV** | 655 | Premier energy certification. DNV certification for PacVolt LVRs = market credibility. |
| **Oak Ridge National Lab** | 2349 | DOE research lab. Grid modernization R&D. Potential R&D partner. |

### The Pitch to Engineering Firms
> "When you model voltage profiles for a cooperative with edge-of-grid problems, the Pacific Volt LVR50 is the solution that works at the secondary/service level — where traditional primary-side regulators can't reach. We have proven deployments in outback Australia solving the exact same physics."

---

<a id="australian-context"></a>
# 12. AUSTRALIAN MARKET CONTEXT & LESSONS LEARNED

## Why Australia Matters

Australia's remote electricity networks face the most extreme version of the same problems US cooperatives deal with:

### Australian Grid Challenges (That PacVolt Has Solved)

1. **SWER Lines (Single Wire Earth Return)**: Australia uses SWER lines extensively in rural areas — single-wire distribution running hundreds of kilometers. Voltage drop on these lines is severe. PacVolt's LVR has been deployed to manage end-of-line voltage on these networks.

2. **Massive Solar Penetration**: Australia has the world's highest rooftop solar adoption rate (~30%+ of homes). On weak rural feeders, solar backfeed causes significant voltage rise. PacVolt's bidirectional LVR handles both the voltage drop during load AND voltage rise during solar export.

3. **Remote Agriculture**: Australian outback farms are comparable to US ranching operations — large properties, heavy equipment (irrigation, cold storage, shearing), hundreds of kilometers from substations, often on single-phase supply.

4. **Stand Alone Power Systems (SAPS)**: Australian network operators (Essential Energy, Western Power, Ergon Energy) are deploying SAPS — disconnecting remote customers from the grid and providing solar+battery standalone systems. Before SAPS, voltage regulation was the alternative — keeping customers connected but managing the voltage. PacVolt's LVR has been part of this solution set.

5. **Thermal and Load Growth**: Remote Australian properties face increasing electrical load from cooling (climate change), electrification of farm equipment, and modern amenities. This loads already-strained long feeders further.

### Key Australian Network Operators Familiar with LVR Technology

| Operator | Region | Key Challenge |
|----------|--------|---------------|
| **Essential Energy** | NSW rural/regional | Long feeders, aging infrastructure, high solar |
| **Ergon Energy / Energy QLD** | Queensland rural | Extreme distances, tropical load growth, solar |
| **Western Power** | Western Australia | SWER lines, outback mining/farming |
| **Horizon Power** | Remote WA | The most remote grid in Australia |
| **SA Power Networks** | South Australia | World-leading solar penetration, voltage rise issues |
| **TasNetworks** | Tasmania | Hydro + solar integration, rural areas |

### Australian Standards Context
- **AS 4777.2**: Mandates smart inverter voltage regulation functions (Volt-Watt, Volt-VAR)
- **AS 61000.3.100**: Power quality limits for LV installations
- PacVolt LVRs comply with Australian LV standards for voltage regulation equipment

---

<a id="us-market-opportunity"></a>
# 13. US MARKET OPPORTUNITY: THE AUSTRALIA PARALLEL

## The Same Problem Exists in America

US rural electric cooperatives face the SAME physics — just with different numbers:

| Factor | Australia | US Cooperatives |
|--------|-----------|-----------------|
| **Voltage** | 240V/415V AC | 120/240V AC |
| **Long feeders** | 50-300+ km SWER lines | 10-50+ mile rural feeders |
| **Solar adoption** | 30%+ rooftop penetration | Rapidly growing, especially community solar |
| **Remote agriculture** | Outback farming, mining | Midwest/Great Plains farming, ranching |
| **Single-phase challenges** | Common on SWER | Common at end-of-line rural |
| **Heavy single-phase loads** | Irrigation, cold storage, shearing | Irrigation, grain dryers, cold storage, dairy |
| **Aging infrastructure** | Decades-old SWER lines | Decades-old rural distribution |
| **Standards** | AS 61000, AS 4777 | ANSI C84.1, IEEE 1547-2018 |

### Why US Cooperatives Are Ready for PacVolt NOW

1. **The transformer shortage** — cooperatives are waiting 1-3+ years for new distribution transformers. They can't upgrade infrastructure even if they want to. LVR deployment is a **faster, cheaper alternative** to rebuilding feeders.

2. **Solar mandate compliance** — IEEE 1547-2018 mandates voltage regulation features for new DER interconnections. Cooperatives need tools to manage bidirectional voltage.

3. **USDA RUS funding** — Rural Utilities Service provides financing for cooperative grid modernization. LVR deployment is an eligible expenditure.

4. **Infrastructure Investment and Jobs Act (IIJA)** — Federal funding for grid modernization, smart grid, and rural electrification. PacVolt LVR fits all these categories.

5. **Cooperative board pressure** — members complaining about low voltage, especially those with heavy equipment (irrigation pumps, grain dryers). The LVR is a visible, deployable solution.

### Target US Markets (Australia Equivalents)

| Australian Market | US Equivalent | Key Cooperatives/Regions |
|-------------------|--------------|--------------------------|
| NSW outback farming | Great Plains agriculture | Kansas, Nebraska, Oklahoma, Texas cooperatives |
| Queensland remote | Deep South rural | Mississippi, Alabama, Georgia cooperatives |
| WA mining/pastoral | Western ranching | Montana, Wyoming, New Mexico cooperatives |
| SA high-solar | Sunbelt solar belt | Arizona, California, Nevada cooperatives |
| Tasmania rural | New England rural | Vermont, Maine, New Hampshire cooperatives |

### The PacVolt Narrative at TechAdvantage
> "We've already solved this problem in outback Australia — some of the most challenging grid conditions on earth. Now we're bringing that proven technology to American cooperatives. The LVR50 is software-controlled, handles bidirectional power flow for your solar installations, and deploys at the service level where traditional regulators can't reach."

---

<a id="conference-strategy"></a>
# 14. UPDATED CONFERENCE STRATEGY

## Revised Priority Visit Schedule

### Day 1 — Intelligence & Adjacent Neighbors

| Priority | Company | Booth | Purpose |
|----------|---------|-------|---------|
| 1 | **Virtual Peaker** | 400 | NEXT DOOR. DERMS partnership. Bidirectional DER + bidirectional LVR. |
| 2 | **Hitachi Energy** | 1625 | #1 competitive intelligence. C-LVR specs, pricing, bidirectional capability. |
| 3 | **Gridco Systems** | 504 | Solid-state technology peer. LV product plans? Complementary positioning? |
| 4 | **NISC** | 901 | LVR data integration into cooperative IT. Software-driven = richer data. |
| 5 | **OATI** | 945 | VVO/DERMS integration. Can LVR accept real-time setpoint commands? |
| 6 | **Integral Analytics** | 401 | Adjacent booth. Load forecasting for LVR deployment planning. |
| 7 | **Prolec GE Waukesha** | 418 | Walk-by. "We solve the last mile your SVR can't reach." |

### Day 2 — Partners & Channels

| Priority | Company | Booth | Purpose |
|----------|---------|-------|---------|
| 8 | **Tantalus (TRUVolt)** | 735 | "Monitor + fix" partnership. |
| 9 | **MICATU** | 554 | Precision voltage sensing + LVR correction. |
| 10 | **Milsoft** | 1424 | Get LVR into WindMil component library. |
| 11 | **Survalent** | 1934 | SCADA/VVO integration to secondary level. |
| 12 | **SEL** | 1201 | DNP3 compatibility, substation automation. |
| 13 | **Irby** | 1045 | Distribution channel exploration. |
| 14 | **NRECA Nat'l Discounts** | 1348 | National purchasing program listing. |
| 15 | **Silicon Ranch** | 1545 | Solar-driven LVR demand. Community solar projects. |
| 16 | **Ubicquia** | 2245 | UbiVolt voltage monitoring partnership. |
| 17 | **Uticom Systems** | 1307 | VVO at secondary level — the gap PacVolt fills. |

### Day 3 — Strategic & Engineering

| Priority | Company | Booth | Purpose |
|----------|---------|-------|---------|
| 18 | **PSE** | 1740 | Engineering consultants who specify regulators. Educate on LVR. |
| 19 | **ERMCO** | 1017 | Cooperative-owned transformer manufacturer. Relationship building. |
| 20 | **T&R Electric** | 1749 | "Primary + secondary" complementary pitch. |
| 21 | **RWE Clean Energy** | 708 | Renewable-driven LVR demand conversations. |
| 22 | **FlexGen** | 827 | BESS + LVR coordination. |
| 23 | **NovaTech** | 2445 | OrionLX substation automation compatibility. |
| 24 | **ELM Microgrid** | 2350 | Edge-of-grid microgrid + LVR. |
| 25 | **DNV** | 655 | Certification and credibility. |
| 26 | **Finley Engineering** | 718 | Trusted cooperative engineering firm. |
| 27 | **S&C Electric** | 1919 | Distribution automation compatibility. |

### Ongoing Walk-Bys
- **Eaton** (Booth 1825) — Understand EVER-Tap status, VR-32 pricing/lead times
- **Reinhausen** (Booth 209) — ETOS platform, distribution-level ambitions
- **ABB** (Booth 1734) — General competitive awareness
- **Howard Industries** (Booth 615) — OEM/distribution partner potential
- **Sentient Energy** (Booth 934) — ENGO status check

---

## Key Questions for Hitachi Energy (C-LVR Intelligence)

1. What is the C-LVR voltage range and kVA rating lineup?
2. Does the C-LVR support bidirectional power flow (solar backfeed)?
3. What communication protocols are supported (DNP3, Modbus, IEC 61850)?
4. What is the pricing structure — per-unit or project-based?
5. How many C-LVR units are deployed? At which cooperatives?
6. Is the C-LVR deployed in Australia?
7. What firmware/software capabilities does it have? Remote management? OTA updates?
8. What is the C-LVR product roadmap?

---

<a id="talking-points"></a>
# 15. KEY TALKING POINTS FOR BOOTH 404

## Reframed Messaging (Updated from Original Survey)

### DO Say:
1. **"Software-controlled voltage regulation"** — not just a regulator, a smart grid device
2. **"Proven in outback Australia"** — world's toughest edge-of-grid conditions
3. **"Bidirectional for solar"** — handles both import and export power flow
4. **"Boost AND buck"** — regulates to setpoint regardless of whether voltage is too high or too low
5. **"100-600V AC, secondary/service level"** — we solve the LAST-MILE problem
6. **"Complements your existing regulators"** — works alongside Eaton VR-32, not against it
7. **"Remote management and firmware updates"** — deploy it and manage it from anywhere
8. **"No mechanical parts, no oil changes"** — lower lifetime cost than mechanical regulators

### DON'T Say:
1. ~~"We compete with the VR-32"~~ — You don't. You solve a different problem at a different point on the grid.
2. ~~"Better than step regulators"~~ — Misleading comparison. PacVolt is a different product category.
3. ~~"Works like a traditional regulator"~~ — It doesn't. It's software-controlled power electronics.

### Elevator Pitch (30 seconds)
> "Pacific Volt makes the LVR50 — a software-controlled low voltage regulator for 100 to 600 volt AC. It regulates voltage at the last mile of the grid — the secondary/service level that traditional primary-side regulators can't reach. It boosts and bucks to a setpoint, handles bidirectional power flow for solar, and manages itself autonomously with firmware you can update remotely. We've proven this technology in outback Australia — the toughest grid conditions on earth — and we're now bringing it to American cooperatives."

### For Engineering Audiences (60 seconds)
> "Think about your worst edge-of-grid feeders. Twenty miles out, single-phase, 108 volts at the end. Now add a 200kW solar array feeding back, and voltage spikes to 128 during peak generation. A traditional VR-32 at the substation can't solve either problem at the service level. The LVR50 deploys at the distribution transformer or service entrance. It's solid-state power electronics — boost and buck to setpoint, bidirectional for DER, software-controlled with DNP3. We've been doing this in Australia for years on SWER lines that make your worst feeder look short. Now the LVR50 is ready for the US cooperative market."

---

# APPENDIX: BOOTH PROXIMITY MAP (Near Booth 404)

| Booth | Company | Updated Strategic Notes |
|-------|---------|----------------------|
| **400** | **Virtual Peaker** | **#1 PARTNERSHIP OPPORTUNITY.** DERMS platform. Walk next door Day 1. |
| **401** | **Integral Analytics** | Load forecasting. LVR deployment planning data. |
| 405 | American Power Systems | Power generation. Low priority. |
| 409 | Jarraff By Prinoth | ROW equipment. Not relevant. |
| 414 | Laminated Wood Systems | Poles. Not relevant. |
| 415 | **Henkels & McCoy** | Utility contractor. Potential LVR installer. |
| 416 | AIMXCEL | Utility tech. Low priority. |
| 417 | **Meinberg USA** | Precision timing. Relevant if LVR needs synchronized measurements. |
| **418** | **Prolec GE Waukesha** | **Adjacent market (MV SVRs).** "We complement your SVR at the service level." |
| 419 | UtiliSource | Outsourcing. Not relevant. |
| 421 | KCI Energy | Engineering. Brief intro. |
| 425 | **Honeywell** | Grid solutions, DERMS. Worth a conversation. |
| 435 | VERSALIFT | Bucket trucks. Not relevant. |
| 447 | **Phoenix Contact** | Industrial connectors. Potential component supplier. |
| **504** | **Gridco Systems** | Solid-state VR peer. Technology conversation. |
| **554** | **MICATU** | Voltage sensing partnership. |

---

*Report compiled March 2, 2026 for Pacific Volt. Updated from original survey to reflect PacVolt's specific product capabilities: software-driven, bidirectional, 100-600V AC, boost/buck LVR with proven Australian edge-of-grid deployments. Strategic focus: building the American cooperative market from Australian lessons learned.*

*Sources: TechAdvantage 2026 exhibitor data, web research, industry knowledge. Items noted with [NEEDS LIVE VERIFICATION] should be confirmed with current sources, particularly Hitachi Energy C-LVR specifications and pricing.*
