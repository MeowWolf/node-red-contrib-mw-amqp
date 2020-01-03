![](https://github.com/MeowWolf/node-red-contrib-mw-amqp/workflows/Lint,%20Build,%20Test/badge.svg)

# node-red-contrib-mw-amqp

AMQP nodes for node-red

## Installation

Install via the Palette Manager or from within your node-red directory (typically `~/.node-red`) run:

```
npm i @meowwolf/node-red-contrib-mw-amqp
```

## Usage

Provides two standard nodes and an amqp broker config node:

![mw amqp nodes](./nodes.png)

Please see the `Node Help` section from wihin node-red for more info

## Development

### Build the project

```
npm run build
```

### Run tests

Run in watch mode:

```
npm test
```

Run coverage:

```
npm run test:coverage
```

## Roadmap

- Add TLS authentication
- Implement headers exchange
