# JIRA
Execute testcase in JIRA using SopaUI.
Tool used : SoapUI
The suite will create TestCycle first --> Add testCase to cycle and then Execute the testcase.
JIRA do not provide API to execute testcase directly on JIRA. You have to use ZAPI add on to achieve this. But this is paid not free.
Generate AccessKey and Secret Key in ZAPI.
JWT Token : https://stackoverflow.com/questions/48298900/how-to-generate-jwt-token-for-jira-api
Add 'commons-codec-1.11.jar' and 'commons-lang-2.6.jar' in lib folder.
Add 'jwt-generator.jar' and 'zfj-cloud-rest-client-3.0.jar' in bin -> ext folder.