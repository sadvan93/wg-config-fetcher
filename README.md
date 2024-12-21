# WireGuard Config Fetcher

Automatically fetches and updates WireGuard configurations from a public Telegram channel every hour. This tool regularly checks the channel and saves the three most recent WireGuard configurations with anonymized identifiers.

## Features

- Fetches the latest WireGuard configurations every hour
- Removes identifying information from configs
- Maintains exactly three most recent configs
- Automatically updates via GitHub Actions
- No Telegram API required

## Setup

1. Fork this repository
2. Enable GitHub Actions in your fork:
   - Go to the "Actions" tab
   - Click "I understand my workflows, go ahead and enable them"

That's it! The GitHub Action will automatically run every hour to fetch new configs and update the repository.

## Configuration File

The WireGuard configurations are stored in `configs/wireguard_configs.txt`. Each config is tagged with an anonymous identifier (Anon1, Anon2, Anon3).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.