### s(t)ackwarrior

[viha.sh](https://viha.sh) · [llm-id.sh](https://llm-id.sh) · [Discord](https://discord.gg/viha)

#### OpenCode plugins

| Plugin | What it does |
|---|---|
| [**oc&#8209;goal**](https://github.com/xenial/oc-goal) | Codex-style `/goal` for OpenCode. Gives each session a durable objective with an optional token budget, and the agent keeps going until the goal is complete, blocked or over budget. |
| [**oc&#8209;backoff**](https://github.com/xenial/oc-backoff) | Lets agents survive a provider outage overnight. Adds full-jitter exponential backoff, a per-provider circuit breaker, and a watchdog that re-dispatches failed sessions for up to 12 h. |
| [**oc&#8209;256k**](https://github.com/xenial/oc-256k) | Compacts the session at 256k active context tokens instead of waiting for the window to fill. |
| [**oc&#8209;crowbot**](https://github.com/xenial/oc-crowbot) | Unofficial [Crowbot](https://crowbot.sh/) plugin. Keeps the `crowbot` provider's model catalog up to date in OpenCode V2. |

```sh
opencode plugin add github:xenial/<name>
```

#### Older

- [**algorithms**](https://github.com/xenial/algorithms): competitive programming solutions in C++
- [**motion**](https://github.com/xenial/motion): internal CS:GO base with a CreateMove hook and an ImGui menu
