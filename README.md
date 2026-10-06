# Unreal Labs Homebrew Tap

Install Unreal Agent on macOS or Linux (ARM64 or AMD64):

```sh
brew tap unreallabsai/tap
brew install unreallabsai/tap/unreal-agent
unreal-agent
```

This installs `unreal-agent-tui` and `unreal-agent-runner`. `unreal-agent` and
`uat` both launch the TUI. `unreal-agent-tui` and `uat` are also formula aliases.

To install only the non-interactive runner:

```sh
brew install unreallabsai/tap/unreal-agent-runner
```

Upgrade with `brew update && brew upgrade unreal-agent`.

See the [TUI guide](https://github.com/unreallabsai/unreal-agent/tree/main/cmd/unreal-agent-tui)
for provider setup, and the [runner guide](https://github.com/unreallabsai/unreal-agent/tree/main/cmd/unreal-agent-runner)
for prompts and JSON requests.

Formulae install prebuilt binaries from public
[Unreal Agent releases](https://github.com/unreallabsai/unreal-agent/releases).
The source repository's release workflow verifies all archive checksums and
updates this tap with a dedicated deploy key. CI installs and tests the packages
on Linux AMD64 and macOS ARM64 and AMD64.
