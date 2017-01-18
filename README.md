# N1-Slack

`v0.1.0` - A Slack-inspired theme for Nylas N1

![Screenshot](/screenshot.png "Check it out!")


## Installing

1. Of course you'll need to [get N1](https://nylas.com/n1) first.
2. [Download](https://github.com/jodyheavener/N1-Slack/releases) the latest release of N1-Slack; unzip it.
3. From the menu bar select `Nylas N1 > Install new theme...` from the dropdown.
4. Navigate to and select the theme directory! You're done!

## Customizing

N1-Slack supports your custom Slack sidebar colors!

1. Go to your Slack preferences (web or native app) and copy the hex values from Sidebar Theme > Custom Theme.
2. Find your theme installation location (typically `.nylas/packages/N1-Slack`) and open up [`styles/variables.less`](https://github.com/jodyheavener/N1-Slack/blob/master/styles/variables.less).
3. Replace the value for `@theme-colors` with your custom Slack hex colors.
4. Hit save and refresh N1. You're done!
