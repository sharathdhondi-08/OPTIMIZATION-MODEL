#  OPTIMIZATION-MODEL
COMPANY : CODTECH IT SOLUTIONS
NAME : Sharath Dhondi
INTERN ID : CT04DA212
DOMAIN : Data Science
DURATION : 4 weeks 
MENTOR : NEELA SANTOSH

#Description:

This project addresses a real-world business problem faced by a mid-sized bakery: how to maximize profit given limited resources such as flour, sugar, eggs, and butter. 
Using a dataset of 5,000 product entries (bakery_products_5000.csv), each representing a batch of a bakery item (Cake, Muffin, Cookie, Donut, Bread, or Pastry) 
with slightly varied ingredient requirements and profit margins, we aim to determine the optimal number of units of each product to manufacture. 
To make the problem manageable and realistic, the dataset is grouped by product type, and average values are used to represent standardized recipes. 
The business objective is to decide the most profitable product mix without exceeding the available quantities of raw materials. 
Linear Programming (LP) is applied to this problem, and the Python library PuLP is used to construct and solve the optimization model. 
Decision variables represent how many units of each product the bakery should make, the objective function is to maximize total profit, 
and constraints ensure resource usage does not exceed available stock. The LP model is solved under the assumption that products must be produced in whole units (integer constraints), 
reflecting practical manufacturing limitations.

The results of the optimization provide a clear and actionable production plan that highlights which products should be prioritized based on their profit-to-resource ratios. 
For example, high-profit but resource-intensive products may be deprioritized if their production would deplete scarce ingredients, while more resource-efficient products may be favored. 
The output includes the optimal number of units for each product, the expected maximum profit, and the exact usage of each resource, ensuring that nothing exceeds its available quantity. 
This approach not only maximizes profit but also minimizes waste and improves operational efficiency. Moreover, the model is highly flexible—it can be extended to include additional constraints
 such as labor hours, machine capacity, or even fluctuating ingredient prices. This project demonstrates how optimization techniques like Linear Programming can empower small and medium businesses 
 to make smarter, data-driven decisions that directly impact their bottom line, all with the help of simple Python tools like PuLP and pandas. It showcases the practical value of combining operations 
 research with programming to solve real-world business problems efficiently and effectively.



#output : ![Image](https://github.com/user-attachments/assets/af0450f1-bf32-41a1-995c-0c5fff19227c)
