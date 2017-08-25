# way2smswrapper
A Python Messaging Module Using Way2Sms & Selenium Module.  
Created By $implic@

Requirements :-

               Python3. 
               Selenium Module. 
               Firefox Browser. 
               Geckodriver. 
               Xvfb - Installation. 
               Xvfbwrapper Module. 
               Way2SMS Account.

The python module uses selenium module to control the firefox browser which is being controlled by geckodriver.
The module is using xvfb(x-virtual frame buffer) and the xvfb wrapper for python3 to run the firefox browser 
headlessly(in the background). Way2SMS Account is being used to send the message to the desired mobile number.

One can import the module in his/her own python3 program to send the status of the current running program to 
the user's mobile phone number through sms using the user's Way2SMS Account.

Usage   :-
          
          import w2swrapper

Methods : 
          
          w2swrapper.login()
          w2swrapper.sms(Message)

Tested In Ubuntu-17.04
