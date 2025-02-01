---
layout: post
author: Josue Moura
title:  "Ordination - Current carrying capacity - Voltage Drop"
subtitle: "Getting ready for the test!"
date:   2025-02-01 08:48:33 +1100
last_modified_at: 2025-01-03 09:55:07
categories: 3000:2018 Maximum Demand
tags: [australia, NSW, capstone, preparation,Voltage Drop, Current carrying capacity, Ordination]
location: "Sydney - Australia"
permalink: "Ordination-CurrentCarryCapacity-VoltageDrop"
images:
  banner:
    file:         "VD.png"
    alt_text:     ""
    caption:      "Ordination - Current carrying capacity - Voltage Drop"
    title:        "Ordination - Current carrying capacity - Voltage Drop"
---
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
<style>

  .iconImage {
      font-size: 40px; /* Tamanho do ícone */
    }

    /* Sentence container */
    .mxiImgInteraction {
      position: relative;
      display: inline-block;
      cursor: pointer;
    }

    /* Image initially hidden */
    .mxiImgInteraction img {
      display: none;
      position: absolute;
      top: 100%; /* Show below the phrase */
      left: 0;
      width: 400px; /* Show the size */
      border: 1px solid #ccc;
      background: #fff;
      padding: 5px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    /* Display image on mouseover */
    .mxiImgInteraction:hover img {
      display: block;
    }

    /* Media query for small screens (mobile and tablet) */
@media (max-width: 768px) {
  .mxiImgInteraction img {
    position: fixed; /* Fix the position relative to the viewport */
    top: 50%; /* Center vertically */
    left: 50%; /* Center horizontally */
    transform: translate(-50%, -50%); /* Adjust position */
    width: 90%; /* Adjust size to fit smaller screens */
    max-width: 400px; /* Prevent the image from being too large */
    z-index: 1000; /* Ensure it appears on top of other elements */
  }
}


.circle {
    display: inline-block;
    padding: 10px;
    border: 2px solid red;
    border-radius: 50%;
    text-align: center;
    white-space: nowrap;
    color: red;
    position: relative;
  }

  .circle:hover::after {
    content: '≤ 63A one hour \A >63A two hours'; 
    white-space: pre;
    position: absolute;
    bottom: 150%;
    left: 50%;
    transform: translateX(-50%);
    background-color: black;
    color: white; 
    padding: 5px;
    border-radius: 5px;
    font-size: 12px;
    opacity: 0;
    transition: opacity 0.3s ease;
    opacity: 1;
  }

  .circle:hover::before {
    content: '';
    position: absolute;
    bottom: 120%;
    left: 50%;
    transform: translateX(-50%);
    border-width: 5px;
    border-style: solid;
    border-color: black transparent transparent transparent;
    opacity: 1; 
  }

  /* CB */
  .circleCB {
    display: inline-block;
    padding: 10px;
    border: 2px solid blue;
    border-radius: 50%;
    text-align: center;
    white-space: nowrap;
    color: red;
    position: relative;
  }

  .circleCB:hover::after {
    content: url('assets/images/capstone/Co-o_CCC_VD/form.png'); 
    white-space: pre;
    position: absolute;
    bottom: 150%;
    left: 50%;
    transform: translateX(-50%);
    color: white; 
    padding: 5px;
    border-radius: 5px;
    font-size: 12px;
    opacity: 0;
    transition: opacity 0.3s ease;
    opacity: 1;
  }

  @media (max-width: 768px) {
    .circleCB:hover::after {
        position: fixed; 
        top: 50%; 
        left: 50%;
        transform: translate(-50%, -50%); 
        width: 90%;
        max-width: 400px; 
        z-index: 1000; 
    }
}

  .circleCB:hover::before {
    content: '';
    position: absolute;
    bottom: 120%;
    left: 50%;
    transform: translateX(-50%);
    border-width: 5px;
    border-style: solid;
    border-color: black transparent transparent transparent;
    opacity: 1; 
  }

  /* Fuse */
  .circleFuse {
    display: inline-block;
    padding: 10px;
    border: 2px solid blue;
    border-radius: 50%;
    text-align: center;
    white-space: nowrap;
    color: red;
    position: relative;
  }

  .circleFuse:hover::after {
    content: url('assets/images/capstone/Co-o_CCC_VD/form2.png'); 
    white-space: pre;
    position: absolute;
    bottom: 150%;
    left: 50%;
    transform: translateX(-50%);
    color: white; 
    padding: 5px;
    border-radius: 5px;
    font-size: 12px;
    opacity: 0;
    transition: opacity 0.3s ease;
    opacity: 1;
  }

  @media (max-width: 768px) {
    .circleFuse:hover::after {
        position: fixed; 
        top: 50%; 
        left: 50%;
        transform: translate(-50%, -50%); 
        width: 90%;
        max-width: 400px; 
        z-index: 1000; 
    }
  }

  .circleFuse:hover::before {
    content: '';
    position: absolute;
    bottom: 120%;
    left: 50%;
    transform: translateX(-50%);
    border-width: 5px;
    border-style: solid;
    border-color: black transparent transparent transparent;
    opacity: 1; 
  }

  /* Table 1 */
  .circleT1 {
      display: inline-block;
      padding: 10px;
      border: 2px solid blue;
      border-radius: 50%;
      text-align: center;
      white-space: nowrap;
      color: red;
      position: relative;
      cursor: pointer;
    }

    .circleT1:hover::after {
      content: '';
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 90%; 
      max-width: 400px; 
      aspect-ratio: 1 / 1; 
      background-image: url('assets/images/capstone/Co-o_CCC_VD/t1.png'); 
      background-size: contain; 
      background-repeat: no-repeat; 
      background-position: center; 
      z-index: 1000;
      opacity: 1;
      transition: opacity 0.3s ease;
      pointer-events: none;
    }

    .circleT1:hover::before {
      content: '';
      position: fixed; 
      top: 50%; 
      left: 50%;
      transform: translate(-50%, -50%);
      border-width: 10px;
      border-style: solid;
      border-color: black transparent transparent transparent;
      opacity: 1; 
      z-index: 1001; 
      pointer-events: none;
    }

    @media (max-width: 768px) {
      .circleT1:hover::after {
        width: 80%; 
        max-width: 300px; 
        aspect-ratio: 1 / 1; 
        background-size: contain;
        background-position: center;
      }

      .circleT1:hover::before {
        position: fixed; 
        top: 50%; 
        left: 50%;
        transform: translate(-50%, -50%);
        border-width: 10px;
        border-style: solid;
        border-color: black transparent transparent transparent;
        opacity: 1; 
        z-index: 1001; 
      }
    }

/* temp */

    .typing {
      font-size: 24px;
      font-weight: bold;
      color: #333;
    }

    .dots::after {
      content: "";
      display: inline-block;
      animation: dots 1.5s steps(4, end) infinite;
    }

    @keyframes dots {
      0% {
        content: "";
      }
      25% {
        content: ".";
      }
      50% {
        content: "..";
      }
      75% {
        content: "...";
      }
      100% {
        content: "";
      }
    }
/* temp */
  </style>

<h2>Co-ordination</h2>

Co-ordination: what does it mean?

Co-ordination means ensuring that the operating characteristics of a protective device (such as a circuit breaker or fuse) are correctly adjusted in relation to the electrical conductor, so as to protect it against possible overloads. In other words, it is the alignment of the load, maximum demand, protected device and the current carry capacity to ensure that the system operates safely, meeting the conditions specified in AS/NZS3000, clause 2.5.3.1.


A practical example of the importance of coordination in a residential installation is the overload protection of the kitchen socket circuit. Let's assume that this circuit is designed to support a maximum current of 20 A, with a cable sized for this capacity. The circuit breaker protecting this circuit must also be set to trip when the current exceeds this limit.

Why is it important?

If the circuit breaker is incorrectly sized, for example, set to 25 A, it may not trip in the event of an overload. This means that if too many appliances, such as a microwave, coffee maker, toaster etc, are turned on at the same time, the current in the circuit may exceed the 20 A supported by the cable. In this case, the cable may overheat, damage its insulation and, in the worst case scenario, cause a fire.

Risks of lack of coordination:

- <b>Overheating of cables</b>: Can damage insulation and expose conductors, increasing the risk of short circuits and electric shocks.

- <b>Fires</b>: Undetected overloads can lead to prolonged overheating and eventually flames.

- <b>Faults in electrical devices</b>: Equipment connected to the circuit can be damaged by high current.

- <b>Reduced service life of the installation</b>: Without adequate protection, wiring and devices are subject to premature wear.

Therefore, ensuring coordination between the protection devices and the conductors is essential for the electrical safety of the installation, preventing damage to the system, connected equipment and, most importantly, protecting the integrity of residents.

The operating characteristics of a device protecting a conductor against overload shall satisfy the following two conditions: 

. <b>2.1</b>   IB ≤ IN ≤ IZ  
. <b>2.2</b>   I2 1.45 x IZ 

-  <b>IB</b> = the current for which the circuit is designed, e.g. maximum demand. <span class="mxiImgInteraction"><i class="fas fa-solid fa-image iconExclamation" aria-hidden="true"></i><img src="assets/images/capstone/Co-o_CCC_VD/vdimg.png" alt="Imagem de exemplo"></span>  
-  <b>IN</b> = the nominal current of the protective device. <span class="mxiImgInteraction"><i class="fas fa-solid fa-image iconExclamation" aria-hidden="true"></i><img src="assets/images/capstone/Co-o_CCC_VD/pDevices.jpg" alt="Imagem de exemplo"></span>  
-  <b>Z</b> = the continuous current-carrying capacity of the conductor
<span class="mxiImgInteraction"><i class="fas fa-solid fa-image iconExclamation" aria-hidden="true"></i><img src="assets/images/capstone/Co-o_CCC_VD/cable.jpg" alt="Imagem de exemplo"></span>  
-  <b>I2</b> = the current ensuring effective operation of the protective device and may be taken as equal to either—  

<b>(a)</b> the operating current in <span class="circle"><b> conventional time</b></span> for <span class="circleCB">circuit- breakers</span> (1.45 IN) = ; or  
<b>(b)</b> the fusing current in conventional time for <span class="circleFuse">fuses</span> (1.6 IN for fuses in accordance with the IEC 60269 series).

Below are the clauses that address this issue:

2.5.3 Protection against overload current  
2.5.3.1 Coordination between conductors and protective devices 

**Current carrying capacity**

Current Carrying Capacity refers to the maximum current that an electrical conductor (such as a cable or wire) can carry continuously without its temperature exceeding the safe limits specified by the conductor material and its insulation.

In simple terms, it is the safe limit of current that the cable can carry without overheating or causing damage to the electrical installation.

<span class="circleT1">Table 1</span> of AS/NZS 3008.1.1 is typically used for most calculations, provided the cable operates within the maximum allowable temperature limits.

For thermoplastic or XLPE cable first determine the installation method from tables

- 3(1) unenclosed in air
  - Refers to cables installed on supports or suspended in the air, without ventilation restrictions.
  - Generally allows greater heat dissipation, resulting in greater current capacity.
- 3(2) enclosed
  - Refers to cables installed in ducts, conduits or enclosed spaces.
  - Reduced ventilation may limit heat dissipation, reducing current capacity
- 3(3) buried direct in ground
  - Cables installed directly in the ground, usually in a bed of sand or similar.
  - Current capacity depends on the thermal conditions of the ground.
- 3(4) buried in enclosure
  - Cables installed in ducts or enclosures buried in the ground.
  - May limit heat dissipation compared to direct installation in the ground.

On the table, the columns are organized by

1. Item number  
2. Cable details (two or three core)  
3. Reference drawing  
4. Current-carrying capacity table reference  
5. Methods of installation for cables deemed to have the same current-carrying capacity  
6. Derating table  


Below is an example of selecting the appropriate 4-core + E unarmored V75 Circular Cu cable, with insulation installed using the method "clipped directly to a vertical surface and open to air," protected by a circuit breaker (CB), for a sub-main circuit designed to handle a maximum demand of 172A.

Circuit breaker: 200A  

1. The cable will be opened to air, so <b> table  3(1)</b>.  
2. Check column 5 for the description that applies for it, <b> item 13</b>.    
    - <b>Cables installed — (a) clipped direct to a wall, floor, ceiling or similar surface;</b>
3. Double check on colun 2 if it is three core  
4. Confirm in column 4 which table and column should be checked to find the CCC value, <b> Tables 13 and columns 5.  
5. The selection of the cable should be based on the current carry capacity of the cable, so that means for the protection of a device selected as 200A the cable needs to satisfy the form IN ≤ IZ, in this case the cable selected is 95mm, once it is capable to carry 213A (200 is ≤ 213).  

A sub-main cable
Maximum demand: 172A
4 core + E unarmored V75 Circular Cu
Insulation methond clipped directly to a vertical surface open to air protected by CB


Answer:

cb 200A
Table select 13(1) -> Item 13 -> Selected table 13 Columns 5
The selection of the cable should be based on the current carry capacity of the cable, so that means for the protection of a device selected as 200A the cable needs to satisfy the form IN ≤ IZ, in this case the cable selected is 95mm, once it is capable to carry 213A (200 is ≤ 213).

<h2>Voltage drop</h2>

<h2>Voltage drop</h2>

On the book AUSNZS 3000, clause 3.6.2 says:

"The cross-sectional area of every current-carrying conductor shall be such that the voltage drop between the point of supply for the low voltage electrical installation and any point in that electrical installation does not exceed 5% of the nominal voltage at the point of supply."

Electrical equipment is designed to operate within a specific voltage range (e.g. 220-250 V AC). An excessive voltage drop in a circuit can reduce the voltage available to the load, causing the equipment to operate outside its optimal range. This can result in malfunction, reduced efficiency, overload or even permanent damage to the device, compromising its useful life and the safety of the electrical installation.

Therefore, VD is a fundamental concept for electrical installations to ensure the correct functioning of the network and:

1. Equipment Performance  
When the voltage at the terminals of a piece of equipment is lower than specified (due to voltage drop), performance may be impaired.  
  - Electric motors: may lose efficiency, generate less torque or overheat.  
  - Light bulbs: may illuminate with less intensity.  
  - Electronic equipment: may fail or operate improperly.  

2. Energy Saving  
Excessive voltage drop results in energy losses in the cables (in the form of heat). This increases the total energy consumption and reduces the efficiency of the system.

3. Safety  
A high voltage drop can lead to overheating of conductors, especially in undersized installations, increasing the risk of:  
  - Electrical fires.  
  - Damage to cable insulation.  

4. Standards Compliance
Electrical standards (such as AS/NZS 3000 in Australia) set limits on voltage drop, typically around 5% of nominal voltage for low voltage installations.
  - This ensures that the voltage at the most distant points of an installation is sufficient for the proper operation of equipment.  

5. Conductor Sizing
The calculation of voltage drop directly influences the choice of conductor gauge (cross-section).
  - Thicker cables have lower resistance and, therefore, less voltage drop.
  - Correct sizing avoids unnecessary expenses with oversized conductors and ensures economic and technical efficiency.

6. Long Distances
In long circuits, voltage drop is even more relevant because the cable resistance increases proportionally to the length. It is essential to correctly size the cables to avoid problems.

**Calculating Voltage Drop**

The mV/A.m value represents the number of millivolts dropped when a current of one ampere flows in a one metre length of cable. The following equation can be used to determine the voltage drop in a given circuit:

<img src="assets/images/capstone/Co-o_CCC_VD/voltageDropCalc.png" alt="Voltage Drop calculation" />


Where:

Vd  =  voltage drop in volts (V)

Vc  =  three phase millivolts per ampere-metre (mV/A.m)<b>*</b>

L  =  route length of the circuit conductors in metres (m)

I  =  total load current/maximum demand of the circuit in amperes (A)<b>**</b>


<b>* </b>To determine voltage drop in a single phase circuit, the three phase values of Vc must be multiplied by a factor of 1.155.

<b>** </b>AS/NZS 3000:2018 Clause 3.6.2 Exception 1 states that half of the circuit protection device nominal current rating may be used for calculating voltage drop on circuits where the load is distributed across the length of the circuit, such as with socket outlets and lighting circuits.


**Example**

A 400 V three phase final subcircuit has a maximum demand of 28 A, a route length of 46 m, and is supplied by a 4 mm2 multicore V-90 TPS Cu cable. Determine the voltage drop in the final subcircuit.

The first step is to find the value of Vc from the applicable table in AS/NZS 3008.1.1:2017. In this case, Table 42 is selected based on the type of cable, and Column 6 is selected based on the conductor operating temperature of 75⁰C.

The value of Vc for a 4 mm2 cable operating at 75⁰C is 9.71 mV/A.m.

![Calculation for voltage drop]({{site.image_path}}/capstone/Co-o_CCC_VD/VDCalc.png)

How can you select the right cable to minimize excessive voltage drop?

To determine the minimum cable size needed to meet a specified permissible voltage drop, the following rearrangement of the equation can be applied:

![Calculation for the permissible voltage drop]({{site.image_path}}/capstone/Co-o_CCC_VD/PVD.png)

Where:

Vc  =  maximum permissible value of millivolts per ampere-metre (mV/A.m)

Vd  =  maximum permissible voltage drop in volts (V)

L  =  route length of the circuit conductors in metres (m)

I  =  total load current/maximum demand of the circuit in amperes (A)

The calculated mV/A.m value can then be used to reference the minimum cable size from the relevant table in AS/NZS 3008.1.1:2017.

**Example**

**Select Cables to Satisfy Voltage Drop Limitations**

Determine the minimum size cable for a 230 V final subcircuit based on current carrying capacity and voltage drop requirements. The final subcircuit has a maximum demand of 20 A, a route length of 24 m and is to be wired using twin and earth V-90 TPS cable tied to a perforated cable tray with minimum spacing.

The first step is to determine the maximum permitted voltage drop in the final subcircuit.

![Calculation for the permissible voltage drop]({{site.image_path}}/capstone/Co-o_CCC_VD/first.png)

The maximum voltage drop permitted in the cable is 2.83 V. The next step is to determine the minimum cable size based on current carrying capacity requirements. In this case, AS/NZS 3008.1.1:2017 Table 10, Column 2 is used based on the cable and installation method. The minimum cable size based on current carrying capacity is 2.5 mm2, which has a current carrying capacity of 27 A.

The next step is to determine the minimum cable size based on voltage drop limitations. This is done by determining the maximum permitted Vc for the cable.

![Calculation for the permissible voltage drop]({{site.image_path}}/capstone/Co-o_CCC_VD/second.png)

This is a single phase value of Vc and must be converted to a three phase value, as we will be referencing three phase values in AS/NZS 3008.1.1:2017.

![Calculation for the permissible voltage drop]({{site.image_path}}/capstone/Co-o_CCC_VD/third.png)

Finally, we find the applicable voltage drop table in AS/NZS 3008.1.1:2017. In this case, Table 42 is selected based on the type of cable, and Column 6 is selected based on the operating temperature of 75⁰C.

The value of Vc for the cable must be less than or equal to 5.11 mV/A.m, which means that the minimum cable size to satisfy voltage drop limitations is 10 mm2, which has a Vc of 3.86 mV/A.m.

Note that in this case, it is likely that the submains and possibly the consumer mains cables would be upsized to assist with reducing the installation voltage drop.

Conclusion:

Coordination between protective devices and conductors, as well as voltage drop control, are fundamental aspects to ensure the safety, efficiency and compliance of electrical installations, as established by the AS/NZS 3000 standard. Proper coordination ensures that protective devices, such as circuit breakers and fuses, operate correctly in the event of overloads, preventing damage to cables, equipment and fire risks. On the other hand, calculating and minimizing voltage drops are essential to keep the voltage within the operating limits of the equipment, avoiding malfunctions, energy losses and compromising the service life of the installation.

The correct selection of cables, based on the current carrying capacity (CCC) and the permissible voltage drop values, is crucial to meet the demands of the circuit and ensure the safe and efficient performance of the electrical system. Tables such as those in AS/NZS 3008.1.1 provide precise guidelines for sizing cables and calculating voltage drops, considering factors such as installation method, temperature and circuit length.

Therefore, strict application of these principles not only complies with technical standards, but also protects lives, equipment and property by ensuring that electrical installations operate reliably and safely. Attention to detail in the design and execution of electrical installations is essential to prevent failures, reduce operating costs and extend the life of systems.

