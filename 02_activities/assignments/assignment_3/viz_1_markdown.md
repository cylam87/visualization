The dataset is https://data.ontario.ca/dataset/bumble-bee-diversity-and-abundance-survey 

1. What software did you use to create your data visualization?
Python

2. Who is your intended audience? 
Scientists, government officials and members of the general public who are 
interested in year-to-year trends in bee abundance across Ontario. 

3. What information or message are you trying to convey with your visualization? 
The abundance of these bee species across counties in Ontario. Counties along 
the Thames river (Essex, Middlesex, Oxford) have especially high abundances.

4. What aspects of design did you consider when making your visualization? How 
did you apply them? With what elements of your plots? 
I made sure the map had a clean layout (simple land vs water coloring) and used
geometric shapes to represent bee abundances. 
I used absolute scales for both the axes (latitude and longitude) and colormap
(bee abundance) to minimize cognitive load. 

5. How did you ensure that your data visualizations are reproducible? If the 
tool you used to make your data visualization is not reproducible, how will this 
impact your data visualization? 
I included all code used for data processing and making the visualization. I 
also included many comments to ensure the code can be easily understood. 
    
6. How did you ensure that your data visualization is accessible?  
I represented bee abundance with both circle color and size for redundancy. 
I used viridis color scheme for the color map for accessible viewing. 
I made sure the background map was simple (few details, dim colors) so that 
viewers could focus on the abundance data. 
Unfortunately Basemap doesn't appear to support the addition of figure captions.
The plot title is informative and uses the accessible Helvetica font. 
    
7. Who are the individuals and communities who might be impacted by your visualization?  
Those who care about bee abundances and distributions in Ontario. For example, 
bee farmers and government officials from the Ministry of Agriculture could 
glean useful information on trends in bee abundance across the province (e.g. 
higher abundance along the Thames river). This may drive decisions and policies, 
e.g. study what factors cause the Thames river to be a bee-friendly environment, 
and apply those factors in other counties hoping to increase bee populations.

8. How did you choose which features of your chosen dataset to include or exclude from your visualization? 
I aggregated total bee numbers across all species rather than display each 
species separately. I did so as plotting abundances of all 14 species separately
for all counties would overwhelm viewers, especially due to the spatial nature 
of the visualization.

9. What ‘underwater labour’ contributed to your final data visualization product?
Government staff collected bee samples in the field. 

