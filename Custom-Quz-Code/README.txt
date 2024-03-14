Code functionality
    -The provided code is designed for personality quizzes with X amount of questions, each with
    the SAME amount of answer options (e.g. 4 options). Each option corresponds to a reuslt which will be
    shown at the end of the quiz as well as a lead capture system which provides the users with an option to enter 
    their name and email address to have the results sent to their email

    -The code is designed to integrate into Webflow
Instructions
    1. Edit the questions object to have your questions
        -If you need to add/delete answer options, do so but make sure
        the number of answer options match in each questions and the number of results
        match the number of answer options
    2. Edit the results object to have your results. Only edit the text inside the 
    Archetype property, DO NOT CHANGE Archetype property name
    3. Create a collection for your results on Webflow. 
        -Place a collection list on the page and ensure to wrap the contents of
         the collection item with a div which you will give an inside    
            -Make the ID a field from the which matches the name of the Archetype in the
            results object
    4. Add a div on Webflow at the top called "quiz-wrapper" which will hold the quiz 
    5. Add another div called "email-wrapper" to capture leads and design that how you would like 
    just make sure to have the following elements:
        -Add a form block which has a text-link with class name "skip-link" 
        -Add a submit button with class name "quiz-email-btn"
    6. Paste the questions and result object in a <script> tag on the <head> section
    of your page's custom code section. Paste everything with the <style> tag in there too
    7. Paste everything after the results object in another <script> tag on the code before the <body>
    tag in Webflow on the custom code section of the page's settings
