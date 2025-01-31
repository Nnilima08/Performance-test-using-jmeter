# Performance test using jmeter
#  Project Summery

# Overview:
This project uses Apache JMeter to test two APIs:

1. Booking API: Load and stress testing to evaluate the server's performance under high traffic.
2. dmoney API: Functional testing for agent, customer, and merchant transactions.

# Technologies:
- Apache JMeter for Load Test & Stress Test.
- CSV Files for dynamic transaction data.
- GitHub for version control.

# Tasks Completed:

# Task 1: Booking API
- Test Plan: Includes login, booking creation, and booking search.
- Load Test: Simulated 120,000 users over 12 hours in 3 stages (5, 10, and 20 minutes).
- Stress Test: Increased load to identify system bottlenecks.
- Reports: Generated HTML and Excel reports for load and stress tests.

# Task 2: dmoney API
- Test Plan: Simulated deposit, send money, and payment transactions for agents, customers, and merchants.
- Data: Used CSV files for dynamic data.
- Assertions: Ensured successful transaction responses.
- Ramp-up: 120-second ramp-up for each transaction type.

# How to run?

- git clone <repo_url>
- Open ApacheJMeter
- From ApacheJMeter open the JMX File
- Finally Run

# Load and Stress Test Excel Report -

https://docs.google.com/spreadsheets/d/185uJf6f6KcpWjQBXxodi1DGnjHck7MGhDwQnLUosgys/edit?usp=sharing

# Generated Load Test Html Report for booking API collection-

- jmeter -n -t .\booking.jmx -l .\booking.jtl -e -o Reports
![image](https://github.com/user-attachments/assets/2f0f3c12-bbed-4022-a2b6-9fdd31590dd4)

![image](https://github.com/user-attachments/assets/c71b07f7-55e0-4afa-8ddf-8450311cd982)

# Generated Stress Test HTML Report for booking API Collection-
![image](https://github.com/user-attachments/assets/be59dcf4-15ea-4e50-8c76-2461f9484ba7)

![image](https://github.com/user-attachments/assets/0d56d6b1-c32c-4851-a5f7-dbf9814543c4)

# Generated HTML Report for dmoney API Collection-
- jmeter -n -t .\dmoneytest.jmx -l .\dmoneytest.jtl -e -o Reports
  
![image](https://github.com/user-attachments/assets/d9baaa58-1402-4f8a-b454-89f256e086ea)

![image](https://github.com/user-attachments/assets/f3b2aa65-8e56-4cbe-a36c-c6cfabc4a5cf)









