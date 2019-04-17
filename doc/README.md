# AWS IoT Core Instructions

Goto [AWS IoT Core](https://console.aws.amazon.com/iot) on your [AWS console](https://console.aws.amazon.com)

## Create a Policy

1. Generate a **Policy** first
![1-policy-create](https://github.com/debsahu/ESP-MQTT-AWS-IoT-Core/blob/master/doc/1-policy-create.png)

2. Create a Policy details
- Provide a **Name**
- **Action: `iot:*`**
- **Resource ARM: `*`**
- **Effect: Allow**
![2-policy-create](https://github.com/debsahu/ESP-MQTT-AWS-IoT-Core/blob/master/doc/2-policy-create.png)

## Create a Thing

1. Create a **Thing** first
![1-thing-create](https://github.com/debsahu/ESP-MQTT-AWS-IoT-Core/blob/master/doc/1-thing-create.png)

2. Single Thing
- Create a AWS IoT Thing
![2-thing-single](https://github.com/debsahu/ESP-MQTT-AWS-IoT-Core/blob/master/doc/2-thing-single.png)

3. Thing Name
- Provide a **Name** to the Thing
- Copy thing name into **THINGNAME**
- Click **Next**
![3-thing-name](https://github.com/debsahu/ESP-MQTT-AWS-IoT-Core/blob/master/doc/3-thing-name.png)

4. Create Certificates
- Click on **Create Certificate**
![4-thing-create-certs](https://github.com/debsahu/ESP-MQTT-AWS-IoT-Core/blob/master/doc/4-thing-create-certs.png)

5. Download Certificates
Download the following
- Contents for **client_cert[]** from **XXXXXXXXXX.cert.pem**
- Contents for **privkey[]** from **XXXXXXXXXX.private.key**
- Contents for **cacert[]** from **[Root CA for AWS](https://docs.aws.amazon.com/iot/latest/developerguide/managing-device-certs.html#server-authentication)**
![5-thing-download-activate-certs](https://github.com/debsahu/ESP-MQTT-AWS-IoT-Core/blob/master/doc/5-thing-download-activate-certs.png)

6. Download the Root CA Certificate
- Download the **RSA 2048 bit key**
![6-thing-root-ca-cert](https://github.com/debsahu/ESP-MQTT-AWS-IoT-Core/blob/master/doc/6-thing-root-ca-cert.png)

7. Attached the Policy created from step above
![7-thing-policy-attach](https://github.com/debsahu/ESP-MQTT-AWS-IoT-Core/blob/master/doc/7-thing-policy-attach.png)

8. Interact with AWs IoT Core
- look for HTTP end point and copt it into **MQTT_HOST[]**
- Copy thing name into **THINGNAME** (same name from step 3)
![8-thing-endpoint](https://github.com/debsahu/ESP-MQTT-AWS-IoT-Core/blob/master/doc/8-thing-endpoint.png)











