---
title: Product Requirements
---

## Project Objective
This project aims to investigate and develop a smart heart-rate monitoring device that is affordable, comfortable, easy to use, and accessible to everyone. The goal is to create a product that provides accurate heart rate tracking while maintaining a simple and user friendly design. Making it suitable for everyday use across a wide range of users, including fitness enthusiasts, professionals, older adults, and individuals who simply want to monitor their health. The device will focus on improving comfort and fit so that it can be worn for extended periods without becoming distracting or uncomfortable. We aim to reduce unnecessary features and complexity while maintaining reliable heart rate monitoring and clear, easy to understand information. By prioritizing affordability, comfort, simplicity, and accurate tracking. Our product will be a directly rival to the Google Fitbit series and Apple Watches that would be to expensive to the everyday customers that require only the basic heart rate monitoring systems.  The target is to maintain global dominance in the heart monitoring market, drive up our sales to 230 million+ units sold with a 40% global market share in 2027 and expand the user base more towards the cheaper, down to earth, barebones devices.

## Stakeholders

* **Target group** Adults aged 18–40 who regularly engage in running, weightlifting, cycling, or general fitness. Their personalities tend to be goal‑oriented, health conscious, and data driven.
* **Target purchaser** Individuals who value convenience and tech‑enabled wellness. Special attention to Single I, Full Nest I, and Full Nest II households, as well as parents balancing work, fitness, and family.
* **Customer service** Fast troubleshooting and intuitive interfaces, easy to repair/replaceable straps and sensors, clear guidance through online support, and eco-friendly materials. 
* **Marketing & Sales division** Looks for unique selling points around precision tracking with real time analytics. Lifestyle messaging around motivation, discipline, and personal growth. Partnerships with gyms, trainers, and fitness influencers. Visual branding with modern data empowered living. 
* **Retailers** Withstand temperature changes, vibration, humidity, and long storage periods. Include clear product information for customer convenience. 

## Use Cases

### User Story #1: Aiden

Aiden is a 27‑year‑old guy who goes to the gym almost every morning before work. He doesn’t care about fancy smartwatch features or paying hundreds of dollars for something he’ll barely use. He just wants to know his heart rate while he’s working out.

When he gets to the gym, he puts on our heart‑rate band. It’s super lightweight and doesn’t feel bulky like an Apple Watch. As soon as he starts jogging, the band shows his heart rate in big, simple numbers. No apps, no menus, no complicated setup. Just the info he needs.

Aiden likes that the band is way cheaper than a Fitbit or Apple Watch but still does the one thing he actually needs: track his heart rate accurately.

### User Story #2: Maria

Maria is a 68‑year‑old retiree who wants to keep an eye on her heart health. She doesn’t like complicated tech and definitely doesn’t want to spend a ton of money on a smartwatch she won’t use.

Every morning she puts on our heart‑rate band before she starts her day. The strap is soft and comfortable, and she forgets she’s even wearing it. As she moves around the house, the band quietly tracks her heart rate and shows it in big, easy‑to‑read numbers.

When she sits down to rest, she taps the band to check her current heart rate. If it’s higher than normal, the band gives her a gentle vibration. She likes that it doesn’t blast loud alarms or send confusing notifications. She also doesn’t need to connect it to a phone or deal with apps, which makes her feel more confident using it.

When she goes on walks with her friends, the band helps her stay at a comfortable pace. She likes that it’s affordable and simple, and she often tells her doctor her heart rate to double check all her vitals are correct. 

## Aspects

The new product design will be based on that of the Google Fitbit Charge with improvements based on the following requirements. The **P1 - P10** is the "code" to indicate the priority of the requirement, from low to high.

1. **Producer Design**
   * 1.1 The product shall be visually easy to distinguish from existing fitness wearables as well as main competitors Google Fitbit series, Apple Watches, Samsung Watches, Generic Medical Watches. (P10)
   * 1.1 The product shall be easy to recognize as a watch without needing instructions. (P10)
   * 1.2 The product shall be easily hidden/slim to blend in with everyday clothing (P7)

1. **Functionality**
      * 2.1 The product shall incorporate one or more optical or pulse sensing  sensors to detect the user and record data. (P10)
      * 2.2 The product shall offer reliable readings and understandable biometrics. (P10)
      * 2.3 The product shall be easily warn (P10)
      * 2.3.1 and not irritate skin or impair movment. (P10)

## Requirement Criteria Specifications

**1.1.1 - Regulate system power from 9 volts to 5 volts**
Uses a voltage regulation module capable of stepping down 9 V to 5 V with
          minimal ripple (<50 mV).
Includes thermal protection to prevent overheating during continuous operation.
Efficiency target: ≥85% to support battery‑powered use cases.
Must maintain ±5% output tolerance under varying load conditions.
  
**1.1.2 - Provide over-amperage project to not exceed 1.5 amps**
Integrates a current‑limiting circuit (resettable fuse, PTC, or dedicated
          current‑limit IC).
Trip threshold set at 1.5 A ± 0.1 A.
Must respond within <10 ms to over‑current events to avoid component damage.
Includes status indication (LED or digital flag) to alert the user of fault
          conditions.
  
## Open Questions

* Can we design a battery system that lasts multiple days while still keeping the device lightweight and comfortable?
* Can we reduce adhesives and instead use clips, screws, or snap‑fit parts to simplify disassembly?
* How can we make the device intuitive for people who don’t use smartphones or wearable tech?
