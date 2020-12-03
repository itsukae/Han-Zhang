


The problem is about Discrete-Event Simulation study. The question is required to simulate the process of workers handling parcels. In this problem, there are 9 post-office workers and 2 queues, one of the queues is priority queues. So the problem is m/m/c queue. The length of the simulation is 2000.The objective of the simulation is to find the proportion of time that all workers are busy during the period of T=2000 and get the 95% confidence interval. In this simulation, we also can get the average waiting time. We can conclude that whether the 9 post-office workers are enough or not. If the proportion of busy time is very small, we can decline the number of post office workers.

Event-Arrival:
When the parcel arrives, the system will add an arrival event.

Event-Departure:
When the parcel departs, the system will add a departure event.

Arrive rate:
According to a Poisson process with rate, 𝝀 = 𝟒

Process time:
Time is exponentially distributed with mean 2

The state of post-office workers:
There are two states, BUSY or IDLE.

The simulation time:2000

The waiting time:
The waiting time of each parcel 

The number of parcels:
If the parcel arrives, the number +1

The number of departures:
If the parcel has been packed and departs, the number +1

The time in system:
The total time of each parcel in this system. (waiting time + process time)

Queues:
There are two queues，the priority queue and the regular queue.
