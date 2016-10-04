# swarm3k
SwarmZilla 3000 Collaborative Project

## Goals
This is the 2nd collaborative project to distributedly form a huge Docker cluster.
SwarmZilla 3000 will be targeting 3,000 nodes. This test will be done on the stable 1.12.2 version of Docker to make it more stable of course.

  * Networking; We will be creating a large subnet /20 to and trying to assign, as many as possible, IP addresses to each container on each node distributedly. We expect to have around ~3,000 IP addresses assigned and the workload application should be working fine.

  * Routing Mesh; We will be testing the Routing Mesh feature on Docker 1.12.2.
  * For the routing mesh tests, the workload will be Wordpress applications.
  

## Beginner's Guide
If you're an individual and it's your first time joining SwarmZilla, we encourage you to *not* contribute more than 50 nodes.
The provision steps for number of nodes more than 50 will make things complex.

If you're joining us for the second time (welcome back Heroes!!), feel free to contribute any number of nodes.

## Contributing nodes
  0. Create a pull request, saying you'd like to contribute nodes. Please include your full name, Twitter's handle *and* your company name.
  0. Date for the experiments will be announced after we get more than 3,000 nodes.
  0. Node specification for this run is 1GB of RAM with 1 vCore. We're sorry that 512MB will be not enough for our testing this time.

## Public results
All experimental results will be provided publicly for all of you to analyze, write blogs, 
or even used as information for further development of your own commercial projects. Please feel free to use it.
If you'd like to refer to the set of published data, just link back to this project page.