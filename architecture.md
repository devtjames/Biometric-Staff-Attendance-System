# System Architecture

## Overview

The Biometric Staff Attendance System uses a centralized architecture built around biometric authentication and controlled data storage to ensure accurate and tamper-resistant attendance records.

---

## Core Components

### 1. Biometric Input Layer

- Fingerprint scanner
- Captures staff fingerprint data
- Uses SDK-provided matching algorithms for verification

---

### 2. Application Layer

- Handles fingerprint verification
- Controls clock-in and clock-out logic
- Manages staff enrollment
- Provides admin functionality

---

### 3. Database Layer

- Stores staff profiles
- Stores fingerprint templates
- Stores attendance logs
- Preserves historical attendance records

---

### 4. Presentation Layer

- Staff attendance interface
- Admin dashboard
- Attendance summaries and reports

---

## Data Flow

1. Staff places fingerprint on the scanner  
2. System verifies fingerprint against stored templates  
3. Attendance event is recorded with timestamp  
4. Admin reviews attendance history and reports  

---

## Security Considerations

- Biometric data is stored securely
- Access to administrative actions is restricted
- Attendance actions require successful biometric verification
