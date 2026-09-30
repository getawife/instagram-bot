# Instagram-bot

A small Puppeteer project for keeping track of your Instagram followers and following list.

It checks your account periodically, saves what it finds, and compares it with the previous check so you can see what's changed.

## Setup

Please follow the instructions given below.

### Download

If you don't want to build the project yourself, download the latest release from the [Releases page](https://github.com/getawife/instagram-bot/releases)

### From source

```bash
git clone https://github.com/getawife/instagram-bot
cd instagram-bot
pnpm install
pnpm start
```

On the first run, the browser may require you to login to Instagram.

We do **not** recieve your login details.

## Contributing & Issues

Bug fixes, performance improvements, documentation updates, and feature suggestions are all welcome.

### Issues

Found a bug or something behaving unexpectedly? Open an issue on the [Issue tracker](https://github.com/getawife/instagram-bot/issues).

Before opening a new issue, please:

- Search existing issues to avoid duplicates.
- Check that you are running the latest release.

Include the following in your report:

- Your operating system and version.
- A clear description of what you expected and what actually happened.
- Reproduction steps if you can determine them.
- Any error message shown.

### Pull Requests

- Fork the repository and create a branch from main.

- Keep commits focused.

- Open a pull request against main. Include a short description of the change, why it is needed, and how you tested it.

- It will be reviewed and may require additional changes. Push additional commits to the same branch in response.

- Do not force-push over review comments.

## License

Please click [here](./LICENSE) for more information.

## Notes

Instagram's website is dynamic and may change its DOM, navigation, or loading behavior. The automation therefore depends on the current Instagram web interface and may break.

Use the tool only with accounts and data you are authorized to access, and comply with Instagram's applicable terms and policies.

Not affiliated with Instagram.

```
▐▒▒▒▒▒  ▐▒▒ ▐▒▒      ▐▒▒▒▒▒▒ ▐▒▒▒▒▒▒ ▐▒▒▒▒▒ ▐▒▒▒▒▒  ▐▒      ▐▒▒ ▐▒▒▒▒▒▒ ▐▒▒▒▒▒▒ ▐▒▒▒▒▒▒
▐▒  ▐▒▒ ▐▒▒ ▐▒▒      ▐▒      ▐▒        ▐▒   ▐▒  ▐▒▒ ▐▒      ▐▒▒   ▐▒    ▐▒      ▐▒
▐▒▐▒▒▒    ▐▒▒▒▒      ▐▒▒▐▒▒▒ ▐▒▒▒      ▐▒▒  ▐▒▒▒▒▒▒ ▐▒▒ ▐▒  ▐▒▒   ▐▒▒   ▐▒▒▒    ▐▒▒▒
▐▒  ▐▒▒     ▐▒▒      ▐▒▒ ▐▒▒ ▐▒▒       ▐▒▒  ▐▒▒ ▐▒▒ ▐▒▒ ▐▒  ▐▒▒   ▐▒▒   ▐▒▒     ▐▒▒
▐▒▒▒▒▒  ▐▒▒▒▒▒       ▐▒▒▒▒▒▒ ▐▒▒▒▒▒▒   ▐▒▒  ▐▒▒ ▐▒▒ ▐▒▒▒▒▒▒▒▒▒▒ ▐▒▒▒▒▒▒ ▐▒▒     ▐▒▒▒▒▒▒
```
