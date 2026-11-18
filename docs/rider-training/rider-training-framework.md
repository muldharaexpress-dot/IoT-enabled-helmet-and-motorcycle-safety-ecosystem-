# Motorcycle Rider Training Framework — Bangladesh

**Component 2 of the IoT-Enabled Helmet and Motorcycle Safety Ecosystem**
Tiered training: Primary → Secondary → Advanced (High level)
Delivered by a Motorcycle Riders Academy run by a manufacturer consortium (Honda, Yamaha, Suzuki, TVS, Bajaj and others) under a Motorcycle Safety Initiative.

> **Status:** Working draft v0.1 (18 Nov 2026). This is a framework for discussion with the Road Transport and Highways Division, BRTA and consortium members. It is **not** an approved curriculum. Hour counts and pass marks are proposals. Section 9 lists every point that still needs official confirmation before anyone cites it.

---

## 1. Why this is needed (checked figures)

| Indicator | Figure | Source |
|---|---|---|
| Road deaths, Bangladesh, 2024 | 7,294 deaths, 12,019 injuries in 6,927 crashes | Road Safety Foundation (RSF) annual report 2024, reported by Prothom Alo, Dhaka Tribune, The Financial Express |
| Motorcycle deaths, 2024 | 2,609 deaths (≈35.8% of road deaths) in 2,761 crashes | RSF 2024, same reports |
| Other 2024 count | 8,543 total deaths; 2,570 motorcycle deaths | Bangladesh Jatri Kalyan Samity (BJKS), 4 Jan 2025 |
| Trend (RSF) | Motorcycle deaths 2,487 (2023) → 2,609 (2024) → 2,671 (2025) | RSF data, reported by UNB |
| Global target | Cut road traffic deaths **and injuries** by at least 50% by 2030 | UN GA Resolution A/RES/74/299 (31 Aug 2020); SDG target 3.6 |
| Age group at risk (LMICs) | People aged 15–34 make up over 60% of powered two- and three-wheeler deaths | WHO news release, 10 Oct 2022 (launch of PTW manual, 2nd ed.) |

**How to read these figures.** RSF and BJKS count deaths from newspaper reports, so their totals differ, and neither is an official police or health figure. In formal submissions, cite the organisation and year, and where possible add the BRTA/police figure and the WHO *Global Status Report on Road Safety* estimate (the WHO estimate is usually much higher than media-based counts).

---

## 2. Design principles (international basis)

1. **Graduated (progressive) access.** Riders move up in steps by skill, experience and machine power. This follows the model in EU Directive 2006/126/EC: category A1 (≤125 cc, ≤11 kW) from age 16, A2 (≤35 kW, ≤0.2 kW/kg) from 18, and full category A from 20 after 2 years on A2, or directly from 24. Bangladesh has its own licence ages (see §3). The **idea of progression** is what we adopt, not the EU ages.
2. **Goals for Driver Education (GDE) matrix.** The curriculum covers all four GDE levels: (1) vehicle control, (2) traffic situations, (3) trip goals and context, and (4) personal attitudes and life goals. Most crash risk sits in levels 3–4 (speed choice, fatigue, peer pressure), which skills-only courses leave out.
3. **Safe System approach.** This follows the WHO *Global Plan for the Decade of Action 2021–2030* and the WHO manual *Powered two- and three-wheeler safety* (2nd ed., 2022, ISBN 978-92-4-006056-2). Training is **one** pillar. It works alongside helmets, safer vehicles (ABS/CBS), safer speeds and enforcement, and is not a substitute for them.
4. **Measured on outcomes.** Training on its own has a mixed evidence record for cutting crashes. The academy should therefore measure results (§7), not only count graduates.
5. **Standard structure.** Courses are built from theory plus closed-range modules plus on-road modules. This mirrors widely used formats, such as the MSF Basic RiderCourse (about 5 h theory/e-course + 10 h range).

---

## 3. Legal anchor in Bangladesh

- **Road Transport Act 2018** (in force from 1 Nov 2019): minimum age 18 for a non-professional licence and 21 for a professional licence. Press summaries of the Act also report a minimum schooling requirement (class VIII) for drivers. *Confirm section numbers against the Gazette text.*
- **Motorcycle policy drafts, 2023.** The Road Transport and Highways Division drafted a "Motorcycle Movement/Operation Policy 2023". Reported proposals: 30 km/h urban limit, restrictions on motorcycles under 126 cc on highways, and a licence required before purchase or registration. **Final legal status is unconfirmed.** Treat these as drafts.
- **Motor Vehicle Speed Limit Guideline 2024** (BRTA): issued. Training content on speed must match its limits.
- **Ministry letter of support** (held by the project): attach it to the academy's accreditation application.

**Proposal to government:** Make a certificate from an accredited academy course a **condition for a learner or smart-card motorcycle licence**, with BRTA keeping control of the final test. Professional riders (ride-hailing, delivery) would need a Level 2 certificate.

---

## 4. Three-level curriculum

### Level 1 — PRIMARY (New rider / Learner)
*Target:* people with no riding experience, applying for a learner licence. *Machine:* ≤125 cc, with CBS or ABS.
*Proposed duration:* **20 h** (6 h theory + 10 h closed range + 4 h supervised on-road).

| Module | Content | GDE level |
|---|---|---|
| P1 Theory | Traffic signs and rules (RTA 2018), right of way, speed limits (2024 Guideline), penalties | 2 |
| P2 Protective gear | Certified helmet: fit, strap, replacement after impact. Gloves, jacket, boots, high-visibility gear. **IoT helmet basics** (§5) | 1, 4 |
| P3 Machine familiarisation | Controls, pre-ride check (tyres, chain, lights, brakes), T-CLOCS-style checklist | 1 |
| P4 Basic control (range) | Starting, clutch friction zone, straight-line riding, gear change, stopping | 1 |
| P5 Braking (range) | Progressive braking with front and rear brakes. **How CBS and ABS behave.** Emergency stop from 30 km/h | 1 |
| P6 Low-speed manoeuvres | Slow ride, figure-8, U-turn, weaving through cones | 1 |
| P7 Cornering basics | Slow–Look–Press–Roll, lane position | 1–2 |
| P8 Supervised road ride | Quiet roads, junctions, signalling, mirror checks | 2 |
| P9 Risk and attitude | Why riders die (local crash cases), alcohol and drugs, phones, carrying passengers | 4 |

*Assessment:* written test (pass mark ≥ 80%) + range skills test (emergency stop, U-turn, slow ride, swerve) + instructor sign-off on the road ride.

### Level 2 — SECONDARY (Licensed rider / Professional rider)
*Target:* licensed riders, and ride-hailing, delivery and corporate fleet riders. *Entry:* Level 1 certificate or a valid licence plus a screening ride.
*Proposed duration:* **16 h** (4 h theory + 6 h range + 6 h on-road).

| Module | Content | GDE level |
|---|---|---|
| S1 Hazard perception | Video-based hazard perception test, scanning (SIPDE/SEE), being seen | 2 |
| S2 Urban traffic | Buses and trucks (blind spots), rickshaws and CNG three-wheelers, pedestrians, filtering rules | 2 |
| S3 Highway riding | Overtaking, following distance, crosswinds, night riding, monsoon/wet roads | 2 |
| S4 Advanced braking and swerving | Threshold braking, ABS full-stop on wet and dry surfaces, braking in a corner | 1 |
| S5 Passenger and load | Pillion briefing (passenger must wear a helmet), load limits, effect on stopping distance | 1–3 |
| S6 Fatigue and work pressure | Trip planning, delivery-target pressure, rest breaks, heat stress | 3–4 |
| S7 First response | Post-crash scene safety. **Do not remove an injured rider's helmet unless trained**. Calling 999 | 3 |
| S8 IoT data review | Rider sees their own helmet/telematics data: harsh braking, speeding events (§5) | 3–4 |

*Assessment:* hazard perception test + on-road observed ride (scored rubric) + written test (≥ 80%).

### Level 3 — ADVANCED (High level / Instructor / Specialist)
Three streams:
- **3A Advanced Rider** (about 16 h): higher-capacity machines (the 2023 draft policy allowed up to 500 cc+ for the industry), cornering lines, emergency avoidance at higher speeds, group riding.
- **3B Instructor (RiderCoach) Certification** (proposed **≥ 60 h**, modelled on international instructor-preparation courses): teaching methods, range management, risk-awareness coaching, assessment calibration, first aid. Instructors renew every 2 years, with audited teaching sessions.
- **3C Specialist:** police and emergency escort riders, fleet safety managers (with ISO 39001:2012 *Road traffic safety management systems* as the management reference).

---

## 5. Linking the IoT helmet to training

| Training use | IoT helmet / telematics function |
|---|---|
| Helmet-use compliance | Strap-fastened sensor; the training motorcycle will not start unless the helmet is worn and fastened (pilot only, needs testing for reliability and failure modes) |
| Range scoring | IMU data (deceleration, lean, stopping distance) gives objective scores for the emergency stop and swerve |
| Post-course coaching | Monthly anonymised report: harsh braking, speeding over the 2024 Guideline limits, night riding exposure |
| Crash response | Automatic crash detection → SMS or call to 999 or a family contact, with GPS location. Taught in S7 |
| Research evidence | Graduates against a matched control group: event rates and crashes (§7) |

**Data protection:** Get informed, written consent. Share data with the academy or insurers only with consent. Store data under Bangladesh's personal data protection rules in force at launch. *Confirm which law applies.* Never use the data for enforcement without a legal basis.

---

## 6. Academy governance (consortium model)

- **Motorcycle Safety Initiative Board:** representatives of member manufacturers and distributors, BRTA, the Road Transport and Highways Division, Police (Traffic), BUET Accident Research Institute (ARI), and a road-safety NGO.
- **Existing industry programmes to build on (publicly reported):**
  - Bangladesh Honda Pvt. Ltd.: Safety Riding Department set up in 2019. Instructors trained at Honda's traffic education centre in Japan. Reported to have trained more than 4,000 riders.
  - Yamaha (ACI Motors): "Yamaha Riding Academy" and women-rider training events (2017).
  - Suzuki: "Suzuki Riding School" campaign (Banani, Dhaka).
  - TVS, Bajaj and others: *programme details still to be collected*.
- **One common curriculum and one common certificate** across all brands. Each brand may run training centres, but all assessments follow one standard.
- **Accreditation and audit:** BRTA (or a body it names) accredits centres. Instructor sessions and test results are audited every year.
- **Funding options:** CSR contributions from manufacturers, a per-vehicle levy at sale (needs policy approval), subsidised fees for women and low-income riders, and fleet operators paying for Level 2.

---

## 7. Monitoring and evaluation (KPIs)

| KPI | Baseline source | Target (proposal) |
|---|---|---|
| Riders certified per level per year | Academy MIS | Set after pilot |
| Helmet-wearing rate (rider and pillion), observed | Roadside observation survey (WHO method) | ↑ year on year |
| Pass rate on first attempt, by level | Academy MIS | 70–85% (very high rates suggest the test is too easy) |
| Harsh-braking and speeding events per 100 km (IoT cohort) | Telematics | ↓ 6 months after the course |
| Self-reported and police-recorded crashes, graduates vs control | Cohort study with BUET-ARI | Statistically significant reduction |
| Share of women trainees | Academy MIS | Set target with the ministry |

**Pilot design:** Start in 2–3 districts (for example Dhaka, Chattogram, and one district with a high highway crash rate). Follow trainees for 12 months against a matched control group, before rolling out nationally.

---

## 8. Proposed phases

1. **Months 0–3:** Curriculum approval workshop with BRTA and the consortium. Translate into Bangla. Prepare the instructor training course.
2. **Months 3–6:** Train and certify the first instructor group (Level 3B). Build or upgrade ranges to a standard layout.
3. **Months 6–18:** District pilot for Levels 1–2, with an IoT-helmet cohort.
4. **Month 18:** Independent evaluation report → decision on national rollout and on linking certificates to licensing.

---

## 9. Points that need official confirmation before citing

1. Exact section numbers of the Road Transport Act 2018 for licence ages and schooling. Also whether the Road Transport Rules 2022 changed them.
2. Whether the Motorcycle Movement/Operation Policy 2023 was finalised and gazetted, and its final wording.
3. BRTA's current licence categories and learner-licence rules for motorcycles.
4. The current BSTI helmet standard (number and year), and whether UN Regulation No. 22 (series 06) is accepted.
5. Whether Bangladesh requires ABS or CBS on new motorcycles (India, for comparison, required ABS above 125 cc and CBS at or below 125 cc from April 2019). *Check with BRTA/BSTI.*
6. Official (police/BRTA) motorcycle death figures for 2024–2025, and the WHO GSRS estimate for Bangladesh.
7. Which data protection law applies, and its status.
8. Programme details and training figures for TVS, Bajaj and other consortium members, confirmed directly by each company.

---

## 10. References

- Road Safety Foundation 2024 report, reported by: Prothom Alo — https://en.prothomalo.com/bangladesh/m4kzejfpvx ; Dhaka Tribune — https://www.dhakatribune.com/bangladesh/370317/report-bangladesh-witnessed-7-294-road-accident ; The Financial Express — https://thefinancialexpress.com.bd/home/tk-218-billion-human-resources-lost-as-7294-killed-rsf
- UNB, RSF and BJKS figures — https://unb.com.bd/category/Bangladesh/bangladesh-witnessed-7294-road-accident-deaths-in-2024-report/150760
- UN GA Resolution A/RES/74/299 — https://digitallibrary.un.org/record/3879711/files/A_RES_74_299-EN.pdf
- WHO, *Powered two- and three-wheeler safety*, 2nd ed., 2022 — https://www.who.int/publications/i/item/9789240060562
- WHO news release, 10 Oct 2022 — https://www.who.int/news/item/10-10-2022-new-global-guidelines-to-curb-motorcycle-crash-deaths
- EU Directive 2006/126/EC, Art. 4 — https://legislation.gov.uk/eudr/2006/126/article/4/2012-11-21 (check against the consolidated EUR-Lex text)
- MSF Basic RiderCourse formats — https://www.safety.af.mil/Portals/71/documents/Occupational/AFD-160408-008%20MSF%20BRC.pdf
- Road Transport Act 2018 key features — https://en.banglatribune.com/national/news/9555/Key-features-of-Road-Transport-Act-2018
- Draft Motorcycle Movement Policy 2023 — https://www.tbsnews.net/bangladesh/draft-motorcycle-movement-policy-limits-speed-30kmh-city-588134 ; https://www.thedailystar.net/backpage/bangladesh-road-transport-authority-made-licence-mandatory-to-buy-a-bike-1761424
- Bangladesh Honda safety initiatives — https://www.bdhonda.com/safety-bd/safety-initiatives ; https://bikebd.com/blog/bangladesh-honda-safety-riding-activities
- Yamaha/ACI women-rider training — https://bikebd.com/blog/motorcycle-riding-training-event-for-female-riders
- Suzuki Riding School — https://www.tbsnews.net/features/wheels/suzuki-hosts-riding-school-campaign-335572
- GDE matrix: Hatakka, M., Keskinen, E., Gregersen, N.P., Glad, A., Hernetkoski, K. (2002). From control of the vehicle to personal self-control. *Transportation Research Part F*, 5(3), 201–215.
- ISO 39001:2012 *Road traffic safety (RTS) management systems*.
