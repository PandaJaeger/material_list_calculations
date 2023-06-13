# material_list_calculations
First paper for the IT-course at Bauhaus-University

Problem formulation:

For a building made up of any number of components, the concrete volume and the total volume can be determined. 
When calculating the reinforcement of the components it's volume shall be taken into account and subtracted from the concrete volume.
Also the amount of steel per component type and the total amount of steel are to be determined. 
In addition, the total costs for the materials used are calculated based on freely selectable prices.
A program is to be implemented that reads the component attributes from a text file, and outputs all calculated values in the console as text.
The text file consists of Values separated with semicolons for the number of the component,
the component type, the reinforcement of the component (𝐴𝑆 in [cm2] or 𝐴𝑆,𝑥 in [cm2/m]), 
the length L of the component in [m], the width B in [m], the height H in [m] and the diameter D in [m] (depending on the component types).
{ComponentNumber ; Type ; As/As,x ; lengh ; width ; height ; diameter}

