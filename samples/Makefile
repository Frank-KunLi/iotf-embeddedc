all: sampleDevice helloWorld

sampleDevice: sampleDevice.c
	$(CC) sampleDevice.c -I ./../ -I ./../lib ./../iotfclient.c ./../lib/MQTTClient.c ./../lib/MQTTLinux.c ./../lib/MQTTFormat.c  ./../lib/MQTTPacket.c ./../lib/MQTTDeserializePublish.c ./../lib/MQTTConnectClient.c ./../lib/MQTTSubscribeClient.c ./../lib/MQTTSerializePublish.c ./../lib/MQTTConnectServer.c ./../lib/MQTTSubscribeServer.c ./../lib/MQTTUnsubscribeServer.c ./../lib/MQTTUnsubscribeClient.c -o $@
	strip $@

helloWorld: helloWorld.c
	$(CC) helloWorld.c -I ./../ -I ./../lib ./../iotfclient.c ./../lib/MQTTClient.c ./../lib/MQTTLinux.c ./../lib/MQTTFormat.c  ./../lib/MQTTPacket.c ./../lib/MQTTDeserializePublish.c ./../lib/MQTTConnectClient.c ./../lib/MQTTSubscribeClient.c ./../lib/MQTTSerializePublish.c ./../lib/MQTTConnectServer.c ./../lib/MQTTSubscribeServer.c ./../lib/MQTTUnsubscribeServer.c ./../lib/MQTTUnsubscribeClient.c -o $@
	strip $@

clean:
	rm -f sampleDevice helloWorld
