# Privacy Policy for Crisp Chat Message Tracker

**Last Updated**: [05-07-2025]

## Overview

Crisp Chat Message Tracker ("the Extension") is committed to protecting your privacy. This privacy policy explains how my Chrome extension collects, uses, and protects your information.

## Single Purpose Statement

This extension has a single, clearly defined purpose: **To track and display your message sending activity on the Crisp Chat platform for personal productivity and analytics purposes.**

## Information We Collect

### Automatically Collected Information
- **Message Content**: Text content of messages you send in Crisp Chat
- **Timestamps**: When messages are sent
- **Chat Identifiers**: Unique identifiers for chat sessions
- **Media Indicators**: Whether messages contain attachments (file names/content not stored)
- **URL Information**: Crisp Chat page URLs to identify different conversations

### Information We Do NOT Collect
- Personal identifying information beyond what's in your messages
- Received messages from other users
- Login credentials or authentication tokens
- Crisp Chat account information
- Any data from websites other than Crisp Chat

## How We Use Your Information

Your information is used exclusively for:
- **Personal Analytics**: Displaying your daily message counts and activity
- **Chat Organization**: Grouping messages by conversation and date
- **Productivity Tracking**: Helping you monitor your messaging patterns
- **Local Storage**: All data processing occurs locally in your browser

## Data Storage and Security

### Local Storage Only
- All data is stored locally in your browser using localStorage API
- **No cloud storage** or external servers are used
- **No data transmission** to third parties or external servers
- Data remains on your device and under your control

### Data Retention
- Data is retained until you manually clear it using the "Clear All" button
- Uninstalling the extension will remove all stored data
- No automatic data expiration or cleanup

## Permissions Justification

### Required Permissions

#### "storage"
- **Purpose**: Store tracking data locally in your browser
- **Justification**: Essential for saving message count data and analytics between browser sessions
- **Scope**: Only accesses localStorage for this extension's data

#### "activeTab"
- **Purpose**: Access the current Crisp Chat tab to collect messaging data
- **Justification**: Required to monitor message sending activity on active Crisp Chat pages
- **Scope**: Only activates when you're actively using Crisp Chat

#### "scripting"
- **Purpose**: Execute content scripts to monitor message activity
- **Justification**: Necessary to detect when messages are sent and extract relevant data
- **Scope**: Scripts only run on Crisp Chat domains (https://app.crisp.chat/*)

### Host Permissions

#### "https://app.crisp.chat/*"
- **Purpose**: Monitor message sending activity on Crisp Chat platform
- **Justification**: This is the core functionality - tracking messages requires access to Crisp Chat pages
- **Scope**: Limited exclusively to Crisp Chat domains
- **Data Access**: Only monitors outgoing messages you send, not incoming messages or other user data

## Data Sharing and Third Parties

### No Data Sharing
- We do **NOT** share, sell, or transmit your data to any third parties
- We do **NOT** have servers that collect or store your data
- We do **NOT** use analytics services that track your usage
- All data processing occurs locally on your device

### No Third-Party Services
- No external APIs or services are contacted
- No tracking pixels or analytics codes
- No advertising networks or data brokers involved

## User Rights and Control

### Complete Data Control
- **View Data**: Access all stored data through the extension popup
- **Delete Data**: Use "Clear All" button to remove all tracking data instantly
- **Data Portability**: Data is stored in standard localStorage format
- **Uninstall**: Completely removes all data when extension is uninstalled

### Transparency
- All data collection is visible in the extension popup
- Source code logic is transparent and auditable
- No hidden data collection or background processes

## Children's Privacy

This extension does not knowingly collect information from children under 13. If you're under 13, please don't use this extension without parental supervision.

## Changes to Privacy Policy

I may update this privacy policy to reflect changes in my practices or for legal compliance. I will notify users of significant changes through:
- Extension update notifications
- Updated version information in the Chrome Web Store

## Compliance

### GDPR Compliance (EU Users)
- **Lawful Basis**: Legitimate interest for personal productivity tracking
- **Data Minimization**: Only collects necessary data for core functionality
- **Right to Access**: Full access to your data through extension interface
- **Right to Deletion**: Complete data deletion via "Clear All" function
- **Data Portability**: Data stored in accessible localStorage format

### CCPA Compliance (California Users)
- **No Sale of Data**: We do not sell personal information
- **No Third-Party Sharing**: Personal information is not shared
- **Right to Delete**: Available through "Clear All" functionality
- **Right to Know**: This policy details all data collection practices

## Security Measures

### Technical Safeguards
- Data stored locally with browser's built-in security
- No network transmission of sensitive data
- Content scripts run in isolated environment
- Minimal permission scope reduces attack surface

### Limitations
- Security depends on your browser and device security
- Local storage may be accessible to other extensions with storage permissions
- Physical access to your device could allow data access

## Contact Information

For questions about this privacy policy or data practices:

- **Extension Support**: [Create an issue in extension repository]
- **Privacy Concerns**: [Contact email/form]
- **Data Requests**: Use extension's built-in "Clear All" function

## Legal Compliance

This extension complies with:
- Chrome Web Store Developer Program Policies
- General Data Protection Regulation (GDPR)
- California Consumer Privacy Act (CCPA)
- Children's Online Privacy Protection Act (COPPA)

---

**Important Note**: This extension is not affiliated with Crisp Chat. I am an independent developer creating tools to enhance user productivity on the Crisp Chat platform.

**Effective Date**: This privacy policy is effective as of the date of installation and will remain in effect until superseded by an updated version.
