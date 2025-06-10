
CRISP-DM Report: Analysis of Quiz Responses

Project Overview
This report intends to analyse the performance and patterns in quiz responses of different students in
Newcastle University’s data of various conducted courses and provides actionable insights to improve learner outcomes and course delivery.

Directory Structure
	cache/:		Contains cache files and Dataframes for intermediate processing.
	config/: 	Contains configuration files for project settings.
	data/: 		Contains all the raw and unprocessed data files.
					1. cybersecurity_1_question_response.csv
					2. cybersecurity_2_question_response.csv
					3. cybersecurity_3_question_response.csv
					4. cybersecurity_4_question_response.csv
					5. cybersecurity_5_question_response.csv
					6. cybersecurity_6_question_response.csv
					7. cybersecurity_7_question_response.csv
	munge/: 	Preprocessing and data wrangling scripts.
					1. 01-CleanTransform.R
					2. 01-DataAnalysis.R
					3. 02-DataAnalysis.R
	renv.lock: 	This is the renv lock file. Ensures reproducibility of the R environment.
	reports/:	Contains Analysis rmd and pdf report files.
					1. AnalysisReport.pdf
					2. AnalysisReport.Rmd
	.git/: 		Git version control folder.
	GitLog.txt: Contain the list of all the git commits done till date staring from Project Template creation.
	README: This File.


Data Description
The project uses 7 CSV Files related to Quiz Responses:
	1.	Quiz Responses: Learners' quiz performance data.

Setup Instructions
	1.	Install R (version 4.x or higher).

Execution Instructions
	1) Open the .RProj file
	2) Run renv::restore() to build the project library
	3) Open the AnalysisReport.Rmd file and click "Knit" to PDF to generate the AnalysisReport.pdf file.

Outputs
The project generates:
•	Visualizations of quiz performance and trends.
•	Actionable insights for teachers so that they can improve the clarity of the questions in the quiz and in general improve the course content.
•	A comprehensive report: AnalysisReport.pdf.

Summary
This structured and reproducible project provides key insights into quiz performance, adding value to help to improve the student learning outcomes.

