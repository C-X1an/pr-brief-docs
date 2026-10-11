# PR Brief

PR Brief is a GitHub App that automatically generates structured summaries for pull requests.

It helps developers and teams review changes faster by providing:

- Clear high-level summaries
- Risk indicators
- Developer-focused notes
- GitHub Check integration

PR Brief operates entirely as a GitHub App and does not require OAuth authorization.

---

## How It Works

1. Install PR Brief on your repository
2. Open or update a pull request
3. PR Brief posts an automated summary

No configuration required.

---

## Security & Privacy

- Pull request titles, descriptions and diff excerpts are sent to OpenAI to generate summaries.
- Generated summaries and operational metadata can be retained and summaries are posted to GitHub. This is not a zero-retention service.
- Limited pattern checks run before AI processing. They do not guarantee that all secrets or personal data will be detected; do not submit sensitive content.
- Review the [Privacy Policy](./PRIVACY.md) and the provider's [data controls](https://developers.openai.com/api/docs/guides/your-data) before installing the app.
- PR Brief uses GitHub App installation permissions only

---

## Legal

- [Privacy Policy](./PRIVACY.md)
- [Terms of Service](./TERMS.md)

---

For support, please open an issue in this repository.
