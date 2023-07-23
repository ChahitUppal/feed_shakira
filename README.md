## FEED SHAKIRA
Meet our intern room fish SHAKIRA!

<img src="https://github.com/ChahitUppal/feed_shakira/assets/71035269/d6666d4b-dca5-459d-920e-4fb038307a18" alt="image" width="200" height="200">

# Background
Our lovely fish needs to be fed regularly to maintain a healthy lifestyle. However, with a 5-day work week, we have to plan ahead on how we will provide him on weekends.

<img src="https://github.com/ChahitUppal/feed_shakira/assets/71035269/11100cf9-676d-4c3a-bc30-d4f6d0990199" alt="image" width="300" height="250">

# Motivation
The care and welfare of our fish in the intern room will be significantly enhanced by the installation of an automatic fish feeder. The feeder will guarantee a timely and regular food supply, avoiding under- or overfeeding. Scheduled feedings support a balanced diet and encourage healthy growth and development. The automation also reduces the possibility of human error or forgetfulness when feeding the fish, improving their chances of survival. As the fish get used to the regular feeding schedule, their stress levels will decrease. This hands-free method also enables interns to concentrate on their job without being concerned about manual feeding, promoting a pleasant and tranquil work atmosphere.


https://github.com/ChahitUppal/feed_shakira/assets/71035269/bc1c37ee-d544-47bb-8797-dbeb0256b9ed

# Design

We decided to use a servo motor to have a closed-loop feedback system to achieve precise feeder movement. We used an Arduino Nano 33 BLE to control our feeder throughout the week. We used the Protothreads library to run the timer and a Neural Network simultaneously. The feeder feeds when the internal timer hits 6 hrs or when the microphone senses someone saying "Feed Shakira". We created our audio classification using edge impulse and received a 90% accuracy while using 38.5K RAM and 121.4K flash storage
![image](https://github.com/ChahitUppal/feed_shakira/assets/71035269/d3007f6c-2190-4bb9-8d21-d2441ed3e742)

# Final working design


