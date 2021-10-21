# CS305Final
## Final Project for CS 305 Software Security Final Questions

* Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

The Artemis Financial application is a company that seeks to create individualized financial savingsplans for clients for their svaings, retirement, investment, and insurance finance needs. Artemis wishes to update its software system and with this comes an upgrade in security. The issue that they wanted addressed was that they needed insure secure communication of client data and financial information.

* What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I believe I did fairly well at the initial breakdown of the security risks in the project. I think the most important aspect is being able to break the project down into the individual security components. This makes it less overwhelming to tackle each area individual as well as strategize how to solve each security risk. This allows the risks to be address more thoroughly without missing details. Software security adds great value to any project it is one of the most important aspect of any software application. Most applications today have stored or access to private costumer information. If this data is leaked it can cause damage to that person as well as the companies reputation. With software security we minimize these risks to the companies reputation.

* What about the process of working through the vulnerability assessment did you find challenging or helpful?

I found that generating the certificate authority and utilizing in the project to be most challenging. This allowed the web routing to utilize the more secure https protocol rather than http protocol. I found this challenging for one because I was on a different OS than instructed which meant the console commmands were going to vary slightly. I also found that I had to run them as an administrative user on my machine.

* How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

When tackling the layers of secruity I made sure to take the project piece by piece rather than trying to look at it as a whole. This made it much easier and less stressful to tackle each risk. I think in the future it would be interesting to try different dependency checkers that are formatted in different ways. I would also I think take a different order and tackle the protocol http to https before handling the the encryption of data.

* How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

After writing the functionality of the code I first tested the link to insure data was coming through correctly. I tested both with https to make sure the link ran and with http to make sure that would no longer work due to the protocol added. From here I did a maven dependency check and compared the two reports to insure that no new secruity risks where added to the report. I also did a manual review of the code to see if there was any logistics that could impose a future problem and saw that I had a couple class variables as public which could cause potential risks if more classes were added.

* What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

I think this project has helped me reinforce some clean coding concepts I had previously learned since code quality was one of the security areas in our diagram. This is always important to remember when working in software because it makes everyones jobs easier when building ontop of eachothers code.

* Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

I would want to showcase that I have an understanding of software security and the importants it imposes on an application. I would also like to showcase that I am able to utilize software that is designed for catching dependency issues that lead to potential security risks so I can assist in debugging those. 
