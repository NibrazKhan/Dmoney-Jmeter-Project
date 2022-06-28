# DmoneyAPI-Jmeter-Project
This is a Jmeter Project where the DmoneyAPI is tested by creating test cases for **Login** , **Creating users** , **Searching users** and also 
performing **Update** and **Delete** operations. The ramp-up and the number of threads were kept as 1.Here login credentials can also be used from the csv file without explicitly writing it in the body.

Steps to run this project:
- Clone this project or download the .jmx file in the project directory.
- You can generate your own HTML summary report by running the following code in the terminal:
```
jmeter -n -t DmoneyAPI.jmx -l DmoneyAPI.csv -e -o Reports
```
### Summary Report 

![Statistics_report](https://user-images.githubusercontent.com/55280106/176236351-44f81561-6822-473f-a284-6e6f5d8e0a88.png)
### Whole project structure in Jmeter
![Image 1](https://user-images.githubusercontent.com/55280106/176236655-27631c53-2fbf-4983-9ca5-735bf88722e1.png)
- All test cases passed can be viewed from Jmeter result tree:

![Viewing_result_tree](https://user-images.githubusercontent.com/55280106/176237191-2347f629-4619-4fdd-9d52-ca7df394157c.png)
### Summary report in Jmeter.
![Summary_report_jmeter](https://user-images.githubusercontent.com/55280106/176237605-fea6d6c2-8d51-46a9-af63-2ab8593a0fa0.png)
