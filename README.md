# COVID-19-Health-Records

Introduction:

- Discrete mathematics is a field that explores mathematical structures fundamentally characterized by their discreteness, as opposed to the continuous nature of real numbers. While real numbers vary smoothly, objects in discrete mathematics, such as integers, graphs, and logical statements, possess distinct, separated values.

- In the project, you can leverage discrete mathematics to address three crucial divisions. Despite the rapid surge of the coronavirus pandemic, which has made obtaining specific data challenging, there are various global resources providing graphs and approximate data. These resources have enabled to develop our analyses with the assistance of diverse tools.

- Our process begins by converting the provided resource into an Excel file. Subsequently, a Python code is employed to calculate the daily count of new cases, utilizing inputs such as current test results, recoveries, and fatalities.

- Moving beyond the initial division, i.e. calculate present cases, the next step is to delve into more intricate analyses. Using the Excel sheet, we shall conduct various data manipulations, including generating graphs and performing complex calculations. This data is then imported into SQL, where we shall apply a range of functions to yield precise and explicit outcomes.

- Given the urgency of the pandemic's spread and the need to optimize hospital resources, there is another critical aspect to be tackled. This involves creating schedules for doctors and nurses, ensuring efficient patient care. These schedules are meticulously crafted with specific shifts and duties, allowing to monitor and enhance the overall work efficiency of medical staff, thus maximizing patient recovery rates.

Throughout this project, numerous libraries are levereged, with extensive coding, and statistical analyses, then, fine-tuned data, and provided practical solutions to enhance the efficiency of hospital operations during these challenging times.

Discussion:

- Dataset: data.md
- Division-One: div1.md
- Division-Two: div2.md
- Division-Three: div3.md

Observations:

A brief of Discrete Mathematics that is observed in the Project are as follows: 

- Basic Combinatorics: The Rule of Sum

  - A very simplest rule in combinatorics, the rule of sum. In the rule of sum, you 
have k objects of the first type, and we have n objects of the second type. The 
rule of sum tells us that we have n plus k objects in total.

- Set Theory:
Set theory is a branch of mathematical logic that studies sets, which informally 
are collections of objects.

  - Union: of the sets A and B, denoted A ∪ B, is the set of all objects that are a 
member of A, or B, or both. The union of {1, 2, 3} and {2, 3, 4} is the set {1, 
2, 3, 4}.
  - Intersection: of the sets A and B, denoted A ∩ B, is the set of all objects that are 
members of both A and B. The intersection of {1, 2, 3} and {2, 3, 4} is the 
set {2, 3}.
  - Set difference: of U and A, denoted U \ A, is the set of all members of U that 
are not members of A. The set difference {1, 2, 3} \ {2, 3, 4} is {1}, while, 
conversely, the set difference {2, 3, 4} \ {1, 2, 3} is {4}.
  - Cartesian product: of A and B, denoted A × B, is the set whose members are all 
possible ordered pairs (a, b) where a is a member of A and b is a member of B. 
The cartesian product of {1, 2} and {red, white} is {(1, red), (1, white), (2, 
red), (2, white)}.
- Graph Theory: Graph Colouring
In a vertex colouring each vertex is marked by a colour which is taken from a 
finite set of possible colours. A colouring is called proper if endpoints of any 
edge or adjacent vertices are coloured by different colours. So here we see an 
example of a graph which is properly three coloured. The graph is called 
Peterson graph, it's just the proper name. we schedule on the basis of colour 
differentiation.

Thus, the concepts of Discrete mathematics are covered for the given use case.

