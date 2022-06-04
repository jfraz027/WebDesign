# WebDesign
For this project, a website was created using visualizations that were developed in a Python-APIs analysis using the provided cities.csv.

In building the dashboard, create individual pages for each plot and a way to navigate between them. These pages contain the visualizations. There is also a landing page to provide a comparison of all the plots, along with another page to present the data used to build them.

### Website Requirements

The website must consist of seven pages in total, including:

![image](https://user-images.githubusercontent.com/99145651/171969143-7210aa6f-b8a7-4533-bd83-c19b0580a126.png)

* Containing the following elements:

  * An explanation of the project

  * Links to each visualizations page with a sidebar containing preview images of each plot. Clicking an image takes the user to that visualization.

* Four pages
 
 ![image](https://user-images.githubusercontent.com/99145651/171969282-0564209c-d5a0-429d-8c56-20e19db41aaf.png)
 ![image](https://user-images.githubusercontent.com/99145651/171969301-bfefcfcc-26c9-4dda-9c56-7dc1645556e1.png)
 ![image](https://user-images.githubusercontent.com/99145651/171969313-15210064-6d07-4670-91bd-aec78bdb5f8f.png)
 ![image](https://user-images.githubusercontent.com/99145651/171969326-9947eb7e-8091-46e3-a8bc-9e0a84ea06f5.png)

 * A descriptive title and heading tag.

  * The plot or visualization for the selected comparison (latitude vs: max temperature, humidity, cloudiness, or wind speed). 

  * A paragraph describing the plot and its significance.
 
  ![image](https://user-images.githubusercontent.com/99145651/171969243-e3ab4cb2-00d1-4222-818b-3a848f99127c.png)
 

* A ["Comparisons" page](#comparisons-page) that does the following:

  * Contains all of the visualizations on the same page so they can easily be compared with each other.

  * Uses a Bootstrap grid for the visualizations.

    * The grid must be two visualizations across medium and large screens, and it must be one visualization across on extra-small or small screens.

![image](https://user-images.githubusercontent.com/99145651/171969851-5c58c335-600a-453c-80b2-64a744a16486.png)


* A ["Data" page](#data-page) that displays a responsive table containing the data used in the visualizations.

  * The table must be a Bootstrap table component. 

  * The data must come from exporting the `.csv` file as HTML or by converting it to HTML. 


![image](https://user-images.githubusercontent.com/99145651/171969890-3bbb4c40-5ad1-48d6-b84f-011134a706b2.png)


At the top of every page, the website must have a navigation menu with the following elements:

* Name of the site on the left of the navigation bar to return to the landing page from any page.

* Dropdown menu on the right of the navigation bar, named "Plots," to provide links to each individual visualization page.

* Text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.

* Be responsive (using media queries). 

![image](https://user-images.githubusercontent.com/99145651/171969914-fe5ad463-4c8b-4998-ab99-918a042b9ef7.png)


### Considerations

* Use Bootstrap and include
* Bootstrap `navbar` component for the header on every page, 
* Bootstrap table component for the data page, 
* Bootstrap grid for responsiveness on the comparison page.
* Bootstrap and/or `@media` for the navigation bar.

* Website works at all window widths or sizes.

### Screenshots

This section contains screenshots of each page that must be built, at varying screen widths. 

#### <a id="landing-page"></a>Landing page

Large screen:

![image](https://user-images.githubusercontent.com/99145651/171970082-df8202ce-5ab3-4196-9f02-2dcd0494ec17.png)


Small screen:

![image](https://user-images.githubusercontent.com/99145651/171970116-0aa54bbb-ecf3-41ed-ab05-453d358d2757.png)

￼

#### <a id="comparisons-page"></a>Comparisons page

Large screen:

![image](https://user-images.githubusercontent.com/99145651/171970179-647d1a34-f861-4774-9918-87a953ec598c.png)


Small screen:

![image](https://user-images.githubusercontent.com/99145651/171970212-4af1c231-2d69-4289-a358-77c6353c422b.png)


#### <a id="data-page"></a>Data page

Large screen:

![image](https://user-images.githubusercontent.com/99145651/171970273-1f0fe3c8-45f3-4383-afeb-af0042942754.png)



Small screen:

![image](https://user-images.githubusercontent.com/99145651/171970327-ce719e88-173d-4061-a6a8-8ecd2037a320.png)


#### <a id="visualization-pages"></a>Visualization pages

You'll build four of these, one for each visualization. Here's an example of one visualization page on two different screen sizes:

Large screen:

![visualize page large screen](Images/visualize-lg.png)

Small screen:

![image](https://user-images.githubusercontent.com/99145651/171970434-1a3ff9a7-e3f3-4fd0-acd4-650faea20986.png)


#### <a id="navigation-menu"></a>Navigation menu

Large screen:

![nav menu large screen](Images/nav-lg.png)

Small screen:

![image](https://user-images.githubusercontent.com/99145651/171970478-04b5b1e7-900c-4cf3-b49f-fd5e7f10cff2.png)
