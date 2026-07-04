# Ticket 003 - Add User to Security Groups

## Ticket Information

- **Ticket ID:** INC-0003
- **Category:** Active Directory
- **Priority:** Medium
- **Status:** Closed
- **Assigned To:** IT Support Technician

---

## User Issue

Human Resources requested that a newly created employee account be added to the appropriate Active Directory security groups for department access.

---

## Initial Assessment

The user account already existed in Active Directory but did not yet have the required group memberships for network resources and shared folders.

---

## Troubleshooting Steps

1. Verified the user's identity.
2. Opened Active Directory Users and Computers.
3. Located the user account.
4. Opened the user's Properties.
5. Selected the **Member Of** tab.
6. Added the user to the required security groups.
7. Applied the changes.
8. Verified successful group membership.

---

## Resolution

The user was successfully added to all required Active Directory security groups and now has access to authorized resources.

---

## Root Cause

New employee onboarding required department-based security group assignments.

---

## Lessons Learned

Proper security group assignments reduce manual permission management and ensure users receive the correct access immediately.

---

## Ticket Closed

**Resolution Time:** 15 minutes

**Final Status:** Closed

---

## Related Lab

Lab 4 – Active Directory User & Group Management

### Skills Demonstrated

- Active Directory
- Security Groups
- Group Membership
- Access Control
- User Administration
- Windows Server Administration