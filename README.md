# ANB IVR System – Arab National Bank

An Interactive Voice Response (IVR) system designed and implemented for Arab National Bank (ANB) as part of the Multimedia & Internet Apps lab project at the Islamic University of Madinah.

The project demonstrates the design, configuration, and testing of an IVR system using FreePBX, with external call testing through Zoiper and the Misk application.

## Table of Contents

- [Introduction](#introduction)
- [Organization Overview](#organization-overview)
- [System Setup](#system-setup)
- [IVR System Design](#ivr-system-design)
- [Voice Recordings](#voice-recordings)
- [System Testing](#system-testing)
- [Organization Structure](#organization-structure)
- [Conclusion](#conclusion)


## Introduction

Automated systems such as Interactive Voice Response (IVR) have become important tools for improving customer service in the banking sector.

The purpose of this project is to analyze, design, configure, and test an IVR system for Arab National Bank (ANB).

The project demonstrates the system setup, voice prompts, menu structure, customer authentication flow, banking service options, and testing procedures.

## Organization Overview

Arab National Bank (ANB) is a financial institution in Saudi Arabia that provides banking services to individuals, businesses, and corporations.

The proposed IVR system aims to improve customer service by automating access to banking information and services through an interactive telephone menu.

## System Setup

The IVR system setup involved several configuration steps using FreePBX and supporting applications.

### 1. Adding System Recordings

The first step involved adding the necessary system recordings in FreePBX. These recordings provide the voice prompts and announcements used throughout the IVR system.

![Adding the necessary system recordings](adding%20the%20necessary%20system%20recordings.png)

### 2. Configuring the IVR Menus

The recorded voice prompts were integrated into the IVR system. The menus were configured to allow callers to navigate through the available options using their telephone keypad.

![Configuring the IVR menus](configuring%20the%20IVR%20menus.png)

### 3. Creating Specific Extensions

Specific extensions were created to allow external applications, such as Zoiper, to connect to the IVR system for testing purposes.

![Specific extensions](specific%20extensions.png)

### 4. Creating the Misk Application

The Misk application was created to generate the dialable numbers used to access the IVR system.

![Creation of the Misk application](creation%20of%20the%20Misk%20application.png)

## IVR System Design

The IVR system was designed to provide customers with a clear and straightforward navigation experience.

Its main components include:

1. **Welcome Message:** Provides a greeting, branch working hours, and a fraud-prevention announcement.
2. **Language Selection:** Allows customers to select English or Arabic.
3. **Customer Authentication:** Includes prompts for an 8-digit customer number, the last four digits of the registered mobile number, OTP, phone number, Saudi ID or Iqama number, address or ZIP code, and telephone secret code.
4. **Main Menu:** Provides access to banking services, fraud reporting, card services, application status, and the phone banking survey.
5. **Banking Services Menu:** Provides account services, digital banking services, ANB Rewards, and cashing services.
6. **Cash Services:** Allows callers to be transferred to phone banking officers.

## Voice Recordings

The project includes voice prompts for the following IVR stages:

| No. | Recording | Purpose |
|---|---|---|
| 1 | Welcome Message | Greeting, working hours, and fraud prevention |
| 2 | Language Selection | English and Arabic selection |
| 3 | Customer Authentication | Customer number verification |
| 4 | Registered Mobile Number | Last four digits verification |
| 5 | OTP Prompt | One-time password entry |
| 6 | Phone Number | Mobile or home/work phone number |
| 7 | Saudi ID or Iqama | Identity number entry |
| 8 | Address or ZIP Code | Address information |
| 9 | Telephone Secret Code | Four-digit secret code |
| 10 | Main Menu | Main banking options |
| 11 | Banking Services Menu | Banking service categories |
| 12 | Account Services | Account-related options |
| 13 | Digital Banking Services | Beneficiary and e-banking options |
| 14 | ANB Rewards Program | Rewards program information |
| 15 | Cashing Services | Transfer to a phone banking officer |

## System Testing

Zoiper was used as an external application to make test calls and interact with the IVR system.

The testing process involved:

1. Configuring the required extensions.
2. Establishing a connection through Zoiper.
3. Using the Misk application to generate and dial the required numbers.
4. Navigating through the IVR menus and testing the available options.
5. Recording a demonstration video of the IVR flow and system interactions.

These tests were used to evaluate the system's menu navigation and response to user input.

## Organization Structure

The following diagram illustrates the organization structure included in the project report.

![Diagram of Organization Structure](Diagram%20of%20Organization%20Structure.png)

## Conclusion

The ANB IVR system project demonstrates how an Interactive Voice Response system can organize customer interactions and provide access to banking service options through automated telephone menus.

The project includes voice recordings, bilingual menu navigation, customer authentication prompts, banking service options, and external testing using Zoiper and the Misk application.

The implementation and testing helped demonstrate the IVR system's structure, functionality, and potential role in improving customer service.




---

*Academic project – Interactive Voice Response System Design and Implementation for Arab National Bank.*
