Foxy Proxy Extension Installation Guide:

First run Burp-Suite  
Run Temporary Project in memory, click "Next" then under Proxy > Proxy Settings (Get Proxy IP and port# / DNS)

![Burp Suite Proxy Settings](images/burp-proxy-settings.png)

Go back to Foxy Proxy then drop down to "Options" then Proxy Tab then Add Host-Name and Port Number / DNS

Once completed

Enable the intercept on Burpsuite 

***Warning this might cause an issue where you can't browse due to the certificate***

Go to Burpsuite page “http://burpsuite/” and download the CA certificate

![BurpSuite Download CA Certificate](images/burp-cert-download.png)

Once downloaded go back to your Firefox browser and Add the certificate  
Click view certificate and add the trusted CA

Go back to Burp suite and enable intercept then test if you can now search the web.

![BurpSuite Intercept Example](images/burp-intercept-example.png)

In your browser type “About:config” then search “Network.proxy” to see more features.


Credits to YT: HackHunt711
