# Slack PFP Rotator
#### Rotates my PFP by 90 degrees every 5 mins in the [Hack Club Slack](https://hackclub.com/slack)

## How to use it
1. Create Slack app in dashboard and make tokens (`users.profile:read` and `users.profile:write`)
2. Make .env file (follow .env.example)
3. `go build . && ./slack-pfp-rotator`
4. profit

## Credits
[Sam Poder's pfp changer](https://github.com/sampoder/pfp) for original inspiration

[Slack API Docs](https://api.slack.com/) - they weren't too useful but eventually helped get the job done

## License
Licensed under unlicense