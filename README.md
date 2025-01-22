<h1 style="color:blue;text-align:center;">These are the Instructions To follow</h1>

Apex handler
UseCase : This use case works for Amount Distribution for each Service the customer selected for there Vehicle.

1) Login to the respective trailhead account and navigate to the gear icon in the top right corner.
2) Click on the Developer console. Now you will see a new console window.
3) In the toolbar, you can see FILE. Click on it and navigate to new and create New apex class.
4) Name the class as “AmountDistributionHandler ”.



![Screenshot 2025-01-08 150424](https://github.com/user-attachments/assets/6de96fe7-9d1d-4b29-87a2-d2ce649cff2f)



![Screenshot 2025-01-08 150552](https://github.com/user-attachments/assets/50858396-a372-444f-890b-79de1524eaf8)

Trigger Handler :

How to create a new trigger :

1) While still in the trailhead account, navigate to the gear icon in the top right corner.
2) Click on developer console and you will be navigated to a new console window.
3) Click on File menu in the tool bar, and click on new? Trigger.
4) Enter the trigger name and the object to be triggered.
5) Name  : AmountDistribution
6) sObject : Appointment__c


![Screenshot 2025-01-08 150736](https://github.com/user-attachments/assets/36603015-263e-4865-960b-b7f68f7ba081)



Syntax For creating trigger :


The syntax for creating trigger is :


Trigger [trigger name] on [object name]( Before/After event)

{


}

In this project , trigger is called whenever the particular records sum exceed the threshold i.e minimum business requirement value. Then the code in the trigger will get executed.


![Screenshot 2025-01-08 150819](https://github.com/user-attachments/assets/e5032187-63f8-4ecf-a7c1-1e0284f529c8)



<h1>Demo Video </h1>
https://youtu.be/Yi_To5UHawA?si=e9J7G1V7MOpOuMU8

