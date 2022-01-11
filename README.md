# ros-programming-fixes-solutions

1. Dockerfile for ros, if you use catkin_make and it repeatedly gives error 'catkin_make' not found. 
Use CMD for catkin_make instead of RUN
FIX was given here: https://stackoverflow.com/questions/55941916/unable-to-execute-catkin-commands-using-run-in-dockerfile

