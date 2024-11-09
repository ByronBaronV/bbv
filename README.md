# Python Final Project 2024
## Student Name: [Byron Baron]
## Project Title: [Montreal Local Artists Music]

This repository contains my final project for the Python course.
- `proposal.md`: Project proposal
- `project_exploration.ipynb`: Jupyter notebook for project exploration and prototyping

Python Project Assessment Guide requests:
1. As core architecture, to implement an application web with:
   1.1. Python back-end using Flask or Django
   1.2. SQLite database integration
   1.3. Web-based front-end

2. Technical Requirements & Assessment Criteria:
   2.1. Core Development, to evaluate how well your project is constructed overall:
- Does it work as a complete, polished product?
- Is the code well-organized and maintainable?
- Would another developer understand how your project is structured?
   2.2. Debugger Usage. I will need to demonstrate:
- Setting and using breakpoints in PyCharm
- Inspecting variables during runtime execution
- Step-through debugging of a meaningful interaction (e.g., route handling, data processing)

3. Debugging Strategies (3 marks)
   3.1. Include at least two (2) print statements in any of the following key areas:
- Before and after database operations (e.g., print(f"Inserting record: {data}"))
- When routes/endpoints are hit (e.g., print(f"POST /api/users with data: {request.json}"))
- When key functions are called with their parameters (e.g., print(f"calculate_total called with items: {items}"))
- Before returning results (e.g., print(f"Returning result: {result}"))
- When errors occur (e.g., print(f"Error in process_data: {str(e)}"))
   3.2. Solution Documentation
The project will have a solutions.md file in my project repository documenting one significant issue encountered.

4. Backup Strategy
The project must be uploaded to GitHub, preferably in a subfolder of your existing python-final-project-2024 repository.

5. Access Rights
You only need to complete ONE of the following options:
   a. Add your professor or a fellow student as a GitHub collaborator with read access.
   b. Introduce a Python class into your program that demonstrates access control using private attributes with underscore prefix ("_")
   c. Implement a custom access control feature in your application

6. Security - Firewall
For web applications:
- Demonstrate port blocking/unblocking using your system's firewall
- Show how it prevents client-server communication when the port is blocked
- See the Firewall-Port-Blocking-Guide.pdf guide on Omnivox for how to do this


Assessment Meeting Checklist
Project core functionality is complete
One issue is documented in SOLUTIONS.md
Code is pushed to GitHub
Required security features are implemented
Added a peer collaborator (if choosing this option)
Print statements are added in key areas
All product demonstrations have been tested
