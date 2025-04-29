-- Day 1: 

SECTION 1: Cyber Defence Frameworks

Topic: Junior Security Analyst Intro:
  - Role is to Manage event logs and alerts

    
  - Implement basic IDS (Intrusion Detection System)
      - IDS: Device or software that monitors a netwrok for malicious activity or policy violations.
      - Some IDS are capable of responding to detected intrusion upon discovery. These are called Intrusion prevention systems (IPS).
      - There are alot of different IDS, most common classifications are:
          - Network intrusion detection systems (NIDS): System that analyzes incoming network and traffic.
          - Host-based intrusion deetection systems (HIDS): System that monitors important operating system files.
      - There are also subsets such as Signature-based and Anomaly based.
          - Signature: Looks for specific patterns, really hard to detect new attacks as they are unknown.
          - Anomaly: Newer tech and uses machine learning to make a model, then it comares bahavior against its trust model. Can suffer from alot of false-postives.
      - IDS usage in networks: Placed at a strategic point or points within a newtwork to monitor traffic to and from all devices. The IDS will perform an analysis of passing traffic and if matched
        it will be passed on the subnets to the library of known attacks. Once it is identified or abnormal behavior is sensed, the alert can then be sent to the administrator.
      
