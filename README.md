# Phishing-simulation-incident-Analysis-splunk-
1. PROJECT OBJECTIVE
   -Analyze phishing simulation logs to detect suspicious emails and user interactions.
   -Identify malicious senders, lookalike domains, and users at risk.
   -Create splunk detection rules and alerts to automate future detection.

   2. Tools Used
      -Splunk Enterprise- log ingestion, search, and alerting
      - Ubuntu VM - lab environment
      - Phishing logs - simulated corporate phishing emails

    3. Step-by-step workflow
       -step 1: uploaded phishing.logs into splunk
       -verified ingestion with index=main search
       -step 2: Examined _raw logs to understand field names
       step 3: Detected phishing sender (security@micr0soft-alerts.com
       -Detected typosquatting domain: micr0soft-password-reset.com
       -Step 4: analyze affected users
       -showed who was targeted and number of emails.
       -Step 5: Detect users who clicked links
       - tracked which users interacted phishing link
       - step 6: create detection query/alert
       - This query can be saved as a splunk alert to notify SOC analysts in real         time
       - step 7: summarized: typosquatting campaign, affected users, phishing             link, and actions taken.
       - included mitigation recommendation: block domain, educate users, monitor        future events.
