# Завдання 1. Підготовка репозиторію та локальний запуск

a. http://localhost:8080/api/status:
![alt text](image.png)

b. http://localhost:8080/api/items?filter=a
![alt text](image-1.png)

c. http://localhost:8080/api/slow
![alt text](image-2.png)

d. http://localhost:8080/api/error
![alt text](image-3.png)

e. http://localhost:8080/healthz
![alt text](image-4.png)

f. http://localhost:8080/ready
![alt text](image-5.png)

# Завдання 2. Контейнеризація застосунку

docker build -t k8s-demo-app:1.0.0 .
![alt text](image-6.png)

docker run --rm -p 8080:8080 -e SECRET_TOKEN=local k8s-demo-app:1.0.0
![alt text](image-10.png)
![alt text](image-7.png)
![alt text](image-9.png)

# Завдання 3. Запуск Minikube та перевірка кластера

1. Запустити Minikube:
   ![alt text](image-12.png)

2. Переглянути список профілів (.\minikube profile list)
   ![alt text](image-13.png)

3. Перевірити та налаштувати контекст kubectl:
   ![alt text](image-14.png)

4. Перевірити стан кластера:
   ![alt text](image-15.png)

# Завдання 4. Розгортання Namespace, ConfigMap, Secret, Deployment, Service


