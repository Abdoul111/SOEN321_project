# Information Security Research Project  

**To read the full paper, consult "Information_Security___SOEN_321_Main" and then "Additional_apps_Results___SOEN_321_Android_Apps_Analysis" for the remaining detailed findings**

**And for credits, despite this class project team consists of 7 members, Mohammed Mousa and me (Abd Alwahed Haj Omar) made most of the research and formatting**

## Abstract  
This report analyzes the security and privacy risks of 14 Android apps serving vulnerable populations, such as individuals with disabilities and those struggling with addiction. The study identifies critical vulnerabilities, including weak encryption, cleartext traffic, hardcoded sensitive information, and insecure app components. These issues expose users to risks like data interception and unauthorized access. Recommendations include enforcing HTTPS, improving cryptographic practices, and securing app components. Addressing these issues is vital to protect sensitive data and enhance user safety.  

## Key Findings  
- **Janus Vulnerability**: Found in 9/14 apps due to outdated signature schemes.  
- **Cleartext Traffic**: Present in 8/14 apps, making data interception possible.  
- **Hardcoded Sensitive Information**: Detected in 11/14 apps, increasing exposure to reverse engineering.  
- **Insecure WebView Implementation**: Identified in 6/14 apps, allowing potential code execution.  
- **Logging of Sensitive Data**: Found in 7/14 apps, risking unauthorized data exposure.  
- **Insecure Random Number Generation**: Affects 5/14 apps, weakening cryptographic security.  
- **Dangerous Permissions**: Detected in 8/14 apps, potentially leading to data misuse.  
- **Insecure Data Storage**: Found in 9/14 apps, allowing unauthorized access to user information.  

## Recommendations  
- Enforce HTTPS to secure data transmission.  
- Remove hardcoded credentials and use secure key management.  
- Improve cryptographic implementations to prevent data leaks.  
- Restrict app permissions to minimize potential exploitation.  
- Regularly audit and update app security measures.  

## Conclusion  
Many Android applications catering to vulnerable groups lack fundamental security measures, putting users at significant risk. Strengthening security practices is essential to protect sensitive data and maintain user trust.  
