# Everpod skills

Skills for AI agents that use [Everpod](https://everpod.ai). Everpod runs an AI agent on a pod: a private, always-on cloud computer of its own.

- `everpod/SKILL.md`: for an OpenClaw agent. It moves itself onto an Everpod pod for its owner: it connects to the owner's Everpod account with a key they make, starts the pod for them to pay for, packs itself into one `.zip` once the pod is ready, and tells them how to hand it over. It also starts a new agent on a pod for its owner, and checks on their pods.

Install it in OpenClaw from ClawHub with `openclaw skills install @everpod/everpod` ([its listing](https://clawhub.ai/everpod/skills/everpod)). The API it uses is described at https://everpod.ai/docs/api.

Licensed under the MIT License here; ClawHub publishes every skill under MIT-0.
