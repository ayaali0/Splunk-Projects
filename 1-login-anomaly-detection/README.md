# Login Anomaly Detection (Simulated Data)

This project simulates failed login events from Windows logs to demonstrate how to use Splunk for detecting brute-force attempts, unusual user behavior, and login anomalies.

## What’s Included

- Sample Windows failed login events
- SPL queries to detect:
  - Multiple failures by same user
  - Failed logins from multiple hosts
  - Login attempts outside working hours

##  Project Structure

- `sample_logs/failed_logins.log`: Fake Windows security logs
- `SPL_queries/detect_failed_logins.spl`: Saved SPL queries for analysis

##  Tools Used

- Splunk
- SPL (Search Processing Language)

## Note

All data in this project is simulated for educational purposes only.
