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
