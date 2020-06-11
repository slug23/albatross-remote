# Albatross Remote

A JSON-RPC client for Nimiq Albatross nodes.

## Installation

```bash
# Install dependencies with npm or yarn:
npm install
# or
yarn
```

## Usage

```bash
node remote.js [options] [action [args]]
```

**Options:**

```text
    --host HOST             Define hostname or IP address of Nimiq JSON-RPC
                            server to connect to. Defaults to 127.0.0.1 (localhost).
    --port PORT             Define port corresponding to HOST.
                            Defaults to 8648.
    --user USER             Use basic authentication with username USER.
                            The password will be prompted for.
```

When no `action` is specified, a REPL is opened.
