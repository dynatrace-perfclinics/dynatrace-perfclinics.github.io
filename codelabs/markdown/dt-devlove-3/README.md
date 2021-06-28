summary: Why Developers Love Dynatrace - Episode 3
id: why-devs-love-dynatrace-3
categories: codelevel, cicd, qualitygates
tags: codelevel
status: Published
authors: sergio.hinojosa
Analytics Account: UA-193960361-1

# Why Devs Love Dynatrace - Episode 3

## Introduction 
Duration: 10


Positive
: ***In this Developer Webinar Series we want to bring you from Zero 👶 to Hero 🦸 from Diagnosing Transactions and releases with Dynatrace to building unbreakable delivery pipelines with automatic performance tests and release validation alongside fullstack comparison.***

**Watch the recording of Episode 3 on YouTube!**

![https://www.youtube.com/watch?v=akMlRknwY7U](.)

### Abstract of Episode 3
In the previous episodes you learned how Dynatrace automates observability from Dev to Ops environments, how to analyze distributed traces on real time (we call them PurePaths) to detect code or performance hotspots and how to automate code evaluation as part of your development process and delivery pipelines. You learned about automated performance validation and release comparison through intelligent quality gates and were introduced into the concepts of SLOs (Service Level Objectives).

On Episode 3 will learn the foundations of Load Test Analysis with Dynatrace. We will compare failed releases that did not pass the Quality Gate due performance degradations. We will show how easy it is to compare functional performance tests with each other learning how Dynatrace can pinpoint the degradations up to code-level through the application stack. We will even decompile the code to understand the root cause of a bad implementation whether it is a bad algorithm or thread synchronization issue.


### Live Hands-On for Episode 3

All the steps done during the Webinar will be uploaded to this codelab. The powerpoint will be available (like the past episodes) in the [Dynatrace University 🧑‍🎓](https://university.dynatrace.com/). 


Negative
: For following along you need to have the CICD environment setup with the endless pipeline active running through the Intelligent QualityGate. Below are the steps to update your monaco configuration. Just some links to the loadtesting dashboard will be updated. 



### Update the GIT Repo containing the monaco configuration
```bash
git pull
```
### Load the variables in the shell
```bash
source set_dt_variables.sh
```
### Execute Monaco

```bash
monaco deploy -e environment.yaml -v
```

Positive
: If you don't have a CICD Environment of your own, we will provide during the Webinar a live access to a Dynatrace cluster so you can follow along.



<!-- 

- Show Dashboard of DT E2

- Do a pull, EXPLAIN what happens with the ID of Service and PGI need of JQ

- Show Dashboard of DT E3 with Links
-->




