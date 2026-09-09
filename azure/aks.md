Top AKS Interview Questions

1. AKS Fundamentals

What is AKS?
Why do we use AKS instead of deploying containers directly on Azure VMs?
What is Kubernetes?
What is the difference between Docker and Kubernetes?
What are the main components of Kubernetes?
What is a Pod?
What is a Node?
What is a Cluster?
What is a Deployment?
What is a Service in Kubernetes?
What is the difference between Pod, Deployment and Service?
What is a Namespace?

2. AKS Architecture

Explain AKS architecture.
What is the control plane in AKS?
What is the worker node?
Who manages the Kubernetes control plane in AKS?
What happens when you create an AKS cluster?
What are node pools?
Why would you create multiple node pools?
What is the difference between system node pool and user node pool?

A good interview explanation:

“AKS is a managed Kubernetes service. Azure manages the Kubernetes control plane, while we manage workloads, node pools, applications and configurations.”

⸻

3. Deployment Questions

How do you deploy a .NET 8 application to AKS?
Explain the flow from Docker image → AKS → Pod.
How do you create a Docker image for a .NET application?
Where do you store Docker images in Azure?
What is Azure Container Registry (ACR)?
How does AKS pull an image from ACR?
What is a Kubernetes Deployment YAML?
What is a ReplicaSet?
How do you deploy multiple replicas of an application?
How do you perform a rolling deployment?
How do you rollback a deployment?

Networking — Very Important

How does networking work in AKS?
What is a Kubernetes Service?
Difference between:

ClusterIP
NodePort
LoadBalancer

What is an Ingress?
Difference between Ingress and LoadBalancer?
What is Azure Application Gateway?
What is Application Gateway Ingress Controller / Application Gateway for Containers?
How does traffic reach a Pod from the internet?
How do two Pods communicate with each other?
How do two microservices communicate inside AKS?

5. Scaling Questions

How do you scale Pods in AKS?
What is Horizontal Pod Autoscaler (HPA)?
What is Cluster Autoscaler?
Difference between HPA and Cluster Autoscaler?
What happens when CPU reaches 80%?
How does AKS automatically add nodes?
Can AKS scale based on memory?
How would you handle sudden traffic of 10x?
What is KEDA?
How can you autoscale a worker based on Azure Service Bus queue length?

This last question is particularly important for your Azure Service Bus architecture.

6. Configuration & Secrets

How do you store configuration in Kubernetes?
What is a ConfigMap?
What is a Secret?
ConfigMap vs Secret?
Should database passwords be stored directly in YAML?
How would you integrate AKS with Azure Key Vault?
What is Workload Identity?
How does a Pod authenticate with Azure services without storing credentials?

Health & Reliability

What is a liveness probe?
What is a readiness probe?
Difference between liveness and readiness?
What happens when a Pod becomes unhealthy?
How does Kubernetes restart a failed Pod?
What is a startup probe?
How do you achieve high availability in AKS?
What happens if an AKS node crashes?
What happens if a Pod crashes?

Pod is in CrashLoopBackOff. What could be the reason?
Pod is in Pending state. Why?
Pod is running but API is not accessible. How do you troubleshoot?
Service cannot reach the Pod. What would you check?
Container is running but health check fails. What do you check?
ImagePullBackOff — what does it mean?
How do you check events in Kubernetes?
How do you check CPU/memory usage?
How do you troubleshoot high CPU in a Pod?
 
⸻
 
9. Security
How do you secure AKS?
What is RBAC?
Kubernetes RBAC vs Azure RBAC?
What is Managed Identity?
What is Workload Identity?
How do you secure communication between microservices?
How do you restrict network communication between Pods?
What is a Network Policy?
How would you secure an AKS cluster exposed to the internet?
 
⸻
 
10. Real-World Scenario Questions ⭐⭐⭐
These are the ones I’d focus on for a 7+ year .NET developer interview.
Scenario 1
You have 10 .NET microservices running in AKS. One service suddenly receives 10,000 requests/sec. What happens and how would you design scaling?
Scenario 2
Your .NET worker consumes messages from Azure Service Bus. How would you deploy it in AKS and continuously consume messages?
Scenario 3
A Pod is consuming 2 GB memory and getting killed. How do you troubleshoot?
Scenario 4
Your new version of the API has a bug. How do you rollback in AKS without downtime?
Scenario 5
You have 5 replicas but only one Pod is receiving traffic. Why might that happen?
Scenario 6
Your API works inside the AKS cluster but cannot be accessed from the internet. Explain your troubleshooting approach.
Scenario 7
Database credentials are currently stored inside appsettings.json. How would you improve the security?
Scenario 8
You have a Service Bus queue. When messages increase from 1,000 to 1 million, how would your AKS workers automatically scale?

