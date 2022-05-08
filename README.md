# Azure-Identity-Protection

What is the purpose of Azure Idenitity Protection>?
- Try to understand malicious users who are trying to use user identity to access your accounts.

What does it do?
- It uses the data that it has collected overtime from other microsoft services, it tries to understand what are the risks when a user signs onto a particular service.
- It can automate the detection of identity-based risks.
- Investigate risks using data in the portal
- Export risk detection data to your SIEM.


What does Identity Protection risk?
- It uses machine learning and heuristic systems to provide risk scores for 18 billion login attempts for over 800 million different accounts.

Identity Protection can identify many types of risks, including:
- Anonymous IP address use (Sign-in risk)
- Atypical travel (Sign-in risk)
- Malware linked IP address (Sign-in risk)
- Unfamiliar sign-in properties (Sign-in risk)
- Password spray (Sign-in risk)
- - Leaked credentials (User risk)
- and more.

Creating the policies
- When creating the policies, understand that it will be enforced based on the low-high risks.
- IT admins can use these policies to include or exclude particular users or groups.
- IT admins can also block or allow access but require MFA (Sign-In Risk)
- IT admins can also block or allow access but a password change (User-Risk - Leaked credentials)

User-Risk (Leaked Credentials) - <em> Allow access but require a password change </em>
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167277850-ab35891d-f612-478c-993e-c650b3665568.png" height="70%" width="70%" alt="AZ Active Directory"/>
  
<p/>

Sign-In Risk - <em> Allow access but require MFA </em>
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167277876-1bdce105-7ec7-4702-b26e-1831c54d806d.png" height="70%" width="70%" alt="AZ Active Directory"/>
  
<p/>


Risk investigations
- Admins can review detection and take manual action on them if needed. There are 3 key reports administrators will use for investifations in Identity Protection.
