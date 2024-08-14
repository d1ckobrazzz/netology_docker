# netology_docker

# задание 1
  
  https://hub.docker.com/repository/docker/dckbrz/custom-nginx/general

  

# задание 2

  ![netology](https://github.com/user-attachments/assets/17e5b0c8-290e-4215-9e75-9052034a9fa3)

  

# задание 3
  
  ## 1-3

  ![task 3](https://github.com/user-attachments/assets/e4a11bf2-dda1-42e0-a255-12ad41209c10)
  
  причина в том, что команда attach подключает оператора к сеансу терминала, в котором работает сам контейнер. Нажание CTRL+C отправляет сигнал прерывания процессу (SIGINT), в следствие чего контейнер останавливается

  ## 4-10
  
  ![task 3_2](https://github.com/user-attachments/assets/11e87d86-e9bd-4c7e-a9d3-3b6084de8460)
  
  причина в том, что в порт 8080 хоста пробрасывается 80 порт контейнера, на котором изначально висел nginx, после правки конфигурации и перечитывания конфига nginx начал слушать 81 порт, который не проброшен в хост систему
  
  ## 11
  
  под wsl схема правки порта иная, правка конфига в лоб к успеху не привела, у меня не получилось поменять порт без удаления контейнера
  
  ## 12
  
  ![task 3_3](https://github.com/user-attachments/assets/4a8ca03b-a052-42cb-b5ed-ebb439b4c2ff)
  
  docker rm -f custom-nginx-t2

  

# задание 4
  
  ![task4](https://github.com/user-attachments/assets/b4c0ccf0-a35d-4aff-aac4-a8f3997c9b05)

  

# задание 5

  ## 1
    compose допускает несколько названий конфигурационных файлов, compose.yaml является предпочтительным в случае наличия нескольких файлов описаний
    
  ## 2
    include:
    - docker-compose.yaml #subtask 2
  
  ![task5](https://github.com/user-attachments/assets/40d2a09a-4ae8-4a7f-867b-c74001829ac9)
    
  ## 3-5
    
  ![task5_5](https://github.com/user-attachments/assets/82d69165-9b20-4f1a-aa71-f239c2d607fc)
    
  ## 6
    
  ![task5_6](https://github.com/user-attachments/assets/32f6a15e-7123-4add-ade5-17335cb59698)
    
