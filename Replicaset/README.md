## ReplicaSet 101

#### Objective

Learn how to create and view ReplicaSets

#### Instructions

1. Create a ReplicaSet with 2 replicas. The app can be anything.
2. Verify a ReplicaSet was created and there are 2 replicas
3. Delete one of the Pods the ReplicaSet has created
4. If you'll list all the Pods now, what will you see?
5. Remove the ReplicaSet you've created
6. Verify you've deleted the ReplicaSet

## Ans
**RelicaSet** A ReplicaSet's purpose is to maintain a stable set of replica Pods running at any given time. As such, it is often used to guarantee the availability of a specified number of identical Pods.

A ReplicaSet then fulfills its purpose by creating and deleting Pods as needed to reach the desired number. When a ReplicaSet needs to create new Pods, it uses its Pod template.