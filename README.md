![Banner](assets/banner.png)

# Exposed ("Client")

Exposed is a Continuous Threat Exposure alert system that makes securing your attack surface easier.

## Usage

> A valid keychain file is required to get started

Simple to install:

```go
go install github.com/privateducky/exposed-client@latest
```

Simple to use:

```zsh
exposed targets                         # list your target domains
exposed start example.com               # start monitoring a new target
exposed stop example.com                # stop monitoring a target
exposed notify https://hooks.slack.com  # get attack surface notifications 
exposed push port example.com 80        # add data to a feed
exposed pull port example.com           # pull data off a feed
```
