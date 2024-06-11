# Kubernetes Deployment, Service, Pod, and ReplicaSet Examples

This repository contains sample YAML scripts demonstrating the concepts of Deployments, Services, Pods, and ReplicaSets in Kubernetes.

## Pods

Pods are the smallest deployable units in Kubernetes, consisting of one or more containers. They share the same network namespace and can communicate with each other using localhost.

## ReplicaSets

ReplicaSets ensure that a specified number of Pod replicas are running at any given time. They are the next-generation ReplicationController with more powerful features.

## Deployments

Deployments in Kubernetes provide a declarative way to manage application deployments. They ensure that a specified number of pod replicas are running at any given time.

## Services

Services in Kubernetes enable communication between different sets of Pods. They provide a consistent endpoint to access one or more Pods.
