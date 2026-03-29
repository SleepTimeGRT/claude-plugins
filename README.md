# SleepTimeGRT Claude Plugins

Custom Claude Code plugins for agent orchestration, developer tooling, and platform-specific skills.

## Plugins

| Plugin | Description | Category |
|--------|-------------|----------|
| [process-todos](https://github.com/SleepTimeGRT/process-todos-plugin) | 3-tier agent orchestration for sequential todo processing with git worktree isolation | Productivity |
| [toss-miniapp](https://github.com/SleepTimeGRT/toss-miniapp-skills) | 토스 미니앱 개발 가이드 — 온보딩부터 배포까지 전체 라이프사이클 지원 | Development |
| [work](https://github.com/SleepTimeGRT/work-plugin) | WORK.md — weekly markdown task management that replaces JIRA. Track shipping, blockers, and weekly rotation in a single file. | Productivity |
| [closed-loop](https://github.com/SleepTimeGRT/closed-loop) | Self-correcting feedback loop — separates generation from evaluation with sprint contracts and browser-based QA | Quality |

## Installation

### Add the marketplace

```bash
claude plugin:add-marketplace https://github.com/SleepTimeGRT/claude-plugins
```

### Install individual plugins

```bash
# Install a specific plugin
claude plugin:add process-todos@sleeptimegrt-plugins
claude plugin:add toss-miniapp@sleeptimegrt-plugins
claude plugin:add work@sleeptimegrt-plugins
claude plugin:add closed-loop@sleeptimegrt-plugins

# Or install directly from the plugin repo
claude plugin:add --url https://github.com/SleepTimeGRT/process-todos-plugin
claude plugin:add --url https://github.com/SleepTimeGRT/toss-miniapp-skills
claude plugin:add --url https://github.com/SleepTimeGRT/work-plugin
claude plugin:add --url https://github.com/SleepTimeGRT/closed-loop
```

## Contributing

To suggest a new plugin or report issues, open an issue on this repository.
