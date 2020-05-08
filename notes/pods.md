## Some basic concepts of writing yamls
	# Pods
	1. There are 4 top level fields
		a. apiVersion (this specifies which kubernetes apiVersion we will be using)
		b. kind (this specifies which kind of objects we will be using. eg. pod/deployment/service etc)
		c. metadata (as the name suggests this is data i.e basic info about our object which we will be deploying)
		d. spec (this section specifies all the parameters for our object like name, imagename etc)

	# Replicas
	1. There are two ways to replicate pods in kubernetes.
		a. replication controller (v1)
		b. replicaset (apps/v1)
	2. Major difference between these two is replicaset requires additional
	selector to select which pods should be replicated.