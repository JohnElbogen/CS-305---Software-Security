# CS-305

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial was looking to add file verification to their web application and ensure secure communications. Specifically, a data verification step in the form of a checksum was necessary. It was my job to implement these features in refactored code.

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
Some things I did well were implementing the security dependencies and utilizing them. For this project Maven was used, and I managed to create a maven depency report and create a functioning active spring server with checksum plus security certificate. Software security is crucial as sensitive data needs protection from attackers. Often security breaches can be found within code through routine security proecdures like, checking dependencies.

What about the process of working through the vulnerability assessment did you find challenging or helpful?
The most challenging part was identifying false-positives. It can be quite difficult determining the difference between the two. Another part that was a bit confusing was how most suggested fixes for security vulnerabilities mainly were updating the dependencies. I would like to learn more about how to fix these security vulnerabilities without having to rely on an update for a dependency.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
My approach was to utilize the workflow provided in the course. I checked what types of security my program required, eg. authentication, secure coding structures, or cryptography, and implemented them as needed. The main strategies I would use are to identify which layers apply to my program, and then implement them, and regularly check my programs have not been introduced vulnerabilities as I progress.

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
I ensureed the code was functional and secure through manual screening and the maven depency tool. In order to check the refactored code, I ran a maven depency test before and after and looked for new vulnerabilities.

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
Implementing cipher algorithms like AES, can be used in the future. Also using tools like Maven to check for known vulnerabilities can be useful in future assignements or tasks.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
I would showcase my ability to implement and apply different security concepts.  While I do not think I have mastered the field, I think my project can showcase how much I can learn in a short time. The growth can be applied to whatever skills are needed in a future project or job.
