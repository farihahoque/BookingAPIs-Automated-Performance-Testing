# BookingAPIs-Automated-Performance-Testing
This project demonstrates load testing using JMeter, involving PUT, POST, and GET requests to evaluate the efficiency and stability of the Booking API under various conditions.

### **Features**

- PUT, POST, GET Requests: Tests cover essential HTTP methods to ensure comprehensive API performance evaluation.
-Load Testing: Simulating multiple users accessing the API simultaneously to assess its ability to handle high traffic.
-Performance Metrics: Gathering and analyzing response times, throughput, and error rates using 600-1200 users.
-Report: Simulation is done from non-gui mode and reports are made.


### **Technology used:**
- JMeter

### **Installation**

-Download JMeter:
Go to the -Apache JMeter website.
Download the latest version of JMeter (ZIP file).

-Extract the ZIP file:
Extract the downloaded ZIP file to a desired directory (e.g., C:\jmeter).

-Set Up Environment Variables:

Open the Control Panel, go to System and Security > System > Advanced system settings.
Click on "Environment Variables".
Under "System Variables", click "New" and create a new variable:
Variable name: JMETER_HOME
Variable value: C:\jmeter\apache-jmeter-x.x (replace with the actual path where JMeter is extracted).
Find the "Path" variable under "System Variables", select it, and click "Edit".
Click "New" and add the path to JMeter's bin directory (e.g., C:\jmeter\apache-jmeter-x.x\bin).

-Verify the Installation:
Open Command Prompt.
Type jmeter -v and press Enter.
If installed correctly, you will see the JMeter version information.
  
