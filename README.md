# Line Orb

Easily integrate custom Line notifications into your CircleCI projects. Create custom alert messages for any job or receive status updates.

## Usage

Example config:

```yml
version: 2.1

orbs:
  line: decoch/line

jobs:
  build:
    docker:
      - image: <docker image>
    steps:
      - line/notify
```

## Generate line access token

see: https://notify-bot.line.me/my/
