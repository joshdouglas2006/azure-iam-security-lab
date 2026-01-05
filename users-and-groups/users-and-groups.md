## Users

The following users were created to represent different identity risk levels
(admin, standard user, contractor, and service account).

!<img width="289" height="323" alt="image" src="https://github.com/user-attachments/assets/b0a04d83-0e46-49f6-9193-22e100dce4e2" />


---

## Groups

Groups are used to assign access and roles instead of individual users,
enabling scalable access control and least-privilege enforcement.

!<img width="396" height="373" alt="image" src="https://github.com/user-attachments/assets/4487ce3b-cded-45f5-9447-9110d05a2864" />


## Users and Groups

This section documents the identity structure created in Microsoft Entra ID
to simulate a small enterprise environment.

### User Types Created
- **Admin User** – Privileged administrative identity
- **Standard User** – Typical employee access
- **Contractor User** – Limited, time-bound access
- **Service Account** – Non-interactive account for services

### Group-Based Access Strategy
Access is assigned to groups rather than individual users to enforce
least privilege and simplify access management.

### Groups Created
- GRP-Global-Admins
- GRP-App-Admins
- GRP-User-Admins
- GRP-Standard-Users
- GRP-Contractors
- Readers

### Why This Matters
- Reduces privilege sprawl
- Simplifies auditing and access reviews
- Aligns with enterprise IAM best practices
