# Lab: Failed Login Detection

## Objective

Simulate failed login attempts and analyze detection in Wazuh.

## Environment

* OS: Ubuntu Server 24.04 (VM)
* SIEM: Wazuh
* Network: Bridged (192.168.x.x)

## Steps Performed

1. Attempted login with wrong password:

   ```bash
   su root
   ```
2. Repeated multiple times

## Observed Behavior

* Alert generated in Wazuh
* Rule triggered: PAM: User login failed
* MITRE Technique: T1110.001 (Brute Force)

## Analysis

This behavior simulates brute-force attempts where an attacker tries multiple passwords.

## Mitigation

* Implement account lockout after X attempts
* Enable MFA
* Monitor repeated failures

## Conclusion

Wazuh successfully detected and classified the attack behavior.
