Artemis Financial was the client we interfaced with for the duration of this class. Artemis requested that we assist them in modernizing their operations - specifically, they wanted to identify vulnerabilities in their RESTful API they utilize for customer interactions, report the findings, and then mitigate the potential threats. When we discovered their vulnerabilities, we addressed them in a number of reports detailing dependencies that had known issues. We also performed code reviews to determine if the company was following industry standard best practices in regards to secure coding. The most difficult part in this process was probably the code review - it's hard to know when something is insecure unless you understand the full picture of how that code is integrated into a project. Luckily there were instances where it was easy to piece together vulnerabilities. 

We increase layers of security by taking a hollistic approach to mitigation. We approached their service from multiple angles, and attempted to mitigate threats as we found them. Specifically we addressed cryptographic requirements the customer had, upgraded the service to utilize HTTPS using certificates we generated for them, and identified dependencies in their code that were vulnerable and needed to be upgraded. To make sure the changes we made were viable, we ran vulnerability checks using Maven's depency check tool via the OWASP. The vulnerability assessment is by far the most useful tool that I found during the course, and I plan to utilize it for future projects to ensure that the dependencies I'm using are as vulnerability free as I can make them. 

From this assignment, I would demonstrate the ability to utilize the dependency checker, as it demonstrates the ability to not only use a tool like this to find issues, but to understand what the issues presented are, why the issues could present severe security implications, and also methods to mitigate them as well. 
