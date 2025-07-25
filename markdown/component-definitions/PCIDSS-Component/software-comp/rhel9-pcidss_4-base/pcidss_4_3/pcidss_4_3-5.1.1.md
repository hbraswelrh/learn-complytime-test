---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_3-5.1.1
      description: Rule for pcidss_4_3-5.1.1
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_3-05.01.01
---

# pcidss_4_3-5.1.1 - \[REPLACE_ME\] Hashes Used To Render Pan Unreadable (Per The First Bullet Of Requirement 3.5.1) Are Keyed Cryptographic Hashes Of The Entire Pan, With Associated Key-Management Processes And Procedures In Accordance With Requirements 3.6 And 3.7.

## Control Statement

All Applicability Notes for Requirement 3.5.1 also apply to this requirement.
Key-management processes and procedures (Requirements 3.6 and 3.7) do not apply to
system components used to generate individual keyed hashes of a PAN for comparison to
another system if:
- The system components only have access to one hash value at a time (hash values are
not stored on the system)
AND
- There is no other account data stored on the same system as the hashes.
This requirement is considered a best practice until 31 March 2025, after which it will
be required and must be fully considered during a PCI DSS assessment. This requirement
will replace the bullet in Requirement 3.5.1 for one-way hashes once its effective date
is reached.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_3-5.1.1 -->

### Rules:

  - rule-pcidss_4_3-5.1.1

### Implementation Status: planned

______________________________________________________________________
