---
layout: post
author: Josue Moura
title:  "Ordination - Current carrying capacity - Voltage Drop"
subtitle: "Getting ready for the test!"
date:   2024-09-22 20:49:10 +1100
last_modified_at: 2024-12-26 16:04:27
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
  </style>

**Co-ordination**

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

To align with environmental values and extend the cable's service life, its capacity must be de-rated.

The book used to do this calculation is AS/NZS 3008.1.1. 