# Reusables

Reusable code snippets and templates.

- css
- cp 
- rest api
- tests

## Conventions usually followed

**1. Modularity**
- Data or inputs or models are defined in a separate class or module.
- Problems or computations required on the data are broken into sub-problems.
- Each subproblem has it's own controller or handler.
- Each handler calls a service. Services are nothing but operations on data.

**2. Variable and function naming**
- Functions and variables that will be exported to other packages or files are in PascalCase
- Local or internal functions and variables are in camelCase
- Unused variables and functions are named _ or start with _ 

**3. Problem Approach**
Each problem has the following approach / hierarchical order of analysis.
- Requirements
- Research
- Plan / Layout / Design
- Write
- Review
- Release