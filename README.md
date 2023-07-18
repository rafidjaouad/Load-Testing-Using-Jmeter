# Load-Testing-Using-Jmeter
Website Load Testing Using Jmeter

**First download and install the Jmeter software for hardware.**
Link: https://jmeter.apache.org/download_jmeter.cgi

![image](https://github.com/rafidjaouad/Load-Testing-Using-Jmeter/assets/132584373/af828978-13de-4c96-989f-d06f97d4336b)

**Open Jmeter tool:**
After extract the file go to -> apache-jmeter-5.6.2\bin  and click on jmeter.bat

**Preview of the software**
![image](https://github.com/rafidjaouad/Load-Testing-Using-Jmeter/assets/132584373/f641e13f-7f24-4c0b-81d7-d3c4f0309021)

**This is a test on Daraz's website**

1: Create a test plan and then add a thread group

![image](https://github.com/rafidjaouad/Load-Testing-Using-Jmeter/assets/132584373/5651e22a-63d5-49e7-850e-8c926171555e)

2: Set the software with your desired values
![image](https://github.com/rafidjaouad/Load-Testing-Using-Jmeter/assets/132584373/254ccbdc-6505-4b69-bc32-b2195bef3046)

3: Right-click on the thread group and add HTTP Request 
![image](https://github.com/rafidjaouad/Load-Testing-Using-Jmeter/assets/132584373/db93460f-204e-49ba-b5da-ba94f53092a0)
Set any name for it. 

Calling a Get API
• Add a Thread Group:
• TestPlan->Add-> Threads->Thread Group
• Add an HTTP Request:
• Thread Group->Add->Sampler->HTTP Request
• Rename the HTTP Request name
• Fill up the following properties
• Protocol: http or https
• Server Name or IP: demoqa.com
• Port Number: 80 or 443
• Method: GET
• Path: /BookStore/v1/Books

4: Set those values as per as you are website you are testing save it and run.
![image](https://github.com/rafidjaouad/Load-Testing-Using-Jmeter/assets/132584373/3429828a-b177-4f4a-a26d-06c529fc5111)

