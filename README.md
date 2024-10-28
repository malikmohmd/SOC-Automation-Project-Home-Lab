# SOC-Automation-Project - Home-Lab

## Introduction
The SOC Automation Project aims to create a fully integrated Security Operations Center (SOC) automation solution using various tools such as Wazuh and TheHive. This project provides hands-on experience with key components in a SOC environment and focuses on enhancing incident response capabilities through automation.

## Project Objectives
- Build a functional SOC automation home lab environment.
- Integrate Wazuh for Security Information and Event Management (SIEM).
- Utilize TheHive for case management and incident tracking.
- Automate the enrichment of alerts and notifications using Shuffle SOAR.
- Gain practical experience in leveraging telemetry for security monitoring.

## Tools Used

| Tool             | Description                                              |
|------------------|----------------------------------------------------------|
| **Wazuh**        | Open-source security monitoring and SIEM tool.           |
| **TheHive**      | Open-source incident response platform for SOC operations.|
| **Shuffle**      | SOAR platform for automating workflows.                  |
| **VMware**       | Virtualization software for hosting the lab environment.  |
| **DigitalOcean** | Cloud service provider for hosting Wazuh and TheHive instances. |
| **Sysmon**       | Windows system service for monitoring system activity.    |


## Project Workflow
1. **Setup Environment**: Configure VMware to host a Windows 10 virtual machine.
2. **Deploy Wazuh**: Install and configure Wazuh to monitor security events.
3. **Install TheHive**: Set up TheHive for case management and integrate it with Wazuh.
4. **Configure Alerts**: Create custom alert rules in Wazuh for specific security events.
5. **Integrate Shuffle**: Use Shuffle for automating the incident response process, enriching alerts with additional data from sources like VirusTotal.

## Challenges Encountered
- Initial configuration complexities with integrating multiple tools.
- Ensuring seamless communication between Wazuh and TheHive.
- Handling false positives in alert generation and refining rules accordingly.

## Results
- Successfully built a functional SOC automation lab.
- Enhanced incident response time through automation and integration of alerts.
- Improved understanding of security monitoring and automation tools.

## Lessons Learned
- Integration of different tools in a SOC environment requires careful planning and configuration.
- Automation can significantly enhance response times and efficiency in handling security incidents.
- Continuous testing and refining of alert rules are essential to minimize false positives.

## Conclusion
The SOC Automation Project has provided valuable insights into the operation of a SOC and the importance of automation in incident response. By integrating various tools, this project demonstrates how a well-structured SOC environment can enhance security posture and response capabilities.
