# Investigating Motor Vehicle Crashes of New York City: Where, When, Why

Contributors:

1. Casey Delaney - https://github.com/CaseyDelaney
2. Manasa Bobba - https://github.com/manasabobba
3. Sudheendra Katikar - https://github.com/sudheendrakatikar

---
The title of our dataset is ‘Motor Vehicle Collisions - Crashes’. It consists of information from all police reported motor vehicle collisions in NYC over the period of 2012-2021, and has over 1.8 million records. The data is very informative since it's generated from a police report template that is quite comprehensive. The dataset was downloaded from https://data.cityofnewyork.us and can be found at https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95.

---
We will try to answer some questions that arise out of reviewing the data, and possibly conduct some prescriptive analysis 
- Are certain localities more prone to accidents than others?
- Do certain vehicles tend to have a recurring cause for the accident?
- Does a street get particularly busy during any hour of the day?

---
Instructions:

1. The code for this project was written in the Google Colab environment. The main file for this project is maincode.ipynb. Other files in this repository contain smaller examples of code that our group was able to referernce while working on the main file. 

2. After opening the file in google colab, you will see sections on the side that splits the code up. To begin, the first block contains the Includes section and so on. Some sections such as the "Define CLeanup Data Functions" will look incomplete. This section serves as a template for our team members to grab important blocks of code and insert it into the appropriate sections and modify them for their own use, since every method is different.

3. In order to run the code, you must make sure that the dataset is in your google drive environment. If you have not added the dataset to your google drive environment, you can download the data here: https://drive.google.com/file/d/11uMX7Er39tQsO_D5Zsm5XbzTKf2mh95I/view?usp=sharing

4. After adding the data to your environment, please run the code. You will be stopped by the "Mount Drive section". This allows google colab to recieve access to your drive and therefore access the dataset. If you are uncomfortable with this you may use Jupyter Notebooks and add the file into a folder. Since we were working in a team environment, it was important for us to be using the same version and Google Colab. However, Google Colab does not allow you to have access to the folders unless you mount the drive. Follow the onscren instructions to mount the drive. At any point where a load data function is used, ensure that you change the filepath to your own google drive filepath to allow access to the data. 


The main part of the code is contained within the Method Functions. This is where the code for each method is performed. There is also a data visualizations section. This is where some of the graphics for visualizing data is displayed.
