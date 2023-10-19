<div align=“center”>

# Woke

Woke is product discoverability for OSS projects via CLI and Repo README.MD in a non-intrusive way. This will help OSS projects generate revenue almost instantly once users of their projects opt-in for ads.

</div>

## Usage in CLI Applications

### Install woke with go 
`go get github.com/onboardbase/woke-go`

After installation, import `woke` as follows:
```go
import (woke "github.com/onboardbase/woke-go")

func main(){
  woke.WokeAds()
  cmd.example()
}
```

## Development

### Install GO
You need to have Go installed on your development machine. Instructions on how to install go can be found here https://go.dev/doc/install


### Install dependencies 
After forking this repository and cloning it to your development machine, install the dependencies by running this command from the project directory:
```
go mod tidy
```

After installation, to start the application locally, run
```
go run ./go/cli.go
```



# Roadmap

### Features

- [x] Opt-in for users.
- [ ] Dashboard.
- [ ] Limiting characters.
- [ ] Analytics (Clicks, Visits, Duplication/IP recognition).
- [ ] Customization for the audience. 
- [ ] Ads via Repo Readme.MD.
