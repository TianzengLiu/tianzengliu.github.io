# Punnett-Square
i. Explain your design decisions

My design decisions followed the instructions of the Design elements:(​https://xd.adobe.com/spec/72ec9d6e-332d-4c4a-6e51-635e283255ee-04dd/)
1. I put a navigation bar on the top and added the content;

2. I separated the "container" under the navigation bar into two columns,
left column is 8(put the Punnett-Square ) and right column is 4(put the Chart).

3. In the left column, I separated three sub-columns which are for the three 
left-pea squares, left-pea squares' children, top-pea three squares + result square.

4. I put three rows in the third sub-column, which are the top-pea three squares, 
their children and the result square.

5. I put the Chart(Phenotypic Ratio) and Genotypic Ratio in the right column.


ii. Explain your development decisions

Layout: I decided to use Bootstrap for the main layout becasue Bootstrap is easy to make 
responsive layout and developed faster than write from ground up.

Functionalities: I chose Javascript and jQuery to manipulate the DOM. When click the top-pea 
squares(parent), we triggered an event to catch the "text" in the top-pea 
squares and separated them into two individuals(child) and updated the children on top of result 
square, same as the left-pea squares(parent). I put two "span" attached to each other in each one of 
the result square, that make the child keep updated in the "span" once we click the parents. Finally,
we get the results in each one of the result square.

In addition, we need keep the Chart(Phenotypic Ratio) and Genotypic Ratio updated every time we
generate the result square.


iii. Explain areas for future improvement

1. I will add the yellow svg and green svg and keep them updated when we generate the results. 
Since only "yy" gives us green svg so I will write a function to decide conditionally by using "if...else"
(if (var varible === "yy") green, else yellow).

2. I will update the color and ratio in the chart according the results we generate from the result
square. The function should keep track the number of "yy"(green), we can set up a "count" varible, the sum is always 4, 
"4-count" will be the numbers of yellow. Also, I will add three "div" to update the ratio and keep it updated. The function
should have three varibles to store "YY", "Yy", "yy", and count each one of the occurances and update
them according the children from the result square.



iv. Add anything else you think is important

1. Since this project shows students the Law of Segregation of genes (the "First Law"), we can add advanced
interactive of Law of Independent Assortment (the "Second Law") and Law of Dominance (the "Third Law"). In order to show students the different aspects of gene inheritance. 

2. For the very beginners among the students we can add "?" tooltips to guide them to read more concepts in this interactive.

3. We also can add "input" to let students try their own thoughts and do experiments dynamically by themselves,
to cultivate and inspire their creative thoughts.

4. We can add quiz to have students to test their knowledge learning from this project to increase their interest
and confidence.

