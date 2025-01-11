# b40d520f57f086f2e58d1f21d093935d

The test repository.

## > Testing [mergeable bot](https://github.com/mergeability/mergeable) locally

* Ensure `smee` is installed globally: `npm install -g smee-client`
* Check the webhook proxy URL of the GitHub app, either in the `.env` or in the GitHub app's settings.
* Copy the URL and paste to the command: `smee -u <WEBHOOK_PROXY_URL>`.
* Open another tab in the terminal in the workspace of the clone of the mergeable app, then run `npm run dev`.
* Make sure `smee` and `npm run dev` runs in a terminal separate from the IDE so that we can monitor all changes.
* Do the changes in `.github/mergeable.yml` then test the results in GitHub.
