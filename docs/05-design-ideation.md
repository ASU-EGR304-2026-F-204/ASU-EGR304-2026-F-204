---
title: Design Ideation
---

## Step Two: Generating Ideas
| Requirement / need | Feature | Detail |
| :--- | :--- | :--- |
| Accurate and Clinically-Valid Readings | PPG Optical Heart‑Rate Sensor | Measures blood‑volume changes using LED illumination and photodiode detection to generate reliable BPM signals |
| Accurate and Clinically-Valid Readings | Dual‑Wavelength LED System | Uses green and infrared LEDs to improve signal penetration and accuracy across varying skin tones |
| Accurate and Clinically-Valid Readings | Analog Front‑End Filtering | Removes noise and stabilizes the PPG waveform, ensuring cleaner input for BPM calculation |
| Accurate and Clinically-Valid Readings | High‑Resolution ADC Sampling | Converts analog PPG signals into precise digital samples for improved heart‑rate extraction |
| Accurate and Clinically-Valid Readings | Motion Artifact Reduction Algorithm | Filters out movement‑induced distortions to maintain accurate readings during daily activity |
| Comfortable and Skin-Friendly Wearability | Hypoallergenic Silicone Strap | Prevents skin irritation and supports extended daily wear for sensitive users |
| Comfortable and Skin-Friendly Wearability | Ergonomic Curved Sensor Housing | Maintains consistent skin contact, improving PPG signal quality and overall comfort |
| Comfortable and Skin-Friendly Wearability | Ventilated Strap Pattern | Enhances airflow to reduce sweat buildup during exercise or long‑term wear |
| Comfortable and Skin-Friendly Wearability | Lightweight Polymer Enclosure | Reduces wrist fatigue and improves overall wearability throughout the day |
| Comfortable and Skin-Friendly Wearability | Soft Backplate Cushioning | Provides gentle pressure against the skin while maintaining stable optical viewing |
| Seamless App Connectivity and Data Export | Bluetooth Low Energy Module | Enables low‑power wireless communication for continuous heart‑rate syncing with mobile devices |
| Seamless App Connectivity and Data Export | Automatic Pairing Mode | Simplifies device setup by detecting and connecting to the app without manual configuration |
| Seamless App Connectivity and Data Export | Real‑Time BPM Streaming | Sends live heart‑rate data to the app for workouts or health monitoring |
| Seamless App Connectivity and Data Export | CSV/JSON Export Function | Allows users to download heart‑rate logs for medical review or personal analysis |
| Seamless App Connectivity and Data Export | Firmware Updates Over BLE | Provides wireless firmware upgrades to improve performance and add new features |
| Transparent, High-Value Pricing | Off‑the‑Shelf PPG Sensor | Uses widely available components to reduce cost while maintaining reliable performance |
| Transparent, High-Value Pricing | Simplified PCB Layout | Minimizes manufacturing complexity, lowering production cost and improving assembly reliability |
| Transparent, High-Value Pricing | Open‑Source Firmware Libraries | Reduces licensing fees and simplifies long‑term software maintenance |
| Transparent, High-Value Pricing | Modular Internal Design | Allows individual component replacement without requiring full device replacement |
| Transparent, High-Value Pricing | Efficient Component Sourcing | Uses common parts to maintain stable pricing and reduce supply chain delays |
| Ease of Use and Clear Navigation | Single Multi‑Function Button | Provides simple control for power, pairing, and measurement modes with minimal user confusion |
| Ease of Use and Clear Navigation | LED Status Indicator | Displays battery, pairing, and measurement status using intuitive color signals |
| Ease of Use and Clear Navigation | Haptic Vibration Alerts | Confirms user actions and alerts abnormal heart‑rate events without requiring a screen |
| Ease of Use and Clear Navigation | Auto‑Start Measurement Mode | Begins heart‑rate monitoring automatically when worn, reducing user steps |
| Ease of Use and Clear Navigation | Simple App Dashboard | Presents BPM, trends, and alerts clearly for users with limited technical experience |
| Durability and High Manufacturing Quality | IP67 Waterproof Gasket Sealing | Uses silicone O-rings and sealed housing seams to protect internal electronics from sweat, dust, and water ingress |
| Durability and High Manufacturing Quality | Scratch-Resistant Optical Window | Protects the PPG LEDs and photodiode with hardened polycarbonate or Gorilla Glass to prevent signal degradation over time |
| Durability and High Manufacturing Quality | Conformal PCB Coating | Applies a thin protective polymer layer over circuit components to guard against moisture, corrosion, and mechanical vibration |
| Durability and High Manufacturing Quality | Reinforced Stainless Steel Lug Pins | Secures the strap to the enclosure using thickened housing walls and metal spring bars to prevent tearing during vigorous activity |
| Durability and High Manufacturing Quality | Impact-Resistant ABS/PC Enclosure | Absorbs mechanical shock from accidental drops or daily impacts to prevent housing cracks and internal solder joint failure |
| Good Battery Life | Deep-Sleep Microcontroller Mode | Places the main processor into ultra-low-power sleep between heart-rate sampling intervals to minimize idle energy draw |
| Good Battery Life | Duty-Cycled LED Pulsing | Rapidly pulses the optical sensor LEDs at a low duty cycle rather than running continuous illumination to cut power consumption |
| Good Battery Life | High-Density LiPo Battery Cell | Maximizes milliamp-hour capacity within a compact physical footprint to support extended multi-day operation |
| Good Battery Life | Motion-Triggered Auto-Sleep | Uses an onboard accelerometer to power down optical sensing when the device is stationary or removed from the wrist |
| Good Battery Life | Batch BLE Data Transmission | Buffers BPM readings locally in onboard memory and transmits data in periodic bursts rather than keeping the radio continuously active |
| Regulate system power from 9 volts to 5 volts | Synchronous Buck Converter IC | Steps down 9V to 5V with high efficiency using pulse-width modulation to minimize heat dissipation and battery drain |
| Regulate system power from 9 volts to 5 volts | Low-Dropout (LDO) Linear Regulator | Provides a simple, ripple-free 5V output ideal for powering noise-sensitive analog PPG sensor circuitry |
| Regulate system power from 9 volts to 5 volts | Hybrid Buck-LDO Two-Stage Regulator | Steps 9V down to 5.5V via a switching converter followed by a 5V LDO to combine thermal efficiency with low analog noise |
| Regulate system power from 9 volts to 5 volts | Switched-Capacitor Charge Pump | Regulates 9V down to 5V using flying capacitors without inductors, reducing electromagnetic interference and PCB height |
| Regulate system power from 9 volts to 5 volts | Zener Diode Shunt Regulator | Uses a 5.1V Zener diode and series resistor network for basic, low-cost voltage clamping in low-current auxiliary subcircuits |
| Provide over-amperage project to not exceed 1.5 amps | Resettable PTC Polyfuse | Transitions to a high-resistance state to limit current when draw exceeds 1.5A, automatically resetting once the fault clears |
| Provide over-amperage project to not exceed 1.5 amps | Electronic eFuse IC | Actively monitors current via an internal FET and disconnects the load within microseconds if draw surpasses the 1.5A threshold |
| Provide over-amperage project to not exceed 1.5 amps | Fast-Blow Surface-Mount Fuse | Permanently opens the power rail if current exceeds 1.5A to protect downstream components and the user from severe short circuits |
| Provide over-amperage project to not exceed 1.5 amps | Shunt Resistor with Comparator Cutoff | Measures voltage drop across a precision sense resistor and triggers a P-channel MOSFET shutoff when current reaches 1.5A |
| Provide over-amperage project to not exceed 1.5 amps | Foldback Current-Limiting Circuit | Reduces both output voltage and current in the regulator stage when load current hits 1.5A to prevent overheating without full shutdown |

## Step 3: Sort, Rank, and Group

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

#### 2. Ranking and Discussing the Top Ideas

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

#### 3. Generating New Features

After discussing the strongest ideas, we began combining features from different groups to create new features. This allowed us to move beyond the original brainstorm and develop ideas that could provide multiple benefits at the same time.

##### Automatic Monitoring System

We could combine **automatic measurement mode**, **Bluetooth Low Energy**, and **real time BPM streaming** into an automatic monitoring system. When the user puts on the device, it could automatically begin collecting heart rate data and send that information to the mobile application without requiring the user to manually start a measurement.

##### Intelligent Heart Rate Alerts

Another new feature could combine the **motion artifact reduction algorithm** with **haptic vibration alerts**. This could allow the device to analyze the user's heart rate while accounting for movement and provide a vibration alert when a potentially abnormal heart rate is detected.

##### Modular Repair and Upgrade System

We could also combine the **modular internal design** with the **off the shelf PPG sensor** to create a device that is easier to repair or upgrade. Instead of replacing the entire device when a component fails or becomes outdated, individual components could potentially be replaced.

---

### Product Concepts

After sorting and ranking the features, we created three separate product concepts. Each concept uses a different combination of the brainstormed features so that the concepts have distinct priorities while still addressing the main needs of the user.

#### Product Concept 1: Clinical Monitoring Focus

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

#### Product Concept 2: Everyday Comfort and Simplicity

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

#### Product Concept 3: Affordable Modular Design

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

#### Features Kept for Future Inspiration

Features that were not selected for a particular product concept were not discarded. We kept the remaining ideas separate so that they could be reused if we modify one of the concepts later. This allows us to continue developing the designs without losing any of the ideas generated during the original brainstorming session.

Overall, the three concepts represent different combinations of the same original brainstorm. The first concept emphasizes **measurement accuracy and data quality**, the second emphasizes **comfort and ease of use**, and the third emphasizes **affordability and maintainability**. This allowed us to create three distinct designs while preserving the original ideas for future development. 

## Step Four
![](<image/HRT 1.png>)
![](<image/HRT 2.png>)
![](<image/HRT 3.png>)
## Step Five 
Our team used a brainstorming method called rapid ideation to generate as many ideas and concepts as possible within a short period of time. We began by writing down as many random words and ideas as we could on the whiteboards in the library within a five-minute period. The purpose of this initial stage was not to evaluate the quality of each idea, but to generate a large number of concepts for later evaluation. For example, we may have initially written a word such as “shoe,” which we eventually removed because it was not directly relevant to our project, while concepts such as “sweat” and “comfort” were retained because they were more applicable to our heart rate monitor design.

Our entire team participated in the brainstorming session. We met at the library on Friday, September 25, after everyone had finished their classes, and reserved a pod for the duration of the assignment. Since the area we used had six whiteboards, we took turns writing on different boards so that we would have enough space to record our ideas. The whiteboards were our primary tool for capturing our ideas, while caffeine helped sustain our energy and the brainstorming process.

After generating a large number of concepts, we began categorizing and evaluating them based on their usefulness and alignment with our project's overall theme. We then considered the functionality and feasibility of each concept. In other words, we asked whether an idea was not only possible to implement but also useful for our intended product. For example, we considered using carbon fiber straps instead of plastic ones for our heart rate monitor. Although carbon fiber could provide a highly durable strap, its cost would significantly increase the product's price. This would conflict with one of the important concepts we had identified, affordability.

After this initial evaluation, we began combining concepts to determine which combinations could yield useful features or design ideas. This process eventually evolved into a bubble map, which made it easier for us to visualize how different concepts could work together and to rank the resulting ideas. An unexpected challenge we encountered was that combining two ideas that were individually considered poor could sometimes result in a concept that was better than the combination of two ideas that were individually considered good. For example, we considered the ideas of a disposable wristband and a removable heart rate sensor. Individually, neither idea seemed particularly useful because a disposable wristband could increase waste, while a removable sensor could make the product less convenient. However, when combined, the concept could allow the sensor to be reused while the inexpensive wristband could be replaced when it became sweaty or uncomfortable. This created a potential solution that addressed both hygiene and comfort. This demonstrated that we needed to remain open-minded about ideas rather than immediately eliminating concepts based solely on their individual rankings.

The requirements we used during our brainstorming session primarily came from our User Needs and Benchmarking assignment. Through that assignment, we had already developed a better understanding of how heart rate monitors function and had identified components and features commonly shared across existing products on the market. For example, many heart rate monitors worn on the arm use green light to obtain readings from the blood. This existing information provided a foundation for generating additional ideas and potential improvements.

When grouping features, we initially considered each feature individually and then combined it with other features, even when the combination did not immediately appear logical. We did this to explore as many possibilities as possible before narrowing down our concepts. We then established several definite needs for our product, including affordability, comfort, reliability, and appearance. Each idea was ranked against these criteria on a scale of 1 to 5. For example, the carbon fiber strap received a score of 2 for affordability, 2 for comfort, 5 for reliability, and 5 for appearance. This allowed us to compare ideas more objectively and identify which concepts best aligned with our product's requirements and goals.

Because we were still in the early stages of developing our heart rate monitor, the team did not reach a complete agreement on which direction the final product should take. However, we agreed that our opinions may change as we gain more information about heart rate monitors and continue developing our engineering skills. For this reason, we decided to keep our ideas open to further evaluation rather than immediately committing to one final concept.


