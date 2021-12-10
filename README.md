# CS305
SNHU CS-305: Software Security

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a financial consulting company that puts together financial plans to help their clients store their money wisely. They required the security of their customer's data and their data base. For example, the program could hold customer information such as names, addresses, social security numbers, phone numbers, bank information, and more. The program could also do transfers, withdrawls, and deposits. While this data is being transfered, encryption is a must to keep that information secure while in transit.

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I believe that I thoroughly reviewed what they were asking for from their program and what type of security they would need as a financial company. Especially, when it comes to a financial instatute, secure code protects a lot of sensitive information that should not be easily accessed by malicious users. If there was no security, then that could lead to hundreds of thousands of dollars lost for the company and their customers. Which could result in Artemis Finanial becoming bankrupt, being sued and/or closing. 

What about the process of working through the vulnerability assessment did you find challenging or helpful?

I found that the knowledge I gained from researching how to mitigate the vulnerabilities to be very helpful. It was interesting to look into what versions are safe to use while developing a program. Though, some versions have fixed bugs, but have their own vulnerabilities. So, finding exactly what version is safest to use can be challenging.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

First, I determined what Artemis Financial wanted from the program, and what type of attacks would be the most threat to them. For a financial institution, it is important to keep the client's and their customers' information as secure as possible. So, securing the API, client/server, encapsulating data, error handling, encryption, and code quality are all important to include in Artemis Financial's program. Also, while developing program's I will always run dependency checks to determine if there are any security vulnerabilities within the program. False possitives are always possible, so supressing those is important in figuring out what dependencies really need to be mitigated. This saves time and allows me to focus on securing other parts of the program.

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

When I refactored the code and ran it, I made sure that my certificate was properly connected to the HTTPS. Also, I ran a dependency check before and after refactoring the code. Running the check twice helped me determine if my code introduced any new vulnerabilities. In my case, it did not. Though, if it did, more refactoring would have been necessary to mitigate any new issues.

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

I did a lot of research during this course. Especially, to figure out the best way to implement SHA-256 hashing with Java. I also got to learn about how to run a dependency check using the pom.xml file. I know that dependency checks are going to play a huge role in program development and will be a tool that I will use throughout my career.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

The biggest thing that I believe would benefit me in finding a future employer is showing that I know how to implement an algorithm cipher. With how essential cryptography is now, I think knowing how to develope something so critical to keeping information secure on the the internet is very important.
