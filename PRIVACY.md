# Privacy Policy for PR Brief

PR Brief uses pull request titles, descriptions and diff excerpts to generate automated summaries through OpenAI's API.

## Data handling

- Generated summaries may include information from the pull request. They are posted to GitHub comments and checks, where repository access controls apply.
- PR Brief can retain generated summaries, repository and pull request identifiers, commit identifiers, installation/account metadata, credit records and payment event identifiers to operate the service and avoid duplicate processing.
- The service does not provide a blanket guarantee that all repository-derived information is deleted immediately after processing. A fixed application deletion schedule and the retention of all backup copies have not been verified for the deployed service.
- Limited pattern checks can identify some potential secrets before AI processing. These checks are not comprehensive; users must avoid submitting credentials, personal data or other confidential material that they are not authorized to share with the service and its providers.

## Third-party services

PR Brief sends the selected pull request content to OpenAI. Provider retention depends on the API endpoint, account settings and applicable service terms. As verified on 12 October 2026, the service's configured OpenAI project uses Standard Retention; Zero Data Retention is not enabled for that project.

The configured OpenAI organization has API input/output sharing enabled for all projects, including PR Brief's configured project, as verified on 12 October 2026. Inputs and outputs sent to OpenAI under this setting may be used for model evaluation, improvement and training. Do not submit sensitive, confidential or proprietary content to PR Brief while this setting is enabled. See [OpenAI's data-sharing guidance](https://help.openai.com/en/articles/10306912-sharing-feedback-evaluation-and-fine-tuning-data-and-api-inputs-and-outputs-with-openai) and [data controls](https://developers.openai.com/api/docs/guides/your-data) for current rules.

GitHub stores posted summaries under its own policies. Credit purchases are processed through Stripe; the app may retain payment event identifiers and credit/account records.

The deployed service is configured to use Neon for PostgreSQL storage of the retained summaries and metadata described above. Database recovery history can preserve earlier versions of records, including records deleted from the active database, within the provider's configured history window. This window does not automatically delete active records or establish when every backup copy is erased. See [Neon's history window documentation](https://neon.com/docs/introduction/history-window) for how recovery history works.

## Contact

For general questions, open an issue in this repository. Public issues are visible to others; do not include credentials, private repository content or personal information in an issue.
