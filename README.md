### QHACKS 2023 WINNERS!
## FEED SHAKIRA
Meet our intern room fish SHAKIRA!

<img src="https://github.com/ChahitUppal/feed_shakira/assets/71035269/ccb9f599-4800-4f8b-b7cd-63c56cd7b96f" alt="image" width="300">



[Video](https://qualcomm-my.sharepoint.com/:v:/p/shehata_qti/EZMsvYgL8D5MkqIPFp4EpKUBpx3D6tjhTKpRWfwsofGn1w?e=Eg8kxs)

# Background
Our lovely fish needs to be fed regularly to maintain a healthy lifestyle. However, with a 5-day work week, we have to plan ahead on how we will provide him on weekends.

![image](https://github.com/ChahitUppal/feed_shakira/assets/71035269/59c7b087-1f7e-474b-bff5-f85c4cf64199)


# Motivation
The care and welfare of our fish in the intern room will be significantly enhanced by the installation of an automatic fish feeder. The feeder will guarantee a timely and regular food supply, avoiding under- or overfeeding. Scheduled feedings support a balanced diet and encourage healthy growth and development. The automation also reduces the possibility of human error or forgetfulness when feeding the fish, improving their chances of survival. As the fish get used to the regular feeding schedule, their stress levels will decrease. This hands-free method also enables interns to concentrate on their job without being concerned about manual feeding, promoting a pleasant and tranquil work atmosphere.

https://github.com/ChahitUppal/feed_shakira/assets/71035269/d30b20f8-e054-4991-94f6-b304388a93a1


# Algorithm Design

We decided to use a servo motor to have a closed-loop feedback system to achieve precise feeder movement. We used an Arduino Nano 33 BLE to control our feeder throughout the week. We used the Protothreads library to run the timer and a Neural Network simultaneously. The feeder feeds when the internal timer hits 6 hrs or when the microphone senses someone saying "Feed Shakira". We created our audio classification using edge impulse and received a 90% accuracy while using 38.5K RAM and 121.4K flash storage
![image](https://github.com/ChahitUppal/feed_shakira/assets/71035269/e943d162-ba82-4cf6-942f-c9029b9382a4)

# CAD design

![image](https://github.com/ChahitUppal/feed_shakira/assets/71035269/580e11db-970c-4b37-9a24-4fcfa797c62d)


