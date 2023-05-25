Neetcode YouTube Video

[20 System Design Concepts Explained in 10 Minutes](https://www.youtube.com/watch?v=i53Gi_K3o7I&list=PLot-Xpze53le35rQuIbRET3YwEtrcJfdt) - ( They lied its 11:39 minutes video xD)


key take aways

- Vertical Scaling - add more resource to scale your app's server (To increase the RAM & CPU).very easy to perform but very limited from resource POV.

![vertical scaling](./images/verticalScaling.jpg)

<hr>

- Horizontal Scaling - add more machine power by creating replicas.it also add redundancy and fault tolerant.

![Horizontal scaling](./images/horizontal%20scaling.jpg)

<hr>

- load balancer - Horizonatal scaling eliminates single point of failure since its complicated, so how to ensure that one server is over loaded and other one is idle. so it is done with the help of load balance which is just a server which is a reverse proxy it directs incoming requests to appropriate server.


![loadBalancer](./images/loadBalancer.jpg)