# Simulation in Visual Basic Application

## This repository contains codes, scripts and simulation strategies learnt in the class SC&IS 545 (Supply Chain & Information System) by Dr. Russell Barton at Penn State.
This course provided an introduction to Monte Carlo and discrete-event simulation

## Following are the simulation cases performed in this class.

### 1. Time to Repair. 
#### This case introduced simulation of two component video player for commercials scenario. At a time, one player will be used and other will be in spare. When the current in-use player fails other spare player will be used. Failed player will go in repair state and have a fix repair time. Time to failure is "random variable" and equally likely to be integer from 1 to 6. System failure is a state when second player fails before the first player is repaired. Again, system failure will be a random variable as well.

#### Questions answered through this simulation case.
#### a. What is the average time until system failure in 100 replications?
#### b. Average number of operational components in the 100 replications?
#### c. Average utilization of Repair technicians in 100 replications?

### 2. Single Product Inventory System
#### This case introduced simulation of inventory system. It performed simulation for scenarios with different inventory policies and cost associated with each one of them. It included upper level for inventory specifying maximum holding limitations(S) and lower level (s) at which new order for inventory will be placed. A periodic evaluation is performed for assessment of inventory level. The system had different fixed demand sizes from customers with mean interdemand time. The inventory system associated costs for ordering, holding and sales cost.

#### Questions answered through this simulation case.
#### a. Which is the optimal policy (s,S) for inventory?
#### b. Cost associated with each policies?
#### c. which policies cost back orders and which ones are safe? 

### 3. M/M/1 Queue Simulation
#### This simulation represents the queue length in a system having single server, where arrivals are determined by a Poisson process and job service time have an exponential distribution. The variables used in the system: Entities - Customers, Resources - server and queue,  Attributes - arrival and service time, Performance - Avg Q(t): number of customers in queue at time t, Avg D(t): waiting time for ith customer, Avg B(t): server utilization

#### Questions answered through this simulation case.
#### a. What is the average wait time in queue? (CTS or DTS)
#### b. What is the average queue length? (CTS or DTS)
#### c. What is the server utilization in the system? (CTS)

### 4. Multiteller bank with separate queues & jockeying
#### A bank system with different number tellers for servicing customers is a typical queueing system example. In this case, we silumated a multi teller bank with different number of tellers and calculated different performance metrics with each one of them. For e.g. a bank may use less number of tellers than needed to decrease the cost but it can lead to longer customer delays and alienation from customer. Using this simulation, bank can decide number of tellers needed to provide the adequate service to the customers who wants to cash a check or make saving deposit. This system included jockeying where customers are allowed to move from one queue to other if it seems to be their advantage.

#### Questions answered through this simulation case.
#### a. What are average number in queues with different tellers (4, 5, 6 and 7)?
#### b. What is the average delay in queue with different tellers (4, 5, 6 and 7)?
#### c. What is the maximum and minimum delay faced by a customer?
#### d. What is the highest and lowest number of customers served in a day with different tellers?



