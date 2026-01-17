# Zero Trust: Core Architectural Principles

Zero Trust is not a product or a network design. It is an architectural approach that assumes breach and continuously verifies trust based on identity, context, and risk.

This note outlines the core principles of Zero Trust from a security architecture perspective.

---

## 1. Never Trust, Always Verify
Trust is not granted based on network location. Every access request must be explicitly verified using identity, device posture, and contextual signals.

## 2. Identity as the Primary Control Plane
Identity replaces the network perimeter as the central enforcement point. Authentication and authorization decisions must be identity-driven, not IP-driven.

## 3. Least Privilege with Continuous Enforcement
Access should be scoped to the minimum required permissions and continuously re-evaluated during a session, not only at login time.

## 4. Assume Breach
Architectures must be designed with the assumption that attackers are already inside the environment. Controls should focus on limiting blast radius and lateral movement.

## 5. Strong Authentication and Authorization
Multi-factor authentication, device trust, and risk-based authorization are mandatory components of Zero Trust architectures.

## 6. Visibility, Telemetry, and Feedback Loops
Zero Trust relies on continuous visibility. Telemetry from identity systems, endpoints, networks, and workloads must feed policy decisions and enforcement.

---

## Architectural Note
Zero Trust succeeds or fails based on **architecture**, not tooling. Without identity-centric design, policy enforcement, and telemetry, Zero Trust becomes a marketing label rather than a security model.

---

**Author:** Mahfuzur Rahman  
Cybersecurity Architect
