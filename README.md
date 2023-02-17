# simple-grade-tracker
by HeadStart Development
A simple weighted grade calculator with a save function to help users keep track of their overall class grade throughout a semester.


OverView:

This simple software allows users to add, update, save and delete records of classes and assignments in order to track the overall grade for a class, considering the weight of an assignment. Over the semester add in grades to each class, giving your grade for the assignment and the weight of that assignment and simple-grade-tracker will calculate your weighted grade and add it to your total for that class. These details are saved between sessions allowing the user to keep track over the whole semester.

To Start:
- Add a class
- Add an assignment, enter the grade you got for that assignment and the weight of that assignment as a percentage (often listed as "30% of your overall grade") 
- Click "Calc/Save" NOTE: Your total will not update and the values will not be saved if you dont click "Calc/Save"

Features:
- Saved using XML files for speedy and efficient saving
- Delete any assignment or class NOTE: deleting a class deletes all its associated assignments forever so be sure
- Clear any assignment to start again

Limitations / Not Yet Implemented:
- It is possible to enter more assignment weight than 100% of a class, so pay attention to those weights

If you encounter any issues or bugs please email headstartdevelopment@gmail.com

Acknowledgements:
Written in C++ using the Walnut ImGui wrapper from The Cherno. You can find details on this excellent system here: 
https://github.com/TheCherno/Walnut
and watch a Youtube video on the topic here:
https://www.youtube.com/watch?v=5zS-DZhCA2g&ab_channel=TheCherno
Uses tinyxml an excellent xml parsing library
