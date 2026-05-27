# SOC CTF Challenges Lab 🔒

## Overview

This is an interactive **Security Operations Center (SOC) Capture The Flag (CTF)** lab designed to help students practice real-world cybersecurity incident response and SIEM (Security Information and Event Management) skills.

## What You'll Do

You'll work through **10 cybersecurity missions**, each simulating a different security incident that a SOC analyst would encounter. Each mission contains **5 tasks** that you must complete in sequence.

### Mission Types Include:
- Network intrusion detection (VPN anomalies, suspicious connections)
- Insider threat investigation (data theft, USB misuse)
- Malware analysis (cryptominers, backdoors)
- Supply chain attack response
- Cloud security incidents (AWS compromise)
- SIEM rule creation and tuning
- Threat intelligence integration
- Behavioral baseline analysis
- Registry persistence attacks
- Web shell investigations

## How the Lab Works

### Getting Started
1. Open `index.html` in your browser (this is the hub page)
2. Use a **private/incognito window** if you want to start fresh
3. Click on any challenge card to begin that mission

### Playing the Challenge
- **Read the scenario** and simulation panel for each mission
- **Answer all 5 tasks** in each mission to complete it
- Each task **validates before unlocking** the next task
- When you complete all 5 tasks in a mission, you'll receive a **mission flag**
- Copy the flag when the mission completes (you'll need it for verification)
- **Progress is automatically saved** in your browser's localStorage

### Challenge Navigation
- **Hub page (index.html)** - Shows all 10 challenge cards
- **10 Independent Challenges:**
  - Q1: VPN Anomaly
  - Q2: Insider Threat
  - Q3: Cryptominer
  - Q4: Supply Chain
  - Q5: Web Shell (AWS)
  - Q6: SIEM Use Case
  - Q7: Alert Tuning
  - Q8: Registry Persistence
  - Q9: Threat Intel
  - Q10: Baseline Behavior

Each challenge is **independent** - you can complete them in any order.

### Resetting Progress
To start over:
- Open the lab in a **private/incognito browser window**, OR
- Clear your browser's localStorage for the page

## What You'll Learn

By completing this lab, you'll gain hands-on experience with:

✅ **Incident Response** - Investigating security incidents step-by-step  
✅ **Threat Detection** - Identifying indicators of compromise (IOCs)  
✅ **SIEM Skills** - Creating correlation rules, tuning alerts, building use cases  
✅ **Forensic Analysis** - Analyzing logs, processes, and network traffic  
✅ **Cloud Security** - AWS incident response and security group misconfigurations  
✅ **Risk Mitigation** - Recommending appropriate containment and remediation actions  
✅ **Malware Analysis** - Identifying persistence mechanisms and malicious files  
✅ **Registry Security** - Understanding Run keys and malicious registry values  


## How to Use This Lab

### For Students:
1. **Clone or download** this repository
2. **Open** `index.html` in your web browser (double-click the file)
3. **Start the challenge** - no installation needed!
4. **Click any challenge card** to begin that mission
5. **Read** each mission scenario carefully
6. **Think like a SOC analyst** - what would you investigate next?
7. **Submit answers** based on the scenario evidence
8. **Track your flags** - each mission gives you a flag upon completion

### Tips for Success:
- 🔍 **Read scenarios thoroughly** - key details are in the text
- 📊 **Think about the attack chain** - what happened before/after?
- 🎯 **Consider the stakeholder perspective** - what does the manager/team need?
- 🛡️ **Prioritize containment** - what stops the threat fastest?
- 📝 **Document your reasoning** - even if not required, it helps thinking
- ⚠️ **Dropdown answers vary** - correct position changes per task (don't assume any pattern)
- ✅ **Read all options carefully** - some tasks have checkboxes, some have dropdowns

## Learning Objectives

This lab aligns with SOC Level 1/Junior Analyst competencies:

- Identify suspicious activity from scenario descriptions
- Recommend appropriate incident response actions
- Understand SIEM correlation and alert tuning concepts
- Recognize common attack patterns (insider threat, malware, supply chain)
- Apply cloud security incident response principles
- Balance detection accuracy with operational efficiency
- Identify registry-based persistence mechanisms
- Analyze web server logs for malicious activity

## Assessment

This lab is designed for:
- **Self-paced learning** - track your own progress
- **Classroom labs** - instructor can verify completion via flags
- **Interview preparation** - practice SOC-style scenario questions
- **Skill assessment** - evaluate incident response decision-making

### Troubleshooting

**If you see raw HTML source instead of the UI:**
1. Files may be saved as UTF-16 (wrong encoding)
2. Close all browser tabs
3. Run `scripts/fix_utf8.py` or `fix-encoding.ps1`
4. Hard refresh with **Ctrl+F5**
5. Reopen `index.html`

**If a challenge seems stuck:**
- Reset the challenge using the **Reset challenge** button
- Or use private/incognito window

---

## Ready to Start?

**Open `index.html` in your browser** and click any challenge to begin!

Good luck, future SOC analyst! 🎯🔐

---

*This lab is designed for educational purposes. Flags and scoring are for learning verification only.*
