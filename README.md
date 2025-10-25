# -Task-3-Analyze-a-Phishing-Email-Sample.

# Table of Contents

- [Objective](#objective)
- [Tools Used](#tools-used)
- [What is Phishing?](#what-is-phishing?)
- [Creating the Phishing Environment](#creating-the-phishing-environment)
- [Step-by-Step Procedure](#step-by-step-procedure)
- [Analysis of the Facebook Phishing Email](#analysis-of-the-facebook-phishing-email)
- [Conclusion](#conclusion)


# Objective
To analyze a sample phishing email and identify key characteristics of phishing attempts, such as spoofed sender details, header discrepancies, suspicious content, and linguistic errors, in order to develop skills in recognizing and reporting email-based threats effectively.

# Tools used 
- Tools :
   - Setoolkit (A social engineering tool)
 
# What is Phishing ? 
- Phishing is a type of cyberattack where attackers try to trick people into revealing sensitive information — like passwords, credit card numbers, or personal details — by pretending to be a trusted organization (such as a bank, company, or government agency).

# Creating the phishing Environment 

# Step-by-Step Procedure 

## Step 1 : 
- Lunching Setoolkit to create a phishing `url`.
  <img width="1364" height="656" alt="1" src="https://github.com/user-attachments/assets/63c3b94d-b79e-48ad-ba36-e0518c528bc9" />


## Step 2 : 
- Choosing type of attack. In this task I choose `option 1` (Social-Engineering Attacks).
<img width="1364" height="656" alt="Screenshot_2025-10-25_04_56_18" src="https://github.com/user-attachments/assets/d13a1d74-d7c9-4712-896b-5121d3d0ee8c" />



## Step 3 : 
- Choosing What type of attack to do. In this tack I choose `option 2` (Website Attack vector).
<img width="1364" height="656" alt="2" src="https://github.com/user-attachments/assets/2c274ac5-cc56-44fb-adec-a4328d176662" />


## Step 4 : 
- Choosing type of method. I have choos `option 3` (Credential Harvesting Attack Method)
- <img width="1364" height="656" alt="3" src="https://github.com/user-attachments/assets/dc6e6b5c-7be2-42ce-ad56-7062a2c7340f" />
/>

## Step 5 : 
- Choosing `option 2` for attack which is (Site cloning). I have choose `https://www.Facebook.com` for cloning and to perform attack.
<img width="1336" height="288" alt="kmfa" src="https://github.com/user-attachments/assets/61abfb9d-3cdd-4608-86cd-b0345ab6f700" />

## Step 6 : 
- To perform a phishing attack after cloning the `Facebook.com` We have to provide Ip address of our localHost.
- After providing the Ip it ask for url that you want to clone i have give the url `https://www.Facebook.com`
<img width="1364" height="656" alt="5" src="https://github.com/user-attachments/assets/76224b17-8619-4f43-861e-5ad080dfb54d" />

## Step 7: 
- Sending email to a target by changing the placeholder of url.
<img width="510" height="507" alt="Changing url  " src="https://github.com/user-attachments/assets/20e3ef7c-50ea-42ae-9a8b-e615170e7811" />

## Step 8 :
- Verfying the email the sended to targeted machine.
<img width="1035" height="483" alt="Verfying the email" src="https://github.com/user-attachments/assets/94999025-73e8-4ad1-b8d1-db5d0b07bee7" />

## Step 9 :
- Output of phishing
<img width="1342" height="144" alt="output" src="https://github.com/user-attachments/assets/a685a579-2c64-4f40-9cb9-51e739f1399d" />

# Analysis of the Facebook Phishing Email

| Aspect | Observation / Analysis | Phishing Indicator |
|--------|------------------------|--------------------|
| **Sender Address** | `security@facebook-notify.com` — looks official but not a real Facebook domain (`facebookmail.com` is legitimate). | Spoofed or fake sender domain |
| **Subject Line** | “⚠️ Urgent: We have Suspended a login from another devices!” — creates fear and urgency to make user act quickly. | Urgent / threatening tone |
| **Email Header** | Likely sent from an unknown mail server not matching Facebook’s IPs. SPF/DKIM/DMARC checks fail. | Header discrepancy |
| **Body Message** | Claims unauthorized login and asks to verify identity. | Social engineering (fear + urgency) |
| **Link in Email** | `https://facebook-account-secure.com/login` — appears like Facebook but is a fake domain. Hover reveals real malicious link. | Mismatched / fake URL |
| **Grammar / Spelling** | Minor issue (“another devices” instead of “another device”). | Grammar errors, non-professional writing |
| **Request for Action** | Asks user to click a link and verify login info. Facebook never requests this by email. | Request for sensitive information |
| **Branding / Design** | May include fake Facebook logo or poor formatting, lacks real Meta footer. | Forged or incomplete branding |

---

# Conclusion

The analysis of the Facebook phishing email demonstrates how cybercriminals use social engineering, spoofed domains, fake URLs, and urgent messaging to trick users into revealing sensitive information. By examining the sender address, email headers, links, attachments, and language, we can identify multiple phishing indicators that clearly mark this email as malicious.

This exercise highlights the importance of vigilance when handling unexpected emails, verifying sender authenticity, and avoiding suspicious links or attachments. Understanding these tactics equips users with the skills to recognize, report, and protect themselves against email-based cyber threats, thereby reducing the risk of credential theft and malware infections.



















  
