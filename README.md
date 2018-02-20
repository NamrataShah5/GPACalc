# GPACalc
The purpose of this project was to build a versatile GPA calculator for college students. UC Santa Cruz doesn’t have its own, official GPA calculator. 

So far, the project has two different calculators. 

In one, the student can enter their current GPA, the GPA they would like to have, how many units they’ve already taken, how many units they will take in the future, and in how many quarters they want to raise their GPA. Our methods should read the user form data to calculate what GPA they need to raise their GPA. 

In the second one, the student can enter everything current GPA, GPA they want, how many units they have, and what GPA they need to raise their GPA. We will use the user form data to calculate how many units they need to take in order to raise their GPA. 

We did this by first creating forms on HTML. We used Brackets to help us start building the website. The next step was reading in the data from the forms submitted by users. We created two separate functions in JavaScript, each one would initiate after the click of the submit button, calculating the result based on the formula used. Additional base case checks are performed, such as whether the fields entered are valid (e.g. GPA isn’t greater than 4.0). After that, we output the result out to the HTML page, and the function returns false so that the page doesn’t refresh after every time the user hits the “submit” button. 

We would like to increase functionality of this website by having class and professor ratings (in terms of difficulty, course load, etc.), as well as a list of internship opportunities for all majors.
