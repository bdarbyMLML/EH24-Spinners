# Team Spinners

## Vorticity Budget Closure

In this project we seek to close the vorticity budget for ECCOv4r5. 

| Name | Personal goals | Can help with | Role |
| ------------- | ------------- | ------------- | ------------- |
| Basil Darby | I want to learn how to better work with global ECCO data  | I can help python and working in curvilinear coordinates | Project Lead |
| Fernando Eder Campos Gonzales | ... | ... | Project Lead |
| Jonathan Aparco Lara | ... | ... | Project Lead |

### The problem

The main problem when calculating the global vorticity budgets is the differences on the face edges which lead to non-closure of the budget (all terms dont go to zero).

## Methods

Use updated derivative method that deals with face edges on previous vorticity budget tutorial.

### Data

ECCOv4r5 data


### Additional resources or background reading

Vorticity budget equation can be found here: https://journals.ametsoc.org/view/journals/phoc/49/11/jpo-d-19-0111.1.xml

Calculating derivatives on grid faces can be found here: https://ecco-v4-python-tutorial.readthedocs.io/ECCO_v4_Gradient_calc_on_native_grid.html


## Project Results

We successfully calculated three of the five terms of our vorticity budget equation. Graphs and code can be found here: [notebooks](notebooks/).
