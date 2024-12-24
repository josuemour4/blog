---
layout: post
author: Josue Moura
title:  "Ordination - Current carrying capacity - Voltage Drop"
subtitle: "Getting ready for the test!"
date:   2024-09-22 20:49:10 +1100
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
  </style>

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

<b>(a)</b> the operating current in conventional time for circuit- breakers (1.45 IN); or  
<b>(b)</b> the fusing current in conventional time for fuses (1.6 IN for fuses in accordance with the IEC 60269 series).

Below are the clauses that address this issue:

2.5.3 Protection against overload current 
2.5.3.1 Coordination between conductors and protective devices 

