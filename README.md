# Apollo Automation

Your Trusted Partner in Smart Home Automation

![Apollo_Square](https://github.com/user-attachments/assets/532bb579-2346-4b1e-a612-ef8372781a4a)


Links: \
Discord (Support/feedback/discussion/future products): https://dsc.gg/ApolloAutomation \
Shop: https://shop.apolloautomation.com \
Wiki: https://wiki.apolloautomation.com 

## Shared repository config

This repo holds org-wide defaults for ApolloAutomation repositories:

- `profile/README.md`: the org profile page.
- `.github/release-drafter.yml`: release notes config. Product repos without
  their own `.github/release-drafter.yml` use this one (release-drafter v7
  reads it from this repo's default branch).

A per-repo copy of any of these files overrides the shared one entirely, so
delete the local copy to inherit changes made here. This repo must stay
public, because other repos read it with their own `GITHUB_TOKEN`.
