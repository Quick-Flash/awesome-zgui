# Awesome zgui

A curated list of crates, applications and resources for [zgui](https://github.com/zortax/zgui),
a native Rust UI framework with fine-grained reactivity, real CSS and a retained GPU renderer.

> [!NOTE]
> zgui is experimental and changes often. Projects listed here may pin a specific zgui revision
> or a fork.

## Contents

- [Official resources](#official-resources)
- [Libraries](#libraries)
  - [Components](#components)
  - [Editors and terminals](#editors-and-terminals)
  - [Data visualization](#data-visualization)
- [Applications](#applications)
  - [Development tools](#development-tools)
  - [Media and communication](#media-and-communication)
  - [Utilities](#utilities)
  - [Mobile](#mobile)
- [Community](#community)
- [Contributing](#contributing)

## Official resources

- [zgui](https://github.com/zortax/zgui) - Source repository.
- [Documentation](https://zgui.zortax.de) - Guides, API reference and architecture notes.
- [Getting started](https://zgui.zortax.de/docs/getting-started/installation) - Installation and first app.
- [Component library](https://zgui.zortax.de/docs/component-library/components) - `zgui-ui` components, a shadcn/ui port.
- [Tokens and theming](https://zgui.zortax.de/docs/component-library/tokens-and-theming) - Design tokens and `ThemeProvider`.
- [Architecture overview](https://zgui.zortax.de/docs/architecture/overview) - Document, cascade, layout, paint and composition pipeline.
- [Cost model](https://zgui.zortax.de/docs/performance/cost-model) - What sparse and wide updates cost.
- [Examples](https://github.com/zortax/zgui/tree/main/examples) - Runnable examples (`cargo run -p zgui-examples --example counter`).

## Libraries

### Components

- [zgui-flow](https://github.com/zortax/zgui-flow) - Node graphs and diagrams, in the style of React Flow.

### Editors and terminals

- [zgui-editor](https://github.com/zortax/zgui-editor) - Embeddable code editor with incremental tree-sitter highlighting, multiple cursors and large-file support.
- [zgui-terminal](https://github.com/zortax/zgui-terminal) - Embeddable terminal emulator with scrollback, selection and modern keyboard protocols.

### Data visualization

- [zgui-plot](https://github.com/Quick-Flash/zgui-plot) - Backend-neutral 2D plotting, retained chart components, SVG/PNG export and docking workspaces.

## Applications

### Development tools

- [zdt](https://github.com/zortax/zdt) - Modal code editor with splits, file tree, LSP, Git, terminals and coding-agent workflows.

### Media and communication

- [Canora](https://github.com/zortax/canora) - Spotify client with playback, playlists, search and custom window chrome.
- [moqspeak](https://github.com/Newspicel/moqspeak) - Voice chat and screen sharing over Media over QUIC.

### Utilities

- [Enlumi](https://github.com/Quick-Flash/enlumi) - Time-series log viewer for ULog, Betaflight Blackbox and MAVLink telemetry with docked plots.

### Mobile

- [Roamlog](https://github.com/Quick-Flash/Roamlog) - Local-first Android trip recorder with road coverage history and encrypted peer-to-peer location sharing.

## Community

- [Discord](https://discord.gg/E6SDmyRRmd) - Official chat.
- [GitHub Issues](https://github.com/zortax/zgui/issues) - Bug reports and feature requests.

## Contributing

Contributions welcome. Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights
to this work.
