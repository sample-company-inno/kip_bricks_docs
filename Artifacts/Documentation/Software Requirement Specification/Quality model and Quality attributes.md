Initialization: 09.03.2025
Modified: 11.03.2025
#### **Quality model**: ISO 25010
#### **Quality attributes**
##### Performance Efficiency
* **Time behaviour** 
	- Web page loading ≤ 2 sec
	- Updating the score rating after the competition: synchronization ≤ 30 sec
	- Time to generate a resume ≤ 5 sec
* **Resource utilization**
	- Handling 2000+ active student avatars simultaneously
##### Security
- **Confidentiality**
	- A student, while participating in a competition, can only view the lists of teams registered for the competition, a company that created the competition and the competition assignment
	- A student may not see the personal contacts of other students who are not co-teammates, nor have access to the decisions of the other teams
	- A student can only view the decisions of other students if he/she is the Jury for the competition and if he/she is not participating in the competition
- **Authenticity**
	- When registering, the company must confirm its existence (fill in the TIN field)
- **Integrity**
	- Data encryption: All data is transmitted using SSL/TLS.
##### Interaction Capability
- **Inclusivity**
	- High contrast mode for visually impaired people
- **User assistance**
	- Contextual prompts when registering students and companies, as well as when creating a team (100% coverage of required fields)
- **User engagement**
	- Game-like interaction of students with the system
##### Reliability
- **Recoverability** 
	- Backup progress of student levels before each competition
	- Automatic rollback of transactions in case of points calculation failure
- **Availability** 
	- 98% uptime during the period of competition registration in the system 
	- 99.95% uptime during the period of competition start and execution