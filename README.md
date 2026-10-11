# Jordan Partridge

Senior Laravel and full-stack engineer. I build systems that do the work, then I automate the systems.

Mesa, AZ. Currently at PSTrax. Open to senior and staff Laravel roles.

## What I build

- **Production integrations.** At PSTrax I built the Fleetio integration: retries, logging, and the boring parts that keep data correct.
- **API clients for Laravel.** Saloon-based clients for GitHub, Strava, and Packagist that are tested and documented.
- **Agent infrastructure.** A home "factory" where agents take work in, plan it, run it in isolated containers, and get checked by quality gates before anything merges.
- **Home automation.** Home Assistant with a locally cloned voice, and grocery ordering automation for Kroger/Fry's.

## Featured

| Project | What it is |
|---|---|
| [agentctl](https://github.com/jordanpartridge/agentctl) | Go. Spawns isolated Claude Code agents in containers that work until the task is done. |
| [github-client](https://github.com/jordanpartridge/github-client) | PHP. A GitHub API client that fits Laravel conventions. |
| [strava-client](https://github.com/jordanpartridge/strava-client) | PHP. Laravel client for the Strava API. |
| [pi-runtime-gateway](https://github.com/jordanpartridge/pi-runtime-gateway) | JS. Local HTTP runtime for coding-agent sessions: profiles, streaming, cancellation. |
| [bifrost-agent](https://github.com/synapse-sentinel/bifrost-agent) | PHP. Agent layer on a webhook event bus: Redis subscriber, Slack responder, failure analysis. |
| [gate](https://github.com/synapse-sentinel/gate) | Quality checks that agent work has to pass. |

More of the agent system lives in [synapse-sentinel](https://github.com/synapse-sentinel).

## How the house factory fits together

- **Bifrost**: webhook receiver and event bus
- **Lexi**: chief-of-staff agent that routes and tracks work
- **Asgard**: intake and knowledge
- **Prefrontal Cortex**: planning and decisions
- **agentctl**: runs the work in isolated containers
- **Quality runners**: Pint, Pest, Rector, and PHPStan on every PR, posted as GitHub Checks
- **SpecReady**: turns a loose idea into a short, buildable spec

## Stack

PHP, Laravel, Laravel Zero, Livewire, Filament, Saloon, Pest, PHPStan. Go, Rust, Python, TypeScript/Vue. Redis, Docker, GitHub Actions, Home Assistant. Linux (Omarchy/Hyprland).

## Background

Before PSTrax I managed engineers at Goodwill. I prefer building, and I can lead when it's needed.

## Contact

- Email: jordan@partridge.rocks
- LinkedIn: <!-- TODO add URL -->
