# Authentication vs Authorization

## What I Learned

Authentication and authorization are closely related security concepts, but they serve different purposes.

- Authentication answers:

  > "Who are you?"

- Authorization answers:
  > "What are you allowed to access or do?"

## Authentication

Authentication is the process of verifying a user's identity.

Common examples include:

- passwords
- multi-factor authentication (MFA)
- fingerprint or facial recognition
- single sign-on systems

The goal is to confirm that the user is genuinely who they claim to be.

## Authorization

Authorization happens after authentication.

Once a user is verified, the system determines:

- which resources they can access,
- what actions they can perform,
- and what permissions they have.

For example:

- an employee may be allowed to view reports,
- while only managers can approve changes.

## Why It Matters

I found it interesting that strong authentication alone is not enough if access permissions are not properly managed.

Organizations also need clear authorization rules to reduce unnecessary access and protect sensitive information.

This connects cybersecurity not only to technical systems, but also to organizational structure and workflow design.

## Example

When logging into an online banking platform:

- authentication verifies the user's identity,
- while authorization determines which accounts, transactions, or settings the user is allowed to access.

## Reflection

Learning the difference between authentication and authorization helped me better understand how digital systems balance security, usability, and access control in everyday workflows.
