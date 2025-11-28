# OPTIMIZATION-MODEL

*COMPANY: CODTECH IT SOLUTION

*NAME: SHAIK SOHAIL

*INTERN ID: CT04DR1947

*DOMAIN: DATA SCIENCE

*DURATION: 4 WEEKS

*MENTOR: NEELA SANTHOSH

#Optimization Model, where the objective was to solve a real-world business problem using mathematical optimization techniques. Optimization is one of the core areas in data science and operations research, used to find the best possible decision under constraints. The purpose of this task is to demonstrate how linear programming can be applied to maximize profit, minimize cost, or optimize resources using Python’s powerful optimization library PuLP.

This task showcases a practical implementation of Linear Programming (LP) to determine the ideal production quantities of multiple products given machine limitations. The model is fully implemented and tested using Google Colab, which provides a cloud-based Python environment without requiring any local setup. Google Colab also supports PuLP out of the box after installation, making it perfect for experimentation and fast development.

Task Objective
To understand and apply optimization techniques in Python.
To use Linear Programming (LP) to solve a business-based production problem.
To use the PuLP library to define decision variables, constraints, and objective functions.
To solve the optimization problem programmatically and interpret results.
To generate insights into how optimization models help organizations improve efficiency and profit.

Tools & Technologies Used
Platform Used
Google Colab Notebook (cloud-based, browser accessible)
Zero installation required, easy to execute and share
Programming Language
Python 3 (pre-installed in Colab)
Python Libraries
PuLP – for Linear Programming and optimization
NumPy – optional numerical support
Matplotlib – optional visualization tools
Google Drive Integration (optional for saving files)

Where This Model Can Be Applied (Real-World Applications)

Optimization models are used everywhere in industry. This same logic is used in:
1. Manufacturing Optimization
Companies decide how many units to produce to maximize profit with limited machine hours.
2. Transportation & Logistics
Determining shortest routes, fuel optimization, vehicle scheduling.
3. Supply Chain & Inventory Management
Finding the ideal stock levels to minimize storage cost while meeting demand.
4. Workforce Scheduling
Assigning employees to shifts while meeting labor laws and capacity.
5. Portfolio Optimization in Finance
Balancing risk vs return in investments.
6. Resource Allocation
Distributing limited resources (machines, manpower, budget) for maximum efficiency.
7. Marketing Budget Optimization
How to divide budget across campaigns for maximum impact.

This task replicates a simplified version of the same decision-making logic used in billion-dollar companies.

Project Structure (Google Colab Version)
Since this task is performed on Google Colab, the structure is notebook-based:

optimization_model_task4
│
├── task4_optimization.ipynb     # Main Google Colab notebook
│
├── README.md                    # Complete documentation
│
└── output/
    ├── solution_printout.txt    # Optimization results (optional)
    └── screenshots/             # Graphs / results (optional)


If desired, additional files (plots or exports) can be stored in /content/drive/MyDrive/ through Google Drive.

Problem Explanation
In this project, a company manufactures two products, A and B.
Each product requires a fixed number of machine hours.
The company has two machines, and each machine has limited operating hours.

Goal:
Maximize the total profit by choosing optimal quantities of Product A and Product B.

Decision Variables:
A → Units of Product A to produce
B → Units of Product B to produce

Objective Function:

Maximize Profit:
30A + 20B

Constraints:

Machine 1 capacity:
2A + B ≤ 40

Machine 2 capacity:
A + 2B ≤ 45

Both variables must be ≥ 0.
These constraints reflect real manufacturing limits — similar to factories, labs, and industrial production units.
Results from Optimization Model

After solving using PuLP, the optimal solution is:

Status: Optimal
Product A = 15.0
Product B = 15.0
Maximum Profit = 750.0

Interpretation:
The company should produce 15 units of Product A
And 15 units of Product B
To achieve maximum possible profit: 750
This solution uses all available machine resources efficiently.

Running the Code in Google Colab (Steps)
1. Install PuLP
!pip install pulp
2. Run the optimization model
Paste the provided code into a Colab cell and run it. Output appears below the cell.
3. View results
Colab prints the optimal values directly, which can be exported or screenshotted for submission.

Conclusion
This Optimization Model project successfully demonstrates how mathematical programming and Python can be used to solve business-level decision problems. Through the PuLP library, we were able to build a clear objective function, apply realistic constraints, and compute the most profitable production strategy. The solution shows how organizations use similar optimization models to allocate limited resources, reduce operational costs, and improve profitability.

Completing this task on Google Colab also highlights the ease of using cloud-based platforms for data science, eliminating dependency issues and enabling fast execution. Overall, this project reflects strong analytical, mathematical, and practical skills in optimization — a valuable component of any data science or business analytics workflow.

#OUTPUT

