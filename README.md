# ReactorModel

A. Topic

Model for Consistent Process Control

B. Why

The Process Control cannot be easily modelled using conventional methods.
Looking at machine learning concepts to solve this / partially answer the 
difficult problem

C. Data

1. Data will be generated on proprietary machine and uploaded to postgres.
2. Data includes all input/output parameters including machine ID.

D. Expected Results

1. To predict input parameter to control the behavior of the process
to produce certain predictable/consistent outcomes needed in manufacturing

E. Logistics

1. Solo Project : Lakshmanan Karuppiah
2. Data : Real Machine Data (multiples)
3. Initial data was loaded into Postgres and read using sqlalchemy create_engine
4. Multiple data generated from various machine will be merged in postgres
5. sep30.ipynb is the jupyter notebook file with data extraction,transformation, 
and machine model
6. Google slide link is  the inital presentation  and will be expanded as the 
project progresses
7. the picturs are snipits of the jupyter notebook to show the data loading /extraction 
,cleaning and machine model coded in  jupyter notebook
8. temp.csv is the inital data file generated and used for inital trial run
9. Created machine inputs with temp.csv data. We ran the machine with different parameters and two of the inputs were based on the model
10. Data collected during the run was cleaned and transformed for comparison of the output vs predicted.
11. For meanigful comparison threee pressures (low, medium , high ) were seperated and plotted

E. PRESENTATION (Google Slides Link)

[oct7]https://docs.google.com/presentation/d/1z78O63M3M7ujIqjIRi2hlsEVZtfQPtE0wT2LkSDIUQs/edit?usp=sharing

[oct10]https://docs.google.com/presentation/d/1z78O63M3M7ujIqjIRi2hlsEVZtfQPtE0wT2LkSDIUQs/edit?usp=sharing

F. Results from running predicted models

![OCT17](low_pressure.PNG)

![OCT17](medium_pressure.PNG)

![OCT17](high_pressure.PNG)

G. Snipits From python file

![oct7](Final_Project_Deliverable_1b.PNG)

![oct7](Final_Project_Delivarable_1a.PNG)

![oct10](SQLCOMMANDSUSED_TABLECREATION_TABLEUNIONS.PNG)

![oct10](Final_projectDEliverable2.PNG)

![oct10](Final_project_deliverable_2a.PNG)

![oct10](final_project_delivarable_2b.PNG)









