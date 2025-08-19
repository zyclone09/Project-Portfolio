# Bluetooth Speaker Build

> _Basic Bluetooth Speaker build to learn about circuitry and soldering_

![Cover](media/Components.jpeg)

## 1) Overview
-The goal of this project was to design and assemble a portable Bluetooth speaker using off-the-shelf electronic modules, hand tools, and a custom housing. The build provided hands-on learning in electronics assembly, soldering, power management, and acoustic design.
- **Dates:** 17-09-2021
- **Tools:** Soldering iron, flux, CAD for enclosure, finishing tools
- **Skills:** Circuit basics, driver selection, acoustic enclosure design
- **Outcome:** Compact speaker with Bluetooth connectivity; clean sound with minimal resonance

## 2) Gallery
![Step 1](media/Speaker_circuit.jpeg)
![Step 2](media/Schematic.png) - found online

> Embed short clips via links:  
> - Build timelapse: https://youtu.be/your-video
> - Drive folder (raw media): https://drive.google.com/your-folder

## 3) Bill of Materials (BOM)
| Item | Spec | Source | Cost |
|---|---|---|---|
| Drivers | 2x 20mm drivers | Local Electronics store| $8 |
| Bluetooth Audio Module | ESP32 | Local Electronics store| $4 |
| Battery | Li-ion 800mAh with JST connector | Local Electronics store| $10 |
| Wires | Assorted wires | Local Electronics store| $1 |
| Switch | Push switch | Local Electronics store| $0.3 |
| Flux | Standard soldering paste | Local Electronics store| $0.98 |
| Soldering coil | Standard solder | Local Electronics store| $0.40 |
| Case | Clear Casette case | Local Electronics store| $5 |
| Channel splitter | charging and channel spliter circuit board | Local Electronics store| $2 |

Store Name: Marutsu Akihabara https://maps.app.goo.gl/WamnnXX7eM4C1Lz96

## 4) Process Notes
- **Planning & Selection:**
  - Chose small full-range drivers for balanced output and compact size (20mm)
  - Bluetooth connectivity for portability with built-in decoding and amplification
  - 800mAh battery for short/medium use (for portability factor)
  - Planned on designing a custom acoustic case however due to lack of printing services during pandemic times, opted for making a small compact case out of a cassette case.

- **Layout & Circuit Preparation:**
  - Researched initially on the appropriate circuit board to buy and how to layout the schematic
  - Battery -> Switch -> Bluetooth Module -> Channel splitter / charging board -> L&R channels
  - Measured component dimensions for enclosure fitment
  - Color coded wires for ease of understanding

- Wiring & Assembly
	-	Stripped, tinned, and soldered wires using flux paste for clean joints.
	-	Connected battery leads through the push-button switch before routing to the amplifier module.
	-	Wired speaker drivers to the left/right output terminals of the module.
	-	Secured wiring inside the case using heat shrink and hot glue for strain relief.

- Power & Testing
	-	Inserted the Li-ion battery pack and verified correct polarity.
	-	Powered the system through the push-button switch; confirmed LED indicator on the Bluetooth module.
	-	Paired with a phone to test audio playback; verified both speakers produced sound.
	-	Checked for distortion at higher volumes; adjusted wiring lengths to minimize noise pickup.

- Finishing & Optimization
	-	Ensured all wiring was insulated and enclosed safely.
	-	Mounted the metal spring as part of the structural support inside the case (shock absorption for speaker vibrations).
	-	Sealed the enclosure and performed extended playback tests (~2–3 hours on battery).

<details>
<summary>Build Log (expand)</summary>

1.	Component Sourcing: Purchased speakers, Bluetooth module, battery, and wires.
2.	Initial Mock-up: Laid out components on graph paper to visualize circuit and enclosure placement.
3.	Soldering Work:
  -	Prepped wires with flux and solder.
	-	Connected switch to control power from battery.
	-	Wired speakers to amplifier outputs.
4.	Circuit Testing: Connected battery → tested Bluetooth pairing → confirmed audio output.
5.	Debugging: Fixed one loose speaker wire that caused channel imbalance.
6.	Enclosure Work: Installed speakers into case, reinforced joints with glue and rubber band.
7.	Final Testing: Played music for several hours to confirm stability and battery life.
8.	Project Completion: Fully portable Bluetooth speaker with clean sound output and stable wireless connection.

</details>

## 5) Results
-	Successfully built a fully functional Bluetooth speaker.
-	Learned practical skills:
-	Circuit wiring & soldering
-	Power management (Li-ion battery integration)
-	Debugging audio systems
-	Enclosure design considerations
-	Final system provided ~3 hours playback per charge, portable size, and reliable Bluetooth connectivity.

## 6) Reflection (STAR)
- **Situation:** I decided to build a Bluetooth speaker from scratch. I’d always been curious about how electronics came together, and I wanted a fun project that would push me to learn new skills outside of uni work.
   
- **Task:** The goal was simple: make a working portable speaker on a small budget while teaching myself the basics of wiring, soldering, and power management.
  
- **Action:** I bought affordable parts in-person; speakers, a Bluetooth module, and a Li-ion battery – and started experimenting. Most of it was trial and error. I learned how to solder properly using flux, figured out how to wire the switch and battery safely, and fixed issues like one speaker not working due to a loose connection. It wasn’t perfect, but each problem made me stop, research, and try again until it worked.
  
- **Result:** The end product was a working Bluetooth speaker with around 3 hours of playback. More importantly, I came out of it with a lot more confidence in problem-solving and taking initiative to learn.
  
- **Future:** Next time, I’d focus more on enclosure design especially and budgeting for better sound quality. I’d also like to add a proper charging circuit and maybe even design a custom PCB to make it neater.

I am always keen to expand my knowledge in all engineering fields and passionate towards learning new skills through applying theory into practice.
