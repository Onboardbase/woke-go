<div align=“center”>

# Woke

Woke is product discoverability for OSS projects via CLI and Repo README.MD in a non-intrusive way. This will help OSS projects generate revenue almost instantly once their users opt-in. 

</div>

## Install

To use `woke`,

```bash
# npm
yarn add woke-ads # npm i woke-ads

# go
go get github.com/onboardbase/woke-cli
```

## Usage

### js

Just before the entry point of your CLI, put the function.

```js
import WokeAd from 'woke-ads'

function cliEntry(){
  wokeAd()
  // rest of your logic
}
cliEntry()
```

To make the opt-out option as a prompt

```js
import WokeAd from 'woke-ads'

function cliEntry(){
  wokeAd({prompt:true})
  // rest of your logic
}
cliEntry()
```

## End users

to opt-out woke-ads

`npx woke-ads --opt-out true/false`

### go 
`go get github.com/onboardbase/woke`

```go
import (woke "github.com/onboardbase/woke-cli")

func main(){
  woke.WokeAds()
  cmd.example()
}
```
Or you can append this function inside your CLI

## Development

### Install GO

```
Go to GO website, https://go.dev/doc/install. Download and install GO.
```

### Install dependencies 

```
go mod tidy
```

Once all things are done, run the `dummy.go` file. This creates a view using tea, bubbletea, glamour, lipgloss. So, this is the dependency of the projects.


# Roadmap

### Features

- [x] Opt-in for users.
- [ ] Dashboard.
- [ ] Limiting characters.
- [ ] Analytics (Clicks, Visits, Duplication/IP recognition).
- [ ] Customization for the audience. 
- [ ] Ads via Repo Readme.MD.
