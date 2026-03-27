# Splunk Log Analysis

## Overview

Simulated a SOC analyst investigation using Splunk to analyze log data, identify patterns, and detect potential abnormal activity.

## Tools Used

* Splunk (SIEM)
* TryHackMe Lab Environment

## What I Did

* Queried log data using SPL (Search Processing Language)
* Filtered events using search terms like "error", "failed", and "login"
* Aggregated data using:
  index=* | stats count by src_ip
* Identified high-frequency IP addresses
* Analyzed patterns in login activity and source locations

## Findings

* Multiple IP addresses generated a high number of events (~200)
* Activity distribution suggested repeated or automated behavior
* Patterns indicated potential brute-force or scripted login attempts

## Why It Matters

SOC analysts rely on tools like Splunk to quickly identify suspicious patterns in large datasets. Detecting abnormal login behavior early can help prevent unauthorized access and security breaches.

## Key Takeaways

* Learned how to use SPL to search and analyze logs
* Gained experience identifying suspicious patterns in real-world data
* Improved ability to interpret log data for threat detection

## Screenshots

1. Raw Log Data (Initial View)
<img width="2854" height="1564" alt="raw-logs png" src="https://github.com/user-attachments/assets/17d65f60-13fa-4fc7-9e29-697c2d8c7a7b" />
Displayed all available log data to understand the dataset structure, event fields, and overall activity volume.

2. Initial Exploration (Limiting Results)
<img width="2862" height="1566" alt="head-20 png" src="https://github.com/user-attachments/assets/f351907a-fb8e-4a57-934c-647174c1f3d5" />
 Reduced the dataset using head 20 to quickly inspect individual log entries and identify key fields such as user, source IP, and timestamps.

3. Aggregating Events by Source IP
<img width="2880" height="1920" alt="stats-src-ip full page png" src="https://github.com/user-attachments/assets/58a45424-5369-4d7b-b1a5-7cb9ca82e4e4" />
<img width="2836" height="1386" alt="stats-src-ip cropped png" src="https://github.com/user-attachments/assets/1e3738c5-f8a4-4d83-8659-35df82ea2be7" />
Grouped events by source IP using SPL to identify which IP addresses were generating the most activity.

4. Identifying High-Volume Activity
<img width="2838" height="1460" alt="sorted-ip png" src="https://github.com/user-attachments/assets/d3911e26-399e-4ac3-b02d-f2d468eee702" />
Sorted results by event count to highlight high-frequency IP addresses that may indicate suspicious or automated behavior.
