# stdin-env

## About

Sets environment variable from stdin.

### Why

- TypeScript
- Cross-platform
- Dynamically generated values from other commands

## Prerequisites

- [Node.js version 10 or higher](https://nodejs.org/en/download/)

## Installation

```bash
npm install cross-cat --global
```

## Usage

```bash
<command> | stdin-env <variable_name>
```

### Example

#### Input from `stdin`

```bash
date +%s | stdin-env START_TIME
```

#### Input from argument

```bash
stdin-env --key NODE_ENV --value PRODUCTION
```