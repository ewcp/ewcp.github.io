---
layout: page
title: Research Agenda
permalink: /research-agenda/
---

# The EWCP FRC Research Agenda
This document represents EWCP's vision for the achievable scientific and technological advancements to be made within the youth STEM competition community, and especially the FIRST Robotics Competition (FRC) community, within the next five years.

EWCP’s mission is to develop the sustainability of competitive youth STEM teams and strengthen the diversity, robustness, and impact of the youth STEM education community through strategic advocacy, expert consensus-building, and technical leadership.

## Controls
[HMI.01 Gamepad thumbstick axis linearity]({% post_url 2021-03-01-HMI-01 %})
[HMI.02 Isometric joystick initial development]({% post_url 2021-03-01-HMI-02 %})

### UTIL.01
Develop a library for automating pre-match self-tests of common FRC mechanisms, with user-definable pass/fail criteria.

### NAV.01
Develop a standard test path(s) which can be used by the FRC community to compare the performance of robot path-following strategies, along with metrics to quantify the degree to which the test path(s) are followed. The test path(s) should include movements required by typical FRC gameplay.

### NAV.02
Quantify the effects of choice of wheel tread material on the growth rate of odometry error.

### COM.01
Determine optimal placement of FRC networking equipment including the robot radio and the field access point.

### COM.02
Optimal packet sizes and transport protocols to get data reliably and quickly to and from the robot on the field network. Also optimal TCP Window sizing and other information. ZeroMQ compared to NetworkTables compared to ROS2 DDS, among others.

## Electromechanical
### MOT.01
Independently validate the motor performance testing conducted by VEX Robotics and reported at motors.vex.com.

### MOT.02
Quantify the short- and long-term performance effects of using compressed air to cool the internals of common FRC drivetrain motors.

### DSTR.01
Independently develop time-current characteristic curves, spanning the region from 0.1 to 10s, for circuit breakers commonly used in FRC. These circuit breakers should be installed as they would be in a legal FRC robot.

### DSTR.02
Quantify any performance degradation related to exercising FRC circuit breakers.

### CAN.01
For various common techniques of joining CAN bus wires, measure impedance across the connection.

## Pneumatics
### PNEU.01
Build and validate a dynamic simulation of a basic FRC pneumatics system. Quantify the predictive power of the model in response to incremental changes to the system design.

### PNEU.02
Demonstrate a scheme for optimizing the conversion of stored electrical energy to a stored pneumatic energy during FRC match conditions.

### PNEU.03
Measure how the choice of tubing inner diameter impacts the extension/retraction time of pneumatic cylinders in a typical FRC robot.

## Other mechanical
### STRC.01
Quantify the in-plane and out-of-plane strength of common joinery techniques for two rectangular tubes of equal shape, joined perpendicularly.

### WHLS.01
Characterize the static and dynamic friction of common COTS FRC wheels against an HDPE surface with orange-peel texture. Identify any relationship to tread temperature, and any nonlinearity with respect to normal force.

## FRC
### AWD.WFA.01
Compare word frequency in the corpus of winning and non-winning Woodie Flowers Award / Finalist Award submissions.

### AWD.WFA.02
Compare gender diversity in the corpus of winning and non-winning Woodie Flowers Award / Finalist Award Submissions and assess geographic equality. 

### AWD.WFA.03
Compare career diversity in the corpus of winning and non-winning Woodie Flowers Award / Finalist Award Submissions and assess geographic equality. 
(Did you know - no female WFA’s are career engineers? They are all teachers. Compared to the 50/50 split between male career engineers and male teachers). 

### AWD.DL.11
Compare gender diversity in the corpus of Dean’s List Finalists & assess according to geographic area for equality. 

### AWD.DL.12
Compare submission rates (is it possible to get this data?) by region to determine the % of students nominated in a specific region. 
Pull out regional vs District data.

### GDC.001
Computationally predict GDC responses to arbitrary Q&A questions.

## Other areas of research interest
- CAD
- Networking
- 3d printing
