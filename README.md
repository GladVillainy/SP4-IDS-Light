# SP4-IDS-Light

SP4-IDS-Light is a lightweight **Intrusion Detection System (IDS)** developed in **Java**.
The system is implemented as a console-based application that analyzes log data and detects suspicious behavior using simple, rule-based logic.

The project is intended as a foundational IDS solution that can be extended with additional detection rules and log formats.

## Background and Scope

This project is built on top of the **SP3 Streaming Service project**, which serves as its technical foundation.  
While SP3 focused primarily on streaming functionality, SP4-IDS-Light extends the solution with a strong emphasis on **security monitoring and intrusion detection**.

The system is intended for environments with **strict security requirements and monitoring needs**, such as applications, software systems, or server-based solutions where log analysis and threat detection are relevant.

It is important to note that this is a **student project** developed for educational purposes.  
The system is **not intended for production use** and does not meet the security, reliability, or compliance standards required for real-world deployment.

---

## Purpose

The purpose of SP4-IDS-Light is to:

* detect suspicious behavior in log files
* record and store security-related events (threats)
* provide an overview of previous incidents via the console
* serve as an extensible foundation for further IDS development

---

## Functional Requirements

### 1. Threat Detection and History

The system is capable of storing and displaying previously detected threats.

* Threats are stored during runtime in a CSV file
* Historical threats can be viewed via the console
* Enables post-incident analysis of security events

### 2. Simple and Understandable Design

The system is designed with simplicity and clarity in mind:

* clear and structured console output
* focus on core IDS functionality
* avoids complex security mechanisms

### 3. Console-Based Application

SP4-IDS-Light runs exclusively as a console application:

* no graphical user interface
* suitable for server and workstation environments

### 4. Detected Events

The system can detect the following types of suspicious behavior:

* login attempts outside a defined time window
* repeated failed login attempts (brute-force attacks)
* deletion of lines in log files

If any of the above events are detected, the system can automatically **lock the user**.

---

## Technology

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" width="32"/>

* **Language:** Java
* **Execution:** Console application
* **Data Storage:** CSV files

---

## Project Status

The project is under development and can be extended with:

* additional detection rules
* support for more log formats
* more advanced event analysis
