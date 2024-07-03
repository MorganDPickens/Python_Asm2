# Python_Asm2
# HW2: Interior Design

---

### Policy of Due Dates

If you need additional time to complete this assignment, please contact me before the due date. **No excuses or extensions will be accepted after the due date.** You are allowed up to two extensions: the first extension grants an additional two days, and the second extension grants one extra day. After these two extensions, no further extensions will be permitted, and you must submit whatever work you have completed.

---

### Grading Policy for Uncovered Topics

Avoid incorporating advanced topics or functions that haven't been covered in our studies. The use of uncovered/unfamiliar topics or functions like ChatGPT answers may result in a deduction of points.

---

You are working for an interior design company and they need you to design software for them. Specifically, for a rectangular room they need a program to determine and display:

- Total area on the walls and ceiling (for paint)
- Total area on the floor for flooring
- Total room volume for fans and lighting
- Total length along the perimeter for trim (the total amount includes both at the floor and the ceiling)
- Total cost for paint and total cost for flooring

Some things to note:

- When calculating the area for paint, subtract 10% from the total *wall* area to account for windows.
- One gallon of paint covers 350 square feet.
- The program should only recommend whole numbers of paint cans (for example, not 3.2 paint cans, but 4 paint cans. 3 paint cans would not be enough). Similarly, no decimal values for the amount of flooring needed. Round up to the next whole number.
- All the units are in feet (or square feet or cubic feet)

---

## User Interface

### INPUT

After a user introduction, the program prompts the user for: 

- the length, width and height of the room. Make sure that the units of input are clear to the user.
- the price for a one-gallon can of paint
- the price per square foot of flooring

### OUTPUT

After the user finishes entering above information, the program will print:

- The user input
- The final results and costs
    - total area of walls and ceiling (adjusted for windows)
    - volume of the space
    - length of trim needed
    - amount of paint needed and the cost
    - amount of flooring needed and the cost
    - total material costs

Here is a sample output. Feel free to follow this design or create your own. Note, the numbers here are ***incorrect***. As the programmer, you must come up with your own test cases (see below).

```html
Given:
    length = 10 ft
    width = 15 ft
    height = 12 ft
    unit price for paint = $12.99
    unit price for flooring = $3.49

The results are:
    total area = 123 sq ft
    volume = 1 cu ft
    trim = 2.9 ft
    cans of paint needed = 2
    total cost of paint = $2.99
    flooring needed = 3.3 sq ft
    total cost for flooring = $1.01

Total costs = $0.01
```

Make sure to include units in the final display. Format dollar amounts to 2 decimal places.

---

## **Code Specifications**

- Your python filename should be “yourLastNameHW2.py”. For an example, my last name is “suk” so my filename should be “sukHW2.py”.
- This program, and all solutions this quarter, should start with a simple user introduction.
- Do not hide your work. In other words, do not do calculations outside the program and then use the results inside the program. All of the calculations needed to produce results should be visible and clear within your code.

## **Comments & Style**

- Include **header** comments at the top of the file that has your name, date, and a brief description of the program. The description should be 1 to 2 lines long describing the purpose of the program. Assume that the person reading your program has not seen this homework page.
- Include **comments** for each section: input, process, output. An example might be: **# get room dimensions from user**
- Include **blank lines** to separate the main sections of the code
- Use descriptive **variable names.**
- Use a **named constant** for the one value noted in the description section above. See the sales price example.

For this and all homework, make sure to follow the Comment Description and Documentation Standards Guide**,** found on the class website.

---

## **Suggestions**

I recommend doing this in stages. First just try to get the input and display them. Then focus on 1 calculation at a time, and display that result. Make sure to test your program's calculated results against hand-calculated results to make sure your program is correct.

---

## **Testing**

Test your program to make sure everything works.

- Develop several test cases, where you calculate the correct results by hand. These are known as the ***expected results***. Then confirm that the program's ***actual results*** match these.
- Test a few error cases with strange input and see what happens. Realize at this stage you’re not equipped to solve all problems you’d like to; keep notes about what you’d like to do once you learn more.
- Remember that testing is not just about calculations; the user interface needs testing as well. For example, is it easy for a user to read? One good way to test the user interface is for a friend to try your program.
- Document your testing and results in a comment at the bottom of your file (part 2 of your report below). This includes describing the test cases you used and the results you obtained. **NOTE** - copying and pasting the output of your program is not considered documenting your test cases. See the posted examples in week 2 as a style guide.

---

## **Written Report**

At the bottom of your program file, add a comment that answers these questions. Remember full credit is based on the thoughtfulness put into your answers, as well as proper capitalization, spelling, etc.

1. How did you go about starting this assignment? During development, where did you get stuck, if at all, and how did you get unstuck?
2. How did you test your program? Include two test cases (the inputs and the expected results). What doesn't work as you'd like, such as features you'd like to fix as you learn more?
3. What did you learn from this assignment? What would you do differently next time?

## Grading

The following table shows the rubric of grading HW 2. 

| Criteria | Rating | Point |
| --- | --- | --- |
| Program runs correctly | Introduction : 1 pt
Prompt for inputs : 3 pt
Output with story with user’s inputs : 2 pt
Calculation of flooring and paint : 3 pt
Display is within the size of the shell : 1 pt | 10 pt |
| Input and Output with units | Input with prompt : 1 pt
Output with user’s input : 1 pt | 2 pt |
| Comments and Style | 5 pt : Completed
2 pt : Basic comments
0 pt : No comments on your program | 5 pt |
| Written Report/Reflection | 3 pt : Completed
1 pt : At least, 1~2 sentences
0 pt : No written report | 3 pt |
| On-Time Submission | 50% reduction after the due date | 0 pt |
