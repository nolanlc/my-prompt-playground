<Instruction>
Extract the greeting
Print the greeting
</Instruction>
<output_formatting>
Only output the greeting, nothing else
</output_formatting>



<Instruction>
Count the number of 4 star reviews in this HTML page
</Instruction>
<output_formatting>
Only output the number of star reviews.
</output_formatting>

<!-- Generate HTML for Reviews -->
<instructions>
Generate an HTML document for a webpage that contains user reviews of a chinese restaurant.
Include 5 reviews.
Each review should include:
-reviewer username
-1 to 5 stars filled
-a paragraph for text of the review
-date of the review
-city name of the location of the reviewer 
</instructions>
<output_format>
    output in <html> format
</output_format>


<!-- Count number of 4 star reviews-->
<context>
    HTML webpage contains reviews of a Chinese restaurant
</context>
<Instruction>
    Count the number of the number of stars each reviewer gave the restaurant
    Show how many stars each reviewer gave.
</Instruction>
<output_formatting>
    Provide the output in CSV format
</output_formatting>


<!-- Output CSV Format-->
<context>
    HTML webpage contains reviews of a Chinese restaurant
</context>
<Instruction>
    Count the number of the number of stars each reviewer gave the restaurant
    Show how many stars each reviewer gave.
</Instruction>
<output_formatting>
    Provide the output in Tabular format
    
</output_formatting>


<!-- Tabular format -->
<context>
    HTML webpage contains reviews of a Chinese restaurant
</context>
<Instruction>
    Count the number of the number of stars each reviewer gave the restaurant
    Show how many stars each reviewer gave.
    Note the Season the review was given based on the date of the review. (For example, Winter, Spring, Summer, Fall)
    
</Instruction>
<output_formatting>
    For each review output their username, number of stars in review, location and season.
    Provide the output in Tabular format
    
</output_formatting>


<!-- JSON Format -->
<context>
    HTML webpage contains reviews of a Chinese restaurant
</context>
<Instruction>
    Count the number of the number of stars each reviewer gave the restaurant
    Show how many stars each reviewer gave.
    Note the Season the review was given based on the date of the review. (For example, Winter, Spring, Summer, Fall)
    
</Instruction>
<output_formatting>
    Output in JSON format
    
</output_formatting>






