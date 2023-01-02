# RenovateWorkShopGithubAppSetup

### Installing the Github App

- Navigate to the [Renovate Github App page](https://github.com/apps/renovate)
- Click Install/Configure
- Choose the account of your choosing
- Only select repositories
- Select repositories of your choosing
- Once authenticated you will be redirected to the Renovate dashboard
- In your selected repositories you will receive a Renovate pull request to add a configuration file.
- Go back to the Renovate dashboard to see your first run in action.
- You're all set to start configuring.


### Handy Links
- Renovate docs: [Docs](https://docs.renovatebot.com/configuration-options/)
### Example 1: PR limits and automerge capabilities
-- Show config example here to avoid confusion
- Find out how to implement a limit on the amount of PR's Renovate can have open at a given time. Limit this amount to 3
- Find out how to configure Renovate to create PR's that require approval for major versions while minor versions and patches can be automerged.

### Example 2: Configure a Renovate schedule to reduce PR "noise"
- Find out how to implement a schedule for Renovate to run on.
- Warning! Set the correct timezone.