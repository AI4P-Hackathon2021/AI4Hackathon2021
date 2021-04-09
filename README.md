### AI4Hackathon2021

## Installation Steps:

1. Setup a deployment environment with Pega PLatform 8.5.1
2. Login as administrator 
3. Import Ai4EV01.01.01_final.zip 
    https://github.com/AI4P-Hackathon2021/AI4Hackathon2021/blob/main/Ai4EV01.01.01.final.zip
3. Please change the password  [Admin.Ai4EV@ai4process.com / ] to login with admin for Ai4EV
4. Enable the OCR component in the Ai4EV application rule

## Steps to Test
Option 1. 
Steps to test

As a Guest:
------------
Option 1: 
Launch the Guest portal using following URL  https://ai401.pegalabs.io/prweb/PRAuth/Ai4EVGuest

Option 2:
Please login https://ai401.pegalabs.io/prweb/PRServlet using Admin.Ai4EV@ai4process.com  user id login.
And open the Guest Portal from Lauch Portal 

**Registration:**

Launch Registration casetype  from above options

Please download the driving Licence images from github.

Attach a driving license and select register as driver or vehicle owner and click on submit 

Customer and address details  will be fetched from driving license and displayed on screen

Click on submit to go to the next step - Collect License Details :  license id, license issue date,license expiry date  

and date of birth  will be extracted from driving license and displayed on screen 
A confirmation email will be sent to  user with one time password - ev123! which he is forced to change on first login 
Log  in with the one time password and change it on first login
User will be redirected to User Portal

As a Car Owner
---------------

**Host a Car**
Log in to User Portal with the emailid created
Click on Create menu and select "Become a host" case type to  host a vehicle.
Please download the image from github the Vehicle with number plate

Attach a vehicle image . Using an image recognition API , the vehicle plate number  is read   and  vehicle details such as:  
vehicle type , make , model , year and colour are autopopulated . 

Enter the current vehicle mileage and click on submit button

Upload  a second image  from the side to display to potential drivers and click on submit button
Please upload the Side view of the image which is in github.

The vehicle is  added and is now  available for selection. 


**Set a Car Available**

Click on Create Menu and select " Set a car available"

Select a vehicle from the drop-down. The values for vehicle registration, vehicle make , vehicle model will be autopopulated and a vehicle image of the available vehicle will be displayed. Click on Submit to proceed to next step.

Select a location for the vehicle to be picked up from.  The pick-up location is  auto-populated  when a pin is dropped on the map. Click on submit to proceed to next step
Set date from and date to for the new allocation and set the price per day.
Select pick-up and drop off times . 

A Summary of car availability  will be displayed on screen to review the booking . if changes need to be made, use can click back to go back and correct informtation  
Finally the vehicle is now live, and can be selected by a driver - displaying the confirmed  location PEGA passes the required information to Google map Reverse Geo Location Request  API to show the location in real-time. 


As a Driver
---------------

Search for a car
Driver logs in with one time password which he is prompted to change upon first login 
select  “Search for a Car” case type from Create menu in User Portal .
Enter  location , price  and  dates  in the search criteria . The  map automatically updates and  displays the vehicles which meet the search parameters. 
Select the car  in the google maps widget and basic information about the  car will be displayed on screen  
User can see the car which was hosted earlier by vehicle host. 
Select a new vehicle from the map that meets  your search criteria.  Click on  “About” button and  additional information will be prepopulated in the location, vehicle and availability details sections.
select a pick-up and drop-off time between the time window specified by the  owner. 
Next select the insurance coverage which meets your  needs when using the  vehicle. 
Lastly a summary is provided to the driver to confirm all details. Based on the level of insurance selected, calculations are performed to generate the required billing amounts etc. 
Basic contact information is displayed for the owner in the event driver  has a question. 
Once driver click on submit , booking summary is sent to vehicle owner for approval 
Owner logs in to the application, where he sees a new approval work item in their worklist. 
Once they select Go, user is  presented with all of the booking information, including the driver's contact details. 
Vehicle Host can add a comment, and either approve or reject the request. As  vehicle host approve the request,
Them driver will receive an email notification informing him that their request has been approved.
The driver has a new notification in their worklist to review the Rental Contract drafted by vehicle owner. 
As driver provide  banking details for the rental contract and clicks on submit
Then Submit the rental contract. The payment details are processed , and driver needs to wait until the last day of the contract. 
Wait for an email notification to appear in the worklist, to return the vehicle and complete the hand-over process. 
Complete a short questionnaire to generate a rating for their experience when using the vehicle, to build ratings of the owner. 
As driver click on submit, an email notification is sent to the owner to confirm the car has been dropped-off. 
As Owner you will receive an email  notification, in your  worklist, and comments will be available in the Pulse section. You will be 
presented with some basic information about the booking and a driver questionnaire is used to generate a rating for the driver. 

**Admin Portal**

1.Please login Ai4EV_Admin to view the reports and password Rules1234@
We can view the reports in dashboard and in admin reports section.


