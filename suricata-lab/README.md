# Suricata IDS Home Lab

## Overview

This lab demonstrates network intrusion detection using Suricata IDS in a Kali Linux virtual machine.

The objective was to configure Suricata to monitor network traffic, generate IDS alerts, and investigate suspicious network activity from a SOC analyst perspective.

## Lab Environment

- Kali Linux
- Oracle VirtualBox
- Suricata IDS
- Emerging Threats ruleset
- Network interface: eth0

## Suricata Configuration

Suricata was installed and the Emerging Threats ruleset was downloaded using `suricata-update`.

The Suricata configuration was successfully validated before monitoring began.

## Detection Test

Suricata was started on the `eth0` network interface.

A test request was generated using:

`curl http://testmynids.org/uid/index.html`

Suricata successfully detected the test traffic and generated an alert:

**GPL ATTACK_RESPONSE id check returned root**

This confirmed that Suricata was correctly monitoring network traffic and generating IDS alerts.

## SOC Analyst Assessment

The alert demonstrates successful network-based threat detection. Suricata identified suspicious HTTP traffic matching an IDS signature and recorded the source and destination information for further investigation.

## Skills Demonstrated

- Network intrusion detection
- Suricata installation and configuration
- IDS rule management
- Network traffic monitoring
- Alert analysis
- SOC investigation workflow
