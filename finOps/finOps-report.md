# FINOPS REPORT

## Financial Goals and Objectives

1.	Complete the project within the allocated monthly budget of $100.
2.	Minimize cost overruns and avoid unnecessary expenses.

## FinOps Policies and Procedures
<b>Cost Tracking and Cost Visibility:</b>

We want to be able to track, analyze and optimize costs so cost visibility is of utmost importance to our team. This was achieved using tools such as AWS Cost Explorer and AWS Cost Anomaly Detection. AWS provided comprehensive insights into our AWS costs and usage including forecasting future costs and usage.  With AWS Cost Anomaly Detection, we will be able to receive alerts when unusual spend is detected, this will help us catch unintentional spend early. We opted for email alerts to ensure zero spend.

<b>Savings Measurement:</b>
-  Cost Allocation Tags were used in attributing expenses accurately and identifying areas of high spending.
- Budgeting and Forecasting: A custom budget was set using AWS budgets. This tool helped with monitoring spend and ensuring we don’t exceed our budget along with helping us forecast future costs. 
- AWS Cost and Usage Report was used to provide indepth analysis into the cost and usage data, thereby allowing us make informed decisions on cost optimization

## Cloud Costs.
 This is a list of the project's cloud resources and their associated costs, this data was provided using the  [AWS Pricing Calculator](https://calculator.aws/#/estimate?id=718e3e6ca17e8e3be0ef4dfd6bf31f2243438371).
- AWS was the choice cloud service provider because it has a free tier which will cover some of the services we will be using thereby optimizing cost for the project.
- The cost estimates for the services used on AWS are shown below:
 
## FinOps Tools and Resources
These are the tools and resources that the project uses to manage its cloud costs. 
1. AWS Cost Explorer
2. AWS Budgets
3. AWS Cost Anomaly Detection
4. AWS Cost and Usage Report
5. AWS Pricing Calculator
6. AWS Cost Allocation Tags
 
## FinOps Best Practices
 This includes a list of the best practices that the project follows to manage its cloud costs.

1.	Ensure the team leverages open source tools such as Prometheus, Jenkins to minimize spend
2.	Right-sizing EKS worker nodes: Ensure that EKS worker nodes are appropriately sized for the workload.  
3.	Cluster AutoScaler: Enable the Cluster AutoScaler feature in EKS to automatically adjust the size of worker node groups based on cluster resource demands thereby avoiding underutilization or overprovisioning.
4.	 Use Prometheus monitoring to track resource utilization and adjust the instance types or sizes accordingly to optimize cost.
5.	Apply appropriate cost allocation tags to resources, enabling better visibility and cost attribution.
6.	Identify idle or underutilized resources and decommission them to reduce costs.
7.	Use cost management tools like AWS Cost Explorer and AWS Budgets to help analyze, forecast, and control your cloud costs effectively.
