# Ticket 004 - Unlock Locked Active Directory Account

## Ticket Information

- **Ticket ID:** INC-0004
- **Category:** Active Directory
- **Priority:** High
- **Status:** Closed
- **Assigned To:** IT Support Technician

---

## User Issue

The user reported being unable to sign into Windows after multiple unsuccessful login attempts. The account appeared to be locked.

---

## Initial Assessment

Verified the user's identity and confirmed the Active Directory account was locked because of the domain account lockout policy.

---

## Troubleshooting Steps

1. Verified the user's identity.
2. Opened **Active Directory Users and Computers**.
3. Located the user's account.
4. Opened **Properties**.
5. Selected the **Account** tab.
6. Confirmed the account was locked.
7. Selected **Unlock Account**.
8. Applied the changes.
9. Asked the user to sign in again.
10. Confirmed successful login.

---

## Resolution

The Active Directory account was successfully unlocked and the user regained access to the domain.

---

## Root Cause

Repeated incorrect password attempts triggered the organization's account lockout policy.

---

## Lessons Learned

Users should contact the IT Help Desk before repeated failed password attempts trigger an account lockout.

---

## Ticket Closed

**Resolution Time:** 10 minutes

**Final Status:** Closed

---

## Related Lab

Lab 4 – Active Directory User & Group Management

### Skills Demonstrated

- Active Directory Users and Computers
- Account Unlock
- Account Lockout Policy
- User Support
- Windows Server Administration
- Identity Verification