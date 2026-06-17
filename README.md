# Claude Code Plugins

I created this repo to make it easier to install my skills into Claude Code.

```
/plugin marketplace add timgavin/claude-plugins
/plugin install livewire-audit@timgavin
```

After installing, run `/reload-plugins`. To get new releases automatically, open `/plugin`,
select the `timgavin` marketplace, and turn on auto-update (off by default for third-party
marketplaces).

## Available plugins

- **livewire-audit** — security audit for Laravel Livewire (v3/v4) apps; snapshot data
  exposure, client-tamperable properties, missing `#[Locked]`, unauthorized public actions.
  Source: [timgavin/livewire-audit](https://github.com/timgavin/livewire-audit)
