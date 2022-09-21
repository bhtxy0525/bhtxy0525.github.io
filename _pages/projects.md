---
layout: archive
title: "My projects"
permalink: /projects/
author_profile: true
---
---
# <font color="#1E90FF">7-DOF Modular Anthropomorphic Manipulator</font><br />
## **1. Structure & Hardware Design**
- Design of three size robotic modular joint with embeded joint torque sensor;
- Design of 7-DOF anthropomorphic manipulator;
- Design of electromechanical coupling quick changer.

<table>
  <caption> Actuator specifications </caption>
  <tr>
    <th>type</th>
    <th>Small</th>
    <th>Medium</th>
    <th>Large</th>
  </tr>
  <tr>
    <td>Size</td>
    <td>φ96mm×110mm</td>
    <td>φ107mm×140mm</td>
    <td>φ107mm×140mm</td>
  </tr>
  <tr>
    <td>Mass</td>
    <td>1.12kg</td>
    <td>1.75kg</td>
    <td>2.35kg</td>
  </tr>
  <tr>
    <td>Rated torque</td>
    <td>27Nm</td>
    <td>75Nm</td>
    <td>150Nm</td>
  </tr>
  <tr>
    <td>Rated speed</td>
    <td>4.7rad/s</td>
    <td>2.21rad/s</td>
    <td>1.83rad/s</td>
  </tr>
  <tr>
    <td>Communication</td>
    <td>EtherCAT</td>
    <td>EtherCAT</td>
    <td>EtherCAT</td>
  </tr>
  <tr>
    <td>Break</td>
    <td>None</td>
    <td>None</td>
    <td>None</td>
  </tr>
</table>

<table>
  <caption> Joint torque sensor specifications </caption>
  <tr>
    <th>Properties</th>
    <th>Small</th>
    <th>Medium</th>
    <th>Large</th>
  </tr>
  <tr>
    <td>Size</td>
    <td>φ60mm×H9mm</td>
    <td>φ70mm×H10mm</td>
    <td>φ80mm×H11mm</td>
  </tr>
  <tr>
    <td>Mass</td>
    <td>36.0g</td>
    <td>56.7kg</td>
    <td>80.2kg</td>
  </tr>
  <tr>
    <td>Rated torque</td>
    <td>35Nm</td>
    <td>90Nm</td>
    <td>200Nm</td>
  </tr>
  <tr>
    <td>Resolution</td>
    <td>0.02Nm</td>
    <td>0.1Nm</td>
    <td>0.3Nm</td>
  </tr>
  <tr>
    <td>Frequency</td>
    <td>2K Hz</td>
    <td>2K Hz</td>
    <td>2K Hz</td>
  </tr>
</table>

<table>
<caption>7-DOF manipulator</caption>
  <tr>
    <th>Properties</th>
    <th>Ours</th>
  </tr>
  <tr>
    <td>Rated torque</td>
    <td>5kg</td>
  </tr>
  <tr>
    <td>Mass</td>
    <td>15.7kg</td>
  </tr>
  <tr>
    <td>DOF</td>
    <td>7</td>
  </tr>
  <tr>
    <td>Reach</td>
    <td>850mm</td>
  </tr>
  <tr>
    <td>communication</td>
    <td>EtherCAT</td>
  </tr>
</table>

<center>
<img src="../images/robot.jpg" width="70%" height="70%" />
<center>7-DOF manipulator prototype</center>
</center>

## **2. Kinematics & Dynamics Modeling and Simulation**
- Arm configuration, forward kinematics, workspace(Reachable & Dexterous) and manipulability analysis;
- Analytical inverse kinematics solution with arm manifold, free-singularity and joint limits avoidance for 7-DOF manipulator;
- Dynamics modeing and simulation of 7-DOF manipulator.
<center>
<img src="../images/kinematics.jpg" width="70%" height="70%" />
<center>Dexterous hand prototype</center>
</center>

## **3. Flexible Joint Modeling, Parameter Identification, and Compliance Control**
- Flexible joint modeing;
- Motor-torque coefficient identification, friction identification, stiffness and damping identification;
- Full-state feedback control.
<center>
<img src="../images/Fjoint.jpg" width="50%" height="50%" />
<center>Flexible joint modeling</center>
</center>
<center>
<img src="../images/software.png" width="50%" height="50%" />
<center>Identification software</center>
</center>

## **4. 7-DOF Manipulator Compliance Control**
- Joint space impedance control;
- Cartesian space impedance control;
- Nullspace impedance control.

## **5. Related Media** 
- [Joint torque sensor](https://youtu.be/-RE1b1pkxbM)
- [Robotic modular joint](https://youtu.be/8-BTJ6ExhIA)
- [7-DOF manipulator](https://youtu.be/ncxNLygdOeQ)

---

# <font color="#1E90FF">Dexterous Hand Design and Compliance Control</font><br />
## **Main work:**
- Proposed a simplified configuration to imitate the daily human hand grasps;
- Dexterous hand design, including modular finger design, thumb design, palm design, and layout optimization;
- Developed a hand prototype, and the dexterity of the prototype was verified by Cutkosky classification test.
<center>
<img src="../images/hand.jpg" width="70%" height="70%" />
<center>Dexterous hand prototype</center>
</center>

## **Related Media**
- [Cutkosky test of dexterous](https://www.youtube.com/watch?v=M8hLrL9GSCc&ab_channel=%E7%94%B0%E6%96%B0%E6%89%AC)

# <font color="#1E90FF">Self-Reconfigurable Modular Robot</font><br />
## **Main work:**
- Responsible for the 3-DOF self-reconfigurable robot design, including modular joint design (structure), connector design (structure & hardware circuit);
- Proposed an electromechanical interface for power & communication transmission and orientation detection;
- Developed a human-interaction software 3-DOF self-reconfigurable robot based on Qt Creator, and a series of experiments of the prototype were carried out.
<center>
<img src="../images/MSR.jpg" width="70%" height="70%" />
<center>3-DOF modular self-reconfigurable robot</center>
</center>
