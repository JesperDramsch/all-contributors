---
id: usage
title: Bot Usage
sidebar_label: Usage
---

> This usage documentation assumes you have already followed the [bot installation steps](installation).

## Commands
<AUTOGENERATED_TABLE_OF_CONTENTS>

### `@all-contributors add`
 Comment on Issue or Pull Request, asking @all-contributors to add a contributor:

```
@all-contributors please add <username> for <contributions>
```
**\<contribution>**: See the [Emoji Key (Contribution Types Reference)](../emoji-key) for a list of valid `contribution` types.

The bot will then create a Pull Request to add the contributor, then reply with the pull request details.

<img alt="Example usage screenshot" src="../../assets/bot-usage.png" width="500px">

> Your request to the bot doesn't need to be perfect. The bot will use [basic Natural Language Parsing](https://github.com/all-contributors/all-contributors-bot/blob/master/src/tasks/processIssueComment/utils/parse-comment/index.js) to determine your intent.
> For example, this will work too:
>
> `Jane you are crushing it in documentation and your infrastructure work has been great too. Let's add jane.doe23 for her contributions. cc @all-contributors`

## What's next
- [Configuring the Bot](configuration)