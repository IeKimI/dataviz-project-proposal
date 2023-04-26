# Data Visualization Project

## Data

The data I propose to visualize for my project is MoMA Artwork Collection from https://github.com/MuseumofModernArt/collection. 
I love going to art museums, and I always found it difficult to see what types of artworks museums have. I would love to create visualizations that would help visitors filter artworks by the medium used, department, period, etc to provide an easier way to find what they are looking for/interested in when visiting museums.

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Which mediums were used the most?
 * How did the use of medium change over time?
 * What is the percentage of each department category (Photography, Drawing, Painting, etc)?
 * What is the percentage of artworks classified as ... (Print, Design, Architecture, Book, etc)?
 * How many artworks are there from this particular artist?
 

## Sketches

![image](https://user-images.githubusercontent.com/59063929/219982038-36a3f517-0bc3-4490-a9d2-5571e7faa8ff.png)

This is the first sketch of ideas I had for this project. The categorical columns such as classification or department are displayed in pie chart. For visualizations that are meant to display the frequency or count, I decided to sketch them in a histogram/bar chart format. Lastly, to display artworks by time, I thought it would be helpful to display it in a timeline format. The goal is to make these visualizations interactive. For example, when a user clicks on a bar, update or filter other graphs depending on user input/interest. This way, it would be easier for users to understand the data better since it can display a lot of data in a clean and organized manner and make the visualization more engaging.


![image](https://user-images.githubusercontent.com/59063929/219982074-68414419-fcbe-456e-82a8-4e88089cc458.png)

This is the iterated design. I modified two visualizations from the previous sketch. The first is a stacked bar. I think this shows how the medium changed over time as well as which medium was most popular at a certain period. This can be done for other category types such as classification, department, etc. The second idea is to assign different colors or sizes for each category.


## Prototypes

I’ve created a proof of concept visualization of this data. 

![image](https://user-images.githubusercontent.com/59063929/219912741-5291a67d-87e6-4432-a514-cd42bbb8019f.png)
(https://vizhub.com/IeKimI/fe22591fde004f0191b1e44c4acc1b9a)

Using the top 10 most used mediums, I created a stacked bar chart for the first 20 dates (years) available in the dataset. As shown in the label on top, each color represents a different medium.

![image](https://user-images.githubusercontent.com/59063929/219981952-a264fd04-bd5f-4e10-a335-0ab323a952f1.png)
(https://vizhub.com/IeKimI/094ee16f51e3488496fcfd6ee85cd7df)

I decided to change my stacked bar chart to a streamgraph for the iteration. Streamgraphs are often used to show changes in different categories over time when there are many categories and when they start and stop at different times. I decided to use this graph because the purpose of this visualization is to show the trend and patterns of changes in the medium used in artworks over time. I think this graph type shows the trend better as it gives a nice flow of each category/medium.
