## Security

- Validate input sanitization practices.
- Search for risks that might expose user data.
- Prefer loading user-facing content or application data from the database instead of hard-coded content. Load configuration, especially secrets such as database URIs, credentials, and API keys, from environment variables, a secret store, or a non-committed config file.

## Code Quality

- Use consistent naming conventions.
- Try to reduce code duplication.
- Prefer maintainability and readability over optimization.
- If a method is used a lot, try to optimize it for performance.
- Prefer explicit error handling over silent failures.