# Ticket 005 - Disable Active Directory User Account

## Ticket Information

- **Ticket ID:** INC-0005
- **Category:** User Management
- **Priority:** High
- **Status:** Closed
- **Assigned To:** IT Support Technician

---

## User Issue

Human Resources requested that a former employee's Active Directory account be disabled immediatley following employment termination.

---

## Initial Assessment

The employee seperation was verified through HR documentation.
The account was still active.
No indication of susoicious activity was found.
The request was approved for immediate action.

---

## Troubleshooting Steps

1. Verified the HR request
2. Opened **Active Directory Users and Computers**.
3. Located the user's account.
4. Confirmed the correct employee.
5. Right-clicked the account.
6. Select Disable Account.
7. Confirmed the account icon displayed the disable indicator.
8. Documentation completion.
9. Informed HR the account had been disabled.

---

## Resolution

The Active Directory account was successfully disabled.
The employee can no longer authenticate to the domain.
Account information, group membership, and profile remain preserved.

---

## Root Cause

Employee seperation required immediate removal of domain access.

---

## Lessons Learned

Disbaling accounts instead of deleting them perserves audit history while preventing unauthorized access.

---

## Ticket Closed

**Resolution Time:** 10 minutes

**Final Status:** Closed

---

## Related Lab

Lab 4 – Active Directory User & Group Management

### Skills Demonstrated

- Active Directory Users and Computers
- User Account Administration
- User Offboarding
- Windows Server Administration
- Identity and Access Management