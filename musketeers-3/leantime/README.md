# Leantime  

## Description  
Leantime is a free, open-source project management software designed for ADHD, ADD, and all brains, streamlining tasks, boosting productivity & collaboration.

## Chart
Used chart: gissilabs/leantime --version 1.2.1

## Docker-images
Used images: mariadb -- 10.6.17
             leantime/leantime

## Deployment  
kubectl apply -f _namespace.yaml
kubectl apply -f leantime-helmrepository.yaml
kubectl apply -f leantime-db-secret.yaml
kubectl apply -f leantime-helmrelease.yaml
