Steps to install certificate:

Chrome and Internet Explorer

1-launch Ext_Certificate.cert file.

2-Click on the install certificate option.

3-Navigate to next and choose option "Place all certificates in the following store".

4-Browse and choose "Trusted Root Certification Authorities".

5-Click on the next and finish it



Firefox

1-Launch Cognizant Intelligent Test Scripter and open either Spy,Heal or Recorder.

2-Launch firefox browser and navigate to Options>Advanced>Certificates.

3-Select the option "Select one automatically".

4-Click on View Certificate,navigate to Servers and then click on Add exception.

5-Give the URL as https://localhost:8887.

6-Click on the "Get Certificate" and "Confirm Security Exception".

7-In case you are facing any challenges adding the security certificate ,make sure to perform following operations:
	a)Open Internet Options.
	b)Navigate to Connections>Lan Settings>Advanced
	c)In the exceptions area add "localhost".
	d)Save the settings and again try to add certificate.