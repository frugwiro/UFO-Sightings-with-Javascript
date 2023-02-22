# UFOs

## Project Overview

This project focuses on building a dynamic webpage that accepts user inputs and adjusts accordingly to display information about UFO sightings.
In order to perform their analysis, users will be able to filter the UFO sightings table based on multiple criteria such as the event date, city, state, country and shape.

## Resources
  * Data Source: (https://github.com/frugwiro/UFOs/blob/main/data.js)
  * Software: HTML/CSS, JavaScript, Visual Studio Code 1.49.1, BootStrap 4.0.0
  
## Results
  
### Search Criteria Procedure
  
#### Index page
  
This is the initial page. The user can re-initialize the page by clicking on the navbar at the top.
![]<img width="545" alt="Screen Shot 2023-02-22 at 03 40 59" src="https://user-images.githubusercontent.com/78386151/220570980-21a5edea-4e78-44ce-984a-04e1c159bc99.png">
  
#### Filtering by event date
![]<img width="945" alt="Screen Shot 2023-02-22 at 03 41 42" src="https://user-images.githubusercontent.com/78386151/220571176-7e1a660c-ce81-44a2-8770-d4265c03129e.png">

#### Filtering by city
The user enters the desired city, the change is detected and the table is updated accordingly.
![]<img width="943" alt="Screen Shot 2023-02-22 at 03 42 06" src="https://user-images.githubusercontent.com/78386151/220571474-79b63627-101f-4f32-ac14-1c652e9bdb1b.png">

#### Filtering by country
The user enters the desired country, the change is detected and the table is updated accordingly.
![]<img width="926" alt="Screen Shot 2023-02-22 at 03 42 29" src="https://user-images.githubusercontent.com/78386151/220571645-39ae8407-2952-4fc9-aa88-359f39405412.png">

#### Filtering by state and shape
The user enters the desired state and shape observed, the changes are detected and the table is updated accordingly.
![]<img width="945" alt="Screen Shot 2023-02-22 at 03 42 52" src="https://user-images.githubusercontent.com/78386151/220571838-61f3977d-a42c-42c1-b920-3cfffbb07b46.png">

All filter parameters can be entered simultaneously.

## Summary

  * One drawback of this design is the difficulty for the user to know what parameter to use for the filtering. For example to pick a city, the user would have to go through the table a find the city desired for the analysis.
  * A way to address this would be to present drop-down lists including all filter values in place of the input fields.Each list would need to update after a parameter is selected in any filter.
  * Including a button to clear the filters is also needed. The button would be located below the last filter.
