# Hostel_Management_System
This the hostel management system made my Saif-ur-Rehman Awan as The Programming Fundamentals (PF) Semester project in 2nd Semester in International Islamic University, Islamabad.

Hotel Reservation System.
Readme file.
===========================

This file contains all the Information about our Hotel Reservation System.

-------------------------------------------------------------------------------------------------------------------------
Prerequisites:

	C++ Compiler (Recommended: TDM GCC 4.9.2) should be installed in order to run the program.

---------------------------------------------------------------------------------------------------------------------
Installation:

1. Ensure you have a C++ compiler installed (e.g., GCC).
2. Copy the source code files (e.g., hotel.cpp, header files) to your project directory.
3. Compile the code using your C++ compiler (e.g., g++ hotel.cpp -o hotel).

----------------------------------------------------------------------------------------------------------------------
Using the Program:

1. Compile the code according to your C++ compiler instructions.
2. Run the compiled executable.
3. The main menu will display the numbered functionalities. Enter the corresponding number to select an option.
4. Follow the on-screen prompts for each function to complete the desired action.

-------------------------------------------------------------------------------------------------------------------------
Project Description:

	This program intends to provide a Hotel Management System in user-friendly interface by displaying sub-menus, so that the user can navigate easily through the whole program.
The program starts with Welcome Screen compromising of 9 functionalities. Each function opens further menu so that user can opt different options. "1 - 8" are Menu options while 9th option "0" exists the program. The 9 functionalities are as follows:

  1. Book a room.
  2. Custromer search.
  3. Room details.
  4. Editor record. 
  5. Information.
  6. Checkout.
  7. Credit.
  8. Instructions.
  0. Exit.


Now each functionality will be described and explained as follows:

1. Book a Room:
	When selecting "1" from the "Main Menu", you are prompted to the "Book A Room" Section, where you have to enter the details of the customer who wants to check in. First of all, you have to enter The "Name of Customer", then you have to enter the "CNIC of Customer", Along with the "Phone Number". Then "Check-in Date" is entered. Upon entering checkin date, you have to enter "Days to Stay" from which room fare will be calculated by day wise. And finally, you are required to enter the "Category of the Room" in which the customer would like to stay according with amenities ranging with price.
Starting from Economy ,Standard And luxury.
After entering the category, customer's data is stored and the customer is alotted with a Room Number according to category selected and your total price of room is displayed.
Pressing any key after this will prompt the user to "Main Menu" again.

2. Customer Search:
	In this section, a user can search about customers checked-in by their name, cnic or phone no. The user can search their data with any one of these crenditials. When you Enter any one of these data, if same data is found, you will be directed to data of that person which includes "Name" , "Room No.", "CNIC", Days to Stay", "Check-in Date", and "Phone Number".
Pressing any key afterwards will prompt user back to "Main Menu" again.

3. Room Details:
	This section displays "Rooms Aailable" in numbers category-wise. When the room is booked, the no. of rooms available/unoccupied decreases by no of rooms booked below Available Room.
"Customer's Checked-in list" of the hotel is also dislayed in this section. It displays all Room No. Booked and all of Customer's Details, and total fare of that Customers.
Pressing any key after-that will prompt to user back to "Main Menu" again.

4. Edit Record:
	When you have to edit records, such as Customer's Data, Room Fare or No of Rooms in each category, you have to press "4" from the "Main Menu" to be prompted to this section.
   If you press "1" you will be directed to "Customer's Data Edit" section, where you have to search for that customer by name and then edit data. If you press "2", "Room Fare Edit" section will be displayed, where the current fare is listed. Upon selecting category, you can increase/decrease room fare. If you Press "3", "Edit No. of Rooms" section will appear, from which yoou can increase/decrease no. of rooms of each category.
Now, if you want to go back to previous Sub-Menu of "Edit Records", use "0" to go back.

5. Information:
	Upon selecting with this option from the "Main Menu", User will be directed to "Information" section, where the the information about rooms will be displayed category wise and in form of bullet points, so that it may be easier for user to read. Information section aims to tell that what facilities you will get depending on category of rooms you choose.

6. Checkout:
	In this section, "Check-out" options are given. First, you have to enter the name of Customer who wanna to check-out. Upon entering Customer's name, all details of that customer are displayed. Then you are asked that you want to checkout or go back to search.
Pressing "1" will checkout that person by displaying multiple types of payment methods. When payment is recieved, then the data of that user is deleted and that room is unoccupied with confirmation message.
Pressing "0" will take user back to "Main Menu".

7. Credits:
	When You press "7" in the "Main Menu", "Credits" section will appear, which will display information about the people working behind this system. Here the credits of this "Hotel Reservation System" development team's names are given along with their Rolls in the team. Also Project Supervisor's and Institute's name are given, along with purpose of building this program.
Afterwords, pressing any key will return the user back to "Main Menu".

8. Instructions:
	This program already aims to provide user friendly interface, however for computer beginners, "Instruction" section is made in the "Main Menu" so that program becomes easier to run by user. In the "Instruction" section, user will be guided with some instructions on how to use program correctly in order to have best user experience and to operate effecively this program.
After Instructions, the program also displays "Features" that a user can use in a program, which are also written in simple words and in bullet points, in order to make it easier for common user to understand the purpose of program.
Afterwords, pressing any key will return the user back to "Main Menu".

0. Exit:
	Pressing "0" will exit the program.

---------------------------------------------------------------------------------------------------------------------
Instructions:
	
The following are some of the instructions a user should follow in order, in order to run and use program effectiviely.
   1) You are free to use any Name, CNIC no, Phone No and Check-in Date, in any format, you can also include white-spaces in between them.
   2) Don't use other Characters than Numeric when entering Stay Days, otherwise, the program will start behiouving unusually.
   3) You are Adviced to use only Options that are showing on the display, program will not accept any other input.
   4) When searching, use exact words to gain expected output, using non-exact words will lead to failure in search. It is also advised that before searching or checking-out a customer, see the exact keywords of Name before, from the "Room Details" Section.

-----------------------------------------------------------------------------------------------------------------------
Features:
	
Here are some features you can use in program.
The user can:
* Book Multiple Rooms at once, and save of their data.
* See how many Un-Occupied Rooms are available in your Hotel.
* See the Details of All the Occupied Room's Customer.
* Modify the Customer's Details.
* Change the fare rate of each category.
* Increase or Decrease the No. of Room of each category.
* Search for one specific Customer.
* Make the customer check-out, at any time.
* See the Information about features of each category's room.
* See the Credits (Developing Team and Core Purpose.).
* Exit the program at any time, with its own free will.

----------------------------------------------------------------------------------------------------------------------
Built With:

1. C++ Language (Compiler: TDM-GCC 4.9.2).
2. Dev C++ (version: 4.9.9.2).

---------------------------------------------------------------------------------------------------------------------
Credits:

Developed by:
	1. Saif-ur-Rehman Awan (Senior Developer and team leader).
	2. Abdul Moiz (Teammate).
	3. Humza Zaheer (Co-leader).
	4. Fahad Hussain (Teammate).

Special Thanks to:
   1. Mr. Shakeel Ahmed (PF Professor).
   2. International Islamic University, Islamabad (IIUI).

This Project is a part of Programming Fundamentals (PF) Assignment no 3.
Under the supervision of Mr. Shakeel Ahmed, Department of SE, IIUI.
Dated: 28-05-2024, Tuesday.

----------------------------------------------------------------------------------------------------------------------
Disclaimer:

	This is a basic system just made for educational purposes and might not encompass all functionalities of a comprehensive hotel management system.

----------------------------------------------------------------------------------------------------------------------
Copy-Rights:

	All rights are reserved. No part of this program shall be copied, sell or use for any type of personal or commercial use without written permission of the developers. Incase of voilence, legal actions could be taken against the user.

----------------------------------------------------------------------------------------------------------------------
Support:

	If you encounter any issues or have questions about using our Hotel Reservation System, please contact our support team at:

Saif-ur-Rehman Awan.
saif.bsse4778@student.iiu.edu.pk 
	
Humza Zaheer.
humza.bsse4803@student.iiu.edu.pk

We're here to help!

-------------------------------------------------------------------------------------------------------------------------

Thank you for using our Hotel Reservation System!

=============================================================
		The End
=============================================================
