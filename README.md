Download Link: https://assignmentchef.com/product/solved-cse321-homework-5
<br>
<ol>

 <li>Profit rates of many companies have changed due to the pandemic. XYZis a retail company with many branches on the Marmaray line. The management of the company is trying to identify the regions where they make the most profit. For this purpose, they gather the profit-loss rates of their retail shops to the table. Entries on the table are sorted in Marmaray station order.</li>

</ol>

<table width="366">

 <tbody>

  <tr>

   <td width="52">A</td>

   <td width="52">B</td>

   <td width="52">C</td>

   <td width="52">D</td>

   <td width="52">E</td>

   <td width="52">F</td>

   <td width="52">G</td>

  </tr>

  <tr>

   <td width="52">3</td>

   <td width="52">-5</td>

   <td width="52">2</td>

   <td width="52">11</td>

   <td width="52">-8</td>

   <td width="52">9</td>

   <td width="52">-5</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Design a dynamic programming algorithm that <strong>finds the maximum profit </strong>belonging to the most profitable cluster (the cluster must contain a consecutive region). For example, the maximum profit is 14 (C-D-E-F) on the table above.</li>

 <li>This question was asked in one of your homework before. <strong>Compare </strong>the algorithm with the algorithms you previously proposed in terms of complexity. Explain your arguments.</li>

</ul>

<ol start="2">

 <li>There is a candy shop, and candies are produced as a stick of length <em>ncm</em>. They can cut and sell candies in different lengths, and there is a price list that shows prices of all pieces of size smaller than <em>n</em>. For example, if the length of the candy is 8 <em>cm </em>and the values of different pieces are given as in the following, then the maximum obtainable value is 22 (by cutting in two pieces of lengths 2 and 6)</li>

</ol>

<table width="412">

 <tbody>

  <tr>

   <td width="46">length</td>

   <td width="46">1</td>

   <td width="46">2</td>

   <td width="46">3</td>

   <td width="46">4</td>

   <td width="46">5</td>

   <td width="46">6</td>

   <td width="46">7</td>

   <td width="46">8</td>

  </tr>

  <tr>

   <td width="46">price</td>

   <td width="46">1</td>

   <td width="46">5</td>

   <td width="46">8</td>

   <td width="46">9</td>

   <td width="46">10</td>

   <td width="46">17</td>

   <td width="46">17</td>

   <td width="46">20</td>

  </tr>

 </tbody>

</table>

Design a dynamic programming algorithm that finds the maximum obtainable value.

1

<strong>For each problem below, propose a greedy algorithm and describe it in detail. Analyze the complexity of the algorithm.</strong>

<ol start="3">

 <li>There is a store where dairy products like milk and cheese are sold. Thereexist <em>n </em>different types of cheese in the store, and each cheese type has a price <em>p<sub>i </sub></em>and a weight <em>w<sub>i</sub></em>. The owner wants to put a combination of different cheeses in a box, and sell it. The box has a weight capacity <em>W</em>, and you are allowed to cut cheeses and put any portion of it in the box to maximize the total price without exceeding the box weight capacity. Design a greedy algorithm that finds the maximum price you can get.</li>

 <li>A group of gifted students will be prepared for an intelligence contest. Inorder to prepare them, a program has been designed where each student can take courses among <em>n </em>courses, and the start and end times of the courses are given. A table is given below as an example.</li>

</ol>

<table width="274">

 <tbody>

  <tr>

   <td width="91"><strong>Course</strong></td>

   <td width="91"><strong>Start</strong></td>

   <td width="91"><strong>Finish</strong></td>

  </tr>

  <tr>

   <td width="91">English</td>

   <td width="91">1</td>

   <td width="91">2</td>

  </tr>

  <tr>

   <td width="91">Mathematics</td>

   <td width="91">3</td>

   <td width="91">4</td>

  </tr>

  <tr>

   <td width="91">Physics</td>

   <td width="91">0</td>

   <td width="91">6</td>

  </tr>

  <tr>

   <td width="91">Chemistry</td>

   <td width="91">5</td>

   <td width="91">7</td>

  </tr>

  <tr>

   <td width="91">Biology</td>

   <td width="91">8</td>

   <td width="91">9</td>

  </tr>

  <tr>

   <td width="91">Geography</td>

   <td width="91">5</td>

   <td width="91">9</td>

  </tr>

 </tbody>

</table>

A student can attend at most <strong>4 </strong>of the above courses . The maximum set of courses that can be attended is {English, Mathematics, Chemistry, Geography}. Design a greedy algorithm to find the maximum number of courses a student can attend among <em>n </em>courses.