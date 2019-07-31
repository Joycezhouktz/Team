# Abstract

# 1.Introduction  

## 1.1 Background  

The rapid development of Chinese express industry has largely promoted the growth of food delivery sevice in catering industry. Recently, plenty of new food delivery apps were launched to facilitate such trend and the market now have attracted millions of consumers. One of the main reasons why consumers choose to order food deliveries is its convenience since consumers could make orders from food suppliers far away, then wait at home or office rather than going for a long way to pick up food. 
Here is a common scenario of food delivery: consumer orders a food delivery service on an app after selecting food, providing address and contact numbers. The app will then randomly releases the delivery task to a deliveryman. The deliveryman will hand the food over to the consumer face to face on his/her arrival.
Safety problems may occur during above face to face food handover. According to an recent investigation, 10 percent of consumers who ordered takeout confronted safety problems[](data). Those problems mostly are offensive behaviors of deliverymen to consumers in private places and consumers' information exposure. Food preservation and the stealing problems may also exist when food are left in destination if consumers are not there on deliverymen's arrival. Therefore above problems result in an increasing concern about the security problems existed in food delivery services.  
(data)  
In this project, we will paticularly focus on designing a high-tech receiving box which have functions of face recongnition, temperature-controlling and anti-stealing. It would prevent problems mentioned above and provide consumers with a safer and more convenient food delivery experiences.

### 1.2.1 Current approach  

In food delivery services, since the store of food is different from other goods, rapid face to face transaction is common. This is because food tend to get deteriorated or lose its original quality quickly after delivery. However, the face to face transcation would cause potential problems for both consumers and deliverymen. Thus, the most effective way to reduce such problems is to prevent direct contact between consumers and deliverymen. 
Most common ways that consumers use to prevent above direct contact currently is asking deliverymen to leave food outside of their doors or at public places in their living buildings, then go out and pick up the food after deliverymen have left. Even through potential problems are still there. For instance, it is not easy to confirm deliverymen really left or are still wandering nearby; the food might be stolen away. Currently, some buildings have already started to use receiving boxes to help residents to receive their products. Those boxes could be locked automatically after products be dropped in.
However, in food receiving scenario, if consumers don’t pick up their food immediately, the food, hot or iced food in particularly, would lose original quality in normal store box.
### 1.2.2  Existing approaches and their limitation  


## 1.3 Objective  
Our objective is providing comsumers a safer way to get takeout

# 2.Methdology  
## 2.1 Overview 
There are three main parts in our design: frame, software, and hardware. Frame is basically the box that contain all components. It also protects segments from being damaged by rain and wind. Software, the most elaborated part, is where everything else is bond together. Arduino helps with the controlling of the hardware and send data to the python code. Then the python code will work out the what will be done next and send data back for further operation. This continues in a loop. Last, the hardware has its job to collect data and display it to the user. This part consists of the output and input device. The buzzer to notify to user, the button to open the box, the insulation to keep food at its optimum temperature. Not a single part can be omitted. 

## 2.2 Hardware  
Insulation is used to keep food at the right temperature so the user can get the food at its optimum condition.

### 2.2.1 Alarm 
The alarm system can first detect the position to know when to open the case for food to be put in. Also, it is able to call the police if the delivery is around too long.

## 2.3 Face recognition device
This device will identify the position of the delivery and provide realtime data to the display and the alarm system. This device will aid the ability of detecting if the delivery man is around. The device will locate the face and add a rectangle surrounding it. Then, a counter(able to alter at any time) is set to count the time of the delivery man in front of the door. In a normal context, a circle will appear as well as notifying the user, when the face recognition device finds the absence of the delivery man. On the contrary, if the man stands there for a long time, the alarm will be set on. An additional function will be to identify whether the person standing is a family member or not. This function will help knowing if the person is safe to the user or not. Then, the alarm would not trigger, if a family memeber is standing in front of the door. 

## 2.4 Processing  
At first, when the user has ordered the takeout, this section will track down the delivery and will also help the detection of the alarm system

## 2.5 User Interface  
Basicly, a display. This part of the product can remind the user, when the takeout is in the box and has not been taken.

# 3.RESULTS AND DISCUSSION  
## 3.1 Assessment of Graph  
Face recognition
automatic lock
Can be applied in receiving other products delivery as well.

## 3.2 Assessment of Application  
Our main targets are the young generations as their parents has concerns over their safty as well as they might not be able to protect themselves.

# 4.CONCLUSION  

# 5.BIBLIOGRAPHY 
APA format
