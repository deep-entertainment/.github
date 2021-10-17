# Contributing to projects of deep Entertainment

Thanks a lot for thinking about contributing to on of our projects! Please read the guidelines outlined in this document on how to most efficiently add your contribution to the project to make it better.

How do you want to contribute?

- [I have a question about how to use one of the Godot addons](#questions)
- [Something doesn't work as documented or intended](#bugs)
- [I want to do something with Escoria, that isn't possible right now](#feature-requests)

# Questions

Of course! We'll help you to answer your question as best as possible. Our community uses [Discord](https://discordapp.com) to communicate and collaborate.

Please simply join our server and state your question in our support channel:

[![Support Server](https://img.shields.io/discord/777604957737451530.svg?label=Discord&logo=Discord&colorB=7289da&style=for-the-badge)](https://discord.gg/T6y6KG4V5K)

# Bugs

Oh no! Sorry about that. We guess you encountered a bug. Please file an issue in our [main issue tracker](https://github.com/deep-entertainment/issues).

[I can also send code changes that will fix the bug](contributions)

# Feature Requests

Sure. We're always open to new ideas. Please make sure you talked to our community in the Discord support channel first. Maybe somebody else already thought about the same thing and found a solution!

[![Support Server](https://img.shields.io/discord/777604957737451530.svg?label=Discord&logo=Discord&colorB=7289da&style=for-the-badge)](https://discord.gg/T6y6KG4V5K)

If not, please add a new feature request in our [main issue tracker](https://github.com/deep-entertainment/issues).

Please note, that we're developing the projects in our free time and can't always implement new features as fast as we would like to. We will usually add a version to your feature request stating when the feature possibly will be added to Escoria. This, however, *might change*, so don't bet on it.

[I can also send code changes that will implement the new feature](contributions)

# Contributions

That's *awesome*. Thanks a lot. Let's talk about how we implement code in our projectts.

For Egoventure, we implement all new code in our example game. That's our testing ground, if you will. Clone the [example game's git repository](https://github.com/deep-entertainment/egoventure-example-game). Checkout the `develop` branch and then create a new branch named "issue-your issue number". (e.g. issue-42)

If you like to submit code for fixing a bug, please recreate the bug in the example game. If you want to implement a new feature, create a demo for the new feature in the game.

Afterwards, add the required code to fix the bug or implement the feature.

When committing in git, please make sure to format your commit message according to the [semantic-release](https://github.com/semantic-release/semantic-release) standard.

When you're ready, please interactively rebase your branch and remove all non-essential commits from your changes. See [this article](https://dev.to/blakedeboer/beginners-guide-to-interactive-rebasing-1ob) for informations about interactively rebasing.

Afterwards open a pull request on the example game repository against the `develop` branch. Maybe we will kindly ask you to add more changes or otherwise communicate about your changes. Please use the PR ui to answer those questions and resolve the conversations once you have implemented the requested change.

Again, thanks a lot for your contributions. ❤️ 🎁