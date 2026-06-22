# Secret-Key Rotation Procedure

## Overview
Secret-key rotation is essential for maintaining security in applications. This document outlines the procedure for rotating secret keys.

## Steps for Rotation
1. **Identify the Key**: Determine which secret key needs to be rotated.
2. **Generate New Key**: Create a new secret key using a secure method.
3. **Update Configuration**: Replace the old key in the application configuration.
4. **Deploy Changes**: Deploy the application with the updated configuration.
5. **Test**: Ensure that the application functions correctly with the new key.
6. **Revoke Old Key**: Once confirmed, revoke the old key to prevent its use.

## Best Practices
- Regularly schedule key rotations.
- Use automated tools to manage keys where possible.
- Monitor usage of keys to detect any unauthorized access.