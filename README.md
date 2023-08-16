# Resource Optimization Dashboard
A dashboard for monitoring K8s cluster resource allocation

# Problem Statement
In a Kubernetes environment where Prometheus is being used as the primary monitoring tool, the task is to design a Grafana 
dashboard. The goal of this dashboard is to help identify deployments (exclude statefulsets, daemonsets, cronjobs etc) that 
are potentially oversized or undersized, thereby facilitating cost optimization through resource adjustments.

Oversized Deployment: If a deployment requests a large amount of CPU or memory but only uses a fraction of it, it is 
considered "oversized" as it inefficiently consumes resources. 

Undersized Deployment: If a deployment consistently maxes out its requested CPU or memory, leading to potential performance 
issues, it is considered "undersized". 

The aim of the dashboard is to quickly and intuitively highlight 
these inefficiencies, which in turn would facilitate informed decision-making and optimize resource utilization.


# Few Snapshots of the Dashboard
![CPU_Percentage_of_Limit](https://github.com/vect-0r/Resource-Optimization-Dashboard/assets/56092166/6bf150ff-2c0a-4ff3-896f-45bb57b37bfc)
![Cluster_Health](https://github.com/vect-0r/Resource-Optimization-Dashboard/assets/56092166/80d74589-5026-414b-9ce7-7d2714f92fcd)
![Memory_and_CPU_as_Percentage_of_Both_Request_And_Limit](https://github.com/vect-0r/Resource-Optimization-Dashboard/assets/56092166/cf44fa5a-ed0c-4ee4-be20-f16dfbd49c48)
