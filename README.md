# EnvYard2.0

#Inspiration
Only last year over 3 Mha were lost in Asia due to deforestation for agricultural purposes. In Africa is even more sensitive because many endangered species of animals lost their habitats and have to be put in shelters. But the problem is that the population need a source of food and it seems like a big compromise regarding environmental ethics.

Some papers were published which describe the way multilevel greenhouses would work. They would save a lot of space and help with the plantation separation. There are some plantations of this kind in Asia, but they don't meet the expectation regarding production. A way in which the production needs might be meet would be to create a sustainable, autonomous system to maintain the plants from the greenhouse. It is more efficient than human work.

#What it does
The project is in the idea state, by presenting a simulation and an administration platform in order to perform supervision of the plantations the farmers own.

The EnyYard is a simulation of a system which provides the services for optimal plantation maintenance. The greenhouse would have the following features:

1. Solar Cells to provide power for the system. There is a panel to provide the power level. In the simulation we found out that the construction provides enough power during the day. In order to provide enough energy for the system, we considered introducing hydropower.
2. IoT devices for maintenance of the plantations: sprinklers, servo, humidifiers, etc. 3.
3. Cameras to inspect the fields in real-time, using an Vision API in order to detect the health of the plants and for the AR view.
4. We also provide a platform for statistics and predictions for the farmers to see their plantations' status.

#How we built it

For the hardware mock-up we used Packet Tracer with the IoT Suite which it provides. We managed to add conditions for maintenance, which are checked in real-time. The hosting is on a public VM from Azure. The dashboard is created in Power BI. Unfortunately, it is available only on Desktop, because the university account we used doesn't allow web public deployment. The dashboard is connected to an SQL Database from Azure. The Vision AI and predictions services are available to be loaded on the IoT devices, like https://azure.github.io/Vision-AI-DevKit-Pages/, and are uploaded in the repo.

#Challenges we ran into
First of all, the fact that we couldn't deploy the dashboard on web was a bummer. Second of all, the simulator from Packet Tracer was limited regarding the number of devices connected in order to not overload the network (the Packet Tracer simulator is more visual and that was the reason why we choose it).

#Accomplishments that we're proud of
The fact that we accomplished to create a functional hardware mock-up is a good thing, because we tried to highlight the idea more than the service and the performance part. Also, we think we will use Power BI in the future for the MVP.

#What we learned
We learned how to work with the Azure portal better than before: VM networking, Visual Development Kit fit IoT and Power BI. Also, we took a next step in learning about Packet Tracer and how the simulators work.

#What's next for EnvYard2.0
The previous iteration the former team accomplished to create the AR view for the greenhouse, available here https://devpost.com/software/envyard. This second project confirmed what services and technologies to use in order to continue the project. In the following months, we intent to build a prototype of the greenhouse and present it to other event. If it proves to be a good invention (which we personally hope it is), we would apply for grants in order to build a full size greenhouse to grow a vineyard plantation in our home country. In time, we hope to extend to other plantation kinds and to implement the system in the places where are needed (Africa especially).
