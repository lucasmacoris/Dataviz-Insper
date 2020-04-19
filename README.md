# Dataviz-Insper


This folder relates the lectures for the Data Analysis and Visualization track of the undergraduate program **Insper - Institute of Research**. This track consists of 5 lectures for the first-year undergraduate students of the Management/Economics courses that aims to provide the students with the basic analysis toolkit that can be used **outside of Microsoft Excel** scope.

The purpose of this document is to introduce, in an very simple way way, a **data analysis format complementary to Excel**, in the sense that groups that are interested in improving the work of PHC will be able to take advantage of the codes used here for the calculation descriptive statistics and graphical visualizations. ^[This material was developed for use as a complementary content for the Microeconomics course in the undergraduate courses in Administration and Economics at **Insper - Instituto de Ensino e Pesquisa**. For more information, contact those responsible through lucassm4@al.insper.edu.br or felipegt1@al.insper.edu.br.]

The course is structured in three lectures, where we analyze a single dataset - with minor adjustments- and explore the basics of data-visualization (*data-viz*) using R programming language. For that, we organize the project in a three-lecture

1. Basic Dataviz techniques on R, including a somewhat simple, but comprehensive guide to the base R commands;
2. Bivariate Data analysis and visualization using `ggplot2` and other packages; 
3. Multivariate data analysis and visualization using `ggplot2` and other packages;

All lectures are held in **portuguese**. However, the markdown files are organized in an intuitive way in a sense that we expected that replication of the code can be interpreted in a straigtforward manner.

## About the dataset - NYC Restaurants

We will analyze a set of data present in Sheather (2009)^[Sheather, Simon. A modern approach to regression with R. Springer Science & Business Media, 2009.] which contains information about a series of Italian restaurants in Manhattan that opened in 2001 (some of which are now closed). This data is used througout the lectures and has some minor adjustments, such as the inclusion of manually-defined variables, in order to accomodate all concepts that should be covered.  

Data is collected through the *Zagat Survey*, a guide to restaurants and entertainment in the main North American cities, with emphasis on New York City, created and published from 1979 by Tim and Nina Zagat. The guide is based on an opinion poll conducted through a survey conducted with New York restaurant customers.

The rating system is based on a 25-point scale, covering aspects such as the quality of the food, the decoration and atmosphere of the establishment, the service and the price. The variables present in the database are:


* `Restaurant`: restaurant name
* `Price`: price of a basic meal (food + drink); 
* `Food`: average rating on *Zagat Survey* for food quality;
* `Decor`: average rating on *Zagat Survey* for decoration quality;
* `Serviço`: average rating on *Zagat Survey* for service quality;
* `East`: binary variable, presenting `1` if the restaurant lies in East Manhattan, and `0` otherwise.





