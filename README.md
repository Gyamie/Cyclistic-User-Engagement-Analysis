##  Google Data Analytics Capstone Project

<p><b>Cyclistic<b>data analysis project is a capstone project of the Google Data Analytics Certificate.In this project, you play the role of a junior data analyst at Cyclistic, a fictional bike-share company based in Chicago. <br><br>The project involves analyzing Cyclistic’s historical bike trip data to understand how annual members and casual riders use Cyclistic bikes differently.

The datasets used for this project are Cyclistic’s historical trip data. The data covers details of every ride logged by Cyclistic customers. The data is available in CSV format and can be found on platforms like Kaggle. The data used in the project typically covers a period of 12 months.
To Access the dataset <a href="https://www.kaggle.com/datasets/sarfarazmulla/google-data-analytics-capstone-cyclistic"><b>Click Here</b></a>.
</p>

## Table of Contents
* [Installations](.i)
* [Project Motivation](.pm)
* [File Description](#fd)
* [Data Analysis Stages](#md)
* [Results](#re)
* [Certificate](#cf)

  ## Installations<a class ="i"></a>
  ##### Install Sql Server Management studio and Tableau
  
 ## Sql Server Management studio(SSM)
<p style='text-align:justify;'>To run <b>Sql Server Management studio(SSM)<b> on your localhost, Follow the steps below ;</p>

1. Download and Install SQL Server: Visit Microsoft’s page for SQL Server and download the free Developer edition. Once the download completes, run the installer.

2. Choose Installation Type: On the initial screen of the installer, choose ‘Basic’ to continue with a conventional installation using the most common options.

3. Agree to the Terms: Read the license and agree to the terms to continue.
   
4. Confirm Installation Location: Confirm or change the installation location and click ‘Install’ to begin the installation process.
  
6. Connect to a SQL Server instance: In the ‘Connect to Server’ dialog box, enter the following information:
   * Server type: Select ‘Database Engine’ (usually the default option).
     
   * Server name: Enter the name of your SQL Server. You can also use ‘localhost’ as 
       the server name if you’re connecting locally.
     
   * Authentication: ‘Windows Authentication’ is set as default. You can also use ‘SQL 
       Server Authentication’ to connect. However, if you select ‘SQL Server 
       Authentication’, a username and password are required.
     
 7. Place the Cyclictic Data in the SSM Folder, call it in the database management 
    Studio and run the scripts.
    
    # Tableau

    <p style='text-align:justify;'>To SignUp <b>Tableau Public <b>, Follow the steps 
     below ;</p>
     
     1. Go to the Sign-Up Page: Navigate to the Tableau Public sign-up page or click 
        the ‘Sign In’ at the top of any page on <a href = 'https://public.tableau.com/desktop/signup_unification.html'>tableaupublic.com.</a>
     2. Fill Out the Form: Fill in the form with your information, including a strong 
        password. Make sure you use an email that you have access to.
     3. Create Your Account: Click 'CREATE MY ACCOUNT’.
     4. Activate Your Account: Look for an email from @tableau.com and follow the 
        instructions to activate your account.
     5. Build Your Profile: After signing up, you can start building out your profile. 
        Once you’ve signed up, you can start creating and exploring data visualizations.

  ## Project Motivation<a class ="pm"></a>
<details>
	<summary>Problem Statement</summary>
	<br>
•	How do annual members and casual riders use Cyclistic bikes differently? 

•	Why would casual riders buy Cyclistic annual memberships? 

•	How can Cyclistic use digital media to influence casual riders to become members? .</p>
</details>

<details>
	<summary>Project Goals</summary>
	<br>
	<p>In this project,the goal is;</p>
	<ol>
		<li>The goal is to design marketing strategies aimed at converting casual riders into annual members.</li>
	</ol>
</details>
<br>

## File Description <a name="fd"></a>
This repository contains the database scripts, a link to the tableau Story and a documentation.

<br>

## Data Analysis Stages<a name="md"></a>
<details>
	<summary>Ask</summary>
	<br>
	<p style='text-align:justify;'>

This is the first step where you define the problem you’re trying to solve. You need to understand the stakeholder’s expectations and focus on the actual problem. Some questions to consider are: 
<u>
<li>What are my stakeholders saying their problems are? </li>
<li>Now that I’ve identified the issues, how can I help the stakeholders resolve their questions?.</li>
	</ul>
</details>

<details>
	<summary>Prepare</summary>
	<br>
	<p style='text-align:justify;'>
<li>In this phase, you decide what data you need to collect in order to answer your questions and how to organize it so that it is useful. You might use your business task to decide what metrics to measure and locate data in your database.</p></li>
	</ul>
</details>

<details>
<summary>Process</summary>
<br>
 <p style='text-align:justify;'>
<li>This phase involves cleaning up your data to get rid of any possible errors, inaccuracies, or inconsistencies1. This might mean using spreadsheet functions to find incorrectly entered data, using SQL functions to check for extra spaces, removing repeated entries, and checking as much as possible for bias in the data.</p></li>
</ul>
 </details>




<details>
<summary>Analysis</summary>
<br>
 <ul>
<li>Analyze: In this stage, you sort and format your data to make it easier to perform calculations, combine data from multiple sources, and create tables with your results.</li></ul>
 <p>&nbsp;</p>
	
To achieve the first goal, I answered a few questions using both quantitative and graphical methods. Some of the questions are listed below.
	
* Number of users for each user group. 

•	Number of bikes for each bike type.

• Bike usage according to user group. 

•	Number of bikes taken daily by each user group. 

•	Days with most rides. 

•	Days with less rides. 

•	Number of bikes return daily by user group. 

•	Number of rides according to days length. 

•	Number of rides according to user type (1 or more days ride).

•	Hours with less and most rides. 

•	Month with most rides. 

</details>

<details>
<summary>share</summary>
<br>
<ul>
<li>This phase involves summarizing your results with clear and enticing visuals of your analysis using data viz tools like graphs or dashboards.<l/i></ul>	
	
</details>

<details>
<summary>Act</summary>
<br>
<ul>
 <li>The final phase of the data analysis process is to act on the insights gained.</li></ul> 
</details>

<br>

## Results<a name="re"></a>
Based on the analysis I performed, below are the key insights I generated from the data; 

* Member riders make up 64.64% of the customer margin of Cyclistic company whiles casual riders’ makeup 35.36%.
* The Users turn to use classic bikes more than electric bikes more but docked bikes are hardly used or preferred by both user groups. 
* It is also worth noting that for member riders, the days preferred for rides are on weekdays whiles weekends are mostly preferred by casual riders.
* Both User groups take rides that rarely extend beyond 24 hours but on exceptionally cases, casual riders turn to take more trips than members that then to extend beyond 24 hours.
 
<br>

## Certificate<a name="cf"></a> 
<a href= 'https://www.coursera.org/account/accomplishments/specialization/89ZPGABZVKMC'>[Earned Certificate]</a>











