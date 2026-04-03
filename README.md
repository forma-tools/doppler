# Doppler

[![Forma](https://img.shields.io/badge/forma-stable-brightgreen.svg)](https://github.com/forma-tools/forma) [![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

> Doppler secrets management - sync, inject, and manage secrets across environments.

**Origin:** Vendor (1st-party) - [docs.doppler.com/docs/cli](https://docs.doppler.com/docs/cli)

## Install

```bash
brew install doppler
```

## Quick Start

```bash
doppler login
doppler setup
doppler secrets
doppler run -- node server.js
```

## Forma Protocol

This tool follows the [Forma Protocol v0.7.0](https://github.com/forma-tools/forma/blob/main/docs/protocol/00-index.md).

| Property | Value |
|----------|-------|
| Type | Vendor (1st-party) |
| Origin | `vendor` |
| Auth | `doppler login` |
