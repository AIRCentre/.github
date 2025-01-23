---
name: Functional Requirement
about: Define a functional requirement with clear and testable acceptance criteria.
title: "[FR] "
labels: feature
assignees: ''

---

# Functional Requirement

### **Description**
Provide a clear and concise description of the functional requirement.  
Example: "Users must be able to reset their password via an email link."

---

### **Acceptance Criteria**
Define testable criteria for validating the requirement, using the "Given-When-Then" format.

- **Given** the user is on the login page and has forgotten their password,  
  - **When** they click the "Forgot Password" link and provide a registered email address,  
  - **Then** the system sends a password reset email with a secure link.

- **Given** the user has received the password reset email,  
  - **When** they click the link and provide a new password,  
  - **Then** the system updates their password and confirms the change.

---

### **Additional Context**
Include any relevant details, diagrams, references, or assumptions to clarify the requirement.  
For example:
- The password reset link should expire after 24 hours.
- The new password must meet security requirements (e.g., minimum length, special characters).

---

### **Dependencies**
List any related issues, pull requests, or tasks that are linked to this functional requirement.

---

### **Checklist**
- [ ] Requirement is clearly defined.
- [ ] Acceptance criteria are testable.
- [ ] Dependencies are linked.
- [ ] Stakeholders have reviewed the issue.
