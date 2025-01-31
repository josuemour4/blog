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


<div class="typing">
    Writing<span class="dots"></span>
</div>