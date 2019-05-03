## Introduction

Welcome to the Stack Monitoring team! We're so happy that you're here.

This document is a subset of the more comprehensive document for the entire Ingest team
which is located in the [Ingest repo](https://github.com/elastic/ingest-dev/blob/master/onboarding.md).

There, you will find a broad overview of the development practices across the Ingest team. You can
also find links to other documents that talk about how developers work at Elastic.

This document focuses on specifics for the Stack Monitoring team.

## Weekly Meetings

The Stack Monitoring team has one team meeting that takes place weekly on Mondays at 1:30 PM UTC for
30 minutes. If a team member can't attend, recordings are available of each meeting.

If you have items that you would like to discuss with the team, please add them to the meeting agenda
which is present in the calendar invitation.

## Daily communication

As with many teams at Elastic, the majority of communication happens asynchronously. That means that
GitHub is often the preferred means of communication. It's a good idea to watch GitHub notifications
closely and to spend time crafting email filters to manage the amount of GitHub email you might
receive. (It's a lot!)

If an issue can't be resolved via GitHub, often a conversation is had in Slack. We prefer that,
whenever possible, conversations be had in public channels instead of in direct messages. This gives
everybody a chance to particpate and gives those in different timezones a record of what happened.

At the start of every day, please post what you plan to do that day in the `#stack-monitoring-news`
channel

## Slack channels

`#stack-monitoring`: This channel is for general topics related to Stack Monitoring. It is often
where questions are asked by the rest of the company about monitoring.

`#stack-monitoring-news`: This channel is used for daily updates. Please avoid cluttering it
with discussion topics.

Other important channels can be found in the [Ingest onboarding guides](https://github.com/elastic/ingest-dev/tree/master/onboarding).

## Project management

Issues are organized into releases using the [Stack Monitoring Project Board](https://github.com/orgs/elastic/projects/74).
What's there are targets and not typically hard deadlines. If an issue does have a hard deadline, it will be identified as such.

## GitHub labels specific to Stack Monitoring

In the Kibana repo, the label is `:Monitoring`. In Beat it is either `monitoring` or `Stack monitoring`.
In the Logstash repo, the label is `monitoring`.

## SDH duty

SDH stands for Support Dev Help. It's a GitHub repo that Support Engineers use to escalate issues to the Development team
by opening issues. Read more about it [here](https://wiki.elastic.co/x/DIZIAw).

It is critical that all engineers keep a close eye on support issues which may be escalated to the
Stack Monitoring team. Any comment on an issue involving the team will result in a comment in the
`#stack-monitoring` Slack channel by a bot called Dr. Strange.

Support escalations are raised by the support team in the https://github.com/elastic/support-dev-help
repo. An easy way to follow monitoring-related issues is just to filter by the the `monitoring` tag
or to [view this page](https://github.com/elastic/support-dev-help/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+label%3Amonitoring).

## Discuss forums

Discuss forums are public discussion forums for Elastic's products and solutions, hosted by us at https://discuss.elastic.co.

Forums should be monitored and questions answered promptly. The forums are:

[Kibana forum with the Monitoring tag](https://discuss.elastic.co/tags/c/kibana/monitoring)

[Beats forum with the Monitoring tag](https://discuss.elastic.co/tags/c/beats/monitoring)

[Logstash forum with the Monitoring tag](https://discuss.elastic.co/tags/c/logstash/monitoring)

[Elastic forum with the Monitoring tag](https://discuss.elastic.co/tags/c/elasticsearch/monitoring)

Sometimes, issues are not tagged correctly and have nothing to do with Stack Monitoring. There is
not a need to answer those unless you wish. Feel free to re-tag such issues so they get re-routed
to the appropriate teams.

Support escalations are raised by the support team in the https://github.com/elastic/support-dev-help
repo. An easy way to follow monitoring-related issues is just to filter by the the `monitoring` tag
or to [view this page](https://github.com/elastic/support-dev-help/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+label%3Amonitoring).

## Parity tests

Stack Monitoring has a series of parity tests and it is important that each team member pay close
attention to any test failure and quickly address them. Test results are emailed nightly and
additional information is [available here](https://github.com/elastic/elastic-stack-testing/playbooks/monitoring/README.md)
