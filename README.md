Download Link: https://assignmentchef.com/product/solved-comp9032-experiment-3
<br>
<span style="font-size: 2.61792em; letter-spacing: -1px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">1.  Objectives</span>




In this lab, you will learn AVR programming on




<ul>

 <li>Parallel input/output,</li>

 <li>Interrupt, and</li>

 <li>Input from keyboard</li>

</ul>










<h1>2.  Preparation</h1>




Before coming to the laboratory, it is recommended that you:

<ul>

 <li>Download and install the Arduino software (avrdude-5.11-Patch7610-win32.zip available on the course website) o arduino-1.0.6-windows.exe</li>

 <li>Read “Introduction to Lab Board” and understand how to use the lab board.  Write your programs at home in order to finish the experiment on time.</li>

</ul>










<h1>3.  Tasks</h1>




Task 1 (7 marks, for week 6, due in week 7)




Implement a LED control system to repeatedly display a sequence of three patterns. The display will be halted when the user presses a button.  To ensure visibility, insert some delay (for example, 1s) between two adjacent patterns. The clock frequency used on the lab board is 16MHz.







Assemble your program using AVR Studio, and run it on the AVR Microcontroller Board. Demonstrate your working program to the lab assessor.






















1 Task 2 (6 marks, for week 7, due in week 8)




Based your code for Task 1, modify it by using an external interrupt to start and stop LEDs’ display.




Assemble your program using AVR Studio, and run it on the AVR Microcontroller Board. Demonstrate your working program to the lab assessor.










Task 3 (9 marks, for week 8, due in week 9)




Write an assembly program that performs multiplication: <em>a = b x c</em>, where <em>a</em>, <em>b</em>, <em>c</em> are all unsigned 1-byte integers. The program takes <em>b</em> and <em>c</em> from the keypad and displays the result on the LED bar. When there is an overflow in the calculation, the LED bar flashes 3 times.




Note: you can use the “*” key for “<em>x</em>” and the “#” key for “=”. For example, to get 12<em>x</em>9, your input key sequence is 1à2à*à9à#.




Assemble your program using AVR Studio, and run it on the AVR Microcontroller Board. Demonstrate your working program to the lab assessor.













Note: All your programs should be well commented. Up to 2 marks will be deducted for each program without proper and sufficient comments.





