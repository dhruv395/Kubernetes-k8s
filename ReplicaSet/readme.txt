Concept
~~~~~~
#What & Why ReplicaSet
It ensures that a specified no of pods are running at any time.
it's next generation replication controller.

#What are Labels & Selectors
ReplicaSet and pods are associated with labels.

#Difference between Equality-based and Set-based selectors
			Eqality | Set-Based
Operators: = 	==	!=	| in	notin	exists

- equality based selector supports service, replication controller.
- set based selector supports job, deployment,replica set and daemon set.


Demo (Review):
~~~~~~~~~~~~~~
ReplicaSet Manifest
Deploy application with ReplicaSet
Display and validate
Test Cases
Clean up
