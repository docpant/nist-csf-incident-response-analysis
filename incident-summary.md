# Incident Summary

## Security Event Overview

A multimedia company experienced a denial of service (DoS) attack that disrupted internal network operations for approximately two hours.

The attack involved a flood of incoming ICMP packets that overwhelmed network resources and prevented legitimate internal traffic from accessing network services.

## Cause of the Incident

The attacker exploited an improperly configured firewall that allowed excessive ICMP traffic into the network.

## Impact

- Internal network services became unavailable
- Employees lost access to network resources
- Critical operations were disrupted
- Network availability was affected

## Immediate Response

The incident management team:
- Blocked incoming ICMP packets
- Disabled non-critical services
- Restored critical network operations

## Security Improvements

The organization implemented:
- Firewall ICMP rate limiting
- Source IP verification
- Network monitoring software
- IDS/IPS filtering systems
