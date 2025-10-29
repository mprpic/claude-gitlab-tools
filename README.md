# Claude GitLab Tools Marketplace

A Claude Code marketplace providing GitLab automation and debugging tools.

## Available Plugins

### GitLab CI Debugger

Debug and monitor GitLab CI/CD pipelines for merge requests. Check pipeline status, view job logs, and troubleshoot CI
failures without leaving your terminal.

## Installation

### Quick Start

1. Add this marketplace to Claude Code:
   ```bash
   /plugin marketplace add mprpic/claude-gitlab-tools
   ```

2. Browse available plugins:
   ```bash
   /plugin
   ```

3. Install a specific plugin:
   ```bash
   /plugin install gitlab-ci-debugger@claude-gitlab-tools
   ```

### Manual Installation

You can also clone this repository and use plugins locally:

```bash
git clone https://github.com/mprpic/claude-gitlab-tools.git
cd claude-gitlab-tools
/plugin marketplace add .
```
