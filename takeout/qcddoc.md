# Abstract

# 1.Introduction  

## 1.1 Background  

The rapid development of Chinese express industry has largely promoted the growth of food delivery sevice in catering industry. Recently, plenty of new food delivery apps were launched to facilitate such trend and the market now have attracted millions of users. One of the main reasons why users choose to order food deliveries is its convenience since users could make orders from food suppliers far away, then wait at home or office rather than going for a long way to pick up food. 

Here is a common scenario of food delivery: user orders a food delivery service on an app after selecting food, providing address and contact numbers. The app will then randomly releases the delivery task to a deliveryman. The deliveryman will hand the food over to the user face to face on his/her arrival.

Safety problems may occur during above face to face food handover. According to an recent investigation, 10 percent of consumers who ordered takeout confronted safety problems[](data). Those problems mostly are offensive behaviors of deliverymen to consumers in private places and consumers' information exposure. Food preservation and the stealing problems may also exist when food are left in destination if consumers are not there on deliverymen's arrival. Therefore above problems result in an increasing concern about the security problems existed in food delivery services.  (data)  

In this project, we will paticularly focus on designing a high-tech receiving box which have functions of face recongnition, temperature-controlling and anti-stealing. It would prevent problems mentioned above and provide consumers with a safer and more convenient food delivery experiences.

### 1.2.1 Current approach  

In food delivery services, since the store of food is different from other goods, rapid face to face transaction is common. This is because food tend to get deteriorated or lose its original quality quickly after delivery. However, the face to face transcation would cause potential problems for both consumers and deliverymen. Thus, the most effective way to reduce such problems is to prevent direct contact between consumers and deliverymen. 

Most common ways that consumers use to prevent above direct contact currently is asking deliverymen to leave food outside of their doors or at public places in their living buildings, then go out and pick up the food after deliverymen have left. Even through potential problems are still there. For instance, it is not easy to confirm deliverymen really left or are still wandering nearby; the food might be stolen away. Currently, some buildings have already started to use receiving boxes to help residents to receive their products. Those boxes could be locked automatically after products be dropped in.

However, in food receiving scenario, if consumers don’t pick up their food immediately, the food, hot or iced food in particularly, would lose original quality in normal store box.
### 1.2.2  Existing approaches and their limitation  


## 1.3 Objective  
Our objective is providing comsumers a safer way to get takeout.

# 2.Methdology  
## 2.1 Overview 
There are three main parts in our smart food receiving box: frame, software, and hardware. Firstly, frame is basically the box that contain all components inside. It also protects food from being damaged by rain and wind. Secondely, software, the most elaborated part, is where everything else is bonded together. Arduino is control center of hardware and it sends data to python data processing center. The python code process data in a loop, it works out what will be done next and sends data back for further operation. Last but not least, hardware collects data via sensor and display processed information to consumers. hardware consists of output and input devices which including a buzzer to notify consumers, a button to open the box, the insulation to keep food at its optimum temperature. All above parts are integrated together, not a single part can be omitted. 

## 2.2 Hardware  
Insulation is used to keep food at a right temperature so consumers can get the food at its optimum condition.

### 2.2.1 Alarm 
The alarm system can detect the position to know the right time to open the case for food to be dropped in. Also, it is able to call the police if the deliveryman is wandering around for too long.

## 2.3 Face recognition device
The part identifys the position of the deliveryman and provide real time data to the display and the alarm system. It will aid the ability of detecting if the deliveryman is around. It will locate the face and add a rectangle surrounding the face. Then, a counter(able to be altered at any time) is set to count the time of the deliveryman in front of the door. In a normal context, a circle will appear to notify the consumer when the face recognition device finds the absence of the deliveryman. On the contrary, if the man stands there for a long time, the alarm will be set on. An additional function is to identify whether the person is a family member or not. In default, the alarm would not trigger, if a family memeber is standing in front of the door. 
Is user able to change the configuration settings?  

## 2.4 Processing  
At first, when a consumer ordered a takeout, the section will start tracking down the delivery and also initial the detection of the alarm system.

## 2.5 User interface  
Basicly, it is a displayer. It is used to remind the user when the takeout was dropped in the box and has not been taken out.

# 3.RESULTS AND DISCUSSION  
## 3.1 Assessment of Graph  
Face recognition
automatic lock
Can be applied in receiving other products delivery as well.

## 3.2 Assessment of Application  
Main target users of the product are the young generations as their parents have concerns over their safety as well as they might not be able to protect themselves.

# 4.CONCLUSION  

# 5.BIBLIOGRAPHY 
APA format?
