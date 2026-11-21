# Security Policy

## GPG Key Rotation

**Date**: 2025-08-21  
**Action**: GPG Key Update

### Previous Key (Deprecated)
- Key ID: `4AEE18F83AFDEB23`
- Status: **Revoked**
- Used for commits: 2021-04-08
- Commits affected: 1 commit (Create README.md)

### Current Key (Active)
- Key ID: `6DCE833EFCCC91A0`
- Fingerprint: `B2BEA916373FBA236DCE833EFCCC91A0`
- Status: **Active**
- Effective from: 2025-08-21

### Reason for Change
Routine security maintenance and GPG key rotation following security best practices.

### Verification
All commits from 2025-08-21 onwards will be signed with the new key. You can verify the signature using:
```bash
git verify-commit <commit-hash>
```

### Historical Note
Previous commits signed with key `4AEE18F83AFDEB23` remain valid for the time period they were created, but the key has been revoked for security purposes.

## Kubernetes Security Considerations

This repository contains Kubernetes learning materials. When using these examples:
- Always review configurations before applying to production
- Update image versions and security contexts as needed
- Follow current Kubernetes security best practices

## Reporting Security Issues

If you discover security issues in the configurations or documentation, please report them to: 13607952+jimc1682000@users.noreply.github.com

---
*This security policy was established on 2025-08-21*