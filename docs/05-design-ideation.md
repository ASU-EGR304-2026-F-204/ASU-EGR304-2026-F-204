---
title: Design Ideation
---

## Step Two: Generating Ideas
| Requirement / need | Feature | Detail |
| :--- | :--- | :--- |
| Accurate and Clinically-Valid Readings | PPG Optical Heart-Rate Sensor | Uses LEDs and a photodiode to measure blood volume |
| Accurate and Clinically-Valid Readings | Dual-Wavelength LED System | Uses green and IR LEDs for accuracy across skin tones |
| Accurate and Clinically-Valid Readings | Analog Front-End Filtering | Hardware filters to remove signal noise |
| Accurate and Clinically-Valid Readings | High-Resolution ADC Sampling | Converts analog signals into precise digital data |
| Accurate and Clinically-Valid Readings | Motion Artifact Reduction Algorithm | Software filter to ignore movement noise |
| Comfortable and Skin-Friendly Wearability | Hypoallergenic Silicone Strap | Prevents skin irritation during extended wear |
| Comfortable and Skin-Friendly Wearability | Ergonomic Curved Sensor Housing | Curves to match the wrist for better skin contact |
| Comfortable and Skin-Friendly Wearability | Ventilated Strap Pattern | Holes in the strap to reduce sweat buildup |
| Comfortable and Skin-Friendly Wearability | Lightweight Polymer Enclosure | Keeps the device light to prevent wrist fatigue |
| Comfortable and Skin-Friendly Wearability | Soft Backplate Cushioning | Provides comfortable pressure against the skin |
| Seamless App Connectivity and Data Export | Bluetooth Low Energy Module | Wireless connection to mobile phones |
| Seamless App Connectivity and Data Export | Automatic Pairing Mode | Connects to phone without manual setup |
| Seamless App Connectivity and Data Export | Real-Time BPM Streaming | Sends live data directly to the app |
| Seamless App Connectivity and Data Export | CSV/JSON Export Function | Lets users download their heart rate logs |
| Seamless App Connectivity and Data Export | Firmware Updates Over BLE | Updates device software wirelessly |
| Transparent, High-Value Pricing | Off-the-Shelf PPG Sensor | Uses standard parts to lower manufacturing costs |
| Transparent, High-Value Pricing | Simplified PCB Layout | Reduces manufacturing complexity and cost |
| Transparent, High-Value Pricing | Open-Source Firmware Libraries | Lowers software development licensing costs |
| Transparent, High-Value Pricing | Modular Internal Design | Allows individual parts to be replaced if broken |
| Transparent, High-Value Pricing | Efficient Component Sourcing | Uses common parts to avoid supply chain delays |
| Ease of Use and Clear Navigation | Single Multi-Function Button | One button controls all major features |
| Ease of Use and Clear Navigation | LED Status Indicator | Uses colors to show device state and battery |
| Ease of Use and Clear Navigation | Haptic Vibration Alerts | Vibrates for events and abnormal heart rates |
| Ease of Use and Clear Navigation | Auto-Start Measurement Mode | Turns on automatically when placed on wrist |
| Ease of Use and Clear Navigation | Simple App Dashboard | Easy-to-read app interface for non-technical users |
| Durability and High Manufacturing Quality | IP67 Waterproof Gasket Sealing | Protects internal electronics from water and dust |
| Durability and High Manufacturing Quality | Scratch-Resistant Optical Window | Hard glass over the sensor to prevent scratching |
| Durability and High Manufacturing Quality | Conformal PCB Coating | Protects the circuit board from moisture and sweat |
| Durability and High Manufacturing Quality | Reinforced Stainless Steel Lug Pins | Strong metal pins to secure the strap to the housing |
| Durability and High Manufacturing Quality | Impact-Resistant ABS/PC Enclosure | Tough plastic prevents cracking from drops |
| Good Battery Life | Deep-Sleep Microcontroller Mode | Places the processor in sleep mode to save power |
| Good Battery Life | Duty-Cycled LED Pulsing | Flashes LEDs briefly rather than continuously |
| Good Battery Life | High-Density LiPo Battery Cell | Maximizes physical battery capacity |
| Good Battery Life | Motion-Triggered Auto-Sleep | Turns device off when taken off the wrist |
| Good Battery Life | Batch BLE Data Transmission | Sends data in bursts to save radio energy |
| Regulate system power from 9 volts to 5 volts | Synchronous Buck Converter IC | Highly efficient 9V to 5V step-down regulator |
| Regulate system power from 9 volts to 5 volts | Low-Dropout (LDO) Linear Regulator | Provides clean, noise-free 5V power for the sensor |
| Regulate system power from 9 volts to 5 volts | Hybrid Buck-LDO Two-Stage Regulator | Combines buck efficiency and LDO low noise |
| Regulate system power from 9 volts to 5 volts | Switched-Capacitor Charge Pump | Inductor-less 5V regulation to save board height |
| Regulate system power from 9 volts to 5 volts | Zener Diode Shunt Regulator | Cheap, simple voltage clamping for auxiliary circuits |
| Provide over-amperage protection (1.5A limit) | Resettable PTC Polyfuse | Auto-resetting 1.5A current limit |
| Provide over-amperage protection (1.5A limit) | Electronic eFuse IC | Fast, active 1.5A current cutoff switch |
| Provide over-amperage protection (1.5A limit) | Fast-Blow Surface-Mount Fuse | Permanent 1.5A cutoff for absolute safety |
| Provide over-amperage protection (1.5A limit) | Shunt Resistor with Comparator Cutoff | Custom op-amp circuit to shut off at 1.5A |
| Provide over-amperage protection (1.5A limit) | Foldback Current-Limiting Circuit | Reduces voltage safely when overloaded |
| Provides visual feedback | OLED Display | High contrast screen for detailed metrics |
| Provides visual feedback | E-ink Display | Extremely low power display that mimics paper |
| Provides visual feedback | TFT LCD | Full color display for vibrant UI elements |
| Provides visual feedback | Seven-segment display | Simple, retro display just for numbers (BPM) |
| Provides visual feedback | RGB LED ring | Circular LED array to show progress or zones |
| Provides audible/tactile notifications | Piezo buzzer | Emits simple beeps for warnings and alerts |
| Provides audible/tactile notifications | Voice prompts (speaker) | Speaks heart rate out loud for visually impaired |
| Provides audible/tactile notifications | Eccentric Rotating Mass (ERM) motor | Traditional strong rumble vibration motor |
| Provides audible/tactile notifications | Linear Resonant Actuator (LRA) | Crisp, precise haptic feedback clicks |
| Provides audible/tactile notifications | Audio jack for headphones | Private audible alerts during exercise |
| Secures device during exercise | Velcro strap | Infinitely adjustable for a perfect fit |
| Secures device during exercise | Magnetic clasp | Quick and easy one-handed attachment |
| Secures device during exercise | Traditional watch buckle | Standard, reliable mechanical security |
| Secures device during exercise | Elastic slip-on band | No hardware required, stretches over the hand |
| Secures device during exercise | Braided nylon loop | Breathable and stretches for active wearers |
| Easy power charging | USB-C port | Standard wired charging cable |
| Easy power charging | Magnetic pogo pins | Snap-on waterproof charging cable |
| Easy power charging | Wireless Qi charging | Charge by placing on a pad (no exposed ports) |
| Easy power charging | Replaceable coin cell | No charging required, swap batteries every 6 months |
| Easy power charging | Solar panel face | Trickle charges the device while outdoors |
| Device hygiene and cleanability | Smooth crevice-free housing | Eliminates gaps where dirt and sweat can hide |
| Device hygiene and cleanability | Alcohol-safe plastics | Allows users to sanitize the device with wipes |
| Device hygiene and cleanability | Detachable washable strap | Strap can be thrown in the washing machine |
| Device hygiene and cleanability | UV-C sanitizing case | Storage case cleans the device with UV light |
| Device hygiene and cleanability | Antimicrobial coating | Prevents bacterial growth on the device surface |
| Secure data handling | Local data encryption | Scrambles data so it cannot be intercepted |
| Secure data handling | Anonymous guest mode | Allows tracking without making an account |
| Secure data handling | Password protected app | Requires a PIN or FaceID to view health data |
| Secure data handling | PIN code on device | Locks the physical screen from prying eyes |
| Secure data handling | Biometric lock | Verifies the wearer's pulse signature to unlock |
| Accessibility for all users | Large text mode | Increases font size on the app and device |
| Accessibility for all users | High contrast colors | Makes the UI easier to read for the visually impaired |
| Accessibility for all users | Screen reader compatibility | App works with iOS VoiceOver and Android TalkBack |
| Accessibility for all users | Braille indicators on buttons | Tactile dots to help users find controls blindly |
| Accessibility for all users | Textured button surfaces | Differentiates buttons by feel rather than sight |
| Environmental robustness | Extreme temperature tolerance | Operates safely in freezing or desert conditions |
| Environmental robustness | UV resistant plastics | Prevents the housing from yellowing in the sun |
| Environmental robustness | Corrosion resistant contacts | Gold-plated charging pins to prevent rust from sweat |
| Environmental robustness | Recessed screen | Screen sits below a raised bezel to prevent shattering |
| Environmental robustness | Internal shock mounts | Rubber bumpers around the PCB to absorb impacts |
| User customization | Swappable face plates | Lets users change the color of the device |
| User customization | Customizable watch faces | Users can choose what data to display on the home screen |
| User customization | Adjustable brightness | Screen dims at night and brightens outdoors |
| User customization | Configurable vibration patterns | Users choose different buzzes for different alerts |
| User customization | Goal-setting parameters | Users can set their own daily heart rate targets |
| Eco-friendly sustainable design | Recycled plastic housing | Uses ocean-bound plastics for the enclosure |
| Eco-friendly sustainable design | Biodegradable packaging | Box dissolves in water or composts easily |
| Eco-friendly sustainable design | Repairable screw assembly | Uses standard screws instead of glue so users can fix it |
| Eco-friendly sustainable design | Lead-free solder (RoHS) | Eliminates toxic heavy metals in manufacturing |
| Eco-friendly sustainable design | Conflict-free minerals | Guarantees ethical sourcing for electronic components |

---

## Step Three: Sort, Rank, and Group

### 1. Sorting the Ideas into Groups

After reviewing our brainstorm, we organized the features into five main groups based on the user needs they address. The five groups were **accurate and clinically valid readings, comfortable and skin friendly wearability, seamless app connectivity and data export, transparent and high value pricing, and ease of use and clear navigation.**

##### Accurate and Clinically Valid Readings
This group contains the features responsible for collecting and processing accurate heart rate data. These include the PPG optical heart rate sensor, dual wavelength LED system, analog front end filtering, high resolution ADC sampling, and motion artifact reduction algorithm. Together, these features focus on making sure that the device can consistently produce reliable heart rate measurements during both stationary and active use.

##### Comfortable and Skin Friendly Wearability
This group focuses on making the device comfortable enough for users to wear for extended periods. The features include a hypoallergenic silicone strap, ergonomic curved sensor housing, ventilated strap pattern, lightweight polymer enclosure, and soft backplate cushioning. These features work together to reduce skin irritation, sweat buildup, wrist fatigue, and discomfort while also maintaining consistent contact between the sensor and the user's skin.

##### Seamless App Connectivity and Data Export
This group focuses on connecting the device to a mobile application and making the collected information useful to the user. The features include Bluetooth Low Energy, automatic pairing, real time BPM streaming, CSV and JSON data export, and firmware updates over Bluetooth. These features allow users to easily connect the device, monitor their heart rate, save their data, and maintain the device through software updates.

##### Transparent, High Value Pricing
This group focuses on keeping the product affordable while maintaining its functionality and reliability. The features include using an off the shelf PPG sensor, a simplified PCB layout, open source firmware libraries, a modular internal design, and efficient component sourcing. These features could reduce manufacturing and maintenance costs while allowing the product to remain functional and reliable.

##### Ease of Use and Clear Navigation
This group focuses on making the device simple to operate without requiring extensive technical knowledge. The features include a single multifunction button, LED status indicator, haptic vibration alerts, automatic measurement mode, and a simple app dashboard. These features reduce the number of steps required from the user and provide clear feedback about the device's status.

---

### 2. Ranking and Discussing the Top Ideas

After sorting the ideas, we discussed which features were most important within each group. We focused on features that directly addressed the primary purpose of the product while also improving the overall user experience.

##### Accurate and Clinically Valid Readings
The **PPG optical heart rate sensor** and **motion artifact reduction algorithm** were among the most important features. The PPG sensor is necessary to collect the heart rate data, while motion artifact reduction can help maintain more consistent readings when the user is moving.

##### Comfortable and Skin Friendly Wearability
The **ergonomic curved sensor housing** and **hypoallergenic silicone strap** were important because the device needs to maintain consistent contact with the skin without becoming uncomfortable during extended use.

##### Seamless App Connectivity and Data Export
**Bluetooth Low Energy** and **real time BPM streaming** were important because they allow the device to communicate continuously with the user's phone. The **CSV and JSON export function** was also considered valuable because it gives users more control over their collected data.

##### Transparent, High Value Pricing
The use of **off the shelf components** and **efficient component sourcing** were important because these features could help lower the overall cost of manufacturing the device.

##### Ease of Use and Clear Navigation
The **simple app dashboard** and **automatic measurement mode** were among the strongest ideas. These features reduce the number of actions the user needs to perform and make the information easier to understand.

---

### 3. Generating New Features

After discussing the strongest ideas, we began combining features from different groups to create new features. This allowed us to move beyond the original brainstorm and develop ideas that could provide multiple benefits at the same time.

##### Automatic Monitoring System
We could combine **automatic measurement mode**, **Bluetooth Low Energy**, and **real time BPM streaming** into an automatic monitoring system. When the user puts on the device, it could automatically begin collecting heart rate data and send that information to the mobile application without requiring the user to manually start a measurement.

##### Intelligent Heart Rate Alerts
Another new feature could combine the **motion artifact reduction algorithm** with **haptic vibration alerts**. This could allow the device to analyze the user's heart rate while accounting for movement and provide a vibration alert when a potentially abnormal heart rate is detected.

##### Modular Repair and Upgrade System
We could also combine the **modular internal design** with the **off the shelf PPG sensor** to create a device that is easier to repair or upgrade. Instead of replacing the entire device when a component fails or becomes outdated, individual components could potentially be replaced.

---

## Product Concepts

After sorting and ranking the features, we created three separate product concepts. Each concept uses a different combination of the brainstormed features so that the concepts have distinct priorities while still addressing the main needs of the user.

### Product Concept 1: Clinical Monitoring Focus
The first concept focuses primarily on accurate and reliable heart rate measurements. It would prioritize the features necessary for collecting high quality data and reducing inaccuracies.

##### Primary Features
1. PPG optical heart rate sensor
2. Dual wavelength LED system
3. Analog front end filtering
4. High resolution ADC sampling
5. Motion artifact reduction algorithm
6. Ergonomic curved sensor housing
7. Bluetooth Low Energy
8. CSV and JSON data export
9. Simple app dashboard

This concept would be designed around users who place a high priority on having detailed and reliable heart rate information that can be reviewed through the application or exported for further analysis.

---

### Product Concept 2: Everyday Comfort and Simplicity
The second concept focuses primarily on making the device comfortable and easy to use throughout the day. Rather than emphasizing advanced features, this concept combines the features that make the device simple, comfortable, and convenient.

##### Primary Features
1. Hypoallergenic silicone strap
2. Ventilated strap pattern
3. Lightweight polymer enclosure
4. Soft backplate cushioning
5. Single multifunction button
6. LED status indicator
7. Haptic vibration alerts
8. Auto start measurement mode
9. Simple app dashboard
10. Bluetooth Low Energy

This concept would be designed for users who want continuous heart rate monitoring without having to constantly interact with or adjust the device.

---

### Product Concept 3: Affordable Modular Design
The third concept focuses primarily on affordability, maintainability, and long term value. It combines the cost reduction features with enough monitoring and connectivity features to maintain the core functionality of the product.

##### Primary Features
1. Off the shelf PPG sensor
2. Simplified PCB layout
3. Open source firmware libraries
4. Modular internal design
5. Efficient component sourcing
6. Lightweight polymer enclosure
7. Bluetooth Low Energy
8. Automatic pairing mode
9. Real time BPM streaming
10. Firmware updates over BLE

This concept would focus on providing the core functionality of the product while keeping manufacturing costs lower and making the device easier to maintain or upgrade over time.

---

### Features Kept for Future Inspiration
Features that were not selected for a particular product concept were not discarded. We kept the remaining ideas separate so that they could be reused if we modify one of the concepts later. This allows us to continue developing the designs without losing any of the ideas generated during the original brainstorming session.

Overall, the three concepts represent different combinations of the same original brainstorm. The first concept emphasizes **measurement accuracy and data quality**, the second emphasizes **comfort and ease of use**, and the third emphasizes **affordability and maintainability**. This allowed us to create three distinct designs while preserving the original ideas for future development. 

---

## Step Four
![](<image/HRT 1.png>)
![](<image/HRT 2.png>)
![](<image/HRT 3.png>)
**The chosen design is the 3rd design. The rounded design will allow for it to be easily found and modular will little heartful edges. Keeping it simple while maintaining the needed room for all team member contributions.**

---

## Step Five 
Our team used a brainstorming method called rapid ideation to generate as many ideas and concepts as possible within a short period of time. We began by writing down as many random words and ideas as we could on the whiteboards in the library within a five-minute period. The purpose of this initial stage was not to evaluate the quality of each idea, but to generate a large number of concepts for later evaluation. For example, we may have initially written a word such as “shoe,” which we eventually removed because it was not directly relevant to our project, while concepts such as “sweat” and “comfort” were retained because they were more applicable to our heart rate monitor design.

Our entire team participated in the brainstorming session. We met at the library on Friday, September 25, after everyone had finished their classes, and reserved a pod for the duration of the assignment. Since the area we used had six whiteboards, we took turns writing on different boards so that we would have enough space to record our ideas. The whiteboards were our primary tool for capturing our ideas, while caffeine helped sustain our energy and the brainstorming process.

After generating a large number of concepts, we began categorizing and evaluating them based on their usefulness and alignment with our project's overall theme. We then considered the functionality and feasibility of each concept. In other words, we asked whether an idea was not only possible to implement but also useful for our intended product. For example, we considered using carbon fiber straps instead of plastic ones for our heart rate monitor. Although carbon fiber could provide a highly durable strap, its cost would significantly increase the product's price. This would conflict with one of the important concepts we had identified, affordability.

After this initial evaluation, we began combining concepts to determine which combinations could yield useful features or design ideas. This process eventually evolved into a bubble map, which made it easier for us to visualize how different concepts could work together and to rank the resulting ideas. An unexpected challenge we encountered was that combining two ideas that were individually considered poor could sometimes result in a concept that was better than the combination of two ideas that were individually considered good. For example, we considered the ideas of a disposable wristband and a removable heart rate sensor. Individually, neither idea seemed particularly useful because a disposable wristband could increase waste, while a removable sensor could make the product less convenient. However, when combined, the concept could allow the sensor to be reused while the inexpensive wristband could be replaced when it became sweaty or uncomfortable. This created a potential solution that addressed both hygiene and comfort. This demonstrated that we needed to remain open-minded about ideas rather than immediately eliminating concepts based solely on their individual rankings.

The requirements we used during our brainstorming session primarily came from our User Needs and Benchmarking assignment. Through that assignment, we had already developed a better understanding of how heart rate monitors function and had identified components and features commonly shared across existing products on the market. For example, many heart rate monitors worn on the arm use green light to obtain readings from the blood. This existing information provided a foundation for generating additional ideas and potential improvements.

When grouping features, we initially considered each feature individually and then combined it with other features, even when the combination did not immediately appear logical. We did this to explore as many possibilities as possible before narrowing down our concepts. We then established several definite needs for our product, including affordability, comfort, reliability, and appearance. Each idea was ranked against these criteria on a scale of 1 to 5. For example, the carbon fiber strap received a score of 2 for affordability, 2 for comfort, 5 for reliability, and 5 for appearance. This allowed us to compare ideas more objectively and identify which concepts best aligned with our product's requirements and goals.

Because we were still in the early stages of developing our heart rate monitor, the team did not reach a complete agreement on which direction the final product should take. However, we agreed that our opinions may change as we gain more information about heart rate monitors and continue developing our engineering skills. For this reason, we decided to keep our ideas open to further evaluation rather than immediately committing to one final concept.