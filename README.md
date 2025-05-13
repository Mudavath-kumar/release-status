# releases.electronjs.org

This repository contains the code for [https://releases.electronjs.org](https://releases.electronjs.org), which provides release status information for the [Electron](https://github.com/electron/electron) project.

---

## Getting Started

The website is built using [Remix](https://remix.run/).

### Installation

To run the app locally:

```bash
npm install
npm run dev
```

### GitHub Authentication

The app fetches release data from GitHub. To avoid hitting rate limits for anonymous requests, you can provide a GitHub Personal Access Token (PAT):

1. Generate a PAT on [GitHub](https://github.com/settings/tokens).
2. Set the `GITHUB_TOKEN` environment variable before running the app:

```bash
export GITHUB_TOKEN=your_personal_access_token
```

3. Then start the app:

```bash
npm run dev
```

---

## License

Distributed under the MIT License. See [LICENSE](https://github.com/electron/release-status/blob/main/LICENSE) for details.
