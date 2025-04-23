# CS305-SNHU


Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
Which part of the vulnerability assessment was challenging or helpful to you?
How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?


Artemis Financial is a financial consulting company that helps handle financial data and manage international transactions and wants to prioritize security, client trust, and comply with governmental regulations while also avoiding any possible threats. The company also wanted me to address any vulnerabilities in their software, and ensure that no external threats could be created and also have encryption and have secure communications. 

What I did well through this project was understand and implement proper code practices and manage the static tests properly. I was able to manually review their code and understand that their error handling and input validation were some areas that needed to be adjusted and that some third party libraries were also some causes for concern since they were out of date and can cause issues. Ensuring that their code was secure allows a company like Artemis Financial to worry more about clientel and less about any possible threats, financial loss, or legal or even governmental issues if attacks were to occur. A company values security and having security allows for clients to trust them and in turn for a company to gain even more clients through word of mouth. 

The most challenging part for me in this project was the static tests and also handling secure communications. Manually checking every library for false positives was very tedious but has to be done and as for handling secure communications, I was quite confused when I connected to my own server and https was established but still not secure. I refactored my code several times till eventually importing my own certificate did not resolve the issue and upon further research indicates that an actual authority can only allow for true https secure communications. 

When it came to increasing layers of security I helped do this through manually handling secure coding practices and have better error handling and also used input validation. I also ensured that only the libraries that were causing issues were either updated o and that those dependencies were in turn upgraded. Since code was changed and depdencies upgraded I had to double check through static tests and dynamic tests as well to verify that no new issues developed. 

Some resources I heavily relied on were OWASP Dependency-Check, W3Schools, and Stack overflow as well as Maven for dependency management. All of these tools helped me learn more and ensure that the best practices for secure coding and dependecy management was implemented. 

If a future employer was to ask for examples and I brought this project up, I would most likely show how this project applies to real-world applications and that documenting vulernabilities was done and that refactoring code with secure practicies as well as a mitigation plan all allow for proactive security measures to be implemented and in turn have made this software more secure.
