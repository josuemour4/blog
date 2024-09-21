---
layout: post
author: Josue Moura
title:  "Maximum Demand"
subtitle: "Getting ready for the test!"
date:   2024-08-09 06:08:28 +1100
categories: 3000:2018 Maximum Demand
tags: [australia, NSW, capstone, preparation,Maximum-demand]
location: "Sydney - Australia"
permalink: "maximum-demand"
images:
  banner:
    file:         "md.jpg"
    alt_text:     ""
    caption:      "Maximum Demand"
    title:        "Maximum Demand"
---

<style>
  .ct {
    text-align: center;
    vertical-align: middle;
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
    content: 'Maximum demand'; /* Texto do balão */
    position: absolute;
    bottom: 150%;
    left: 50%;
    transform: translateX(-50%);
    background-color: black;
    color: white; 
    padding: 5px;
    border-radius: 5px;
    white-space: nowrap;
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

  .niceT {
    font-family: 'Arial', sans-serif;
    font-size: 18px;
    line-height: 1.6;
    color: #333;
    text-align: justify;
    letter-spacing: 0.5px;
    word-spacing: 2px;
    margin: 15px 0;
}
</style>

Finally, I’m going to start writing about maximum demand. As I mentioned in my previous post, I’m still waiting for Fair Skills to tell me if I’ll need to take the aptitude test. If that happens, I want to be as prepared as I have been in the past. However, this time is different; I’m a father now. But what’s really making it hard for me to concentrate is not fatherhood, but the fact that I’ve been working for 7 years without a vacation, that I was intentionally harmed by my last employer, and that I have a number of other problems that have accumulated over the years.

**Maximum Demand**

In the book AS/NZS 3000:2018 the following statement is made:


1.6.3: The maximum demand of an electrical installation shall be determined, taking account of the capacity, physical distribution and intended use of electrical equipment in the electrical installation and the manner in which the present requirements might vary.

<i>Note</i>: <u>Clause 2.2.2</u> contains acceptable methods of determining maximum demand.

Clause 2.2.2: The maximum demand in consumer mains, submains and final subcircuits, taking account of the physical distribution and intended usage of electrical equipment in the electrical installation and the manner in which the present requirements might vary, shall be determined using one of the methods set out in Items (a) to (d). 

a. Calculation  
b. Assessment  
c. Measurement  
d. Limitation  

The guidance for calculating maximum demand is detailed in Appendix C.

Table C1 is used for single and domestic installations.

Table C2 is used for non-domestic installations.

**Example of single domestic maximum demand.**

<p class="niceT">The following scenario is an example used for calculating the maximum demand in a domestic house. It includes the following items:</p>

- 24 - lights  
- 3 - 2X36W flurescent lights @ 0.38A  
- 4 - 80w celiling fans  
- 2 - 150w external lights  
- 2 - 10A single socket outlets  
- 21 - 10A double socket outlets  
- 1 - 15A socket outlet  
- 1 - 20A socket outlet  
- 1 - Clothes dryer @13A (has a 15A plug)  
- 1 - Washig machine @6A (has a 10A plug)  
- 1 - 2.3Kw HWS - storage type  
- 1 - 7.6Kw range  

<div class="table-wrapper">
  <table class="alt">
    <thead>
      <tr>
        <th>Load group</th>
        <th>Number</th>
        <th>Equipments</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><span class="image fit"><img src= "assets/images/capstone/md/loadgroup_light.png" alt="" /></span>
        </td>
        <td class="ct">24</td>
        <td class="ct">Lights</td>
      </tr>
      <tr>
        <td><span class="image fit"><img src= "assets/images/capstone/md/loadgroup_light.png" alt="" /></span></td>
        <td class="ct">3</td>
        <td class="ct">2x36W fluorescent lights @0.38A each fitting</td>
      </tr>
      <tr>
        <td><span class="image fit"><img src= "assets/images/capstone/md/loadgroup_light_fan.png" alt="" />
        </span></td>
        <td class="ct">4</td>
        <td class="ct">80W ceiling fans</td>
      </tr>
      <tr>
        <td><span class="image fit"><img src= "assets/images/capstone/md/loadgroup_light.png" alt="" /></span>
        </td>
        <td class="ct">2</td>
        <td class="ct">150W external lights</td>
      </tr>
      <tr>
        <td><span class="image fit"><img src= "assets/images/capstone/md/socketoutlet.png" alt="" /></span></td>
        <td class="ct">2</td>
        <td class="ct">10A single Socket outlet</td>
      </tr>
      <tr>
        <td><span class="image fit"><img src= "assets/images/capstone/md/socketoutlet.png" alt="" /></span></td>
        <td class="ct">21</td>
        <td class="ct">10A double Socket outlet</td>
      </tr>
      <tr>
        <td><span class="image fit"><img src= "assets/images/capstone/md/socketoutlet2.png" alt="" /></span></td>
        <td class="ct">1</td>
        <td class="ct">15A Socket outlet</td>
      </tr>
      <tr>
        <td><span class="image fit"><img src= "assets/images/capstone/md/socketoutlet3.png" alt="" /></span></td>
        <td class="ct">1</td>
        <td class="ct">20A Socket outlet</td>
      </tr>
      <tr>
        <td><span class="image fit"><img src= "assets/images/capstone/md/appliancemorethan10a.png" alt="" /></span></td>
        <td class="ct">1</td>
        <td class="ct">Clothes dry @13A (has a 15A plug)</td>
      </tr>
      <tr>
        <td><span class="image fit"><img src= "assets/images/capstone/md/socketoutlet.png" alt="" /></span></td>
        <td class="ct">1</td>
        <td class="ct">Washing machine @ 6A (has a 10A plug)</td>
      </tr>
      <tr>
            <td><span class="image fit"><img src= "assets/images/capstone/md/SWH.png" alt="" /></span></td>
            <td class="ct">1</td>
            <td class="ct">2.3Kw HWS - storage type</td>
      </tr>
      <tr>
        <td><span class="image fit"><img src= "assets/images/capstone/md/appliancemorethan10a.png" alt="" /></span></td>
            <td class="ct">1</td>
            <td class="ct">7.6Kw range</td>
      </tr>
    </tbody>
  </table>
</div>

<div class="table-wrapper">
  <table class="alt">
    <thead>
      <tr>
        <th>LG</th>
        <th>Description</th>
        <th>Table C1 Description</th>
        <th>Calculations</th>
      </tr>
    </thead>
    <tbody>
        <tr>
          <td class="ct">a I</td>
          <td class="ct">Lights</td>
          <td><span class="image fit"><img src= "assets/images/capstone/md/LGdescription01.png" alt="" /></span></td>
          <td class="ct">24+3+4+2 = 33pts<br />3 + 2=5 </td>
        </tr>
        <tr>
          <td class="ct">b I</td>
          <td class="ct">10A sockets</td>
          <td><span class="image fit"><img src= "assets/images/capstone/md/LGdescription02.png" alt="" /></span></td>
          <td class="ct">2+42+1 = 44pts <br />10+5+5=20A</td>
        </tr>
        <tr>
          <td class="ct">C</td>
          <td class="ct">Range+Clothes dry</td>
          <td><span class="image fit"><img src= "assets/images/capstone/md/LGdescription03.png" alt="" /></span></td>
          <td class="ct">13A+(7600/230=33A)=46A <br />46*0.5=23A </td>
        </tr>
        <tr>
          <td class="ct">B2/B3</td>
          <td class="ct">15A and 20A sockets</td>
          <td><span class="image fit"><img src= "assets/images/capstone/md/LGdescription04.png" alt="" /></span></td>
          <td class="ct">15A</td>
        </tr>
        <tr>
          <td class="ct">F</td>
          <td class="ct">HWS</td>
          <td><span class="image fit"><img src= "assets/images/capstone/md/LGdescription05.png" alt="" /></span></td>
          <td class="ct">2300/230=10A</td>
        </tr>
        <tfoot>
          <tr>
            <td colspan="3"></td>
            <td>73A</td>
          </tr>
        </tfoot>
      </tbody>
  </table>
</div>

<p class="niceT">The maximum demand for the example of single domestic is 73A.</p>

**Example of multiple domestic maximum demand.**

<p>This example shows the maximum demand of the highest loaded phase in a block of 18 units, each with the following single-phase load:</p>

<div class="table-wrapper">
  <table class="alt">
    <thead>
      <tr>
        <th>LG</th>
        <th>No.</th>
        <th>Equipmente</th>
      </tr>
    </thead>
    <tbody>
        <tr>
          <td class="ct">A1</td>
          <td class="ct">24</td>
          <td class="ct">Lighs</td>
        </tr>
        <tr>
          <td class="ct">B1</td>
          <td class="ct">22</td>
          <td class="ct">10A Double GPO</td>
        </tr>
        <tr>
          <td class="ct">C</td>
          <td class="ct">1</td>
          <td class="ct">8Kw range</td>
        </tr>
        <tr>
          <td class="ct">D</td>
          <td class="ct">2</td>
          <td class="ct">Air Conditioner</td>
        </tr>
        <tr>
          <td class="ct">F</td>
          <td class="ct">1</td>
          <td class="ct">2.4Kw HWS(Storage type)</td>
        </tr>
    </tbody>
  </table>
</div>

**Communal load**

<div class="table-wrapper">
  <table class="alt">
    <thead>
      <tr>
        <th>LG</th>
        <th>No.</th>
        <th>Equipmente</th>
      </tr>
    </thead>
    <tbody>
        <tr>
          <td class="ct"><span class="image fit">
            <img src= "assets/images/capstone/md/LGdescription06.png" alt="" /></span></td>
          <td class="ct">6</td>
          <td class="ct">150w incandescent secutiy lights</td>
        </tr>
        <tr>
          <td class="ct">
            <span class="image fit">
            <img src= "assets/images/capstone/md/LGdescription07.png" alt="" />
            </span>
          </td>
          <td class="ct">9</td>
          <td class="ct">10A single GPO</td>
        </tr>
        <tr>
          <td class="ct">
            <span class="image fit">
            <img src= "assets/images/capstone/md/LGdescription08.png" alt="" /></span>
          </td>
          <td class="ct">2</td>
          <td class="ct">Clothes dryers @12A</td>
        </tr>
        <tr>
          <td class="ct"><span class="image">
            <img src= "assets/images/capstone/md/LGdescription09.png" alt="" />
            </span>
          </td>
          <td class="ct">1</td>
          <td class="ct">1ph motor @8A</td>
        </tr>
        <tr>
          <td class="ct">
            <span class="image">
            <img src= "assets/images/capstone/md/LGdescription09.png" alt="" />
            </span>
          </td>
          <td class="ct">1</td>
          <td class="ct">1ph motor @6A</td>
        </tr>
        <tr>
          <td class="ct"><span class="image">
            <img src= "assets/images/capstone/md/LGdescription10.png" alt="" />
            </span>
          </td>
          <td class="ct">2</td>
          <td class="ct">3ph lift motor @16A</td>
        </tr>
    </tbody>
  </table>
</div>

**Calculation:**

<div class="table-wrapper">
  <table class="alt">
    <thead>
      <tr>
        <th>LG</th>
        <th>Description</th>
        <th>Table C1 Description</th>
        <th>Calculation</th>
        <th>A</th>
        <th>B</th>
        <th>C</th>
      </tr>
    </thead>
    <tbody>
        <tr>
          <td class="ct">A1</td>
          <td class="ct">Lights</td>
          <td class="ct"><span class="image fit"><img src= "assets/images/capstone/md/LGdescription11.png" alt="" /></span></td>
          <td class="ct">5+(0.25*6)=6.5A</td>
          <td class="ct">6.5A</td>
          <td class="ct">6.5A</td>
          <td class="ct">6.5A</td>
        </tr>
        <tr>
          <td class="ct">B1</td>
          <td class="ct">GPO</td>
          <td class="ct"><span class="image fit"><img src= "assets/images/capstone/md/LGdescription12.png" alt="" /></span></td>
          <td class="ct">15+(3.75*6)=37.5A</td>
          <td class="ct">37.5A</td>
          <td class="ct">37.5A</td>
          <td class="ct">37.5A</td>
        </tr>
        <tr>
          <td class="ct">C</td>
          <td class="ct">Range</td>
          <td class="ct"><span class="image fit"><img src= "assets/images/capstone/md/LGdescription13.png" alt="" /></span></td>
          <td class="ct">2.8*6=16.8A</td>
          <td class="ct">16.8A</td>
          <td class="ct">16.8A</td>
          <td class="ct">16.8A</td>
        </tr>
        <tr>
          <td class="ct">D</td>
          <td class="ct">A/C</td>
          <td class="ct"><span class="image fit"><img src= "assets/images/capstone/md/LGdescription14.png" alt="" /></span></td>
          <td class="ct">2 air conditioner of 12A each, 2*12*6*.75=108A</td>
          <td class="ct">108A</td>
          <td class="ct">108A</td>
          <td class="ct">108A</td>
        </tr>
        <tr>
          <td class="ct">F</td>
          <td class="ct">SWH</td>
          <td class="ct"><span class="image fit"><img src= "assets/images/capstone/md/LGdescription15.png" alt="" /></span></td>
          <td class="ct">6*6=36A</td>
          <td class="ct">36A</td>
          <td class="ct">36A</td>
          <td class="ct">36A</td>
        </tr>
        <tfoot>
          <tr>
            <td colspan="3"></td>
            <td><b>TOTAL</b></td>
            <td>204.8A</td>
            <td>204.8A</td>
            <td>204.8A</td>
          </tr>
        </tfoot>
    </tbody>
  </table>
</div>

**Communal load**

<div class="table-wrapper">
  <table class="alt">
    <thead>
      <tr>
        <th>LG</th>
        <th>Description</th>
        <th>Table C1 Description</th>
        <th>Calculation</th>
        <th>A</th>
        <th>B</th>
        <th>C</th>
      </tr>
    </thead>
    <tbody>
        <tr>
          <td class="ct">H</td>
          <td class="ct">Lights</td>
          <td class="ct"><span class="image"><img src= "assets/images/capstone/md/LGdescription16.png" alt="" /></span></td>
          <td class="ct">6*150/230=3.9A</td>
          <td class="ct">3.9</td>
          <td class="ct"></td>
          <td class="ct"></td>
        </tr>
        <tr>
          <td class="ct">I</td>
          <td class="ct">GPO</td>
          <td class="ct"><span class="image"><img src= "assets/images/capstone/md/LGdescription17.png" alt="" /></span></td>
          <td class="ct">9*2=18 <br />But, on the books says max of 15A</td>
          <td class="ct"></td>
          <td class="ct">15A</td>
          <td class="ct"></td>
        </tr>
        <tr>
          <td class="ct">I</td>
          <td class="ct">GPO</td>
          <td class="ct"><span class="image"><img src= "assets/images/LGdescription17.png" alt="" /></span></td>
          <td class="ct">9*2=18 <br />But, on the books says max of 15A</td>
          <td class="ct"></td>
          <td class="ct">15A</td>
          <td class="ct"></td>
        </tr>
        <tr>
          <td class="ct">I</td>
          <td class="ct">Clothes dry</td>
          <td class="ct"><span class="image"><img src= "assets/images/capstone/md/LGdescription18.png" alt="" /></span></td>
          <td class="ct">2*12*0.5=12A</td>
          <td class="ct"></td>
          <td class="ct"></td>
          <td class="ct">12A</td>
        </tr>
        <tr>
          <td class="ct">L</td>
          <td class="ct">Motor</td>
          <td class="ct"><span class="image"><img src= "assets/images/capstone/md/LGdescription19.png" alt="" /></span></td>
          <td class="ct">Description on table C2: <b>Full load of highest rated motor, plus 50% of full load of remainder</b>
            <br /> It is two motor one 8A the other 6A. Full load in the phase A and B.</td>
          <td class="ct">8A</td>
          <td class="ct">6A</td>
          <td class="ct"></td>
        </tr>
        <tr>
          <td class="ct">K</td>
          <td class="ct">Lift</td>
          <td class="ct"><span class="image"><img src= "assets/images/capstone/md/LGdescription20.png" alt="" /></span></td>
          <td class="ct">Description on table C2: <b>(I) Largest lift motor—125% full load <br /> (ii) Next largest lift motor—75% full load.</b> <br /> 16*1.25=20A and 16*0.75=12A</td>
          <td class="ct">20A <br/>12A</td>
          <td class="ct">20A <br/>12A</td>
          <td class="ct">20A <br/>12A</td>
        </tr>
        <tfoot>
          <tr>
            <td colspan="3"></td>
            <td><b>TOTAL</b></td>
            <td>43.9A</td>
            <td>53A</td>
            <td>44A</td>
          </tr>
        </tfoot>
    </tbody>
  </table>
</div>

<p class="niceT">Total maximum demand of the units and communal</p>

<div class="table-wrapper">
  <table class="alt">
    <thead>
      <tr>
        <th>Location</th>
        <th>A</th>
        <th>B</th>
        <th>C</th>
      </tr>
    </thead>
    <tbody>
        <tr>
          <td class="ct">Units</td>
          <td class="ct">204.8A</td>
          <td class="ct">204.8A</td>
          <td class="ct">204.8A</td>
        </tr>
        <tr>
          <td class="ct">Communal</td>
          <td class="ct">43.9A</td>
          <td class="ct">53A</td>
          <td class="ct">44A</td>
        </tr>
        <tfoot>
          <tr>
            <td class="ct"><b>TOTAL</b></td>
            <td class="ct"><b> 248.7A </b> </td>
            <td class="ct"><span class="circle"><b> 257.8A</b></span></td>
            <td class="ct"><b> 248.8A </b> </td>
          </tr>
        </tfoot>
    </tbody>
  </table>
</div>

<p class="niceT">The Balance allowed is 20A or 20% of difference, what mean that the value is good.</p>