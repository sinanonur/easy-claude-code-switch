# easy-claude-code-switch
Very simple to use claude code runnders that can use various providers. It does not effect your claude code config or setup. It only changes the accessed models.

This is very preleneminary and will be made more easy to configure and use. If you configure they can support both regular API and coding plans.
This only

## How to use
After setting up just use one of the following istead of `claude` :
- `claude-deepseek`
- `claude-glm`
- `claude-kimi`
- `claude-minimax`

All the parameters are passed through claude code as is so so you can use them like:

`claude-glm --dangerously-skip-permissions --continue`

You can continue previous sessions with new models using `--continue`

## Requirements

Supports Linux and MacOS

## Setup

- Add API keys in `~/.aliases` file or set each API key ın the scrıpts
- add the bın dırectory to your PATH variable so you can use it with a command
