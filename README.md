<!DOCTYPE html>
<html>
<head>
/* <meta name="viewport" content="width=device-width, initial-scale=1"> */
<style>
body {font-family: Arial, Helvetica, sans-serif;}
 
/* Style the Image Used to Trigger the Modal */
#myImg {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

#myImg:hover {opacity: 0.7;}

/* The Modal (background) */
.modal {
  display: none; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  padding-top: 100px; /* Location of the box */
  left: 0;
  top: 0;
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  overflow: auto; /* Enable scroll if needed */
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0,0.9); /* Black w/ opacity */
}

/* Modal Content (Image) */
.modal-content {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
}

/* Caption of Modal Image (Image Text) - Same Width as the Image */
#caption {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
  text-align: center;
  color: #ccc;
  padding: 10px 0;
  height: 150px;
}

/* Add Animation - Zoom in the Modal */
.modal-content, #caption {
  animation-name: zoom;
  animation-duration: 0.6s;
}

@keyframes zoom {
  from {transform:scale(0)}
  to {transform:scale(1)}
}

/* The Close Button */
.close {
  position: absolute;
  top: 15px;
  right: 35px;
  color: #f1f1f1;
  font-size: 40px;
  font-weight: bold;
  transition: 0.3s;
}

.close:hover,
.close:focus {
  color: #bbb;
  text-decoration: none;
  cursor: pointer;
}

/* 100% Image Width on Smaller Screens */
@media only screen and (max-width: 700px){
  .modal-content {
    width: 100%;
  }
} 
</style>
</head>
<body>




# Senior Data Scientist - Insights Manager - BI and Analytics Lead
I'm Huw. I transform complex data into meaningful stories that drive real-world impact. With seven years of experience, I've learned that the most powerful insights emerge when curiosity meets creativity. My approach goes beyond technical skills—I'm an interdisciplinary thinker who listens deeply and bridges diverse perspectives to craft solutions that genuinely solve my clients' most pressing challenges.

Data isn't just numbers to me; it's a tool for understanding and creating positive change. I'm driven by a belief that analytics can be a force for empowerment and equity, breaking down barriers and illuminating new possibilities. Whether I'm untangling a complex problem or collaborating with a team, I bring intellectual rigor and genuine human connection to every project.

My professional mission is simple: to use data as a lens for understanding the world more clearly and making it work better for everyone.


<br>

## Technical skills

Python/Pandas  -  Google Cloud Platform -  Machine learning  -  Data visualisation  -  Statistics and forecasting  -  Tableau  -  PowerBI  -  Alteryx  -  SQL

<br>

## Education and training
<ul>
 <li>Micromaster program in Statistics and Data Science - current</li>
 <li>PhD, Humanities research, King's College London - 2008-14</li>
 <li>BA(Hons)/BMus(Hons), the University of Melbourne. First class honours, faculty prize for BA(Hons) - 2001-06</li>
</ul>


<ul>
 <li>Mathematics for Machine Learning, Imperial College London, 2024</li>
 <li>Data Science with Python, University of Michigan, 2024</li>
 <li>Professional Data Engineer, Google Cloud Platform, 2023</li>
 <li>ODSC Machine Learning Certification, AI+ Training, 2022</li>
 <li>Machine Learning, Stanford University (Coursera), 2019</li>
</ul>
<br>
 
## Work Experience
<b>Senior Data and Insights Analyst</b>, the University of Oxford (2017-2025)
<br>Analytics and reporting lead for Marketing and Insights team. Provided bespoke business intelligence service to bring modern data science tools and frameworks to strategic decision making. Developed statistical analysis and forecasting models to help define and segment audiences for 80+ successful campaigns. Promoted in 2018 to manage insights team and later digital marketing team (2021-22). Chaired the development and alumni engagement data governance group (2021-22).

<br>


## Projects

### Earnings or environment: an exploration of the relationship between wellbeing, access to nature and earnings across London's boroughs 
##### <i>Data visualisation using Geopandas and Matplotlib</i>
In this project, I explore and visualise the relationship between wellbeing, greenspace and earnings across different parts of London. I ask:

- Is there a link, for Londoners, between wellbeing and access to nature?
- Does being a high earner feature in the relationship between these variables?

I draw on two datasets, from the Office of National Statistics (ONS), which record various wellbeing and wealth metrics across each of London's boroughs. I link these with Ordnance Survey data charting the extent of green and blue spaces - the city’s parks, gardens, trees, green spaces, rivers and wetlands, and features such as green roofs.

<img id="myImg" src="assets/Earnings%20or%20Environment.png" alt="Three maps of London highlighting boroughs with, respectively, the highest concentration of green and blue spaces, the median score out of ten given in response to the survey question, 'To what extent do you feel the things you do in your life are worthwhile?', and average weekly earnings." style="width:100%;max-width:600px">
<div id="myModal" class="modal">
 <span class="close">&times;</span>
 <img class="modal-content" id="img01">
 <div id="caption"></div>
</div> 
<a href="https://github.com/huwhallam/portfolio/blob/main/assets/Earnings%20or%20environment.ipynb">View full Earnings and environment Jupyter notebook</a>

<br>
<br>

### Record temperatures: is London's weather is becoming more volatile?
##### <i>Data visualisation using Matplotlib</i>
This data visualisation explores how London's weather is changing. I show the many instances in 2024 when daily minima and maxima air temperature exceeded the lowest and highest temperatures for that day recorded in the preceding decade. 

<img src="assets/London%20record%20air%20temperatures.png" alt="A chart showing the minima and maxima air temperature in London for each calendar day as recorded across 2014-2023, as well as the 84 maxima and minima recorded in 2024 that exceed those previously recorded.">
<a href="https://github.com/huwhallam/portfolio/blob/main/assets/London%20record%20temperatures.ipynb">View full London record temperatures Jupyter notebook</a>

<br>
<br>

### Neural network from scratch
This project creates a neural network from scratch using Numpy. The purpose was to help me fully understand the mathematics of neural networks and how to translate it into code without recourse to ML libraries. (A subsequent project will construct a more elaborate convolutional neural network using Pytorch.)

<img src="assets/Neural%20network%20diagram.png" alt="Diagram of a neural network containing two inputs, a single hidden layer with three neurons, and one output.">
<a href="https://github.com/huwhallam/portfolio/blob/main/assets/Neural%20network%20from%20scratch.ipynb">View full Neural network from scratch Jupyter notebook</a>

<br>
<br>

## Data Structures and Algorithms
I'm currently upskilling on DSA. I'll be sharing my notes here.
<ol>
 <li><a href="https://github.com/huwhallam/portfolio/blob/main/dsa/Dynamic%20Arrays.ipynb">Dynamic Arrays</a> </li>
 <li><a href="https://github.com/huwhallam/portfolio/blob/main/dsa/String%20Manipulation.ipynb">String Manipulation</a> </li>
 <li><a href="https://github.com/huwhallam/portfolio/blob/main/dsa/Two%20Pointers.ipynb">Two Pointers</a> </li>
 <li><a href="https://github.com/huwhallam/portfolio/blob/main/dsa/Grids%20and%20Matrices.ipynb">Grids and Matrices</a> </li>
 <li><a href="https://github.com/huwhallam/portfolio/blob/main/dsa/Binary%20Search.ipynb">Binary Search</a> </li>
 <li><a href="https://github.com/huwhallam/portfolio/blob/main/dsa/Sets%20and%20Maps.ipynb">Sets and Maps</a> </li>
 <li><a href="https://github.com/huwhallam/portfolio/blob/main/dsa/Sorting.ipynb">Sorting</a> </li>
 <li><a href="https://github.com/huwhallam/portfolio/blob/main/dsa/Stacks%20and%20queues.ipynb">Stacks and Queues</a> </li>
 <li><a href="https://github.com/huwhallam/portfolio/blob/main/dsa/Recursion.ipynb">Recursion</a> </li>
 <li><a href="https://github.com/huwhallam/portfolio/blob/main/dsa/Linked%20lists.ipynb">Linked Lists</a> </li>
</ol>
