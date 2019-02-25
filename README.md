# KMeans
The laboratory from CLOUDS Course at EURECOM

This repository included the Stochastic Gradient Descent laboratory from CLOUDS Course at EURECOM, which was conducted in a group with three other members as NGUYEN Van Tuan (Van-Tuan.Nguyen@eurecom.fr) and Yangxin YUAN (Yangxin.Yuan@eurecom.fr)

Furthermore, the CLOUDS - Distributed Systems and Cloud Computing course was offered by Prof. Pietro Michiardi at EURECOM. The details of the course can be retrieved in here http://michiard.github.io/DISC-CLOUD-COURSE/

### Course Description
The goal of this course is to provide a comprehensive view of recent topics and trends in distributed systems and cloud computing. We will discuss the software techniques employed to construct and program reliable, highly-scalable systems. We will also cover the architecture design of modern datacenters that constitute a central topic of the cloud computing paradigm. The course is complemented by some lab sessions to get hands-on experience with Apache Spark.

### The Laboratory Description
Large-scale Distributed KMeans Algorithm
In this Notebook, we'll focus on the development of a simple distributed algorithm. 

In what follows, we'll proceed with the following steps:

- We first introduce formally the KMeans algorithm
- Then we focus on a serial implementation. To do this, we'll first generate some data using scikit. In passing, we'll also use the KMeans implementation in scikit to have a baseline to compare against.
- Subsequently, we will focus on some important considerations and improvements to the serial implementation of KMeans.
- At this point, we'll design our distributed version of the KMeans algorithm using pyspark, and re-implement the enhancements we designed for the serial version
