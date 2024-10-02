# Mqtt-Commands-
Mqtt Commands 2024
# Brocker 

> docker run -it ubuntu:focal bash

<br>
> apt update
<br>
> apt install net-tools iputils-ping
<br>
> ls
<br>
> apt install mosquitto mosquitto-clients
<br>
> ls
<br>
> ps -ef   or    ps -ef |grep mosq
<br>
> service mosquitto start
<br>
> ifconfig
<br>
> > cat /etc/hosts
<br>
>
<br>
> ps -ef
<br>

#  Subscriber

> docker run -it ubuntu:focal bash
> ls
> apt update
> apt install net-tools iputils-ping
> apt install mosquitto mosquitto-clients
> ls
> ps -ef
> ifconfig
>
> to text with the subcripber
> uses the first  the run the contact the publish
>
> mosquitto_sub -v -h ip addres from the broker -t /
> > mosquitto_sub -v -h test.mosquitto.org -t /x00191146/di/door1
> 
> 


<br>
# Publicth 


> docker run -it ubuntu:focal bash
> ls
> apt update
> apt install net-tools iputils-ping
> apt install mosquitto mosquitto-clients
> ls
> ps -ef
> ifconfig
>
> to text with the subcripber
> get a contact the subcriber
>
> mosquitto_pub -h ip addres from the broker -t /
> mosquitto_pub -h 172. -t /x0019114617.0.2 -m "Hi how are you"
> 
> > mosquitto_pub -h test.mosquitto.org -t /x00191146 -m "Hi how are you"
> 
>mosquitto_pub -h test.mosquitto.org -t /x00191146/d1/door1 -m "open"
>
`






