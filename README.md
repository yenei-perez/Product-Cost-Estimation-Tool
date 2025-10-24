# Product-Cost-Estimation-Tool
This Python program simulates a cost estimation tool for a fiber optic cable installation company. 
It calculates the total installation cost for a customer based on the number of feet of fiber optic cable required, 
applying tiered discounts depending on the quantity ordered.


What It Does:

Prompts the user for their company name and the length of fiber optic cable needed.
Applies a discounted price per foot according to the total length ordered:

$0.87 per foot for up to 100 feet

$0.80 per foot for orders over 100 feet

$0.70 per foot for orders over 250 feet

$0.50 per foot for orders over 500 feet

Calculates the total installation cost using the appropriate rate.
Displays a formatted receipt showing the company name, cable length, price per foot, and total cost.



How It Works:

The program defines price tiers as variables and uses an 
if-elif-else control structure to determine which pricing level applies based on the user's input. 
The calculation is then performed by multiplying the cable length by the corresponding price per foot. 
Finally, the results are printed in a simple, readable receipt format.




