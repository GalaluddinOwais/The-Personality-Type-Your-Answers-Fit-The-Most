# About the project
This project aims to determine the user's personality type (Myers-Briggs Type Indicator) given their answers to a set of questions. This is achieved through statistical calculations using previously surveyed answers from individuals who were certain about their personality type

# Key Achievements
* Implemented the calculation of the probability of a set of chosen answers to be related to a certain personality type. It is performed by determining the percentage of presence of one chosen answer among the surveyed answers for the same question, surveyed from people with that certain personality type. This process is repeated for all the chosen answers, then the average percentage is taken as the probability of being related to that certain personality type. This calculation is performed for each of the 16 personality types
* Built a simple web application that takes the user through a series of questions and compares their answers to previously surveyed answers for each personality type to calculate how similar their answers are to each of them and finally display the results
* Published the web application and received overwhelmingly positive feedback from the users, who ensured the effectiveness of the method 


# Requirements
 Web server environment `XAMPP`
 
 `PHP` (XAMPP provides PHP)
 
 Web browser

# Execution
* Install a web server environment if not already installed

* Locate the document root folder in the web server folders

  ("htdocs" for XAMPP)

* Attach the folder with the php code files ("source") to the document root folder

* Launch the local web server

  (Open XAMPP control panel ➔ Click on "Start" for Apache module) 

* Access the running application through the web browser

  ("http://localhost/source/index.php")

# Run!

www.mbtialikeanswers.epizy.com


# Additional Notes
#### Despite the statistical calculations, the application was implemented in mere HTML and PHP, so it is runnable on a free domain. However, one of the drawbacks of the application is that the implementation does not follow the best practice about moving from one question to another, as it navigates to a different page as it moves to a next question.

#### After the probability calculation method in this project proved successful, it inspired the introduction of [Alphabet Presence Probability Scanner](https://github.com/GalaluddinOwais/Alphabet-Presence-Probability-Scanner) project, which ensured the accuracy of the method
