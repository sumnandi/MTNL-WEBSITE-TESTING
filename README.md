# MTNL-WEBSITE-AUTOMATION-TESTING
In this project rigorous testing is done on the MTNL Website. After testing the website various faults were found and are depicted along with their severity level.

## TABLE OF CONTENTS

1. Functional Testing
2. Navigation Testing
3. Cross Browser Testing
4. Form Based Testing
5. Performance Testing
6. Database Testing
7. Security Testing

## PERFORMANCE TESTING
### LOAD TESTING (TOOL USED: APACHE JMETER)
The average throughput achieved is 146.71 Hits/sec.

![image](https://github.com/sumnandi/MTNL-WEBSITE-TESTING/blob/main/Load%20Test%20Graph.png)


### PERFORMANCE TESTING (TOOL USED: APACHE JMETER)
The average response time achieved is 164.52 millisecond.

![image](https://github.com/sumnandi/MTNL-WEBSITE-TESTING/blob/main/Response%20Time%20Graph.png)


## AUTOMATION TOOL USED : DUCK CREEK TEST AUTOMATION (TAC) ![image](https://github.com/sumnandi/MTNL-WEBSITE-TESTING/blob/main/DuckCreekLogo_1.PNG)
### TAC FRAMEWORK :
![image](https://github.com/sumnandi/MTNL-WEBSITE-TESTING/blob/main/TAC%20Framework.png)

### DATABASE TESTING (TAC) RESULTS
![image](https://github.com/sumnandi/MTNL-WEBSITE-TESTING/blob/main/TAC%20Results.png)

## CONCLUSION
The List of faults are as follows: 

#### 1.	FUNCTIONAL TESTING FAULTS:
  * Accepting Toll Free Numbers for Recharge      **_(Severity: Medium)_**
  *	Accepting Mobile Numbers of other Mobile Service Providers      **_(Severity: Medium)_**

#### 2.	NAVIGATION TESTING FAULTS:
* Dead Link Found: Mobile Recharge      **_(Severity: HIGH)_**
* Dead Link Found: Mobile Complaint     **_(Severity: HIGH)_**
* Dead Link Found: Broadband Service Request      **_(Severity: HIGH)_**
* Dead Link Found: Landline Shifting      **_(Severity: HIGH)_**

#### 3.	FORM BASED TESTING FAULTS:
* Accepting blanks in First name and last name      **_(Severity: HIGH)_**
* Accepting Symbols in Locality Field     **_(Severity: HIGH)_**
* Accepting invalid Email ID      **_(Severity: HIGH)_**

#### 4.	DATABASE TESTING FAULTS:
* Customer Address is not saved. Address 3 linking is not done.	**_(Severity: HIGH)_**
* Service Type is not displayed on selecting ‘FTTH’.			**_(Severity: HIGH)_**

### TABULAR VIEW:

FAULTS SEVERITY | COUNT
----------------|------------
MEDIUM	        |   2
HIGH            |   9
**TOTAL**       | **11**


