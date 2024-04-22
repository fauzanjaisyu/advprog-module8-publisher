# advprog-module8-publisher

1. 5 kali. Karena publisher melakukan publish_event sebanyak 5 kali.

2. Artinya kedua program tersebut(publisher dan subscriber) terhubung ke server RabbitMQ yang sama.

Screen of running RabbitMQ
![Screen of running RabbitMQ](image/mqrabit.png)

# Screenshot terminal
![Screenshot terminal](image/subscriber-console.png)
Ini adalah kondisi terminal subscriber ketika menerima 5 event message dari publisher.

![Screenshot terminal](image/publisher-console.png)
Ini adalah kondisi terminal publisher ketika melakukan publish 5 event message.