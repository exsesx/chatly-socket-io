# Chatly

## Overview

Chatly is a robust and efficient socket.io server implemented in Rust, drawing inspiration from the innovative
approaches seen in [Dreams of Code](https://github.com/dreamsofcode-io). This project aims to demonstrate the power and
flexibility of Rust in handling real-time communication.

For an in-depth understanding and visual demonstration of the concepts behind this project, check out
this [informative video](https://www.youtube.com/watch?v=HEhhWL1oUTM).

> **Update Notice**: The server's API has undergone recent updates, leading to minor changes. However, the core
> functionality and concept remain intact.

## Getting Started

### Running the Server

To launch the Chatly server, ensure you have Rust installed and simply execute:

```shell
cargo run
```

This command compiles and runs the server, making it ready to handle incoming socket connections.

### Setting up the Web Interface

A complementary Web UI, designed specifically for Chatly, is available thanks to the collaboration
with [Dreams of Code (Chatly Web)](https://github.com/dreamsofcode-io/chatly-web). To set it up:

1. Clone the repository:
    ```shell
    git clone git@github.com:dreamsofcode-io/chatly-web
    ```

2. Navigate to the cloned directory and install dependencies:
    ```shell
    npm install
    ```

3. Start the development server:
    ```shell
    npm run dev
    ```

This Web UI provides a user-friendly interface to interact with the Chatly server.