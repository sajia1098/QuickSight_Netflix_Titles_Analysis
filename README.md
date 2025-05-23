<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Visualize data with QuickSight

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-analytics-quicksight)

**Author:** Amna Sajid  
**Email:** amnasajiddd@gmail.com

---

![Image](http://learn.nextwork.org/radiant_amber_brave_peafowl/uploads/aws-analytics-quicksight_6c7f7ef0)

---

## Introducing Today's Project!

Amazon QuickSight enables you to easily analyze data and create visualizations. Today we're going to explore a huge dataset of Netflix shows and movies to create a dashboard that extracts all the juicy insights. 

### Tools and concepts

Services I used were S3 and QuickSights. Key concepts I learnt include creating S3 buckets for the datasets and making visualizations such as bar graphs, pie charts etc. to analyze the datasets. 

### Project reflection

This project took me approximately 2 hours. The most challenging part was making the graphs for the first time without the help of the guide. It was most rewarding to see the final visualizations and learn how to use QuickSight for data analysis. 

After this project, I plan to work on stock market data to analyze stock market patterns. I will start this project after finishing the beginner projects. 

---

## Upload project files into S3

S3 is used in this project to store two files, which are manifest.json (which tells the quicksight about the structure and format of the data) and a CSV file. These files contain the data needed for the creation of a quicksight dashboard. 

I edited the manifest.json file by adding the S3 URL. It’s important to edit this file because it tells the manifest.json the location of the data set file. If we didn't update this file the quicksight will not know the location of the dataset. 

![Image](http://learn.nextwork.org/radiant_amber_brave_peafowl/uploads/aws-analytics-quicksight_3c3cd85a)

---

## Create QuickSight account

Creating a QuickSight account cost $0 for first 30 days

Creating an account took me about 10 min. 

![Image](http://learn.nextwork.org/radiant_amber_brave_peafowl/uploads/aws-analytics-quicksight_f4ab4214)

---

## Download the Dataset

I connected the S3 bucket to QuickSight by visiting the "Datasets" page and clicking "Add dataset". Then i clicked on S3 and selected the bucket i wanted to connect with. 

Manifest.json tells QuickSight what your dataset looks like, so QuickSight knows how to understand the data and show it in charts or graphs. Without this map, QuickSight might get confused a

![Image](http://learn.nextwork.org/radiant_amber_brave_peafowl/uploads/aws-analytics-quicksight_6f874996)

---

## My first visualization

To create visualizations on QuickSight, I clicked on data fields e.g. release years. QuickSight will automatically generate a graph that suits that type of data. 

The chart shown here provides a breakdown of the number of movies versus TV shows for each year. It is grouped by "type". 

I created this graph by dragging and dropping "release_year" into the "Y Axis" and dragging "type" into the "Group/Color" field. 

![Image](http://learn.nextwork.org/radiant_amber_brave_peafowl/uploads/aws-analytics-quicksight_aff3aad7)

---

## Using filters

Filters are useful for analyzing data in a more focused manner. Users can tailor the visualizations according to their needs. 

This visualization is a breakdown of movies and TV shows. Here I added a filter by stacking movies and TV shows in the same row, so you can visualize the % of each.

![Image](http://learn.nextwork.org/radiant_amber_brave_peafowl/uploads/aws-analytics-quicksight_c32248c5)

---

## Setting up a dashboard

As a finishing touch, I added descriptive titles to the graphs. This will help the viewer understand them at a glance. 

Did you know you could export your dashboard as PDFs too? I did this by clicking the export button at the top right of my screen and downloading the PDF file directly to my computer. 

![Image](http://learn.nextwork.org/radiant_amber_brave_peafowl/uploads/aws-analytics-quicksight_6c7f7ef0)

---

## Refreshing source data

---

---
