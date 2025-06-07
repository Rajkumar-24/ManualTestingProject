# Manual Testing Project: Comprehensive Test Case Suite

## 📋 Overview
This repository showcases a collection of meticulously designed test cases for real-world applications including **WhatsApp**, **Amazon E-commerce (Login/Register pages)**, and other critical user flows. Each test case validates functionality, usability, and edge cases to ensure robust software quality.

---

## 🧪 Test Cases Covered
### **1. WhatsApp Functional Test Suite**
- **Chat Features**: Message send/receive, media sharing, status updates
- **Group Functionality**: Member add/remove, admin controls
- **Edge Cases**: Network loss during calls, low storage scenarios

### **2. Amazon E-commerce Flow**
| Page          | Test Scenarios Covered                          |
|---------------|-----------------------------------------------|
| **Login**     | Valid/invalid credentials, password reset     |
| **Register**  | Email validation, OTP verification, T&C checks |
| **Checkout**  | Payment gateway integration, address validation |

[View Full Test Cases](test_cases/) <!-- Link to your test case directory -->

---

## 🚀 How This Project Sharpened My Manual Testing Skills

### 🔍 **Requirement Analysis**
- **Skill Gained**: Translated ambiguous specs (e.g., "login should be secure") into 25+ concrete test conditions
- **Example**: Broke down Amazon's "password strength" into 8 testable parameters (special chars, length, etc.)

### 🧩 **Test Design Techniques**
- **Boundary Value Analysis**:  
  Designed cases for password fields (min=6, max=30 chars → tested 5,6,30,31)
- **Equivalence Partitioning**:  
  Grouped invalid emails (missing @, .com, etc.) into test buckets

### ⚙️ **Defect Discovery**
- Identified 15+ potential flaws like:
  - WhatsApp: Profile photo not updating after network dropout
  - Amazon: Register page accepting expired OTPs

### 📊 **Traceability & Documentation**
- Created bidirectional traceability matrix linking:
  ```plaintext
  Business Requirement → Test Case → Defect Log

