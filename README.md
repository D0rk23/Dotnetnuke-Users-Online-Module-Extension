# Dotnetnuke-Users-Online-Module-Extension
# DNN Users Online Module

This module displays real-time user activity within a DotNetNuke (DNN) portal.  
It shows information about total membership, users currently online, and people active in the past 24 hours.

---

## Overview

The Users Online module can display the following information:

- **Membership:**  
  Shows the latest registered user, total number of members, and user activity for the past 24 hours.
- **People Online:**  
  Displays the number of visitors, members, and total users currently online.
- **Online Now:**  
  Lists currently active users when enabled.

If the module is added to a page before being fully configured, only membership information is displayed.

---

## Configuration

Before all sections are visible, the module must be enabled and configured by a SuperUser.

### 1. Enable in Host Settings
- Navigate to **Host → Settings → Advanced Settings**
- Enable **Users Online**

### 2. Enable the Scheduler
- Go to **Host → Schedule**
- Find the entry named **Users Online**
- Enable it and set it to run every 5–10 minutes

### 3. Add the Module
- Add **Users Online** to any page
- Configure its display options as needed

---

## Example Output
