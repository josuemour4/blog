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

Example of multiple domestic maximum demand.

This example shows the maximum demand of the highest loaded phase in a block of 18 units, each with the following single-phase load:

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
          <td class="ct"><span class="image fit"><img src= "assets/images/capstone/md/LGdescription06.png" alt="" /></span></td>
          <td class="ct">6</td>
          <td class="ct">150w incandescent secutiy lights</td>
        </tr>
        <tr>
          <td class="ct"><span class="image fit"><img src= "assets/images/capstone/md/LGdescription07.png" alt="" /></td>
          <td class="ct">9</td>
          <td class="ct">10A single GPO</td>
        </tr>
        <tr>
          <td class="ct"><span class="image fit"><img src= "assets/images/capstone/md/LGdescription08.png" alt="" /></span></td>
          <td class="ct">2</td>
          <td class="ct">Clothes dryers @12A</td>
        </tr>
        <tr>
          <td class="ct"><span class="image"><img src= "assets/images/capstone/md/LGdescription09.png" alt="" /></span></td>
          <td class="ct">1</td>
          <td class="ct">1ph motor @8A</td>
        </tr>
        <tr>
          <td class="ct"><span class="image"><img src= "assets/images/capstone/md/LGdescription09.png" alt="" /></span></td>
          <td class="ct">1</td>
          <td class="ct">1ph motor @6A</td>
        </tr>
        <tr>
          <td class="ct"><span class="image"><img src= "assets/images/capstone/md/LGdescription10.png" alt="" /></span></td>
          <td class="ct">2</td>
          <td class="ct">3ph lift motor @16A</td>
        </tr>
    </tbody>
  </table>
</div>
