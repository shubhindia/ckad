## Replicas
	1. There are two ways to replicate pods in kubernetes.
		a. replication controller (v1)
		b. replicaset (apps/v1)
	2. Major difference between these two is replicaset requires additional
	selector to select which pods should be replicated.