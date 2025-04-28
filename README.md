# CS305

## 1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial was an Insurance company wanting to generate business in the online space. Since they deal with sensitive client information like banking details, they wanted me to address the security in their website. 

## 2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I think the thing I did well when finding the client's software security vulnerabilities was looking up what the vulnerabilities meant and the harm they have caused in real-life scenarios. This helped me become more familiar with the types of security vulnerabilities a company like Artemis Financial might be more susceptible to.
It is important to code securely so that users can trust a company. If code is sloppily written or has no care put into keeping users' information safe, then their business will ultimately fail. 

## 3. Which part of the vulnerability assessment was challenging or helpful to you?

I enjoyed the vulnerability assessment overall as it helped me see how to properly evaluate security issues in software. However, the dependency check was slightly annoying as the code was severely out of date, which flooded the report and made it more annoying/time consuming to find true potential vulnerabilities. 

## 4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

Layers of security were increased by making sure code was written properly, cryptography was used when taking in data, and making sure the website was secure through HTTPS. In the future, I developing something to automatically pen test the website before it is live would be a good way to see in real time potential exploits and know what needs to be reworked to make the software more secure.

## 5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I made certain the code and software application were functional and secure by running two different dependency checks before and after refactoring the code. This allowed me to see if I introduced new vulnerabilities as well as see what other issues were remaining and if they were relevant. 

## 6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I think the maven dependency check will be helpful in the future, even though it was a bit annoying in these assignments due to the outdated code bases. 

## 7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show a future employer from this assignment my ability to thoroughly assess code for vulnerabilities and my ability to cross reference on sites like NVD and searching whether vulnerabilities are true risks with the dependency alone, or if they need other dependencies in order to truly carry out the exploit flagged.
