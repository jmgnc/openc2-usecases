# Table Of Contents

-   [Participation](#participation)
    -   [Summary:](#summary)
    -   [Programming Languages Used](#programming-languages-used)
    -   [Transfer Protocols Used](#transfer-protocols-used)
    -   [Companies / Organizations
        Participating](#companies--organizations-participating)
-   [Projects / BoF Groups](#projects-bof-groups)
    -   [Project: OpenC2 Schema Tools](#project-openc2-schema-tools)
    -   [Project: OpenC2 Cloud Compute Actuator (New
        Context)](#project-openc2-cloud-compute-actuator-new-context)
    -   [Project: OpenC2 Integration Framework (OIF) Orchestrator (NSA
        OpenC2
        Team)](#project-openc2-integration-framework-oif-orchestrator-nsa-openc2-team)
    -   [Project: Cloud Firewall Common Command (AT&T / UNC / UOslo /
        ...)](#project-cloud-firewall-common-command-att--unc--uoslo--)
    -   [Project: OpenC2 on CANBUS (BAE
        Systems)](#project-openc2-on-canbus-bae-systems)
    -   [Project: Unified Cyber Defense Platform (Northrup
        Grumman)](#project-unified-cyber-defense-platform-northrup-grumman)
    -   [Project: HaHa Actuator on Raspberry Pi (sFractal
        Consulting)](#project-haha-actuator-on-raspberry-pi-sfractal-consulting)
    -   [Project: Dynamic Recognition of Actuator Capabilities (UK Mod /
        CACI
        UK)](#project-dynamic-recognition-of-actuator-capabilities-uk-mod--caci-uk)
    -   [Project: Erlang-based Command Generator
        (NineFX)](#project-erlang-based-command-generator-ninefx)
    -   [Project: Web-based Command Generator
        (Hereuco)](#project-web-based-command-generator-hereuco)
    -   [Project: Vector-based Malware Classifier
        (BluVector)](#project-vector-based-malware-classifier-bluvector)
    -   [Project: VirusTotal Malware Check
        (Google)](#project-virustotal-malware-check-google)
    -   [Project: OpenC2 Producer/Consumer using Yuuki (NSA OpenC2
        Team)](#project-openc2-producerconsumer-using-yuuki-nsa-openc2-team)
    -   [Project: Endpoint File Blacklist and Device Quarantine
        (Symantec
        ICDx)](#project-endpoint-file-blacklist-and-device-quarantine-symantec-icdx)
    -   [Project: Consumer/Orchestrator Handling Multiple Responses
        (Symantec
        ICDx)](#project-consumerorchestrator-handling-multiple-responses-symantec-icdx)
    -   [Project: Blinky Light Board (NSA OpenC2
        Team)](#project-blinky-light-board-nsa-openc2-team)
-   [Scenarios](#scenarios)
    -   [Scenario: Active Cyber Defense of Critical Infrastructure
        (ACDCI) (Clarity Cyber / NSA OpenC2
        Team)](#scenario-active-cyber-defense-of-critical-infrastructure-acdci-clarity-cyber--nsa-openc2-team)
    -   [Scenario 2: Name2](#scenario-2-name2)
-   [Issues Identified](#issues-identified)
    -   [Issue 1: Authentication](#issue-1-authentication)
    -   [Issue 2: Limited data in responses from
        actuators](#issue-2-limited-data-in-responses-from-actuators)
    -   [Issue 3: Temporal Requirements - Start /
        Stop](#issue-3-temporal-requirements---start--stop)
    -   [Issue 4: Multiple Targets or Similar
        Commands](#issue-4-multiple-targets-or-similar-commands)
    -   [Issue 5: Logging per rule?](#issue-5-logging-per-rule)
    -   [Issue 6: Comment on Rule](#issue-6-comment-on-rule)
    -   [Issue 7: Clarify ipv4net](#issue-7-clarify-ipv4net)
    -   [Issue 8: Transfer Response Handling when "Response =
        NONE"](#issue-8-transfer-response-handling-when-response-none)
    -   [Issue 9: Forward packet/duplicate
        packet/offload](#issue-9-forward-packetduplicate-packetoffload)
    -   [Issue 10: What knows the security-group name and priority to
        use?](#issue-10-what-knows-the-security-group-name-and-priority-to-use)
    -   [Issue 11: Content Balance Between HTTPS Headers and OpenC2
        Message
        Content](#issue-11-content-balance-between-https-headers-and-openc2-message-content)
    -   [Issue N: NameN](#issue-n-namen)
    -   [Issue N: NameN](#issue-n-namen-1)
    -   [Issue N: NameN](#issue-n-namen-2)

# Participation

## Summary:

* Approximately 50 people
* 28 Companies / Organizations
* 3 Countries (Norway, UK, USA)

## Programming Languages Used

Python, Erlang, Elixer, ...

## Transfer Protocols Used

HTTP, HTTPS, OpenDXL, MQTT, GCP Pub/Sub, ...

## Companies / Organizations Participating

* APS Global
* AT&T
* BAE Systems
* BLS Government Services (BLSGVT)
* BluVector
* CACI UK
* Clarity Cyber
* Derigo Technology
* EverWatch
* Fuse Solutions
* Google
* Hereuco
* Huntington Ingalls Industries
* NEC Corporation
* NETSCOUT
* National Security Agency
* New Context
* NineFX
* Northrup Grumman
* OASIS
* QoSient
* Saltstack
* sFractal Consulting
* TC9
* U.K. Ministry of Defense
* U.S. Department of Defense
* University of North Carolina
* University of Oslo
* *others TBSL*

# Projects / BoF Groups

If writing up a project, please capture the initial (start of plug fest) and final (end of plug fest) state of your project, so that we have some indication of progress made during the event.

## Project: OpenC2 Schema Tools
*Description:* GCP-based schema processor with a REST API and a web front end.  This is a "meta-project" intended
to support project development during and after the plugfest.

*State:*
* Initial / Final State: API functions available with manual URL typing.  Web-based UI is planned.
* Releaseability: open source [OpenC2 Schema Tools]
     * [Presentation](https://drive.google.com/open?id=1VAMWY9JriFjKNzbRXSz6ZjeVk-oOyYn4XKHP3CouiCI)
     * [API Definition](https://drive.google.com/open?id=1b3XKWbPP41qXPBlrM8BUgPyesmBV7UNz9tllR9frzXo)
     * [Plugfest Schemas](https://github.com/oasis-open/openc2-custom-aps/tree/master/Schema-Template) v1.0.1/Separate/JADN
* Demonstrated? no
* Interworked? N/A

## Project: OpenC2 Cloud Compute Actuator (New Context)
*Description:* The project implements an actuator to create and control cloud VM
s.

*State:*
* At plugfest / described
* Initial / Final State
* Releaseability: open source [OpenC2-aws-actuator](https://github.com/newcontext-oss/openc2-aws-actuator)
* Demonstrated? yes
* Interworked? no, no other implementations available

## Project: OpenC2 Integration Framework (OIF) Orchestrator (NSA OpenC2 Team)

*Description:* this project ...

*State:*
* At plugfest / described
* Initial / Final State
* Releaseability: open source vs. proprietary
* Demonstrated?
* Interworked?

## Project: Cloud Firewall Common Command (AT&T / UNC / UOslo / ...)

*Description:* this project ...

*State:*
* At plugfest / described
* Initial / Final State
* Releaseability: open source vs. proprietary
* Demonstrated?
* Interworked?

## Project: OpenC2 on CANBUS (BAE Systems)

*Description:* this project ...

*State:*
* Described
* Initial / Final State
* Releaseability: open source vs. proprietary
* Demonstrated?
* Interworked?

## Project: Unified Cyber Defense Platform (Northrup Grumman)

*Description:* this project ...

*State:*
* At plugfest / described
* Initial / Final State
* Releaseability: open source vs. proprietary
* Demonstrated?
* Interworked?

## Project: HaHa Actuator on Raspberry Pi (sFractal Consulting)

*Description:* This project is based on the HaHa elixir open
source code. See https://github.com/oasis-open/openc2-lycan-beam/tree/master/haha/elixir.
Several aspects:
* HaHa/SBOM/Blinky actuator running on laptop
* Blinky running on Raspberry Pi Zero
* Blinky running on Raspberry Pi 4

*State:*

* State before plugfest
  + openc2 haha/sbom/blink server running on laptop on HTTP (not OC2-compliant HTTPS)
  + blinky running on raspberry pi's - but not yet OpenC2 controlled
* State at end of plugfest
  + HTTPS was added - alot of issues with certs, headers, and stuff that really wasn't OC2 but impeded
  + other people accessed HaHa & SBOM using postman. Accessing from HII OIF did not work due to header issues. Accessing from NineFX code worked if all the cert checks were disabled
* Everything used was open source
* Demonstrated - yes
* Interworked:
  + Yes via HTTP (non-compliant with OC2 Transport Spec) using Postman
  + Yes via HTTPS using postman (probably not OC2-compliant, not clear on header issues)
  + Sort of Yes from NineFX code (custom response header issues on sFractal side)
  + No from HII OIF

## Project: Dynamic Recognition of Actuator Capabilities (UK Mod / CACI UK)

A demo application for connecting to actuators during the event. Our use case is to provide a theoretical user a GUI which allows them to execute a course of action. The application automatically populates the actuator's capabilities, and then builds and executes an OpenC2 request. We used query features to get the profile and then built the profile up via the GUI as form elements.

We will explore whether it is possible to share further work on actuator auto-discovery using MDNS and MANET data distribution protocols. 

*State:*
* State before plugfest
  + Incomplete implementation for discovering actuators and executing actions
* State at end of plugfest
  + Still not complete but much closer, could discover actuators, configure a profile and then execute actions against a target using 3rd party actuators
* Not open sourced but will be soon.
* Demonstrated - yes (slides)
* Interworked:
  + Yes via HTTP to 3 actuators (Bluevector, Denver Airport Demo and Blinking Lights)


## Project: Erlang-based Command Generator (NineFX)

*Description:* BEAM (Erlang/Elixir) OpenC2 SDK

*State:*
* A set of libaries to facilitate OpenC2 producer actions.
* Initial State: Proof of Concept
* Releaseability: open source
* Demonstrated: Yes
* Interworked: NEC's SPLF firewall over HTTPS with client certificate authentication, HII Blinky IoT over Google Cloud Platform (GCP)

## Project: Web-based Command Generator (Hereuco)

*Description:* this project ...

*State:*
* At plugfest / described
* Initial / Final State
* Releaseability: open source vs. proprietary
* Demonstrated?
* Interworked?

## Project: Vector-based Malware Classifier (BluVector)

*Description:* this project ...

*State:*
* At plugfest / described
* Initial / Final State
* Releaseability: open source vs. proprietary
* Demonstrated?
* Interworked?

## Project: VirusTotal Malware Check (Google)

*Description:* this project ...

*State:*
* At plugfest / described
* Initial / Final State
* Releaseability: open source vs. proprietary
* Demonstrated?
* Interworked?

## Project: OpenC2 Producer/Consumer using Yuuki (NSA OpenC2 Team)

*Description:* This project demonstrates the ability to send
OpenC2 commands from an Yuuki-based OpenC2 Producer to an OpenC2 Consumer 
to an ACME Road Runner Actuator.

*State:*

* Presented at Plugfest:  Please see architecture documents with 
title "OpenC2 Producer Consumer using Yuuki"
* Initial / Final State:  OpenC2 Commands Sent/OpenC2 Responses Received
* Releaseability: open source
* Demonstrated: Yes
* Interworked: Yes

## Project: Endpoint File Blacklist and Device Quarantine (Symantec ICDx)

*Description:* this project ...

*State:*
* At plugfest / described
* Initial / Final State
* Releaseability: open source vs. proprietary
* Demonstrated?
* Interworked?

## Project: Consumer/Orchestrator Handling Multiple Responses (Symantec ICDx)

*Description:* this project ...

*State:*
* At plugfest / described
* Initial / Final State
* Releaseability: open source vs. proprietary
* Demonstrated?
* Interworked?


## Project: Blinky Light Board (NSA OpenC2 Team)

*Description:* This project demonstrates the ability to send OpenC2 commands from an Orchestrator to an OpenC2 Actuator
using a Raspberry Pi device to perform a flashing of lights on a hardware board with WS-2811 LED Flashing Lights.

*State:*
* Presented at plugfest:  Please see two architecture documents with 
titles "Remote Activation of Flashing Lights1" and 
"Remote Activation of Flashing Lights2"
* Initial State: No lights flashing / Final State:  Sequences of lights flashing
* Releaseability: open source
* Demonstrated?  Yes
* Interworked?  Yes

# Scenarios


## Scenario: Active Cyber Defense of Critical Infrastructure (ACDCI) (Clarity Cyber / NSA OpenC2 Team)

*Description:* This project demonstrates the ability to send OpenC2 commands from an python-based 
OpenC2 Producer to an OpenC2 Consumer to a series of nine actuators. It is intended to model
an implementation of a system to defend a geographic area from hostile drone intrusions, but 
is adaptable to other scenarios.

*State:*
* Presented at Plugfest: Please see multiple architecture documents with 
titles "OpenC2 Active Cyber Defense of Critical Infrastructure (ACDCI)", "ACDCI Use case using Google
Kubernetes Engine (GKE)", "GCP Kubernetes Nodes with GKE for NS3 Simulator", "Active Cyber Defense of 
Critical Infrastructure (ACDCI) Use Case.
* Initial / Final State:  ACDCI actuators received and processed commands from multiple OpenC2 Producers
* Releaseability: open source
* Demonstrated: Yes
* Interworked: Yes

## Scenario 2: Name2

*Description:* this project ...

*State:*
* At plugfest / described
* Initial / Final State
* Releaseability: open source vs. proprietary
* Demonstrated?
* Interworked?

# Issues Identified

## Issue 1: Authentication

*Source*:  Firewall / Packet Filtering BoF

*Description:* while doing X, we discovered Y ...

*Potential Solutions*: suggestions for resolutions or work-arounds developed

## Issue 2: Limited data in responses from actuators

Rules, which actuator, support for temporal?  (may need to break this into multiple issues)

*Source*:  Firewall / Packet Filtering BoF

*Description:* while doing X, we discovered Y ...

*Potential Solutions*: suggestions for resolutions or work-arounds developed

## Issue 3: Temporal Requirements - Start / Stop

*Source*:  Firewall / Packet Filtering BoF

*Description:* while doing X, we discovered Y ...

*Potential Solutions*: suggestions for resolutions or work-arounds developed

## Issue 4: Multiple Targets or Similar Commands

*Source*:  Firewall / Packet Filtering BoF

*Description:* while doing X, we discovered Y ...

*Potential Solutions*: suggestions for resolutions or work-arounds developed

## Issue 5: Logging per rule?

*Source*:  Firewall / Packet Filtering BoF

*Description:* while doing X, we discovered Y ...

*Potential Solutions*: suggestions for resolutions or work-arounds developed

## Issue 6: Comment on Rule

*Source*:  Firewall / Packet Filtering BoF

*Description:* while doing X, we discovered Y ...

*Potential Solutions*: suggestions for resolutions or work-arounds developed

## Issue 7: Clarify ipv4net

Ipv4net should be clarified as ANY->ipv4net AND ipv4net->ANY : 2 rules

*Source*:  Firewall / Packet Filtering BoF

*Description:* while doing X, we discovered Y ...

*Potential Solutions*: suggestions for resolutions or work-arounds developed

## Issue 8: Transfer Response Handling when "Response = NONE"

*Source*:  Firewall / Packet Filtering BoF

*Description:* while doing X, we discovered Y ... (conflict between OpenC2 command selecting the "repsonse = NONE" option whereas the HTTP transfer protocols *requires* a response.

*Potential Solutions*: suggestions for resolutions or work-arounds developed

## Issue 9: Forward packet/duplicate packet/offload

*Source*:  Firewall / Packet Filtering BoF

*Description:* while doing X, we discovered Y ...

*Potential Solutions*: suggestions for resolutions or work-arounds developed

## Issue 10: What knows the security-group name and priority to use?

*Source*:  Firewall / Packet Filtering BoF

*Description:* while doing X, we discovered Y ...

*Potential Solutions*: suggestions for resolutions or work-arounds developed

## Issue 11: Content Balance Between HTTPS Headers and OpenC2 Message Content

*Source*:  Multiple groups.

*Description:* PF participants had numerous interworking issues relating to informtion in HTTP headers vs. OpenC2 message content.

*Potential Solutions*: revisit the decisions made for the v1.0  HTTPS specification for such information elements as the CommandID, content type, etc., based on results of plug fest attempts to achieve interoperability between a variety of implementations. Potential changes include simplifying the content type to simply be "JSON", and adding OpenC2 version information and command IDs into the message content.  This may fold back into the definition of OpenC2 messages in the Language Specification.

## Issue N: NameN

*Source*:  (who / what group identified this issue)

*Description:* while doing X, we discovered Y ...

*Potential Solutions*: suggestions for resolutions or work-arounds developed

## Issue N: NameN

*Source*:  (who / what group identified this issue)

*Description:* while doing X, we discovered Y ...

*Potential Solutions*: suggestions for resolutions or work-arounds developed

## Issue N: NameN

*Source*:  (who / what group identified this issue)

*Description:* while doing X, we discovered Y ...

*Potential Solutions*: suggestions for resolutions or work-arounds developed
