# Unreal Labs Homebrew Tap

Install Unreal Agent on macOS or Linux (ARM64 or AMD64):

```sh
brew tap unreallabsai/tap
brew install unreallabsai/tap/unreal-agent
unreal-agent
```

One cask installs `unreal-agent-tui` and `unreal-agent-runner`.
`unreal-agent` and `uat` both launch the TUI.

Upgrade with `brew update && brew upgrade unreal-agent`.

See the [TUI guide](https://github.com/unreallabsai/unreal-agent/tree/main/cmd/unreal-agent-tui)
for provider setup, and the [runner guide](https://github.com/unreallabsai/unreal-agent/tree/main/cmd/unreal-agent-runner)
for prompts and JSON requests.

GoReleaser publishes prebuilt binaries from public
[Unreal Agent releases](https://github.com/unreallabsai/unreal-agent/releases)
and updates this tap with a dedicated deploy key. CI installs the cask and
checks every command on Linux AMD64 and macOS ARM64/AMD64.
