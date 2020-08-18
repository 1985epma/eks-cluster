<h4>EKS-cluster</h4>

Required Tools<BR>
	
-AWS CLI<BR>
-KUBECTL<BR>
-TERRAFORM CLI<BR>
	
	
	
Preparation for EKS Cluster

Now run the following:
terraform init
terraform plan

This will download the appropriate modules and providers, and show what will be created when we decide to apply this.

Create the EKS Cluster

Once satisfied, we can now create the cluster, an Amazon EKS Kubernetes master node, plus 2 Amazon EC2 instances that will be the Kubernetes worker nodes.
