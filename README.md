# GitHub Actions Workflow Secrets

This example demonstrates how to securely use secrets within a GitHub Actions workflow. It shows how to define and access sensitive information like API keys and passwords, which are automatically masked in logs for enhanced security.

## Language

`yaml`

## How to Run

1. Create a GitHub repository.
2. In repository settings, go to 'Secrets and variables' -> 'Actions' and add secrets named 'MY_API_KEY' and 'DATABASE_PASSWORD' with any values.
3. Commit this `main.yml` file to the `.github/workflows/` directory in your repository.

## Original Article

This example accompanies the Turkish article: [GitHub Enterprise Server 3.23 RC: İlk Test Edilmesi Gereken 6 Yenilik](https://fatihsoysal.com/blog/github-enterprise-server-3-23-rc-ilk-test-edilmesi-gereken-6-yenilik/).

## License

MIT — see [LICENSE](LICENSE).
