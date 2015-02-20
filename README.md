# owasp-jenkins

Introduction

This is a command line security/vulnerability testing tool which was created for continues security testing. This exe file can be used in any CI tool which can execute Windows Batch Commands.
How to Use

You need to have ZAP Proxy running on your machine in order to run this tool. You can download the zap proxy from here.
https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project

In ZAP Proxy do the following configuration.
•	Tools -> Options -> Local Proxy. Change the Port to 8090

Configuration with CI Tool

This tool takes five command line parameters.
1.	URL of the Web Application
2.	URL of the Login Page
3.	UserName of the user
4.	Password of the user
5.	Email Addresses foe sending the vulnerabilities.

Ex :- 

ZapPenTester.exe  http://example.com/ http://example.com/login/ user1 mypassoword user@gmail.com
