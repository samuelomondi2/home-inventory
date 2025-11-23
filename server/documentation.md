# Home Inventory — Step-by-Step Study Guide (Node.js backend)
Below is a practical, hands-by-step study guide that turns everything we built into a learnable project. Follow each step in order. Each step includes the goal, commands/code pointers, quick explanations, checkpoints, and suggested exercises so you actually learn why things work (not just copy/paste).

## Overview / Learning goals

By the end you will be able to:
- Create and run a MySQL schema for a multi-tenant household inventory app.
- Build a Node.js (CommonJS) backend with routes, controllers, repositories and DB pooling.
- Implement authentication with JWT access tokens + refresh tokens stored in a sessions table.
- Use role- and household-based authorization (1 = super admin, 2 = admin/head, 3 = normal user).
- Upload files via multer and store them in S3 using AWS SDK v3.
- Use transactions for critical multi-step DB operations.
- Add tests and secure tokens (next steps).