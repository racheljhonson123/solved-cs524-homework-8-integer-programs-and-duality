Download Link: https://assignmentchef.com/product/solved-cs524-homework-8-integer-programs-and-duality
<br>



<ol>

 <li><strong>ABC Investments. </strong>ABC Inc. is considering several investment options. Each option has a minimum and maximum investment allowed (only if the option is chosen). These restrictions, along with the expected return are summarized in the following table (gures are in millions of dollars):</li>

</ol>

<table width="0">

 <tbody>

  <tr>

   <td width="57">Option</td>

   <td width="81">Minimuminvestment</td>

   <td width="81">Maximuminvestment</td>

   <td width="81">Expected return (%)</td>

  </tr>

  <tr>

   <td width="57">1</td>

   <td width="81">3</td>

   <td width="81">27</td>

   <td width="81">13</td>

  </tr>

  <tr>

   <td width="57">2</td>

   <td width="81">2</td>

   <td width="81">12</td>

   <td width="81">9</td>

  </tr>

  <tr>

   <td width="57">3</td>

   <td width="81">9</td>

   <td width="81">35</td>

   <td width="81">17</td>

  </tr>

  <tr>

   <td width="57">4</td>

   <td width="81">5</td>

   <td width="81">15</td>

   <td width="81">10</td>

  </tr>

  <tr>

   <td width="57">5</td>

   <td width="81">12</td>

   <td width="81">46</td>

   <td width="81">22</td>

  </tr>

  <tr>

   <td width="57">6</td>

   <td width="81">4</td>

   <td width="81">18</td>

   <td width="81">12</td>

  </tr>

 </tbody>

</table>

Because of the high-risk nature of Option 5, company policy requires that the total amount invested in Option 5 be no more that the combined amount invested in Options 2, 4 and 6. In addition, if an investment is made in Option 3, it is required that at least a minimum investment be made in Option 6. ABC has $80 million to invest and obviously wants to maximize its total expected return on investment. Which options should ABC invest in, and how much should be invested?

<ol start="2">

 <li><strong>Lagrangian duality. </strong>Consider the problem</li>

</ol>

)       subject to 1       <em>x</em><sub>1           </sub>0<em>:</em>

<ul>

 <li>Write down the solution of this problem and the optimal primal value <em>p </em>.</li>

 <li>Derive the Lagrangian dual function <em>g</em>( ) for 2 R .</li>

 <li>Find the solution of the Lagrangian dual problem max <sub>0 </sub><em>g</em>( ) and write down the optimal dual objective <em>d </em>.</li>

 <li>Is the Slater condition satised for this problem? Does strong duality hold, that is, <em>p </em>= <em>d </em>?</li>

</ul>

<ol start="3">

 <li><strong>Laurent goes to the gym. </strong>Laurent has a regular weight liting program. Today, he will be doing deadlifts and front squats. For each exercise he does 8 sets, with several repetitions per set (i.e., x3 means 3 repetitions). In the table below, you can see the weight he lifts in each set (given in lbs) and the number of repetitions for both deadlifts and front squats.</li>

</ol>

<table width="0">

 <tbody>

  <tr>

   <td width="86"><strong>S et</strong></td>

   <td width="45"><strong>1</strong></td>

   <td width="21"> </td>

   <td width="45"><strong>2</strong></td>

   <td width="21"> </td>

   <td width="45"><strong>3</strong></td>

   <td width="31"> </td>

   <td width="45"><strong>4</strong></td>

   <td width="21"> </td>

   <td width="45"><strong>5</strong></td>

   <td width="21"> </td>

   <td width="45"><strong>6</strong></td>

   <td width="21"> </td>

   <td width="45"><strong>7</strong></td>

   <td width="21"> </td>

   <td width="45"><strong>8</strong></td>

   <td width="21"> </td>

  </tr>

  <tr>

   <td width="86">Deadlift</td>

   <td width="45">310</td>

   <td width="21">x5</td>

   <td width="45">355</td>

   <td width="21">x3</td>

   <td width="45">395</td>

   <td width="31">x1+</td>

   <td width="45">375</td>

   <td width="21">x3</td>

   <td width="45">355</td>

   <td width="21">x3</td>

   <td width="45">330</td>

   <td width="21">x3</td>

   <td width="45">310</td>

   <td width="21">x3</td>

   <td width="45">290</td>

   <td width="21">x3</td>

  </tr>

  <tr>

   <td width="86">Front Squat</td>

   <td width="45">100</td>

   <td width="21">x5</td>

   <td width="45">130</td>

   <td width="21">x5</td>

   <td width="45">160</td>

   <td width="31">x3</td>

   <td width="45">160</td>

   <td width="21">x5</td>

   <td width="45">160</td>

   <td width="21">x7</td>

   <td width="45">160</td>

   <td width="21">x4</td>

   <td width="45">160</td>

   <td width="21">x6</td>

   <td width="45">160</td>

   <td width="21">x8</td>

  </tr>

 </tbody>

</table>

For both the deadlifts and the front squats, Laurent uses a steel bar which weighs 45 lbs. There are many available bumper plates (weights which are put on each side of the bar) with a weight of 2.5 lbs, 5lbs, 10 lbs, 25 lbs, and 45 lbs. Remember that there has to be the same amount of weight and the same type of plates on each side!

<ul>

 <li>Laurent would prefer to not think to much while he is at the gym (lifting takes a lot of concentration). Can you help him solve an optimization problem which takes the current weight (considering one set and one exercise at the time) and minimizes the number of plates he has to put on the barbell? Make a schedule that shows which bumper plates Laurent should use for each weight.

  <ul>

   <li>of 2</li>

  </ul></li>

</ul>

<ul>

 <li>Because of COVID-19, Laurent can no longer go to the gym and has decided to invest in lifting equipment which he will install in his basement. He would like to continue doing the same exercises as in the table above, but now wants to minimize the total number of bumper plates that he has to order (while being able to combine them to give all of the above weights). Solve an optimization problem to determine which bumper plates Laurent should invest in.</li>

 <li>Resolve the problem from (a), but consider that Laurent only has access to the bumper plates that he decided to buy. Print the new schedule that shows which bumper plates to put on the barbell for each exercise.</li>

</ul>