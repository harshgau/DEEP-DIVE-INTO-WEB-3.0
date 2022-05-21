# Loan Management System

A loan management automated system built in C++ with the OOPS concept and data structures.

## My assumptions while designing this system are:-

1. The total amount is provided by the user and thus is not fixed.
2. The time period is specified by the user and thus is not fixed.
3. The primary EMI is provided by the user and thus is not static.
4. Because the interest EMI is given by the user, it is not static.
5. The user specifies the start date, month, and year, so they are not fixed.
6. The next EMI payment is due in 30 days.
7. The calculateNETAmount() function takes eight arguments: the database reference, the total amount, the time period, the principal EMI, the interest EMI, the start date, start month, and start year.

## Input format:

```
1000
10
54.39
10
12
may/May
2022

```
## Ouput Format:

```
Loan creation date: 12 May 2022
Principal Amount : 1000
No of EMI's: 10
Total Payable amount: 1120
EMI Details:
EMI No: 1, Principal EMI: 54.39, Interest EMI: 10, Total EMI: 64.39, EMI Date: 12 Jun 2022, Principal remaining: 1055.61
EMI No: 2, Principal EMI: 54.39, Interest EMI: 10, Total EMI: 64.39, EMI Date: 12 Jul 2022, Principal remaining: 991.22
EMI No: 3, Principal EMI: 54.39, Interest EMI: 10, Total EMI: 64.39, EMI Date: 12 Aug 2022, Principal remaining: 926.83
EMI No: 4, Principal EMI: 54.39, Interest EMI: 10, Total EMI: 64.39, EMI Date: 12 Sept 2022, Principal remaining: 862.44
EMI No: 5, Principal EMI: 54.39, Interest EMI: 10, Total EMI: 64.39, EMI Date: 12 Oct 2022, Principal remaining: 798.05
EMI No: 6, Principal EMI: 54.39, Interest EMI: 10, Total EMI: 64.39, EMI Date: 12 Nov 2022, Principal remaining: 733.66
EMI No: 7, Principal EMI: 54.39, Interest EMI: 10, Total EMI: 64.39, EMI Date: 12 Dec 2023, Principal remaining: 669.27
EMI No: 8, Principal EMI: 54.39, Interest EMI: 10, Total EMI: 64.39, EMI Date: 12 Jan 2023, Principal remaining: 604.88
EMI No: 9, Principal EMI: 54.39, Interest EMI: 10, Total EMI: 64.39, EMI Date: 12 Feb 2023, Principal remaining: 540.49
EMI No: 10, Principal EMI: 54.39, Interest EMI: 10, Total EMI: 64.39, EMI Date: 12 Mar 2023, Principal remaining: 476.1

```
## Time Complexity:

1. The time complexity of the system is inserting the records will be O(1).
2. The time complexity for producing the output from the database will be O(n) where n is the total number of records in the database.

## Centralization has the following drawbacks:

1. Administrative leadership
Centralized management is similar to dictatorial leadership in that employees are only expected to deliver results that the top executives assign them. Employees are unable to contribute to the organization's decision-making process and are merely implementers of decisions made at a higher level.

2. Control via remote
The executives of the organisation are under tremendous pressure to make decisions for the organisation, and they have no control over the implementation process. Executives' failure to decentralise decision-making adds a lot of work to their desks.

3. Work delays
Because records are sent to and from the head office, centralization causes work delays. Employees rely on information communicated from the top, and any delays in relaying the records will result in a loss of man-hours.

4. Employee dissatisfaction
Employees become loyal to an organisation when they are given the opportunity to take personal initiative in their work. They can express their creativity and suggest new ways to complete certain tasks. However, there is no initiative in work when it is centralised because employees perform tasks that are conceptualised by top executives. Because of the rigidity of the work, this limits their creativity and loyalty to the organisation.

