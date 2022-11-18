# publish-release-test

Repository to test a custom github action with.

Have a look at `./github/workflows/main.yml` to see how to call this action.

## Secrets

In order to make it work, the following secret needs to be configured:

- `SLACK_WEBHOOK_URL`: The webhook url that is used to post to Slack.
