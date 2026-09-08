# Flying Vehicle Testing Platform

## Overview

The **Flying Vehicle Testing Platform** is a mechanically constrained experimental setup developed to study the dynamics and rotational behavior of a four-propeller flying vehicle under controlled laboratory conditions.

The project was initiated as a **gimbal-based test rig** to provide a safer and more controlled alternative to repeated free-flight testing during the early stages of flying-vehicle development.

The platform restricts translational motion while allowing controlled rotational motion of the flying vehicle, enabling the study of its response under different operating conditions.

---

## Motivation

Flying vehicles exhibit highly coupled translational and rotational dynamics. Small changes in thrust, mass distribution, or external disturbances can significantly affect their stability and motion.

Testing an unstable flying vehicle directly in free flight can also result in hardware damage and unsafe operating conditions.

The objective of the test platform is therefore to provide an intermediate experimental setup between **theoretical modelling, simulation, and free-flight testing**.

---

## Project Objectives

* Design and develop a mechanically constrained test setup for flying vehicles.
* Provide controlled rotational motion for studying vehicle dynamics.
* Restrict translational motion during testing.
* Develop a stable mechanical structure capable of supporting the flying vehicle.
* Establish suitable mechanical interfaces between the vehicle and test rig.
* Develop a CAD model and assembly of the test platform.
* Enable experimental characterization of propulsion and inertial properties.
* Provide a foundation for future experimental validation of flying-vehicle dynamics.

---

## Mechanical Architecture

The test platform evolved through different design stages during the project.

The initial concept consisted of a **gimbal-based structure** designed in SOLIDWORKS. The setup included:

* Rigid support frame
* Two orthogonal gimbal rings
* Central mounting mechanism
* Cross-shaped support for the flying vehicle
* Mechanical joints for controlled rotational motion

<img width="543" height="485" alt="image" src="https://github.com/user-attachments/assets/00e9459c-37a6-487f-a438-ec6a4bdbfe17" />


The later implemented setup consisted of:

* Rigid base platform
* Lower two-degree-of-freedom joint
* Nylon support rod
* Upper two-degree-of-freedom joint
* Four-propeller flying vehicle mounted at the top


The mechanical arrangement constrains the vehicle's translational motion while permitting rotational motion required for dynamic studies.

---

## Degrees of Freedom

The test setup is designed to study the rotational behavior of the flying vehicle.

The implemented configuration provides:

* **Roll (ϕ)**
* **Pitch (θ)**

The mechanical constraint keeps the vehicle fixed in position while allowing controlled rotational movement.

---

## CAD Design

The mechanical structure was developed using **SOLIDWORKS**.

The CAD development included:

* Overall assembly modelling
* Gimbal mechanism design
* Structural components
* Vehicle mounting arrangement
* Individual component modelling
* Exploded assembly views

### CAD Model

<img width="676" height="621" alt="image" src="https://github.com/user-attachments/assets/d70d988f-7216-4733-ae05-ce24c6338f5c" />



### Exploded Assembly

<img width="536" height="767" alt="image" src="https://github.com/user-attachments/assets/e8e4258a-8c8c-4753-b881-03ca1ef72093" />


---

## System Characterization

Experimental characterization was carried out to obtain physical parameters required for understanding the flying vehicle dynamics.

### Motor–Propeller Characterization

The propulsion system considered an **EMAX MT2213 BLDC motor with EMAX1045 propellers** operating at an 11 V supply.

The available propulsion data was used to study:

* Thrust
* Current consumption
* Power
* Efficiency
* Motor RPM

A thrust–RPM relationship was obtained by fitting a quadratic model to the available data.

---

## Inertial Characterization

The moments of inertia of the flying vehicle were experimentally determined using pendulum-based methods.

### Bifilar Pendulum

The moment of inertia about the **z-axis** was determined using the bifilar pendulum method.

The measured oscillation period was used along with the body mass, suspension-string separation, and string length to estimate the rotational inertia.

The experimentally obtained value was:

**Izz ≈ 0.0246 kg·m²**

### Compound Pendulum

The moments of inertia about the **x- and y-axes** were determined using the compound pendulum method.

The experimentally obtained values were:

**Ixx ≈ 0.01728 kg·m²**

**Iyy ≈ 0.01728 kg·m²**

The approximately equal x- and y-axis values are consistent with the symmetric configuration considered in the project.

---

## Experimental Concept

The overall testing concept was divided into two phases.

### Phase 1 — Static Analysis

The initial phase focused on propulsion and force characterization.

The proposed setup was intended to measure:

* Propeller thrust
* Forces
* Moments
* Motor RPM

These measurements can be used to establish the relationship between propulsion input and generated forces/moments.

### Phase 2 — Dynamic Analysis

The second phase focused on studying the rotational response of the flying vehicle.

The gimbal-based mechanism provides controlled rotational motion while keeping the vehicle mechanically constrained.

This allows the vehicle response to different thrust inputs and external disturbances to be studied without requiring unrestricted free flight.

---

## Design Evolution

The project progressed from an initial gimbal concept toward a mechanically constrained flying-vehicle dynamics platform.

### Initial Concept

The initial design focused on:

* Gimbal-based support
* Controlled rotational motion
* Restriction of translational motion
* Experimental study of forces and moments

### Developed Platform

The later setup incorporated:

* Rigid base
* Mechanical joints
* Nylon support member
* Upper vehicle mounting mechanism
* Four-propeller flying vehicle

This development allowed the mechanical design to be evaluated as a practical experimental platform.

---

## Project Gallery

### Physical Setup

<img width="216" height="356" alt="image" src="https://github.com/user-attachments/assets/c8cbe266-14a3-4d0f-a5a6-2fdc207e4bc3" />
<img width="927" height="233" alt="image" src="https://github.com/user-attachments/assets/4690ec57-7b9e-4145-a2c8-ddc8119d8984" />



### Experimental Characterization

<img width="1400" height="630" alt="image" src="https://github.com/user-attachments/assets/09ebb92a-1b8a-4001-a089-c3d4329ad598" />

---

## Tools & Technologies

* **SOLIDWORKS** — CAD modelling and assembly development
* Mechanical design and fabrication
* Gimbal mechanisms
* Experimental inertial characterization
* Motor–propeller characterization
* Rigid-body dynamics

---

## My Contribution

My contribution to the project focused on the **mechanical and experimental aspects of the flying vehicle testing platform**.

Areas of work included:

* Mechanical design of the test-platform components
* CAD modelling and assembly development
* Development of the vehicle mounting and support arrangement
* Mechanical integration of the test setup
* Design considerations related to rigidity, stability, and constrained motion
* Experimental characterization of system properties

> **Note:** This repository focuses on the mechanical design and experimental characterization work and does not cover the project's controller-development work.

---

## Key Outcomes

The project resulted in a mechanically constrained platform for studying flying-vehicle dynamics under controlled conditions.

The work provided practical experience in:

* Mechanical system design
* CAD modelling
* Gimbal mechanisms
* Structural design
* Mechanical assembly
* Experimental testing
* Inertial characterization
* Propulsion-system characterization
* Flying-vehicle dynamics

---

## Future Development

The platform can be further developed to:

* Support additional rotational degrees of freedom
* Enable full 6-DOF dynamic studies
* Improve modularity for different flying vehicles
* Integrate additional force and motion sensors
* Improve vibration isolation
* Enable more comprehensive experimental validation
* Extend the platform toward free-flight testing

---

## Project Documentation

This repository contains selected CAD models, mechanical drawings, photographs, experimental data, and documentation related to the development of the flying vehicle testing platform.

For additional project details, refer to the project reports included in this repository.
