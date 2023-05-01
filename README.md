Download Link: https://assignmentchef.com/product/solved-ccc-labstatus
<br>
You run four computer labs. Each lab contains computer stations that are numbered as shown in the table below:-

<table width="389">

 <tbody>

  <tr>

   <td width="147"><strong>Lab Number</strong></td>

   <td width="228"><strong>Computer Station Numbers</strong></td>

  </tr>

  <tr>

   <td width="147">1</td>

   <td width="228">1-5</td>

  </tr>

  <tr>

   <td width="147">2</td>

   <td width="228">1-6</td>

  </tr>

  <tr>

   <td width="147">3</td>

   <td width="228">1-4</td>

  </tr>

  <tr>

   <td width="147">4</td>

   <td width="228">1-3</td>

  </tr>

 </tbody>

</table>

Each user has a unique five-digit ID Number. Whenever a user logs on, the user’s ID, Lab Number, and the computer station are transmitted to your station. For example, if user 49193 logs onto station 2 in Lab 3, your system receives (49193, 2, 3) as input data. Similarly, when a user logs off a station, your system receives the Lab Number and computer station number.

Write a computer program that could be used to track, by lab, which user is logged onto which computer. For example, if user 49193 is logged into station 2 in lab 3 and user 99577 is logged into station 1 of lab 4, then your system might display the following:-

Lab Number        Computer Stations

1                          1: empty  2: empty  3: empty  4: empty  5: empty

2                          1: empty  2: empty  3: empty  4: empty  5: empty  6: empty

3                          1: empty  2: 49193  3: empty  4: empty

4                          1: 99577  2: empty  3: empty

<strong>Task</strong>:-

<ol>

 <li>Create a menu that allows the administrator to simulate the transmission of information by manually typing in the login or logoff data. Whenever someone logs in or out, the display table should be updated.</li>

 <li>Write a search option so the administrator can type in a user Id and the system will output what Lab Number and station number the user is logged into, or “None” if the user Id is not logged into any computer station.</li>

</ol>

You should use a fixed array of length 4 for the labs. Each array entry points to a dynamic array that stores the user login information for each respective computer station.

<strong><u>Sample Output</u></strong><strong>:- </strong><em>(User input is in bold and Italics)</em>

LAB STATUSLab # Computer Stations1 1: empty 2: empty 3: empty 4: empty 5: empty2 1: empty 2: empty 3: empty 4: empty 5: empty 6: empty3 1: empty 2: empty 3: empty 4: empty4 1: empty 2: empty 3: empty

MAIN MENU0) Quit1) Simulate login2) Simulate logoff3) Search<strong><em>1</em></strong>Enter the 5 digit ID number of the user logging in:<strong><em>12345</em></strong>Enter the lab number the user is logging in from (1-4):<strong><em>2</em></strong>Enter computer station number the user is logging in to (1-6):<strong><em>3</em></strong>

LAB STATUSLab # Computer Stations1 1: empty 2: empty 3: empty 4: empty 5: empty2 1: empty 2: empty 3: 12345 4: empty 5: empty 6: empty3 1: empty 2: empty 3: empty 4: empty4 1: empty 2: empty 3: empty

MAIN MENU0) Quit1) Simulate login2) Simulate logoff3) Search<strong><em>2</em></strong>Enter the 5 digit ID number of the user to find:<strong><em>12345</em></strong>User 12345 is logged off.

LAB STATUSLab # Computer Stations1 1: empty 2: empty 3: empty 4: empty 5: empty2 1: empty 2: empty 3: empty 4: empty 5: empty 6: empty3 1: empty 2: empty 3: empty 4: empty4 1: empty 2: empty 3: empty

MAIN MENU0) Quit1) Simulate login2) Simulate logoff3) Search


