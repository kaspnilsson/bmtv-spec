# BMTV - Burning Man TV Art Car Project

## Project Overview

Tube TV art car where the truck bed becomes the TV screen and the truck cab is inside the "tube." The TV structure extends forward from the truck bed to approximately the rear of the cab, creating a performance stage area behind the cab but forward of the rear axle.

**Key Spatial Layout:**
- **TV Screen**: Truck bed tailgate area (retractable projection screen)  
- **TV "Tube"**: LED scaffolding extending forward ~8-10 feet to rear cab line
- **Stage Area**: Between cab and rear axle (weight-limited performance space)
- **Audience**: Views screen from behind the truck

**Base Vehicle:** F350 dually or similar

**Timeline:** On playa by Burning Man 2027

**Critical Engineering Constraints:** 
- The stage area is a cantilever structure extending forward from the rear axle, creating significant tipping moment
- **Must be driveable while fully deployed** - no ground support legs or external stabilizers allowed
- All structural loads must be supported entirely by truck frame and suspension
- This fundamentally limits stage capacity and requires conservative structural engineering

## Core Philosophy

### Technical Requirements
- Car must be capable of driving itself to the playa
- Car should have at least mid-tier art car audio
- Car should be built to work with or withstand the elements on the playa (waterproofing and dust proofing, wind resistance / usage of porous materials to counteract wind)
- Make use of collapsible bits, custom fabrication wherever possible

### Project Philosophy: Keep It Achievable
- **Minimal viable product approach** - build something awesome but achievable
- **Fun over perfection** - prioritize getting to playa over gold-plating features
- **Don't bite off more than we can chew** - realistic scope for team skills and timeline
- **Descope ambitious features** - many cool ideas exist but may be too complex for v1
- **Iterate and improve** - build solid foundation, add features in future years
- **Team sustainability** - project should be enjoyable, not overwhelming
- **Budget consciousness** - keep costs reasonable to maintain team buy-in

### Scope Management Principles
- **Core functionality first**: TV screen, sound, basic LED lighting, safe stage
- **Nice-to-haves second**: Advanced VJ controls, complex interactivity, elaborate mechanisms
- **Complex engineering last**: Only if team has expertise and timeline allows
- **When in doubt, simplify**: Choose simpler solution over more impressive but risky option

## Alternatives Considered

### Deployable Ground Support Structure
**Concept:** Use deployable legs/outriggers that extend to the ground when parked, allowing for larger stage capacity and reduced cantilever stress on the truck.

**Pros:**
- Much higher stage capacity (more people)
- Reduced structural stress on truck frame
- More stable platform for performances
- Could allow for larger/heavier LED structure
- Lower engineering complexity for the cantilever design

**Cons:**
- Setup/teardown time required at each location
- Cannot drive while deployed in "fun mode"
- Reduces spontaneous mobility during events
- Additional mechanical systems (deployment mechanisms)
- Ground conditions on playa may not support outriggers
- Storage of deployable components during transport

**Decision:** **REJECTED** - Eliminated because core requirement is to drive while fully deployed in performance mode. The mobility and spontaneous movement capability is essential to the art car concept. Also aligns with "keep it simple" philosophy - fewer moving parts and mechanisms.

### Fixed vs Collapsible TV Structure
**Decision:** **TBD** - Need to research if permanent structure meets road legal requirements vs collapsible structure that deploys for events.

### Screen Location Alternatives

#### Option A: Screen at Truck Bed (SELECTED)
**Concept:** Projection screen integrated with tailgate/truck bed, audience views from behind truck.
**Pros:** Natural integration with truck bed, projector protected in bed, clear audience positioning
**Cons:** Fixed throw distance (~8ft), audience must be behind truck (exhaust/heat)

#### Option B: Screen at Front of TV Structure  
**Concept:** Screen at front of cantilever structure, projector in middle of stage.
**Pros:** Flexible projector distance, audience can be at sides, more "TV-like" appearance
**Cons:** Projector exposed to elements, complex screen mechanism, projector blocks performer space
**Decision:** **REJECTED** - Projector exposure and reduced stage space

### Base Vehicle Alternatives

#### Heavy Duty Trucks (SELECTED)
**Options:** F350/Ram 3500/Silverado 3500 Dually
**Pros:** High payload capacity, existing research, dual rear wheels for stability
**Cons:** High cost ($50-85k), overkill for some applications

#### Medium Duty Box Trucks
**Concept:** Ford E-450, Isuzu NPR, or similar commercial chassis
**Pros:** Lower cost, more interior space, designed for heavy loads, flat loading surface
**Cons:** Less familiar platform, harder to find used, may not handle cantilever loads as well
**Decision:** **NEEDS RESEARCH** - Should investigate medium duty options

#### Bus Conversion Platform
**Concept:** School bus or transit bus chassis as base
**Pros:** Very long wheelbase (better stability), low cost, huge interior space
**Cons:** Wide turning radius, harder to modify, less "truck" aesthetic
**Decision:** **REJECTED** - Poor maneuverability, doesn't fit art car aesthetic

### Power System Architecture

#### Generator + Battery Hybrid (SELECTED FOR RESEARCH)
**Concept:** Batteries handle base load and power spikes, generator provides steady charging, solar at camp for extended charging
**Pros:** 
- **Peak load management**: Batteries handle high-power audio spikes, avoiding oversized generator
- **Smaller generator**: Can use efficient mid-size generator instead of massive unit for peaks
- **Solar integration**: Can charge from solar at camp for extended operation
- **Quiet operation**: Generator can run at steady optimal RPM, batteries provide silent peaks
- **Power availability**: System works when generator off
**Cons:** Complex system, higher cost, more components to fail, requires camp solar setup

#### Generator Only
**Concept:** Direct generator power to all systems
**Pros:** Simpler system, lower cost, proven reliability
**Cons:** Noise during performance, no power when generator off
**Decision:** **UNDER CONSIDERATION** - May be acceptable if quiet generator found

#### Battery Only
**Concept:** Large lithium battery bank, charge via truck alternator + shore power
**Pros:** Silent operation, simpler system
**Cons:** Limited runtime, complex charging, very high battery cost
**Decision:** **REJECTED** - Runtime limitations for multi-day events

### Stage Access Alternatives

#### Access Through Truck Cab (CURRENT ASSUMPTION)
**Concept:** People enter truck cab normally, then climb through rear cab window or similar to reach stage
**Pros:** Natural integration, protected access route, no additional structure needed
**Cons:** Limited access width, single point of entry/exit, safety concerns, ADA non-compliant

#### External Side Stairs/Platforms
**Concept:** Permanent stairs or platforms on sides of TV structure
**Pros:** Better emergency egress, easier access for equipment, ADA potential, wider access
**Cons:** Adds cantilever load and complexity, may interfere with driving clearance, more structural points
**Decision:** **NEEDS RESEARCH** - May be required for safety/ADA compliance

#### Removable/Deployable Access
**Concept:** Stairs or ramps that deploy when stopped, retract when driving
**Pros:** No driving clearance issues, can be optimized for access, lighter when driving
**Cons:** Violates "drive while deployed" requirement, complexity, setup time
**Decision:** **REJECTED** - Violates core mobility requirement and adds complexity counter to "keep it simple" philosophy

#### Rear Access from Truck Bed
**Concept:** People access stage by climbing up through truck bed area, behind screen
**Pros:** Uses existing truck bed access, minimal additional structure
**Cons:** Interferes with projection setup, limited space, poor emergency egress
**Decision:** **REJECTED** - Conflicts with screen/projection equipment

#### Multiple Access Points
**Concept:** Combination of cab access + side emergency exits
**Pros:** Redundant egress, meets safety codes, accommodates different users
**Cons:** Most complex structurally, highest cost and weight
**Decision:** **LIKELY REQUIRED** - May be necessary for code compliance

### Professional vs DIY Labor

#### Professional Fabrication/Installation (CONSIDERED)
**Concept:** Hire professional welders, C-7 contractor, structural engineer
**Pros:** Higher quality, faster completion, professional warranties, code compliance assurance
**Cons:** Major cost increase ($8,500+ in labor costs), less team learning/ownership
**Costs:** Mobile welding $4,000, C-7 contractor $1,500, engineering consultation $3,000

#### DIY All Labor (SELECTED)
**Concept:** Team performs all welding, electrical, and construction work ourselves
**Pros:** Cost savings ($8,500+), team skill development, higher ownership/satisfaction, aligns with maker philosophy
**Cons:** Longer timeline, quality risk, learning curve, need to develop welding skills
**Decision:** **SELECTED** - Significant budget savings, team will do all labor ourselves
**Requirements:** Team must develop welding capabilities, electrical skills, structural engineering knowledge

## Content & Programming

- Silly videos
- DJ sets
- Live performances

## Interactive Elements

- Art cars are cooler if they're interactive. Maybe we could build a big remote that changes channels or something?
- Other ideas welcome 

## Project Timeline: Critical Milestones (Q4 2025 - Q3 2027)

### ⚠️ TIMELINE CONFLICT IDENTIFIED: SB100 Certificate Requirement

**CRITICAL ISSUE**: Research reveals SB100 smog exemption certificates must be applied for on "first business day of January" - this creates timing pressure for our timeline.

**RESOLUTION OPTIONS:**
1. **Accelerate to January 2025**: Submit SB100 application January 2025, begin project Q1 2025 (very aggressive)
2. **Accept 2026 application**: Apply January 2026, build without SB100 and engineer emissions compliance (higher risk/cost)
3. **Delay to 2028**: Apply January 2027, target BM 2028 (more conservative timeline)

**RECOMMENDATION**: Option 2 - Proceed with 2026 timeline but prepare for potential emissions compliance engineering.

### Milestone 1: Foundation Sprint (Q1 2026 - 3 months) ⚠️ SB100 RISK
**Critical Success Factors:**
- Core team recruited and committed
- **SB100 Certificate application submitted** (January 2026 - critical timing)
- Vehicle purchased and basic design approach validated  
- Budget committed ($100-150k confirmed by research) and workshop access confirmed
- **C-7 Low Voltage license obtained** (new requirement)

**Go/No-Go Decision Point:** Do we have the team, truck, plan, AND legal compliance pathway?

### Milestone 2: Build Phase 1 - Structure (Q2-Q3 2026 - 6 months)
**Critical Success Factors:**  
- Primary cantilever frame fabricated and truck-integrated
- Basic weight/stability testing passed
- Core safety systems (access, emergency egress) installed
- Permits and legal compliance sorted

**Go/No-Go Decision Point:** Is the fundamental structure safe and legal?

### Milestone 3: Build Phase 2 - Systems (Q4 2026 - 3 months)
**Critical Success Factors:**
- Audio system operational (simplified approach)
- Basic power system working (focus on reliability over sophistication)
- Screen mechanism functional
- LED lighting basic version installed

**Go/No-Go Decision Point:** Are core systems working together?

### Milestone 4: Integration & Testing (Q1 2027 - 3 months)
**Critical Success Factors:**
- Drive-while-deployed capability proven
- All systems reliable under normal conditions
- Team trained on operation and safety procedures
- Documentation and spare parts ready

**Go/No-Go Decision Point:** Is this ready for desert conditions?

### Milestone 5: Desert Test & Final Prep (Q2 2027)
**Critical Success Factors:**
- Fourth of Juplaya test successful OR alternative desert test completed
- Any critical issues from testing resolved
- Burning Man logistics finalized

**Final Go/No-Go Decision:** Are we confident for Burning Man?

### Milestone 6: Burning Man 2027 (Q3 2027)
**Success Metrics:**
- Safe transport and operation
- Core functionality working throughout event
- Team and participants safe and happy

### Aggressive Timeline Reality Check:
- **Total duration:** 1.5 years of actual build time
- **Emphasis on MVP approach** - core functionality over advanced features
- **Parallel work streams** - research/design while building where possible
- **Simplified systems** - proven approaches over complex engineering
- **Risk mitigation:** Desert test is critical with this timeline
- **Buffer time:** Minimal - requires disciplined scope management

## Research Completed (Comprehensive Professional Analysis)

### Legal & Regulatory Framework ✅
**CRITICAL FINDING: Must Use "Modifier" Classification**
- ✅ **Used vehicle strategy validated** - avoids NHTSA "alterer" requirements
- ✅ **California SPCNS classification confirmed** - triggers multi-agency inspection process
- 🚨 **NEW: SB100 Certificate MANDATORY** - 500/year, first-come-first-served, application due first business day of January
- **Documentation Required**: REG 343, REG 5036, REG 256, component receipts, possible surety bond
- **Inspection Sequence**: CHP VIN → BAR Referee → VSSI Certificate → Final Registration

### Vehicle Options & Costs ✅  
**Primary Option: Ford F350 Dually**
- Used 2024 models: $49,999 - $83,450
- XLT Regular/Crew Cab DRW: $63,000 - $67,000
- Higher trims (King Ranch): ~$82,000

**Alternative Options:**
- **Ram 3500 Dually**: Highest payload (7,680 lbs), best interior comfort, 35,100 lb towing
- **Chevy Silverado 3500HD Dually**: Max payload 7,290 lbs (2WD), similar capabilities to GMC  
- **GMC Sierra 3500HD Dually**: Payload increases from 4,185 lbs (SRW) to 5,607 lbs (DRW)

**Budget Estimate: $50,000 - $85,000** for suitable base vehicle

### Power System Architecture ✅
**Hybrid Generator/Battery System Validated**
- **Detailed power budget completed**: 3600W peak, 13,890 Wh nightly consumption
- **Battery requirement**: 17.4 kWh capacity (25% margin)
- **Generator requirement**: ~4.5 kW for 4-hour recharge cycle
- **Cost estimate**: Honda EU7000iS ($4,500) + 10kWh LiFePO4 banks (~$3,000)
- ✅ **Silent nighttime operation confirmed as critical for BM sound policy**

### Materials & Construction Costs ✅
**Steel vs Alternatives:**
- **Structural Steel**: $350/ton raw + $121-1,030/ton fabrication
- **Weathering Steel (Cor-Ten)**: Recommended for desert environment, self-protecting patina
- **316 Stainless**: $600-3,000/ton, marine-grade corrosion resistance
- **Mobile Welding**: $22-30/hr (Nevada County area)

**Specialized Components:**
- **Aluminet Shade Cloth**: $0.45-3.28/sq ft depending on finish
- **NEMA 4X Enclosures**: Mandatory minimum for all electronics (~$200 each)
- **Professional AV**: Hisense PX3-PRO projector ($3,200), JBL EON715 speakers ($600 each)

### Critical New Requirements 🚨
**C-7 Low Voltage License**: Required for LED systems >$1,000 project value
**Insurance**: Specialty "Agreed Value" policies required - $3,000 annual + $7,000 event coverage
**Burning Man Compliance**: Detailed safety requirements, 5 MPH limit, 36-48" railings, full lighting

**Updated Total Project Estimate: $100,000 - $150,000** (major increase from research findings)

## Critical Questions & Research Needed

*Note: Research priorities reflect "minimal viable product" philosophy - focus on core safety/legal requirements first, nice-to-have features later.*

### 🤔 **STRATEGIC QUESTION: Regulatory Compliance Scope**
**Open Question:** Do we need full regulatory compliance for a "Burning Man only" vehicle?

**Key Considerations:**
- **Highway transport required** - CA to NV public roads mandate DOT/DMV compliance
- **BM requires legal registration** - Mutant Vehicle application needs proof of valid CA registration  
- **Insurance liability exposure** - 20+ people in cantilever structure creates enormous personal liability
- **Safety vs cost trade-off** - regulations exist because art cars have killed people

**Compliance Strategies:**
- **Full Compliance (recommended)**: $104-138k total, legal/insured/safe, minimal project-killing risks
- **Selective Compliance**: $80-90k?, skip some professional services, higher risk of registration/insurance denial
- **Minimum Viable Compliance**: TBD - research what's truly mandatory vs. "best practice"

**Decision Impact:** This choice affects timeline, budget, and project risk profile significantly.

**Action Item:** Investigate minimum legally required compliance for BM-only operation.

### Legal & Regulatory Requirements ✅ RESEARCH COMPLETE → ACTION ITEMS
- ✅ **DOT regulations**: "Modifier" classification confirmed - no safety systems made inoperative
- ✅ **California DMV**: SPCNS process detailed - REG 343, REG 5036, CHP/BAR/VSSI inspections required  
- ✅ **BM registration**: Mutant Vehicle criteria analyzed - mutation, interactivity, safety, lighting, sound
- ✅ **Insurance costs**: $3,000 annual + $7,000 event liability (major budget impact)
- ✅ **Road dimensions**: 8'6" W x 14' H x 40' L (California limiting factor)

**🚨 CRITICAL ACTION ITEMS:**
- **SB100 Certificate application** - MUST submit first business day January 2026
- **C-7 Low Voltage License** - obtain for LED system compliance  
- **SPCNS documentation prep** - compile all component receipts, ownership docs
- **Specialty insurance quotes** - contact Hagerty/Heacock Classic early in design phase

### Remaining Technical Specifications (HIGH PRIORITY)
- **Truck specifications for cantilever design:**
  - **Rear axle weight rating** vs actual rear axle load with structure + people
  - **Wheelbase length** - affects tipping moment calculations (longer = more stable)  
  - **Frame attachment points** - where can cantilever structure safely connect to chassis?
  - **Center of gravity** limits before truck becomes unstable while driving
  - **Suspension capacity** - can truck suspension handle cantilever moment plus road forces?

### Technical Specifications ✅ RESEARCH COMPLETE → DESIGN PHASE  
**Screen and projection system:**
- ✅ **Projector models identified**: Hisense PX3-PRO ($3,200), BenQ X500i, Optoma UHZ35ST
- ✅ **8ft throw distance confirmed** for truck bed mounting
- 🔄 **Screen integration with tailgate** - manual vs motorized mechanism design needed
- 🔄 **Weather protection** - NEMA 4X enclosure required for projector

**Audio system:**
- ✅ **BM sound policy**: <75 dB at camp border, generators must be baffled
- ✅ **Power requirements calculated**: 2,400W speakers + subwoofers peak 
- ✅ **Professional equipment specified**: JBL EON715 speakers ($600 each)
- ✅ **Weatherproofing standard**: All components must be NEMA 4X rated

**Power system:**
- ✅ **Detailed power budget completed**: 3600W peak, 13,890 Wh nightly consumption
- ✅ **Battery capacity determined**: 17.4 kWh LiFePO4 with 25% margin
- ✅ **Generator sizing**: Honda EU7000iS (4.5kW) for 4-hour recharge cycles
- ✅ **Hybrid architecture validated**: Silent nighttime operation critical for BM compliance
- 🔄 **Solar integration logistics** - camp setup and transport planning needed

**LED lighting system:**
- ✅ **LED specifications**: WS2812B addressable strips, $15/meter installed cost  
- ✅ **Control system**: VJ software (Resolume ~$1,200), addressable controllers
- ✅ **Power consumption**: 440W average for 100ft of LED strips
- 🔄 **Mounting system design** - integration with steel frame structure

### Construction & Engineering ✅ CRITICAL INSIGHTS FROM RESEARCH
**Professional Engineering Recommendations:**
- ✅ **Weathering Steel (Cor-Ten)** recommended for desert environment - self-protecting patina, no paint needed
- ✅ **Hybrid welded/bolted approach**: Permanent steel plates welded to chassis, superstructure bolts to plates for modularity
- ✅ **All fasteners must use Loctite** and mechanical locking (nylon insert nuts) - vibration will loosen everything
- ✅ **NEMA 4X enclosures mandatory** for all electronics - playa dust is uniquely destructive
- ⚠️ **GVWR limits are non-negotiable** - exceeding causes repeated drivetrain failures

**Critical Failure Modes Identified by Research:**
- 🚨 **9-foot cantilevers documented as failing** on similar art cars - our design must be much more conservative
- 🚨 **Dynamic amplification** from playa vibration causes static calculations to underestimate loads  
- 🚨 **Overloaded vehicles repeatedly break down** - transmissions and cooling systems most vulnerable

**Frame Design Requirements (ALL LABOR OURSELVES):**
- **Pure cantilever engineering** with NO ground support legs allowed
- **Modular superstructure** - core rigid structure + attachable art elements
- **Team welding capability required** - mounting plates welded to main frame rails
- **Conservative load rating** - research shows failures happen when pushing limits
- **Wind load planning** - anemometer required, retraction protocols for >40 mph winds

**Material Specifications:**
- ✅ **Weathering steel**: $350/ton (raw material cost only)
- 🔄 **Frame attachment engineering** - specific mounting plate design needed

### Safety & Risk Assessment (CRITICAL)
**Structural Safety (DRIVE-WHILE-DEPLOYED):**
- **Driving stability** - truck must remain stable while driving with people on cantilever stage
- **No backup supports** - if cantilever fails, no ground legs to catch it
- **Conservative design required** - significant safety margins needed without external supports
- **Stage collapse scenarios** - catastrophic failure modes without ground supports
- **Emergency evacuation while moving** - people must be able to safely exit moving vehicle
- **Load limits** - maximum people severely constrained by pure cantilever design

**Entry/Exit & Emergency Egress (CRITICAL):**
- **Primary access route** - through cab? External stairs? How do people get on/off?
- **Emergency egress requirements** - minimum number of exits, width requirements?
- **Emergency egress while moving** - how do people safely exit if truck needs to move quickly?
- **ADA accessibility** - required accommodations for performers with disabilities?
- **Entry/exit structural loads** - stairs/ramps add cantilever load and complexity
- **Entry safety while moving** - can people safely board/exit while vehicle is in motion?
- **Queue management** - where do people wait to get on? How many at once?

**Fire & Emergency Safety:**
- **Fire safety plan** and suppression system in enclosed space
- **Stage evacuation routes** - what if primary exit is blocked?
- **Emergency vehicle access** - can emergency services reach performers?
- **Structural failure modes** and prevention for cantilever design
- **First aid station** location and access
- **Electrical safety** in dusty environment near truck engine/fuel

### Budget & Financial Planning ✅ RESEARCH COMPLETE - MAJOR BUDGET INCREASE
**Detailed cost breakdown from professional research (ALL LABOR OURSELVES):**
- ✅ **Vehicle**: $50-85k (confirmed)
- ✅ **Legal/Registration**: $1,120 (SPCNS fees, inspections, surety bond if needed)  
- ✅ **AV Equipment**: $15,200 (Hisense projector $3,200 + JBL speakers $2,400 + subwoofers $1,600 + LED strips $1,500 + screen materials $350 + VJ software $1,199 + misc $4,951)
- ✅ **Power System**: $10,000 (Honda EU7000iS $4,500 + 17.4kWh LiFePO4 $3,000 + NEMA 4X enclosures $800 + inverter/BMS $2,000)
- ✅ **Construction Materials**: $6,700 (Steel materials $2,200 + fasteners $500 + Aluminet $200 + paint/finishing $1,000 + tools $2,800)
- ✅ **Insurance**: $10,000 annual (Agreed Value policy $3,000 + Event liability $7,000)
- ✅ **Storage & Logistics**: $2,400 (12 months storage $1,200 + transport $1,200)

**🚨 TOTAL PROJECT COST: $95,420 - $125,420** (removed $8,500 in professional labor)
**🚨 ANNUAL OPERATING COSTS: $10,000+** (insurance alone)

**Funding strategy:**
- **Payment timeline** - when is money needed?
- **Sponsor opportunities** or grants available?
- **Cost sharing** among team members?

### Team & Skills Requirements (MEDIUM PRIORITY)
**Core skills inventory:**
- **Structural welding and fabrication** - who?
- **Electrical work** - 12V systems, power distribution, LED control?
- **Projection mapping and VJ software** expertise?
- **Audio system design** and setup?
- **Project management** and timeline coordination?
- **Mechanical systems** (retractable screen mechanism)?

**Team size and commitment:**
- **How many people minimum** for construction phases?
- **Time commitment required** from each person?
- **Backup people** for critical skills?

### Location & Logistics (MEDIUM PRIORITY)
- ✅ **Build location**: Safeers house in Nevada City for weekends
- ❓ **Storage location** during build phases and off-season?
- ❓ **Workshop access**: tools, power, covered workspace size?
- ❓ **Permits needed** for construction at residential location?
- ❓ **Material delivery logistics** to Nevada City?

### Timeline & Project Management (MEDIUM PRIORITY)
**Detailed project phases:**
- **Phase 1**: Vehicle acquisition and basic prep (when?)
- **Phase 2**: Frame design and fabrication (duration?)
- **Phase 3**: AV system integration and testing (timeline?)
- **Phase 4**: Final assembly and shakedown testing (when?)
- **Critical path dependencies?**
- **Buffer time for setbacks?**
- **Fourth of Juplaya 2027 test** - what needs to be ready?

### Interactive Elements & Content (LOW PRIORITY)
**User experience design:**
- **Remote control interface** - what functions?
- **Content management** - who curates videos/performances?
- **Channel switching mechanism?**
- **User safety during interaction?**
- **Queue management for performances?**
- **Integration with other art cars or camps?**