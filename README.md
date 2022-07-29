# Web-Design-Challenge
## Background

Data is more powerful when we share it with others! Let's use what we've learned about HTML and CSS to create a dashboard featuring the analysis that we've done, as captured in the following image:

![Landing page](https://user-images.githubusercontent.com/100891182/181826113-bb8df3e2-a5bf-41a2-a2b9-9b8413165a35.jpeg)


## Problems:

We'll create a website by using visualizations that were created in your Python-APIs.

Create individual pages for each plot and a way to navigate between them. These pages will contain the visualizations and des. Build a landing page to provide a comparison of all the plots, along with another page to present the data used to build them.

### Website Requirements

The website consistS of seven pages in total, including:

* A [landing page](#landing-page) containing the following elements:

  * An explanation of the project

  * Links to each visualizations page. 

* Four [visualization pages](#visualization-pages), stored in the `visualizations` folder, each with the following elements:

  * A descriptive title and heading tag.

  * The plot or visualization for the selected comparison (latitude vs: max temperature, humidity, cloudiness, or wind speed). The images displayed on these pages should be stored in the `assets/images` folder.

  * A paragraph describing the plot and its significance.

![Temperature](https://user-images.githubusercontent.com/100891182/181826951-bada7460-a387-4f00-aaf3-99e2bdfa0188.jpeg)

![Humidity](https://user-images.githubusercontent.com/100891182/181827049-a4605f62-1f78-41c8-a73c-6c29a3b03108.jpeg)


![Windspeed](https://user-images.githubusercontent.com/100891182/181827082-2913d45e-89be-4074-8973-c940c14982a0.jpeg)





* A ["Comparisons" page](#comparisons-page) that does the following:

  * Contains all of the visualizations on the same page so they can easily be compared with each other.
  * 
![Comparision](https://user-images.githubusercontent.com/100891182/181827017-0a9935f3-7d5a-4f49-a7e6-4bd9759a9278.jpeg)

   
   
   
* A ["Data" page](#data-page) that displays a responsive table containing the data used in the visualizations.

  * The table must be a Bootstrap table component. Refer to the [Bootstrap documentation](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables) for how to use responsive tables. 

  * The data must come from exporting the `.csv` file as HTML or by converting it to HTML. Try using a tool that you already know: Pandas. Pandas has a method, appropriately called `to_html`, that allows you to generate an HTML table from a Pandas DataFrame. To learn more, review the [documentation](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html).

At the top of every page, the website must have a navigation menu with the following elements:

* It should have the name of the site on the left of the navigation bar, allowing users to return to the landing page from any page.

* It should contain a dropdown menu on the right of the navigation bar, named "Plots," to provide links to each individual visualization page.

* It should provide two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.

* It should be responsive (using media queries). The navigation bar must be similar to the screenshots in the ["Navigation Menu" section](#navigation-menu) (notice the background color change).

#### <a id="comparisons-page"></a>Comparisons page

Large screen:

![Comparision](https://user-images.githubusercontent.com/100891182/181826285-7acb33ff-e64d-4fbf-8b76-898d73dcf083.jpeg)



#### <a id="data-page"></a>Data page

Large screen:

![Data](https://user-images.githubusercontent.com/100891182/181826340-1dd9dc74-cc84-493e-bb6c-2827a15c6280.jpeg)




## References

OpenWeatherMap.org. (2012). Сurrent weather and forecast. Retrieved from [https://openweathermap.org/](https://openweathermap.org/)

- - -

© 2022 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.

