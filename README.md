# datasci_4_web_viz

# Challenges with Shiny R

The biggest challenge of this assignment was trying to deploy the shiny app code onto shinyapps.io. I followed the instructions in the link that was attached to the corresponding section in the assignment. I was able to configure rsconnect using method 2 : ```rsconnect::setAccountInfo(name="<ACCOUNT>", token="<TOKEN>", secret="<SECRET>")```. Then, I copied the code from the cdc.r file in the WK4 folder and adjusted the code accordingly based on the type of data that I wanted to display and explore. I was able to successfuly deploy it in the IDE. After, I was able to successfuly create a shinyapps.io account by using method 2: ```rsconnect add --account <ACCOUNT> --name <NAME> --token <TOKEN> --secret <SECRET>```. I ended up getting stuck on step 2.2.2.2. I tried using the code provided: ```rsconnect deploy shiny /path/to/app --name <NAME> --title my-app``` , but I got an error message saying that ```/path/to/app``` did not exist. Alyssa and I worked together to try out new code to see if it would work like: ```rsconnect shiny . --title "My Shiny App``` and ```rsconnect shiny ." However, both of those codes still didn't work. 
## Photo of Shiny R Error
![image](https://github.com/jesschannn/datasci_4_web_viz/assets/123782059/b5bf4c7a-0eb2-4b5c-a0b5-ac844c2b0372)

## Photo of Shiny R Output
![image](https://github.com/jesschannn/datasci_4_web_viz/assets/123782059/79effa0d-a26b-45b3-8925-a978a6a7fd14)

# Challenges with Python's Shiny

Compared to figuring out Shiny R, working with Python's Shiny was not as difficult. The only issue that I really faced was that when I was able to see the bar chart, I realized that the y-axis limit needed to be increased becauset the data I had went beyond 30. Reading through the given code, I found the line that I needed to edit, which was like line 41. I think that Python Shiny gave me the least trouble compared to the other two.

## Photo of Python Shiny Output
![image](https://github.com/jesschannn/datasci_4_web_viz/assets/123782059/3297fa79-04e0-48df-9400-5afb01986bae)

# Challenges with Python Flask

One challenge that I faced with Python Flask was forgetting to add a templates folder with an index.html file. When I didn't have the templates folder with the index.html file, I kept seeing an error that there was no template found for index.html. After a couple minutes, I realized what I forgot to do and then everything was running fine after.

## Photo of Python Flask Output
![image](https://github.com/jesschannn/datasci_4_web_viz/assets/123782059/2101cf8e-f81b-4af4-8d31-41655fcc22ff)
