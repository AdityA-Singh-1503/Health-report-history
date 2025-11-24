# HEALTH REPORT HISTORY
A Python command-line interface (CLI) application for calculating core health metrics-BMI, BMR, and TDEE and tracking progress over time using data visualization.

<h2>METRIC CALCULATION:</h2>

Calculate three essential health metrics body mass index (BMI), basal matabolic rate (BMR), total daily energy expenditure (TDEE) based on your input like weight, height, age, gender and activity level.

1) Body mass index (BMI) : It calculates body fat based on person's height and weight.

       BMI = WEIGHT (Kg) / HEIGHT (m) X HEIGHT (m)
   
   Classification: The classify_bmi function uses standard health ranges to categorize the result.

   &#8226; < 18.5$: underweight
   
   &#8226; 18.5-24.9: normal

   &#8226; 25.0-29.0: overweight

   &#8226; $\geq 30.0$: obese

2) Basal matabolic rate (BMR) : It is the minimumm number of calories required by your b0ody to function properly.

   Calculation: Widely accepted Miffin-St Jeor equation is used for more accurate solution.
   
       For Men: BMR=(10 X weight in Kg) + (6.25 X height in cm) - (5 X age in years) + 5

       For women: BMR=(10 X weight in Kg) + (6.25 X height in cm) - (5 X age in years) - 161
   
3) Total daily energy expenditure (TDEE) : it is the total number of calories a person burns to maintain his/her weight.

        TDEE = BMR X Activity multiplier
   
  Activity Multipliers: it uses standard multipliers based on the user selected activity level.

  <img width="789" height="318" alt="image" src="https://github.com/user-attachments/assets/070fee9a-6e45-4c27-a6a5-74160724bc31" />


<h2>DATA PERSISTENCE:</h2>
Every entery (weight, height, age, BMI, BMR, TDEE) is stored in the file named health_history.csv.

<h2>REAL TIME VISUALIZATION:</h2>
Uses matplotlib to generate and display 2 graphs which show

1) A bar chart of this session's BMI, BMR and TDEE
2) A line chart which shows the trend of BMI and TDEE over all historical entries.

<h2>USER FRIENDLY CLI:</h2> 
It is easy to use and provides clear input prompts. It also handles basic validaions for a smooth user experience.

<h2>PRESEQUITIES</h2>
You need to have python 3.x installed on you computer and also libraries like

1) matplotlib: For displaying graphs
2) csv, sys and os: Which are standard libraries and are included with python

<h2>OUTPUT</h2>
The data which is inputed is represented as:
<img width="1160" height="598" alt="image" src="https://github.com/user-attachments/assets/2b946de8-29c9-43f3-a777-c73b7dac69ca" />

<h2>GRAPHS</h2>
The graphs are presented as:
<img width="1032" height="837" alt="Screenshot 2025-11-24 235728" src="https://github.com/user-attachments/assets/d65daad4-df65-4f43-a816-43dbaf4f1b0e" />
<img width="1184" height="835" alt="Screenshot 2025-11-24 235925" src="https://github.com/user-attachments/assets/226f99cb-b678-43fd-8821-61b2173b9a23" />







