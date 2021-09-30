import paho.mqtt.client as mqtt
import time
import random

a = 0
b = 0

def conectado(client, userdata, flags, rc):
    print("Connected with result code "+str(rc))

    client.subscribe("lady.medina1998@gmail.com/t1")

def nuevoMensaje(client, userdata, msg):
    print(msg.topic+" "+str(msg.payload))

    mensaje=msg.payload.decode('utf-8')
    if mensaje=='ON':
        print('ON')
        a = 1
    else:
           print('ON')
           a = 0

    if mensaje=='OFF':
        print('OFF')
        b=1
    else:
            b=0

client= mqtt.Client()  
client.username_pw_set('lady.medina1998@gmail.com', password='0986653890lady')
client.on_connect = conectado
client.on_message = nuevoMensaje

client.connect("maqiatto.com", 1883, 60)

def leerSensor1():
    return random.randint(0,1)
def leerSensor2():
    return random.randint(0,1)

while 1:
    time.sleep(1)
    valor1=leerSensor1()
    valor2=leerSensor2()
    sensor1=open('sensor1.txt','a')
    sensor1.write(str(valor1)+' \n')
    sensor2=open('sensor1.txt','a')
    sensor2.write(str(valor2)+' \n')
    
    if a==1:
        sensor1=open('sensor1.txt','r')
        valorSensor1=sensor1=sensor1.readlines()
        client.publish('lady.medina1998@gmail.com/t2',str(valor1)+'-'+str(valor2)+'-'+str(valorSensor1))


    elif b==1:
        sensor1=open('sensor2.txt','r')
        valorSensor2=sensor1=sensor1.readlines()
        client.publish('lady.medina1998@gmail.com/t2',str(valor1)+'-'+str(valor2)+'-'+str(valorSensor2))
        

    else:
          client.publish('lady.medina1998@gmail.com/t2',str(valor1)+'-'+str(valor2))
    client.loop()
   
