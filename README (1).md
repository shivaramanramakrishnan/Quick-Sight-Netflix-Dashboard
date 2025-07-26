<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Visualize data with QuickSight

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-analytics-quicksight)

**Author:** SHIVARAMAN RAMAKRISHNAN  
**Email:** shivaraman.r02@gmail.com

---

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-analytics-quicksight_6c7f7ef0)

---

## Introducing Today's Project!

In this project, I will demonstrate data analytics using quicksight paired up with a database out of AWS

### Tools and concepts

Services I used were S3 and Quicksight. Key concepts I learnt include the way datasets work across platforms in AWS, the way they are linked and how visualizations are to be generated for any sort of business requirement.

### Project reflection

This project took me approximately an hour to 90 mins. The most challenging part was figuring out what sort of visualization helps us analyse the data better.

After this project, I plan to work on a different dataset to see what sort of new challenges can be faced

---

## Upload project files into S3

S3 is used in this project to store two files, which are manifest.json for the structure of the data we are uploading and the netflix_titles csv files, which is the dat we are here to analyse.   

I edited the manifest.json file by updating the S3 url that corresponds to the csv file. It’s important to edit this file because its how quciksight will find and analyse the data.  Without it quicksight wont know the location of the dataset. 

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-analytics-quicksight_3c3cd85a)

---

## Create QuickSight account

Creating a QuickSight account cost zero with the 30 day free trial as long as the pixel perfect reports is unchecked 

Creating an account took me couple minutes

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-analytics-quicksight_f4ab4214)

---

## Download the Dataset

I connected the S3 bucket to QuickSight by visiting the dataset page

The manifest.json file was important in this step because tells QuickSight what your dataset looks like, so QuickSight knows how to understand the data and show it in charts or graphs

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-analytics-quicksight_6f874996)

---

## My first visualization

To create visualizations on QuickSight, we use the visualise tab to drag and drop different data values from our dataset to use and answer any sort of business requirements. very similar to Tableau and Power Bi

The chart/graph shown here is a breakdown of is a Pie chart representing all titles released each year. 

I created this graph by dragging and dropping the release year to the group by column. This makes the end pie chart.

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-analytics-quicksight_aff3aad7)

---

## Using filters

Filters are useful for as the name states, filtering out specific key data points that are needed to gain insights. 

This visualization is a breakdown of the split between movies and tv shows each year.

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-analytics-quicksight_c32248c5)

---

## Setting up a dashboard

As a finishing touch, I organised them to make it more visually appealing. I have also renamed them to make it easier for anyone to understand within a quick glance.

I exported using publish option and generated a PDF

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-analytics-quicksight_6c7f7ef0)

---

## Refreshing source data

---

---
