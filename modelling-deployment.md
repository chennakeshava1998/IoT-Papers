#### Living in the Cloud or on the Edge: Opportunities and Challenges of IOT Application Architecture

##### Introduction:
IoT technology brought in the sensing plus communication on shared protocols devices, which can provide real-time data regarding the environment. Besides, the availablity of low-cost devices has also ushered in an era of performing computations on devices which are at the edge of the network.

This brings in new challenges in non-functional requirements like modelling, deployment, security, privacy, etc. This paper addresses the challenges of deployment and modelling in these situations.

Using powerful edge devices, IoT devices can offload a significant portion of their bussiness logic and processing requirements onto the edge devices. Technical advantages of this new idea are - *lesser latency, lesser communication overhead, provenance detection, privacy and security.*

##### Examples:
1. **Smart Hospital:** We can have multiple rooms full of sensors like temperatue, blood pressure, sugar levels, etc which alert the hospital staff if any of the readings goes beyong the threshold values. Also, a low-cost computer like a Raspberry Pi/Personal Computer may be crunching data from all the rooms for the processing purposes.
2. **Smart Rails:** Every wheel in a train can be fitted with 8-10 sensors to measure quantities like vibrations, torque, etc and data from each wheel can be sent to a small processing unit on a train car. This unit performs some processing and sends the data to a main computer of the train, which recieves data from all the train-cars. There are about eight wheels in every car, and every unit in a train-car is responsible to perform a small amount of computation. Also, the main computer an a train, may perform some computations on the data, and may further send it to a cloud, from where the company can keep track of the states of all the running trains.

##### IoT Applications:
Deployment and modelling of distributed systems is hard in itself. But the modelling of distributed IoT applications prove even more harder, because of the *large number of devices, their sensitivity to non-functional requirements, their diverse nature and heterogenety, etc.*

Most often, modelling of these types of IoT applications demands extensive domain knowledge. But, from a deployment perpective, it also needs to be robust to the dynamic changes in the environment. For instance, we must decide what type of data  to process on the train and what data to send over to the cloud. But this decision, must incorporate the possiility of dynamic changes in the number of train-cars. Having a tradeoff between this type of decoupling and deployment aware modelling is an active area of research.

