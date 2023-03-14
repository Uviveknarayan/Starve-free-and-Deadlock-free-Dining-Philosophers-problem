# Starve-free-and-Deadlock-free-Dining-Philosophers-problem
This repo contains an implementation to solve the Dining Philosophers Problem using C without Starvation and Deadlock.
![alt dining philosophers problem](https://img.youtube.com/vi/kwxrt-LWryQ/0.jpg)
The Dining philosophers is a synchronization problem which is used to evaluate situations where there is a need of allocating multiple resources to multiple processes. The problem is:

Consider there are **five philosophers** sitting around a circular dining table. The dining table has **five forks** and a bowl of food in the middle.
At any instant, a philosopher is either **eating** or **thinking**. When a philosopher wants to eat, he uses *two forks* - one from their left and one from their right. When a philosopher wants to think, he keeps down both forks at their original place.
Eating is not limited by the remaining amounts of food;
