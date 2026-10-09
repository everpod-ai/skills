# Everpod skills

Skills for AI agents that use [Everpod](https://everpod.ai). Everpod is an easy way to get your own always-on, persistent cloud computer for AI agents, working in minutes: as a developer pod with your pick of Claude Code, Codex, OpenCode, Pi, Hermes and OpenClaw installed, or with OpenClaw set up and run for you.

- `everpod-developer-pod/SKILL.md`: for a coding agent on your own computer, such as Claude Code or Codex. It gets you a developer pod: it starts the machine for you to pay for, tells you the steps that are yours (joining it to your Tailscale network and switching off its key expiry), and can log in for you once it has joined. This repository is a plugin marketplace that holds it. In Claude Code, install it with `claude plugin marketplace add everpod-ai/skills` and then `claude plugin install everpod-developer-pod@everpod`; in Codex, with `codex plugin marketplace add everpod-ai/skills` and then `codex plugin add everpod-developer-pod@everpod`. For another agent, copy the `everpod-developer-pod` folder into its skills folder.
- `everpod/SKILL.md`: for an OpenClaw agent. It starts a new agent on an Everpod pod for its owner, or a developer pod, and it prepares its own move onto a pod: it connects to the owner's Everpod account with a key they make, starts the pod for them to pay for, packs itself into one `.zip` once the pod is ready, and tells them how to hand it over. It also checks on their pods. Install it in OpenClaw from ClawHub with `openclaw skills install @everpod/everpod` ([its listing](https://clawhub.ai/everpod/skills/everpod)).

The API both use is described at https://everpod.ai/docs/api.

Licensed under the MIT License here; ClawHub publishes every skill under MIT-0.
