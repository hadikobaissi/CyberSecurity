-- Day 1: 

SECTION 1: Cyber Defence Frameworks

Topic 1: Junior Security Analyst Intro:

Topic 1.1: A career as a Junior Security Analyst
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
      - Evasion techniques: Being aware of the techniques available to cyber criminals whoa re trying to breach can help IT departments. These are different types:
          - Fragmentation: Sending fragmented packets allow the attacker to stay under the radar, bypassing the detection system's ability to detect the attack signature.
          - Avoiding defaults: A port utilized by a protocol does not always provide an indication to the protocol that is being transported. If attacker reconfigures it, the IDS may not be able to detect the trojan.
          - Coordinated, low-bandwids attacks: coording a scan among numeroous attackers, or even allocating various ports or hosts to different attackers. Makes it difficult for the ISD to corellate the captured packets and deduc the netwrok scan in progress.
          - Address spoofing/proxying: Attackers can obscure the source of the attack by using poorly secured or incorrectly configued proxy serves to bounce an attack. If source is spoofed and bounced by server, makes it hard to detect.
          - Pattern change evasion: Making slight adjust to the architecture, detection can be avoided.
       - Why IDS are important: Helps keep breaches away from modern networked business environments that communicate between various organizations.

  - Particpate in SOC meetings
  - Make ticekts and escalate the security incidents to the Tier 2 and team lead if needed.
  - You will be a Triage Specialist.

Topic 1.2: Security Operations Center:

  - Core function of a SOC, is to investigate, monitor, prevent and respond to threates in the cyber realm around the clock.
  - Some responsibilities of a SOC:
      - Ticketing
      - Log Collection
      - Knowledge Base
      - Research and Development
      - Aggregation and Coreelation
      - Threat Intelligence
      - SIEM: Security information and event management
      - Reporting

    - Preparation and
      
