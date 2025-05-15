# LabHost PhaaS Domains Repository

## Overview

This repository contains a list of approximately 42,000 phishing domains associated with the LabHost phishing-as-a-service (PhaaS) platform, as released by the Federal Bureau of Investigation (FBI) in May 2025. These domains were operational between November 2021 and April 2024, before LabHost was disabled by law enforcement.

## Background

LabHost was one of the world's largest PhaaS providers, serving approximately 10,000 cybercriminal users. The platform enabled:

- Infrastructure configuration and technical support for phishing campaigns
- Customized phishing pages impersonating over 200 legitimate organizations
- Adversary-in-the-middle proxy connections to bypass two-factor authentication (2FA)
- Smishing services
- Stolen credential management

According to the FBI, LabHost infrastructure stored over one million user credentials and nearly 500,000 compromised credit cards, facilitating financial theft, fraud schemes, and money laundering activities.

## Purpose of This Repository

This collection is shared for defensive purposes only, to assist:

- Network defenders and security professionals
- Cyber threat intelligence analysts
- Organizations conducting security audits
- Researchers studying phishing infrastructure and techniques

## How to Use This Data

The FBI has explicitly released this information to maximize awareness and provide indicators of compromise. Security teams may use this data to:

1. **Conduct Historical Research**: Identify past connections to these domains in your environment
2. **Enhance Network Protection**: Consider blacklisting these domains
3. **Configure Security Alerts**: Set up monitoring for any connections to these domains
4. **Improve Threat Intelligence**: Better understand phishing tactics and infrastructure

## Important Disclaimer

- These domains are historical in nature and may not currently be malicious
- The FBI has not validated every domain name, and the list may contain typographical errors
- This information should be used responsibly and for defensive purposes only
- Identification of any activity related to these indicators should prompt incident response procedures

## Source Attribution

This domain list was obtained from the FBI's announcement following the takedown of the LabHost platform in April 2024. The original advisory can be found at https://www.ic3.gov/CSA/2025 (reference link from the FBI FLASH).

## Contributing

If you have additional information about these domains or have identified patterns that could benefit the security community, please consider contributing via pull requests or issues.

## Legal Disclaimer

This repository and its contents are provided for informational and defensive security purposes only. The maintainer of this repository is not responsible for any misuse of this information. Always ensure compliance with applicable laws and regulations when using this data.
