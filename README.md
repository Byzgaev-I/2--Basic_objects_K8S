# Домашнее задание к занятию «Базовые объекты K8S»

## Цель задания

В тестовой среде для работы с Kubernetes, установленной в предыдущем ДЗ, необходимо развернуть Pod с приложением и подключиться к нему со своего локального компьютера.

## Задание 1. Создать Pod с именем hello-world

1. Создан манифест hello-world-pod.yaml для создания Pod
2. Использован образ - gcr.io/kubernetes-e2e-test-images/echoserver:2.2
3. Выполнено подключение к Pod с помощью port-forward и проверена работоспособность

## Задание 2. Создать Service и подключить его к Pod

1. Создан манифест netology-web-pod.yaml для создания Pod
2. Создан манифест netology-svc.yaml для создания Service
3. Service успешно подключен к Pod

## Использованные манифесты

Все манифесты находятся в директории manifests:
- hello-world-pod.yaml
- netology-web-pod.yaml
- netology-svc.yaml

