This project is related to performance testing for CrossTours website.

PreRequisite
Apache Jmeter 3+

Scenario:
   - Navigate to http://www.newtours.demoaut.com/
   - Use username/password as yahya/yahya and click login
   - Select current date in flight departing and returning date and Click Continue of Flight finder screen.
   - Select random flights and click continue.
   - Fill firstname, lastname and number and click secure purchase.
   - Click logout.
   - Incorporate use of multiple users for login, name of the user and random selection of the flights for the execution.
   - Execute the test case for 5 virtual users for 20 minutes with the ramp-up time of 1 user / 10 sec. 
   - The SLA of the execution is 1000 ms/page.

Provide datapool used for execution as Task2-datapool.csv, the execution summary results as Task2-Results.csv and an analysis report as Task2-Analysis.docx.
