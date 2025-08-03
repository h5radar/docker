# H5Radar Docker Compose

This repository contains a Docker Compose configuration to run the full H5Radar application locally or in a test environment.

H5Radar application consists of several modules. For an overview of the entire platform and its repositories, please see the [organization-level README](https://github.com/h5radar).

## Features

- One-command startup for H5Radar demo or development instance
- Includes all major modules (UI, Radar backend, Account backend)
- Works on macOS, Linux, and Windows with Docker
- No manual configuration required

## How to run application

The easiest way to run H5Radar is via Docker Compose. This method is ideal for quick local evaluation.

```bash
docker-compose up -d
```

TYou can then open http://localhost:3000 in your browser.

## Resources

- [Website](https://www.h5radar.com)
- [Documentation](https://docs.h5radar.com)
- [Live Demo](https://app.h5radar.com)
- [Blog](https://blog.h5radar.com)

## Contributing

Contributions and issues are welcome. Please open pull requests or issues in this repository. For general discussions, roadmap input, and questions, please join our [organization Discussions](https://github.com/orgs/h5radar/discussions). We appreciate community involvement in shaping H5Radar!

## License

H5Radar Ansible Installer is licensed under the MIT License.

## Appendix 1: Useful commands

- docker compose by command: docker compose up -d
