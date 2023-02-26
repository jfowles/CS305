# CS305

###### Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis is a finance company that deals with investments and clients wealth both domestically and internationally.

###### What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

The thing we did well was identify the security flaws the current code base was using lots of out of date dependencies by patching these or updating to newer versions we have cut down on future problems and possible intrusions. 

###### What part of the vulnerability assessment was challenging or helpful to you?

the most challenging part of the assessment was trying to determine which vulnerabilities were false alarms and could be surprised and which needed us to take action

###### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

We increased the security by upgrading all the dependencies we could and suppressed the ones that could be missed. We added SSL to the API connection added try catches and validation around the input.

###### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

We made sure the application was functional and secure by re-running the same tests after applying the fixes and making sure the fixed items did now show up on the report and that was able to show us if we accidentally added new vulnerabilities. 
###### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Using the documentation on IRON clad java and guides on how to implement CA authorization were useful in making sure everything worked like expected 
###### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I think this work shows future employers that we understand the difference between HTTP and HTTPS and how the browser determines if something is secure or not and how to check the validity of a CA certificate 
