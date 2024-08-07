---
layout: post
author: Josue Moura
title:  "The MEN system"
subtitle: "Getting ready for the test!"
date:   2024-04-25 10:43:28 +1100
categories: 3000:2018 MEN
tags: [australia, NSW, capstone, preparation]
location: "Sydney - Australia"
permalink: "MEN"
images:
  banner:
    file:         "TN-C-S.png"
    alt_text:     ""
    caption:      "MEN System"
    title:        "MEN System"
---

At the end of last year, I applied for my proficiency certificate. To date, I have not yet received an email from the responsible agency reviewing my documents to inform me whether the documents I submitted are sufficient to issue the document required to obtain my full electrician's license.

Since this has not yet occurred, I am considering the possibility of having to take the final test. For this reason, I will write a few posts related to the content that will possibly be covered in the test.

As the title already indicates, this post will be about the MEN (Multiple Earthed Neutral) system.

In the book AS/NZS 3000:2018, in item 5.3 EARTHING SYSTEM PARTS clause 5.3.1 General says:

The protective earthing arrangement for an electrical installation providing protection by means of automatic disconnection of supply and connected to the MEN system of distribution shall include the following parts: 

A) **Protective earthing conductors connecting exposed conductive parts as required.**  
    - Cables that connect exposed metal parts (such as appliance casings) to the grounding system.  
B) **Main earthing conductor.**  
    - The main wire that connects the entire grounding system to earth.  
C) **Main earthing terminal, connection or bar.**  
    - The central point where all grounding conductors meet.  
D) **MEN connection between the main earthing terminal, connection or bar and the supply neutral bar.**   
    - A connection between the main grounding terminal and the neutral bus of the power supply, to ensure that the neutral and earth are connected correctly.   
E) **Earth electrode.**  
    - A device (usually a metal rod) buried in the ground that connects the grounding system   
F) **Equipotential bonding of extraneous conductive and other parts as required.**
    - Connections that ensure that all metal parts that are not part of the electrical system (such as water and gas pipes) are at the same electrical potential, preventing electric shock.


Examples of the parts of the MEN system of earthing are shown in Figures 5.1 and 5.2.

![5.1]({{site.image_path}}/capstone/mensystem/fig_5_1.png "MULTIPLE EARTHED NEUTRAL (MEN) SYSTEM OF EARTHING—GENERAL ARRANGEMENT PEN DISTRIBUTION/TN-C-S"){:.small.image}
<p align="center">5.1</p> 

![5.2]({{site.image_path}}/capstone/mensystem/fig_5_2.png "ALTERNATIVE EARTHING ARRANGEMENT IN AN OWNER OR USER OPERATED SUPPLY SUBSTATION INSTALLATION"){:.small.image}
<p align="center">5.2</p>

![5.3]({{site.image_path}}/capstone/mensystem/fig_5_3.png "EXAMPLES OF EARTHING ARRANGEMENTS (CLAUSES 5.5.2.1 AND 5.5.2.2.3)"){:.small.image}
<p align="center">5.3</p>

**Outbuildings**

First, let's look at the definition of "outbuilding" in the context of the MEN system.

According to AS/NZS 3000:2018, the definition for "outbuilding" is: 

***Outbuilding – Individual – Clause 1.4.88***

“A structure containing a switchboard that is separated by an area of land from the structure containing the switchboard that supplies it.”
- Example: A building (such as a shed or garage) that has its own electrical distribution panel and is separated by a strip of land from the main building that supplies electricity to it.

![5.4]({{site.image_path}}/capstone/mensystem/outbuilding_fig_5_4.png "EXAMPLE OF EARTHING OF AN INDIVIDUAL OUTBUILDING [CLAUSE 5.5.3.1(a)]"){:.small.image}
<p align="center">5.4</p> 

***Outbuilding – Combined – Clause 1.4.89***

“Any number of structures installed or built on the same foundation, or sharing conductive metal roofing or conductive metal frames, with more than one electrical supply, and separated by an area of land from another structure that contains the switchboard from which those electrical supplies are obtained.”

The earthing system in a separate MEN installation must be connected to the neutral conductor of the sub-supply supplying the external building. In this case, the neutral conductor of the sub-supply supplying the external building functions as a combined protective earthing and neutral (PEN) conductor.

- Example: Several buildings that are on the same foundation or that share a roof or conductive metal structures, with more than one electricity supply, and that are separated by a piece of land from another building that has the distribution panel from which the electricity is supplied.

![5.5]({{site.image_path}}/capstone/mensystem/outbuilding_fig_5_5.png "FIGURE 5.5 EXAMPLE OF EARTHING OF COMBINED OUTBUILDINGS [CLAUSE 5.5.3.1(b)]"){:.small.image}
<p align="center">5.5</p> 

**What does this mean?**

 **“connected to a protected earthing conductor”** means that with the active and neutral conductors, a protective earth conductor is fed to the distribution board.  Because a protective earth is fed to the distribution board there will be no MEN link, no main earth and no earth stake at the distribution board.

 **“separate MEN installation”** means that when a sub main is fed to the distribution board no protective earth is fed with the sub main to the distribution board.  If there is no protective earth fed to the distribution board then the distribution board must have an MEN link, a main earthing conductor and an earth electrode.  The sub main neutral is now a PEN (a neutral under normal conditions but a protective earth under fault conditions).

![Example 01]({{site.image_path}}/capstone/mensystem/separete_example.png "EXAMPLE OF SEPARETE"){:.small.image}

![Example 01]({{site.image_path}}/capstone/mensystem/separete_example2.png "EXAMPLE OF SEPARETE"){:.small.image}

Under these conditions there is a further requirement from Clause 5.5.3.1 (c) (v) that says if a distribution board is fed from a main switchboard via another outbuilding’s distribution board then the PEN of the second outbuilding distribution board must not rely on the terminals of the neutral link/bar at the first outbuilding’s distribution board, therefore the PEN is usually soldered to the sub main neutral of the first outbuilding’s distribution board.

**Note 1:** PENs are not connected (ie: soldered) to other neutrals at any time at the main switchboard!

**Note 2:** AS/NZS 3000 clause 2.10.5.4 says **“The terminals for the connection of the MEN connection and for the main neutral conductor shall be legibly and indelibly marked at the main neutral bar.”**