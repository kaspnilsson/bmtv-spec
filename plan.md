# BMTV - Burning Man TV Art Car Project

## Project Overview

Tube TV art car where the truck bed becomes the TV screen and the truck cab is inside the "tube." The TV structure extends forward from the truck bed to approximately the rear of the cab, creating a performance stage area behind the cab but forward of the rear axle.

**Key Spatial Layout:**
- **TV Screen**: Truck bed tailgate area (retractable projection screen)  
- **TV "Tube"**: LED scaffolding extending forward ~8-10 feet to rear cab line
- **Stage Area**: Between cab and rear axle (weight-limited performance space)
- **Audience**: Views screen from behind the truck

**Base Vehicle:** F350 dually or similar

**Timeline:** On playa by 2027

**Critical Engineering Constraints:** 
- The stage area is a cantilever structure extending forward from the rear axle, creating significant tipping moment
- **Must be driveable while fully deployed** - no ground support legs or external stabilizers allowed
- All structural loads must be supported entirely by truck frame and suspension
- This fundamentally limits stage capacity and requires conservative structural engineering

## Core Philosophy

- Car must be capable of driving itself to the playa
- Car should have at least mid-tier art car audio
- Car should be built to work with or withstand the elements on the playa (waterproofing and dust proofing, wind resistance / usage of porous materials to counteract wind)
- Make use of collapsible bits, custom fabrication wherever possible

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

**Decision:** **REJECTED** - Eliminated because core requirement is to drive while fully deployed in performance mode. The mobility and spontaneous movement capability is essential to the art car concept.

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
**Decision:** **REJECTED** - Violates core mobility requirement

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

## Content & Programming

- Silly videos
- DJ sets
- Live performances

## Interactive Elements

- Art cars are cooler if they're interactive. Maybe we could build a big remote that changes channels or something?
- Other ideas welcome 

## Research Completed

### Vehicle Options & Costs
**Primary Option: Ford F350 Dually**
- Used 2024 models: $49,999 - $83,450
- XLT Regular/Crew Cab DRW: $63,000 - $67,000
- Higher trims (King Ranch): ~$82,000

**Alternative Options:**
- **Ram 3500 Dually**: Highest payload (7,680 lbs), best interior comfort, 35,100 lb towing
- **Chevy Silverado 3500HD Dually**: Max payload 7,290 lbs (2WD), similar capabilities to GMC
- **GMC Sierra 3500HD Dually**: Payload increases from 4,185 lbs (SRW) to 5,607 lbs (DRW)

**Budget Estimate: $50,000 - $85,000** for suitable base vehicle

### Material & Construction Costs (Partial)
**Frame Construction:**
- **Steel Fabrication**: $6-18/ft for I-beams, $50-150/hr labor, $24-43/sq ft total installed cost
- **Aluminum Alternative**: 3x lighter but 2-3x more expensive material cost
- **Recommendation**: Steel for primary structure, aluminum for weight-sensitive components

**Shade/Covering Materials:**
- **Aluminet Shade Cloth**: 3-4x more expensive than traditional shade cloth, reduces heat by 30%
- **Alternative**: Traditional shade cloth or canvas for budget option

**Estimated total construction materials**: $15,000 - $35,000 (rough estimate)

## Critical Questions & Research Needed

### Legal & Regulatory Requirements (HIGH PRIORITY)
- **DOT regulations for art car modifications?**
- **California DMV requirements for modified vehicles?**
- **Burning Man art car registration process and timeline?**
- **Insurance requirements and costs for art cars?**
- **Road legal dimension limits?** (8.5' width standard, height varies by state)  
- **Drive-while-deployed regulations** - are there special rules for structures on moving vehicles?
- **Truck specifications critical for pure cantilever design:**
  - **Rear axle weight rating** vs actual rear axle load with structure + people
  - **Wheelbase length** - affects tipping moment calculations (longer = more stable)
  - **Frame attachment points** - where can cantilever structure safely connect to chassis?
  - **Center of gravity** limits before truck becomes unstable while driving
  - **Suspension capacity** - can truck suspension handle cantilever moment plus road forces?
- **Required safety equipment** (lights, mirrors, etc.) for permanent structure

### Technical Specifications & Design (HIGH PRIORITY)
**Screen and projection system:**
- **Projector placement** - must be behind tailgate, distance fixed by truck bed length (~8ft)
- **Short-throw projector requirements** - specific models that work at 8ft distance
- **Screen integration with tailgate** - motorized vs manual, storage when driving
- **Screen material** that works in daylight vs night at fixed 8ft throw distance?
- **Viewing angle** - audience behind truck, screen angled up or straight back?
- **Weather protection** for projector mounted in/on truck bed

**Audio system:**
- **Sound ordinance limits** at Burning Man?
- **Power requirements** for "epic sound"?
- **Speaker weatherproofing** and dust protection?
- **Audio mixing capabilities** - DJ booth location?

**Power system (Peak Load Management):**
- **Peak vs base load analysis** - audio spikes vs steady LED/projection power
- **Battery capacity** for handling audio peaks + base load duration
- **Generator sizing** - steady charging rate vs peak power requirements
- **Solar integration** - camp-based charging capacity and logistics
- **Power consumption breakdown**:
  - Audio system peak loads (amplifiers during bass drops, etc.)
  - LED lighting constant draw
  - Projector steady power
  - Control systems and charging
- **Runtime requirements** (hours per day) and charging cycles
- **Noise restrictions** for generator use at different times

**LED lighting system:**
- **LED tube specifications** (pixel density, weatherproofing)?
- **Control system** - VJ software, hardware interface?
- **Power consumption** for full LED array?
- **Mounting system** for LED tubes on frame?

### Construction & Engineering (HIGH PRIORITY)
**Critical Weight & Balance Constraints (DRIVE-WHILE-DEPLOYED):**
- **Rear axle weight limits** - structure + people must not exceed truck's rear axle rating
- **Center of gravity calculations** - cantilever load affects truck stability while driving
- **No external supports allowed** - everything supported by truck frame only
- **Dynamic loads while moving** - structure must handle driving forces + people on stage
- **Suspension limitations** - truck suspension must handle cantilever moment while driving

**Frame design:**
- **Pure cantilever engineering** - NO ground support legs allowed
- **Truck frame integration** - must distribute loads properly to chassis
- **Drive-ready design** - structure must be permanently attached and road-safe
- **Conservative load rating** - stage capacity severely limited by no-external-support rule
- **Aerodynamics** - structure must not create dangerous wind loads while driving

**Truck Bed Modifications:**
- **Tailgate integration** with projection screen mechanism
- **Bed reinforcement** for cantilever load anchor points
- **Access panels** for equipment storage under stage

**Materials research:**
- **Steel grade and thickness** for cantilever beam design
- **Fastener specifications** for truck frame attachment points  
- **Paint/coating** for rust prevention?
- **Cable management** for power and data?

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

### Budget & Financial Planning (HIGH PRIORITY)
**Detailed cost breakdown needed:**
- ✅ Vehicle: $50-85k (researched)
- ❓ AV equipment: projector ($2-10k?), sound system ($5-15k?)
- ❓ Power system: batteries ($3-8k?), generator ($2-5k?), solar panels + camp setup ($2-5k?)
- ❓ LED lighting system ($3-10k?)
- ❓ Tools and equipment rental/purchase ($2-5k?)
- ❓ Labor costs if hiring welders/fabricators?
- ❓ Insurance and permits ($1-3k annually?)
- ❓ **TOTAL PROJECT ESTIMATE NEEDED**

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