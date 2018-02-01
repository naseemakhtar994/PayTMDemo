Step 1.Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}


Step 2. Add the dependency

	dependencies {
	        compile 'com.github.Sameer-Jani-201:PayTMDemo:-SNAPSHOT'
	}


How to setup paytm account?
----------------------------------------------

->Create your paytm account using mobile number, emailid(option) and password.
-> open this link https://business.paytm.com then go for business signup from right top side menu.
-> Go for 'Payment Gateway for Website/App.
-> If you want to create LIVE account then you need to enter all given data shown in first form.
-> and if you want to create stagging (Testing) account please find 'Developers looking to access Sandbox: Click here' and click on it.
-> To Generate Sandbox Credentials add company name,yourname,email id,accept payment on app/web or both select option from given choice and add app url and weburl.
-> Select Dev Platform. if selected other then enter Callback URL.
-> after successfully register you will get bellow details::

	Sandbox Merchant ID?
	Website Url = ?
	App Url = ?
	Sandbox Merchant Key = ?
	Channel Id = ?
	Industry Type = ?

	Dashboard Login Details
	Merchant Panel Link = ?
	User Name = ?
	Password = ?



----------------------------------------------
Now we are going to explain paytm android demo
----------------------------------------------

-> For android paytm we need to add PGSDK_V2.1.jar file in lib folder.
-> If You have Auth Certificate then keep it in res/raw folder and create PaytmClientCertificate by password and filename.
-> If you have not Certificate file don't worry pass null instead of PaytmClientCertificate object.

Refer above example.


Thank you.