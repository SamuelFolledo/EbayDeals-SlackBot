<p align="center">
  <img src="gopher-typing.gif" height="250">
</p>

# goslackit

[![Go Report Card](https://goreportcard.com/badge/github.com/droxey/goslackit)](https://goreportcard.com/report/github.com/droxey/goslackit) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/7ed40f9f3ecf46709879d5fbac28fd9b)](https://www.codacy.com/app/droxey/goslackit?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=droxey/goslackit&amp;utm_campaign=Badge_Grade)

[BEW2.5] Fork this repo to begin the Slackbot goroutines challenge presented in class on [Day 7](https://github.com/Make-School-Courses/BEW-2.5-Strongly-Typed-Ecosystems/blob/master/Lessons/Lesson07.md).

## Instructions

Follow [this link](https://github.com/Make-School-Courses/BEW-2.5-Strongly-Typed-Ecosystems/blob/master/Lessons/Lesson07.md#setup-project) in order to get the project set up.

## My Notes - To Setup a Go Slack Bot

1. Create a Slack App at https://api.slack.com/apps?new_classic_app=1
2. Clone [Dani's project](https://make-school-courses.github.io/BEW-2.5-Strongly-Typed-Languages/#/Lessons/Lesson09) or [my project](https://github.com/SamuelFolledo/EbayDeals-SlackBot/commit/590d63aea54dc9d65d33a799ff3c62695d54974e) which does not have a go.mod and go.sum
3. Set up Slack project
  - Add name, color, details
  - Give permissions the slack bot need in OAuth & Permissions
    - __Important__ to click ```Add an OAuth Scope``` and 
  - Install the app
4. Install app to the workspace
5. Get the bot token and put token in .env.sample like so
  ```
  BOT_OAUTH_ACCESS_TOKEN="xoxb-471558618------"
  ```
6. Create a .env file by running ```cp .env.sample .env``` which copies code in .env.sample to .env
7. Run app with ```go build && go run main.go```
7. Add bot to a channel and try __Reinstall App__ if it doesn't work

