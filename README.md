# Public API

A simple public API that returns my registered email, current datetime (ISO 8601), and the GitHub repository URL.

## API Endpoint
**Base URL**: [https://profile-api-cfn3.onrender.com/](https://profile-api-cfn3.onrender.com/)

### GET /
Returns a JSON object containing:
- `email`: My registered email address.
- `current_datetime`: The current datetime in ISO 8601 format.
- `github_url`: The GitHub URL of the project's codebase.

### Example Response
```json
{
  "email": "oluwa14tobi@gmail.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/yourusername/your-repo"
}
