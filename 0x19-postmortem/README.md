# Web Application Outrage Incident

## Author

- [@Nsikak-Joseph-Ikpong](https://www.github.com/Nsikak-Joseph-Ikpong)

## Incident Summary
This report outlines a recent web applicationoutrage that occured on May 5, 2024, from 10:00 AM to 12:30 PM(WAT). The outrage impacted the primary web application, resulting in downtime and degraded performace for approximately 40% of users.

##Timeline

- **10:00 AM (WAT):** Monitoring system detected increased latency and error rates.
- **10:05 AM:** Investigation commenced to identify the root cause, initially focusing on database performance.
- **10:30 AM:** Misleading investigation into database query optimization.
- **11:00 AM:** Incident escalated to senior development team for further investigation.- **12:00 PM:** Root cause identified as a misconfigured load balancer.
- **12:30 PM:** Load balancer reconfigured; services restored.

## Root Cause and Resolution

The outrage was caue by a miscofigured load balancer that failed to evenly distribute traffic, leading to server overload and degraded performance. The issue was resolved by the reconfiguration of the load balancer based on the accurate load metrics.

## Corrective and Preventive Measures

To prevent similar incidets in the future and enhance system reliability, the following actions will be implemented:

- Automated load balancer configuration checks to ensure proper functioning.
- Enhanced monitoring to detect load balancer inefficiencies and performane issues.
- Regular load testing to simulate high traffic sceneriors and validate load balancer performance.

## Action Items

1. **Automate Load Balancer Configuration Checks:**
   - Develop scripts to regularly validate load balancer configurations.
2. **Enhance Monitoring Alerts:** 
   - Configure monitoring systems to provide early warnings of load balancer issues.
3. **Conduct Load Testing:**
   - Schedule regular load tests to verify load balancer performance under various conditions.
