# WiSeDB

This project contains code for the WiSeDB project, a part of the [XCloud project at Brandeis University](http://www.cs.brandeis.edu/~olga/XCloud.html). This is a Java implemention of the WiSeDB system as described in:


Marcus, Ryan, and Olga Papaemmanouil. "[Workload Management for Cloud Databases via Machine Learning.](http://www.cs.brandeis.edu/~olga/publications/clouddm-2016.pdf)" Workshop on Cloud Data Management and the IEEE International Conference on Data Engineering, CloudDM. Vol. 16. (2016)

Marcus, Ryan, and Olga Papaemmanouil. "[WiSeDB: A Learning-based Workload Management Advisor for Cloud Databases.](http://arxiv.org/abs/1601.08221)" arXiv preprint arXiv:1601.08221 (technical report, 2016).





## What's it do?

WiSeDB is designed to assist cloud applications in making three decisions:

1. Resource provisioning: determining the number of VMs needed to process a workload
1. Query placement: determining which query should execute on which VM
1. Query scheduling: scheduling the queries within a VM

![Animation of three tasks](https://raw.githubusercontent.com/RyanMarcus/wisedb/master/res/workloadmang.gif?raw=true)


