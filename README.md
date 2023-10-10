<div align=“center”>

# Woke

Woke is product discoverability for OSS projects via CLI and Repo README.MD in a non-intrusive way. This will help OSS projects generate revenue almost instantly once their users opt-in. 

</div>

## Install

To use `woke`,


# go
go get github.com/onboardbase/woke-go
```

## Usage

### go 
`go get github.com/onboardbase/woke-go`

```go
import (woke "github.com/onboardbase/woke-go")

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

Once all things are done, run the `cli.go` file. This creates a view using tea, bubbletea, glamour, lipgloss. So, this is the dependency of the projects.


# Roadmap

### Features

- [x] Opt-in for users.
- [ ] Dashboard.
- [ ] Limiting characters.
- [ ] Analytics (Clicks, Visits, Duplication/IP recognition).
- [ ] Customization for the audience. 
- [ ] Ads via Repo Readme.MD.
