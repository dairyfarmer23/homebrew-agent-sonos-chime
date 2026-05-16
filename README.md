# Homebrew Agent Sonos Chime

Homebrew tap for [agent-sonos-chime](https://github.com/dairyfarmer23/agent-sonos-chime).

```bash
brew tap dairyfarmer23/agent-sonos-chime
brew install agent-sonos-chime
```

After install:

```bash
AGENT_CHIME_AUDIO_DIR="$HOME/.local/share/agent-sonos-chime" \
  /opt/homebrew/opt/agent-sonos-chime/share/agent-sonos-chime/generate-alert-audio.sh
agent-sonos-configure-hooks --bin-dir /opt/homebrew/bin
agent-sonos-diagnose
```
