The existed methods for solving VRP and its variants can be roughly divided into three categories:
- Exact algorithms
- Heuristics (including constructive, improvement and metaheuristics)
- Machine learning

All three approaches are still active and new works are carried out every year. 

In order to have a brief overview, they are arranged as a sequence according to the timeline as follows:


![image](https://user-images.githubusercontent.com/40708416/114839048-e6425a80-9e07-11eb-9360-b8f81f094991.png)



There are some supplementary remarks:
- Heuristics appears as early as the VRP problem
- Exact algorithms gain popularity for half a century and still one of the best approaches.
- With the growing of the size of the problem, heuristics (very often with local search) is usually more efficient.
- Machine learning is a hotspot in recent years.

and following is one way to understand the relationship between different methods:

- Generally, there are two objectives: minimize the budget and the gap to optimal.
- Different categories (exact algorithms, population-based heuristic, local search) emphasize on different areas in this objective space.
- Red lines are generations of the capacity of state-of-the-art methods, it moves towards lower left  corner. 
- In the future, there may be a mixed of different methods with ML as a driver.

![Capture](https://user-images.githubusercontent.com/40708416/114838463-52708e80-9e07-11eb-9854-13990f48348f.PNG)
