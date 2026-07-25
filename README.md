# ElBase

**ElBase** is a local-first database/server for storing important information like usernames, passwords, notes, and other sensitive data — without requiring a sign-in.

It is designed to keep your data on your own machine, giving you direct control over where information is stored and how it is accessed.

## Features

- Local-only storage.
- No account required.
- Stores sensitive data such as usernames and passwords.
- Simple server/database architecture.
- Designed for private, offline-first use.

## Why ElBase?

Many tools for storing sensitive information depend on cloud accounts or remote syncing. ElBase is built for users who want a private alternative that stays on their device and does not require creating an account.

## Security Note

ElBase is intended for local storage of sensitive information, but that does not automatically make it secure.

- Do not commit real passwords or private data to your GitHub repository.
- Protect the local machine where ElBase runs.
- Use encryption and strong access controls if you add them to the project.
- Store secrets in environment variables or a separate secure configuration file when possible.

## Project Site

[https://elbase.tiiny.site/](https://elbase.tiiny.site/)

## Project Structure

```text
ElBase/
├── src/
├── config/
├── data/
├── README.md
└── package.json
```

## Data Model

ElBase is intended to store records such as:

- Username
- Password
- Service name
- Notes
- Tags
- Custom fields

## Roadmap

- Encryption at rest
- Search and filtering
- Import/export support
- Multi-user local access
- Backup and restore tools

## Contributing

Contributions are welcome. If you add new features, please keep the local-first design and avoid introducing unnecessary external dependencies.

## License

Apache 2.0 
