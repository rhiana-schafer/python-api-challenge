# python-api-challenge - How to plan the ideal vacation
![VacationHeatMap](https://user-images.githubusercontent.com/66378414/163219371-a4b0a9b8-0d09-40b9-a6c1-c9ae3c7bdee8.PNG)

The above image shows the perfect cities, with indicated lodging options, for my personal weather taste.

Here's how I got there:

First, I pulled a random sample of cities all over the world, and conducted an analysis on various weather trends: I found that cities closer to the equator had higher temperatures, but there weren't very strong indications of other weather patterns. (in depth analysis can be found alongside code in file "WeatherPy")

![NorthLatVWind](https://user-images.githubusercontent.com/66378414/163219429-6a6d31dc-3d20-4150-9504-cda3657c4813.png)
![SouthLatVCloud](https://user-images.githubusercontent.com/66378414/163219432-791c8225-3fe7-4eac-8143-d50b2fdd55a3.png)
![SouthLatVHumid](https://user-images.githubusercontent.com/66378414/163219433-d99ac1ba-baab-46e4-b159-714a90626d7f.png)
![SouthLatVTemp](https://user-images.githubusercontent.com/66378414/163219434-fc0b923d-e0eb-41dc-af95-19cf2a799beb.png)
![SouthLatVWind](https://user-images.githubusercontent.com/66378414/163219435-ed706d10-57ec-4fe8-b955-dd100372e863.png)
![NorthLatVCloud](https://user-images.githubusercontent.com/66378414/163219445-c23406d9-9154-48ce-8ad3-6fdf19bd6033.png)
![NorthLatVHumid](https://user-images.githubusercontent.com/66378414/163219447-7f0f087e-b9ca-463a-b728-c83832fc08df.png)
![NorthLatVTemp](https://user-images.githubusercontent.com/66378414/163219448-b31b42d0-75d6-4c9b-ae7f-d3fc1cec4398.png)

Next, with code in VacationPy, I narrowed down my dataset to include only places with my perfect weather - between 70 and 80 degrees, 30-60% humidity, and low wind speeds (under 10mph). I was left with a short list of beautiful towns. A quick reference to the google maps API, and I had a place to stay! Wish me a bon voyage, and I'll see you for the next project. 
