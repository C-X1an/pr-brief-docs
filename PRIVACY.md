# Privacy Policy for PR Brief

PR Brief uses pull request titles, descriptions and diff excerpts to generate automated summaries through OpenAI's API.

## Data handling

- Generated summaries may include information from the pull request. They are posted to GitHub comments and checks, where repository access controls apply.
- PR Brief can retain generated summaries, repository and pull request identifiers, commit identifiers, installation/account metadata, credit records and payment event identifiers to operate the service and avoid duplicate processing.
- The service does not provide a blanket guarantee that all repository-derived information is deleted immediately after processing. A fixed deletion schedule and backup retention period have not been verified for the deployed service.
- Limited pattern checks can identify some potential secrets before AI processing. These checks are not comprehensive; users must avoid submitting credentials, personal data or other confidential material that they are not authorized to share with the service and its providers.

## Third-party services

PR Brief sends the selected pull request content to OpenAI. Provider retention depends on the API endpoint, account settings and applicable service terms. Do not assume that this app has Zero Data Retention enabled. See [OpenAI's data controls](https://developers.openai.com/api/docs/guides/your-data) for current provider rules.

GitHub stores posted summaries under its own policies. Credit purchases are processed through Stripe; the app may retain payment event identifiers and credit/account records.

## Contact

For general questions, open an issue in this repository. Public issues are visible to others; do not include credentials, private repository content or personal information in an issue.
