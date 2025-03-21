# GPT for Blueprint Debugging

## Overview
GPT for Blueprint Debugging is a powerful Unreal Engine plugin that enables AI-assisted debugging for Blueprints using OpenAI's GPT models. It helps developers analyze Blueprint structures and detect issues more efficiently.

## Features
- **Automatic Blueprint Data Extraction**: Captures essential Blueprint details for debugging.
- **AI-Assisted Debugging**: Sends extracted Blueprint data to GPT to receive insightful debugging suggestions.
- **Customizable Data Selection**: Users can choose which Blueprint data to send for AI analysis.

## Installation & Setup
### 1. Enable the Plugin
1. Open Unreal Engine and go to **Edit > Plugins**.
2. Enable **GPT for Blueprint Debugging** and restart the editor.

### 2. Configure API Key
1. Navigate to **Edit > Project Settings > GPTforBlueprintDebugging Settings**.
2. Enter your OpenAI API key.

## Usage
### 1. Activate the Plugin
- Open the **Blueprint Editor** and go to **Window > GPTforBlueprintDebugging**.
- Select the GPT model (gpt-4, gpt-4o, o1-preview-2024-09-12).
- Choose the Blueprint data to send using checkboxes.
- Click **Update Blueprint Data** to synchronize the data.

### 2. Debugging Process
- The selected Blueprint data is sent to GPT along with the user’s prompt.
- GPT provides debugging insights based on the received data.

## Data Collected
- **Parent Class Information**
- **Graph Overview**
- **Node Details (Name, Type, Class, etc.)**
- **Node Connection Data**
- **Compilation Logs and Errors**

## Troubleshooting
### Q: Blueprint data is not being retrieved.
**A:** Ensure the **Blueprint Editor** is open and click **Update Blueprint Data**.

### Q: Plugin is unresponsive.
**A:** Verify your **OpenAI API key** is correctly entered.

### Q: Some node connections are missing.
**A:** Make sure all required data options are selected and update Blueprint data again.

## Support
For additional support, visit the official marketplace page or contact the developer.
