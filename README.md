# ReviewMate

> A GitHub App built with [Probot](https://github.com/probot/probot) to assist in the review process of is-a-dev

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t ReviewMate .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> ReviewMate
```

## Contributing

If you have suggestions for how ReviewMate could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[MIT](LICENSE) © 2023 Vaibhav Dhiman
