# Web-Design-Challenge
## Background

Data is more powerful when we share it with others! Let's use what we've learned about HTML and CSS to create a dashboard featuring the analysis that we've done, as captured in the following image:

![Landing page](https://user-images.githubusercontent.com/100891182/181826113-bb8df3e2-a5bf-41a2-a2b9-9b8413165a35.jpeg)


## Instructions 

For this homework assignment, we'll create a website by using visualizations that were created in your Python-APIs homework, or you can use the [weather data](Resources/cities.csv) provided.

As you build this dashboard, you'll create individual pages for each plot and a way to navigate between them. These pages will contain the visualizations and des. You will also build a landing page to provide a comparison of all the plots, along with another page to present the data used to build them.

### Website Requirements


The website consistS of seven pages in total, including:

* A [landing page](#landing-page) containing the following elements:

  * An explanation of the project

  * Links to each visualizations page. There should be a sidebar containing preview images of each plot. Clicking an image should take the user to that visualization.

* Four [visualization pages](#visualization-pages), stored in the `visualizations` folder, each with the following elements:

  * A descriptive title and heading tag.

  * The plot or visualization for the selected comparison (latitude vs: max temperature, humidity, cloudiness, or wind speed). The images displayed on these pages should be stored in the `assets/images` folder.

  * A paragraph describing the plot and its significance.

* A ["Comparisons" page](#comparisons-page) that does the following:

  * Contains all of the visualizations on the same page so they can easily be compared with each other.

  * Uses a Bootstrap grid for the visualizations.

    * The grid must be two visualizations across medium and large screens, and it must be one visualization across on extra-small or small screens.

* A ["Data" page](#data-page) that displays a responsive table containing the data used in the visualizations.

  * The table must be a Bootstrap table component. Refer to the [Bootstrap documentation](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables) for how to use responsive tables. 

  * The data must come from exporting the `.csv` file as HTML or by converting it to HTML. Try using a tool that you already know: Pandas. Pandas has a method, appropriately called `to_html`, that allows you to generate an HTML table from a Pandas DataFrame. To learn more, review the [documentation](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html).

At the top of every page, the website must have a navigation menu with the following elements:

* It should have the name of the site on the left of the navigation bar, allowing users to return to the landing page from any page.

* It should contain a dropdown menu on the right of the navigation bar, named "Plots," to provide links to each individual visualization page.

* It should provide two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.

* It should be responsive (using media queries). The navigation bar must be similar to the screenshots in the ["Navigation Menu" section](#navigation-menu) (notice the background color change).


### Considerations

* You may use the weather data you collected for the WeatherPy section of your Python-APIs Homework, or you may use the included [cities dataset](Resources/cities.csv) and pull the images from the [assets folder](Resources/assets).

* You must use Bootstrap. This includes using the Bootstrap `navbar` component for the header on every page, the Bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.

* You must deploy your website to GitHub Pages, with the website working on a live, publicly accessible URL as a result.

* Make sure to use a CSS media query that uses Bootstrap and/or `@media` for the navigation bar.

* Make sure that your website works at all window widths or sizes.

* Feel free to take some liberty in the visual aspects, but keep the  core functionality the same.



This section contains screenshots of each page that must be built, at varying screen widths. These are intended as a guide; you can meet the requirements without having the pages match the following images exactly.

![Landing page](https://user-images.githubusercontent.com/100891182/181826193-3e8fa02f-8b6a-400f-a5ea-6dd71896b4ec.jpeg)



￼

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

