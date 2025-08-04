# Contributing

## Commit messages

Please follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification to keep commit history clean and consistent.

Examples:
- `feat: add support for dark mode`
- `fix: resolve crash when loading config`
- `docs: update README with installation instructions`

You can include scope in parentheses:  
`feat(auth): implement JWT-based login`

Breaking changes should be marked with `!`:  
`feat(api)!: remove deprecated endpoints`

You can include a longer description if necessary:
```
feat(api): add rate limiting to public endpoints

Introduces a simple in-memory rate limiter to prevent abuse of unauthenticated APIs.
Limits requests to 100 per minute per IP address.
```
