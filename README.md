# Les27

## 1. Створення RDS інстансу в приватній підмережі.
![1](https://github.com/user-attachments/assets/ddf635cc-ed94-43f0-868e-427f18e716dc)


## 2. Створення Bastion host в публічній підмережі для доступу до БД.

![2](https://github.com/user-attachments/assets/83d210c7-84bf-442d-a68a-6f80456cfa73)


## 3. Підключення до БД через Bastion host та прокидання портів.

### - ssh -i "aws.pem" -L 3306:library-db.czi6k4ceafb1.eu-north-1.rds.amazonaws.com:3306 ubuntu@ec2-51-21-132-185.eu-north-1.compute.amazonaws.com

![5](https://github.com/user-attachments/assets/d4347f0a-6415-4d9a-aae3-4925d02e4a59)
![4](https://github.com/user-attachments/assets/a27ab160-c9b7-4bc8-b07c-ea9457de463f)
![3](https://github.com/user-attachments/assets/4546b669-059b-4e74-a7fb-38f9482dd215)

## 4. Створення БД libary, таблиць та наповнення їх даними.
![6](https://github.com/user-attachments/assets/b16f7ac5-ce1c-42dc-a2ca-5b8061b537e8)


## 5. Виконання запитів
![8](https://github.com/user-attachments/assets/41d70c60-7cda-473e-8aff-c4801ee0594e)
![7](https://github.com/user-attachments/assets/85f09d23-7ac6-4260-856d-3cccc5f5663a)


## 6. Налаштування доступу
![9](https://github.com/user-attachments/assets/2a449f45-8afb-4c21-a616-dab8920d193e)


## 7. Моніторинг та резервне копіювання
![11](https://github.com/user-attachments/assets/fc83d7c0-47bc-433f-bc72-cd4478a8594d)
![10](https://github.com/user-attachments/assets/67c82e28-dfc8-4b4c-9b9f-f5e71a831549)
