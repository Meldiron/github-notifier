# GitHub Notifier

Simple CI/CD based script to check your GitHub notification, and post a Discord message if you have been requested for a review.

The script is using [Open Runtimes](https://github.com/open-runtimes/open-runtimes) images for building and running the script in CI/CD environment. Function was also heavely inspired by RainySystems's [appwrite-function-send-discord-webhook](https://github.com/RainySystems/appwrite-function-send-discord-webhook).

## Usage

TODO: Write

- Fork
- Set ENV vars
- Note: Runs every 5 mins

## Local development

After cloning the repository, make sure to install dependencies:

```bash
npm install
```

After making changes, you need to build the code:

```bash
npm run build
```

To run the function locally, you can spin-up Open Runtime, and hit it's HTTP endpoint. You can learn more in [Open Runtimes documentation](https://github.com/open-runtimes/open-runtimes/tree/main/runtimes/node-17.0).

## License

This repository is available under the [MIT License](./LICENSE).
