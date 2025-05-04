# Stored-XSS-via-SVG-Upload


**Vulnerability Name**: Stored XSS (Cross Site Scripting)

**Affected Component** : https://demo.horilla.com/

**Severity** : High

**Impact** : 
Execution of arbitrary JavaScript in the victim’s browser.
Account takeover by stealing session tokens or credentials.
Defacement or malicious redirections.

**Steps to Reproduce** :
Login to the application and Click on the attachment +
![image](https://github.com/user-attachments/assets/f65151db-9fcf-4b1b-bdcf-85add133cbca)

Enter the necessary detail and attach the following file XSS_SVG
![image](https://github.com/user-attachments/assets/7cd926a4-b52a-48f3-9547-6465b3a3298c)

Once done click on save and open up the newly created announcement.
![image](https://github.com/user-attachments/assets/4c9e0c20-2776-4448-a9ca-3dfe6d66cc18)

Open the image in a new tab and observe that the payload gets executed.
![image](https://github.com/user-attachments/assets/fa666aeb-ef89-4127-ba48-a0e7033c98da)
