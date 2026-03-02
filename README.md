# Student-Helpdesk-Automation-System
End-to-end student helpdesk automation built on UiPath Automation Cloud using BPMN orchestration, agents, human-in-the-loop approval app, and RPA email response + logging.

## Overview
This project is an end-to-end student query handling system built using UiPath Automation Cloud.
The system combines BPMN workflow orchestration, modular agents, an approval interface, and RPA automation to automatically process and respond to student helpdesk emails.

## What the System Automates
1. Receives student email query
2. Classifies request category
3. Extracts student information
4. Checks if admin approval is required
5. Generates response
6. Sends email reply
7. Logs request in tracking system

## Key Features
- BPMN orchestration workflow
- Human-in-the-loop approval (UiPath App)
- Automated email responses
- Query tracking log
- Modular agent-based processing

## Architecture
BPMN Orchestrator → Classification Agent → Data Extraction → Approval App → Response Generator → Email Sender → Logging System

## Importing the solution
A full solution export (`StudentHelpdeskAutomation-1.0.0.zip`) is included in the root directory of this repository.  
You can download it directly and import it into UiPath Automation Cloud (Studio Web) to explore the workflows.

### Steps to Import
1. Download `StudentHelpdeskAutomation-1.0.0.zip` from this repository
2. Open UiPath Automation Cloud
3. Go to **Studio Web**
4. Select **Import → Solutions**
5. Upload the `.zip` file
6. The BPMN process, agents, and app components will appear in the workspace

## Note:
This is a cloud-native UiPath solution and requires a UiPath Automation Cloud tenant to import. 
It will not run as a standalone desktop process.

## 🎥 Demonstration Video
A full working demonstration of the system is available here:

[Watch the demo on LinkedIn](https://www.linkedin.com/posts/sneha-ram-7a211239b_uipath-agenticautomation-rpa-activity-7433563059056734208-JJsP?utm_source=share&utm_medium=member_desktop&rcm=ACoAAGIVHuoBwV_KVdWe9IOYOgWkR25gZFO-f7U)
