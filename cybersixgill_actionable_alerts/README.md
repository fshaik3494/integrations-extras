# Agent Check: cybersixgill_actionable_alerts

## Overview
The Cybersixgill actionable alerts check monitors critical assets across the deep, dark, and surface web such as IP addresses, domains, vulnerabilities, and VIPs. Receive alerts with context including severity, threat type, description, post snippet, recommendations, and assessments. This integration provides an out-of-the-box dashboard to prioritize and respond to threats.

This check monitors [cybersixgill_actionable_alerts][1].

## Setup


### Installation

To install the Cybersixgill actionable alerts check on your host:
1. Install the [developer tool][11] on any machine.
2. To build the package, run the command: `ddev release build cybersixgill_actionable_alerts`.
3. [Install the Datadog Agent][10] on your host.
4. Once the Agent is installed, run the following command to install the integration:
```
datadog-agent integration install -t datadog-Cybersixgill Actionable Alerts==1.0.0
```

### Configuration
5. Reach out to [Cybersixgill Support][13] and request access to the Cybersixgill Developer Platform.
6. Receive the welcome email with access to the Cybersixgill developer platform.
7. Within the Cybersixgill developer platform, create the Client ID and Client secret.
8. Copy the Client ID and Client secret and paste them into the Configuration.yaml file.
9. Provide the min collection interval in seconds. For example, `min_collection_interval: 3600`

### Validation
Verify that Cybersixgill events are generated in the [Datadog Event Explorer][12].

## Data Collected

### Service Checks
See [service_checks.json][14] for a list of service checks provided by this integration.

### Events
This integration sends API type events to Datadog.

## Troubleshooting
Need help? Contact [Cybersixgill support][13].

[1]: https://www.cybersixgill.com/
[2]: https://app.datadoghq.com/account/settings#agent
[3]: https://docs.datadoghq.com/help/
[4]: https://github.com/DataDog/integrations-extras/blob/master/cybersixgill_actionable_alerts/datadog_checks/cybersixgill_actionable_alerts/data/conf.yaml.example
[5]: https://docs.datadoghq.com/agent/guide/agent-commands/#start-stop-and-restart-the-agent
[6]: https://docs.datadoghq.com/agent/guide/agent-commands/#agent-status-and-information
[7]: https://github.com/DataDog/integrations-extras/blob/master/cybersixgill_actionable_alerts/metadata.csv
[8]: https://github.com/DataDog/integrations-extras/blob/master/cybersixgill_actionable_alerts/assets/service_checks.json
[9]: https://docs.datadoghq.com/help/
[10]: https://app.datadoghq.com/account/settings#agent
[11]: https://docs.datadoghq.com/developers/integrations/new_check_howto/?tab=configurationtemplate#configure-the-developer-tool
[12]: https://app.datadoghq.com/event/explorer
[13]: support@cybersixgill.com
[14]: https://github.com/DataDog/integrations-extras/blob/master/cybersixgill_actionable_alerts/assets/service_checks.json
