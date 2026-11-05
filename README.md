# 🤖 JARVIS Mini

A 10cm AI robot. Fully autonomous.

This project aims to create a small, expressive robot which can move around my desk, communicate with me, recognise its environment, respond to touch, play games and eventually charge itself.

I wanted to make this robot feel more like a companion rather than just another piece of tech.

The challenge was making all of these features fit onto a 10cm robot.

Status: 🟡 Research and CAD

Program: Hack Club Forge

## 🎯 Objectives

JARVIS Mini will be designed to do the following:

- Move around using 2 legs, turn and make expressive movements.

- Chat using an LLM, using voice to text and text to speech.

- Facial expression with animated eyes.

- Computer vision using a camera.

- Respond to touch/petting on the head.

- Avoid obstacles and detect edges of desk.

- Personality & memory, remembering interactions and responding differently based on context.

- Play small games, dance and interact with user.

- Automatically wake up and approach user safely.

- Charge itself by navigating to a bespoke charging station.

All these features are planned and are not yet implemented.

## 🧠 Hardware

I will be using a Raspberry Pi as the main computer.

This will be used to control the screen, sensors and movement, sound and connection to the external LLM.

### Components

| Component | Description |

|---------|-------------|

| Raspberry Pi Zero 2 W | Main computer |

| Small IPS Screen | For animated eyes |

| Raspberry Pi Camera | For computer vision |

| Micro Servos | For movement |

| PWM Servo Driver | To control motors |

| Microphone | For voice |

| Speaker & Amplifier | For speech and sounds |

| ToF Distance Sensor | To detect obstacles |

| Sensors facing down | To detect edges of desk |

| IMU | To detect orientation and movement |

| Capacitive Touch Sensor | To detect touch |

| Rechargeable Battery | To power robot |

| Battery Charging Circuitry | To safely charge battery |

| 3D Printed casing | For robot |

| Charging pins & Station | For automated charging |

The specific models, quantity and specs will be decided once we have checked the size and electrical compatibility.

## 📐 Design

One of the largest issues is making a moving robot so small.

The initial design aims to be:

| Parameter | Target |

|---------|--------|

| Height | ~100mm |

| Width | ~70-80mm |

| Depth | ~60-85mm |

| Movement | 2 Legs |

| Casing | 3D printed bespoke |

| Colour | White base, Black face, Cyan eyes |

The robot must look good but also work well.

I am looking into where to place the servos, mountings, internal space, movement mechanisms, weight and electronics.

The casing needs to be easy to access for repairs and improvements.

## 💻 Software

This robot will be mainly coded in Python.

The software will include:

- Control Raspberry Pi hardware.

- Facial animation.

- Control servos and movement.

- Computer Vision using camera.

- Voice recognition.

- Text to speech.

- Connect to LLM via Wi-Fi.

- Basic memory for chatting.

- Monitor sensors.

- Battery management.

- Automatic docking.

The LLM will be connected via an external service as the Raspberry Pi Zero 2 W is not suitable for running a large chatbot.

## 🔧 Progress

### Phase 1: Hardware Research

I have started researching the components required for this robot.

Looking into the sizes of components, researching the best hardware options, checking the hole positions for mounting and taking measurements for CAD.

This will help me know how much usable space there will be.

### Phase 2: CAD

I have imported a basic AI generated STEP file into Onshape to get an idea of how the robot will look, the size and how everything will fit together.

This is just a reference design at the moment.

Next step will be to improve the design to fit around the component sizes and create realistic mountings and movement.

### Phase 3: Electronics & Coding

Not started.

### Phase 4: Physical Build

Not started. No hardware built and tested.

## 🧪 Challenges

Challenges to overcome include:

1. Fitting all the components in (Raspberry Pi, Screen, Camera, Battery, Speaker & Sensors).

2. Stable 2 legged movement.

3. Good torque motors.

4. Weight distribution to avoid tipping.

5. Battery and Servo Current.

6. Charging station.

7. Realistic facial animations/movements.

As I learn more the design will be updated.

## 📋 To Do List

[ ] Initial robot design defined.

[ ] Start researching component sizes.

[ ] Imported initial CAD reference into Onshape.

[ ] Decide on components.

[ ] Create BOM linked to suppliers.

[ ] Improved CAD design.

[ ] Design movement.

[ ] Plan wiring.

[ ] Get components.

[ ] Build initial hardware.

[ ] Code robot.

[ ] Test robot.

## 🤖 AI Use

I have used ChatGPT to help with initial ideas for features, researching components, understanding engineering concepts, creating initial designs and a STEP reference.

This design has been used as inspiration.

I will make clear what parts were created by AI and what parts were my changes to the CAD, engineering choices, experimenting and physical work.

I want to learn about robotics, electronics, mechanical engineering and embedded coding.

## 📓 Logs




## IMAGES

<img width="1359" height="750" alt="image" src="https://github.com/user-attachments/assets/82d19fe9-9efc-463a-b19a-bcddcfd43cdc" />
<img width="1055" height="567" alt="image" src="https://github.com/user-attachments/assets/3115b7cf-c348-4346-8fc7-757df98c4b6c" />



I have kept logs of my progress, challenges and the time spent using Hack Club Forge.

I will include images of CAD, component research, photos of the physical build and results from testing.
