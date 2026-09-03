Phishing Email Investigation Project

-> About the Project

This project demonstrates a practical **SOC Analyst phishing email investigation** process. It focuses on analyzing suspicious emails, identifying phishing indicators, extracting Indicators of Compromise (IOCs), and documenting the investigation findings.

->Objectives

* Analyze suspicious phishing emails
* Examine email headers
* Investigate sender and Reply-To addresses
* Analyze SPF, DKIM, and DMARC results
* Identify suspicious IP addresses and URLs
* Perform URL reputation checks using VirusTotal
* Extract Indicators of Compromise (IOCs)
* Prepare investigation notes and professional reports

 ->Cases Investigated

Case 01 – Microsoft Account Security Verification Phishing

This case investigates a suspicious email claiming to be from Microsoft Account Security. The investigation identified a lookalike Microsoft domain, SPF and DMARC failures, a missing DKIM signature, a suspicious verification URL, and urgency-based social engineering.

Case 02 – PayPal Account Limitation Phishing

This case investigates a suspicious email claiming to be from PayPal Security. The investigation identified a lookalike PayPal domain, SPF and DMARC failures, a missing DKIM signature, suspicious verification URLs, and an urgent account-limitation message.

-> Investigation Process


Email Collection
      ↓
Email Header Analysis
      ↓
Received Header Analysis
      ↓
SPF / DKIM / DMARC Analysis
      ↓
URL Investigation
      ↓
VirusTotal Check
      ↓
IOC Extraction
      ↓
Analysis Notes
      ↓
Final Investigation Report


-> Project Structure


Phishing_Email_Investigation
│
├── Case_01
│   ├── Evidence
│   ├── Screenshots
│   ├── Analysis_Notes
│   ├── IOCs
│   └── Report
│
├── Case_02
│   ├── Evidence
│   ├── Screenshots
│   ├── Analysis_Notes
│   ├── IOCs
│   └── Report
│
└── README.md


-> Tools Used

* Email Header Analysis
* VirusTotal
* Email/Text File Analysis
* Microsoft Word
* GitHub
  
 -> Key Skills Demonstrated

* Phishing Email Analysis
* Email Header Investigation
* SPF, DKIM and DMARC Analysis
* IOC Identification
* URL Investigation
* Threat Intelligence
* SOC Investigation
* Security Documentation
* Incident Reporting

Disclaimer

This project uses **synthetic test data** created for cybersecurity learning and portfolio purposes. The domains, IP addresses, email addresses, and attachments used in these cases are not intended to represent real malicious infrastructure.
