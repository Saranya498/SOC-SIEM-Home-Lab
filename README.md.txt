# SOC/SIEM Home Lab – Failed Login Detection

## Overview
This project demonstrates simulated Windows failed-login detection and investigation using Splunk Enterprise.

## Tools Used
- Splunk Enterprise
- Windows Security Event ID 4625
- Simulated Windows authentication logs
- Microsoft Excel

## Project Activities
- Imported simulated failed-login logs into Splunk.
- Created a detection rule for five or more failed login attempts within a 10-minute time bucket.
- Configured and tested a scheduled Splunk alert.
- Investigated seven simulated failed-login events.
- Created a security monitoring dashboard.
- Exported investigation results and documented findings.

## Results
- Account: lab_test_user
- Host: LAB-WINDOWS-TEST
- Failed login events: 7
- Detection threshold: 5 failed attempts within 10 minutes

## Evidence
- SOC_Dashboard_Overview.png
- SOC_Failed_Login_Detection.png
- SOC_Failed_Login_Investigation.xlsx
- SOC Incident Investigation Report

**Note:** This is a simulated cybersecurity lab, not a real-world security incident.