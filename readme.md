# meters to feet/inches
Write a program similar to the previous exercise (Lab 19.3), but now converts from meters into feet and inches. Create and use these functions for the subtasks:
- one for getting input from keyboard
- one for calculating (3 parameters, 2 of which are reference parameters)
- one for displaying result

There are 0.3048 meters in a foot and 12 inches in a foot. Here is example code to do the conversion:
```
double dfeet;
dfeet = meters / METERS_PER_FOOT;
feet = int( dfeet );
inches = (dfeet - feet)*INCHES_PER_FOOT;
```

Optional:
Include a loop that lets the user repeat this computation for new input values until the user says they want to end the program. 