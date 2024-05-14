# ThreatLocker Network Access Control Policy Configuration Exercise

Welcome to the ThreatLocker Network Access Control (NAC) Policy Configuration Exercise repository. This project involves setting up robust network access control policies using ThreatLocker to regulate and monitor network activities effectively. Below, you'll find detailed steps for creating your ThreatLocker account, setting up the software, and configuring NAC policies.

## Overview of ThreatLocker

ThreatLocker provides a comprehensive security solution that allows fine-grained control over network and application access. By implementing Network Access Control policies, you can ensure that only authorized traffic is allowed in your network, enhancing your security posture significantly.

## Prerequisites

Before you start, ensure that you have administrative access to a computer where you can install software and configure network settings.

## Setup Instructions

1. **Create a ThreatLocker Account:**
   - Sign up for ThreatLocker by responding to the 'create password' email sent after initial registration.

2. **Install ThreatLocker Software:**
   - Download and install the ThreatLocker binary on a computer of your choice. This computer will be used for testing the NAC policies.

## Configuration

3. **Configure Default Deny Policy:**
   - Navigate to the NAC module in the ThreatLocker portal.
   - Add a default deny policy. This policy should be applied only to your test computer and placed at the bottom of the policy hierarchy to ensure it executes last.

4. **Operational Testing in Learning Mode:**
   - Allow your computer to operate in learning mode under the default deny policy for a few hours while you continue to use the computer normally.
   - Access the Unified Audit logs, and filter the results to show only network traffic and data related to your computer's hostname.

5. **Create Allow Policies:**
   - Review the logged data to identify all IP addresses and port numbers that your computer has communicated with.
   - Create NAC policies in ThreatLocker to explicitly allow connections to these IP addresses and ports.

## Verification and Submission

6. **Capture and Submit Screenshot:**
   - Once your allow policies are configured, take a screenshot of the NAC policy screen filtered to show only policies applicable to your test computer.
   - Submit this screenshot as part of your assignment deliverables.

## Support

For troubleshooting or further guidance on using ThreatLocker, please refer to the [ThreatLocker Support Center](https://www.threatlocker.com/support) or submit an issue in this repository.

Thank you for undertaking this exercise to configure and validate Network Access Control policies using ThreatLocker. We look forward to reviewing your successful implementation of these security measures.
