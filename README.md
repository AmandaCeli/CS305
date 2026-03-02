# CS305
Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

  Artemis Financial is a financial services company that manages sensitive financial planning and client data. Since the organization handles personally identifiable and financial information, secure communications and data protection were critical requirements. The company needed to ensure its RESTful web application was protected against vulnerabilities that could lead to data breaches or unauthorized access. My role was to evaluate the application’s security posture and recommend improvements to strengthen secure software practices.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

  When identifying vulnerabilities, I carefully analyzed both the source code and dependency reports to determine the severity and potential impact of each issue. I prioritized high-risk findings such as hard-coded credentials and outdated cryptographic libraries. Coding securely is essential because financial institutions must protect sensitive client data from unauthorized access and cyber threats. Strong software security protects a company from financial loss, legal liability, and reputational damage while maintaining customer trust.

Which part of the vulnerability assessment was challenging or helpful to you?

  The most challenging part of the assessment was interpreting CVE details and understanding the practical impact of dependency vulnerabilities. Researching vulnerability severity scores required careful analysis rather than simply accepting automated results. However, this process was also very helpful because it strengthened my ability to evaluate risk critically. It improved my understanding of how technical weaknesses can translate into real-world business consequences.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

  I increased layers of security by recommending TLS enforcement, implementing authentication and authorization controls, removing hard-coded credentials, and upgrading outdated dependencies. I also emphasized secure configuration management and proper input validation to reduce attack surface exposure. In the future, I would continue using automated tools such as OWASP Dependency-Check combined with manual code review to assess vulnerabilities. I would prioritize mitigation techniques based on CVSS severity ratings, exploitability, and business impact.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

  After identifying vulnerabilities and recommending mitigation steps, I rebuilt the application to verify that it continued to function properly. I ensured that dependency updates and configuration changes did not introduce runtime errors. I also re-ran vulnerability scans to confirm that known security issues were resolved and that no new vulnerabilities were introduced. This approach ensured both functional stability and improved security posture.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

  I used the OWASP Dependency-Check Maven plug-in to analyze third-party dependencies and identify known vulnerabilities. I referenced the National Vulnerability Database (NVD) and CVE documentation to better understand the scope and severity of identified issues. I also applied secure coding principles such as least privilege, secure configuration management, and proper error handling. These tools and practices will be valuable in future development projects that require secure software implementation.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

  From this assignment, I can demonstrate my ability to conduct a structured vulnerability assessment and interpret security scan results. The project shows that I can analyze source code, identify security weaknesses, and recommend practical mitigation strategies. It also highlights my understanding of secure software development lifecycle principles and risk prioritization. This work reflects both technical competence and a proactive security-focused mindset.
