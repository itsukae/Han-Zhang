普通和优先级包裹到达邮局的处理速率为(平均每单位时间4个包到达邮局)，服从柏松分布，lambda=4.普通包裹和优先级包裹的分布比例为0.9，服从伯努利分布。邮局有9名工作人员，处理时间为以均值2的指数分布(平均每单位时间可以处理2个包)，如果所有的工人都忙于包装加工，一个新的到达的常规(或优先)包裹则将进入常规(或优先)等待队列。工人一旦完成包处理，他立即会接受一个新包。如果没有等待的包裹，则保持空闲状态。如果在常规队列和优先队列中都有等待的包裹，工人将从优先队列中获取一个包裹。


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
