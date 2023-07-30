# Application for Sponsorship from the Sovereign Tech Fund

## Introduction

The PHP Foundation is a nonprofit organization dedicated to the development and improvement of the PHP language. We are committed to enhancing the PHP ecosystem, making it more secure, reliable, and user-friendly for developers worldwide. 

## Project Proposals

### Milestone 1: PECL Overhaul (€60,000) (12 Months)

The current system for distributing PHP extensions, PECL/PEAR, is outdated and prone to supply-chain attacks, making it unreliable for average developers. This leads to the creation of redundant tools and new security issues.

We propose to rewrite the PECL installer, replacing the messy pear code and the inefficient website. The new system will allow developers to fetch sources and possibly binaries for Windows from GitHub release pages without needing approval to publish. We plan to reuse the existing package.xml files, with some additional configuration to link versions to PHP versions. This will also allow us to rely on GitHub signing with keys.

**_Why is your work important and critical for the Open Source ecosystem and the public interest?_**
The current PECL/PEAR system is extremely inconvenient for extension developers, not supported at all, and most likely vulnerable to attacks, hindering the distribution of PHP extensions. Modernizing this system will enhance security, reliability, and accessibility, fostering innovation and growth in the Open Source ecosystem.

**_Who uses it and who relies upon it?_**
On the one hand, developers of the extensions (individuals and businesses) for distributing their extensions. On the other hand, users of the extensions – developers, software companies, and many open-source projects.

**_If it breaks or something bad happens to it, what are the consequences?_**
A breakdown will break of nearly all custom PHP builds, e.g. Docker images, development environments, deployments, etc. An attack on the system could lead to widespread security vulnerabilities, a loss of trust in the PHP ecosystem, and potential legal and financial ramifications for businesses and developers.


#### Milestone 2: Security Enhancement (€60,000) (9 Months)

PHP, like any other language, has its share of security issues. We would like to collaborate with a security research group for a comprehensive codebase audit and address the discovered issues. This will significantly improve the security of PHP and make it more reliable for developers and businesses.

**_Why is your work important and critical for the Open Source ecosystem and the public interest?_**
Finding security issues and conducting a thorough audit will make PHP more robust and trustworthy, benefiting the entire community.

**_Who uses it and who relies upon it?_**
PHP is used on at least 35% of web applications in the world. Millions of businesses rely on custom as well as open-source PHP solutions such as WordPress, Drupal, Laravel, and Symfony.

**_If it breaks or something bad happens to it, what are the consequences?_**
Security breaches in PHP could lead to data theft, financial loss, legal issues, and a loss of reputation for businesses and developers using PHP.



### Milestone 3: Documentation Improvement (€40,000) (12 Months)

The current PHP documentation has several blind spots, with many functions and methods not covered at all. We propose to update and modernize the English PHP documentation, review and remove user comments, integrate 3v4l.org for interactive examples, and simplify the maintenance process. This will make PHP more accessible to new developers and serve as a reliable reference for experienced ones.

**_Why is your work important and critical for the Open Source ecosystem and the public interest?_** 
Improving PHP documentation will enhance the learning curve for new developers and provide a reliable reference for all. As well as a better source of education for AI models, providing a future-proof ecosystem.

**_Who uses it and who relies upon it?_**
Developers, educators, and students rely on PHP documentation for learning, teaching, and building applications.

**_If it breaks or something bad happens to it, what are the consequences?_**
Incomplete or outdated documentation can lead to misunderstandings, coding errors, and security vulnerabilities, as well as hinder the growth and maintenance of the PHP developer community.


### Milestone 4: PM/SAPI Testing Tool Development (€45,000) (6 Months)

Currently, PHP lacks a server integration test framework that can create automated tests for various FPM issues, especially those requiring higher load. We propose to develop a PM/SAPI testing tool that can execute all applications and set expectations on the produced logs and server responses. This tool will be connected with a load testing tool (e.g., wrk) to simulate real-world usage and load.

**_Why is your work important and critical for the Open Source ecosystem and the public interest?_**
Developing a PM/SAPI testing tool will allow for robust testing of PHP under real-world conditions, improving reliability, performance, and security. It fills a unique gap in the PHP ecosystem, and potentially enhances the quality and performance of PHP applications.

**_Who uses it and who relies upon it?_**  
The absolute majority of all PHP applications rely on PHP-FPM.

**_If it breaks or something bad happens to it, what are the consequences?_**
PHP applications suffer from performance issues, and unexpected failures, impacting businesses, developers, and end-users.



## Conclusion

The proposed projects align with the Sovereign Tech Fund's mission to strengthen open digital infrastructure, foster security, innovation, and economic growth, and ensure a resilient digital foundation for participation and democracy. We believe that these projects will significantly enhance the PHP ecosystem, making it more secure, reliable, and user-friendly for developers worldwide.

We look forward to the possibility of partnering with the Sovereign Tech Fund to bring these projects to fruition. Thank you for considering our application.

--
PHP Foundation