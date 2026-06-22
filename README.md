# build-your-own-redis

Content for the "Build your own Redis" challenge

### Setup

This challenge is developed using https://github.com/codecrafters-io/course-sdk. Read the README there for information
on how to contribute language support & submit solutions.

This repository is used to develop and test CodeCrafters challenges.

## Installation

# Custom Redis Engine

This repository contains the setup, starter templates, and reference solutions for building a custom Redis server from scratch. It is based on the CodeCrafters "Build your own Redis" challenge.

By working through this project, you will learn the underlying mechanics of high-performance data stores, including handling TCP connections, managing memory, and implementing the Redis Serialization Protocol (RESP).

## Repository Structure

*   **`starter_templates/`**: Boilerplate code for over 20 programming languages (Python, Go, Rust, C, Java, etc.) to help you start building your engine.
*   **`solutions/`**: Reference implementations broken down step by step for various languages.
*   **`stage_descriptions/`**: Documentation outlining each milestone of the build process.
*   **`dockerfiles/`**: Container configurations for testing and running your engine in isolated environments.

## Installation & Setup

This challenge uses the CodeCrafters Course SDK for development and testing. Make sure that you have Docker installed. Currently, you will need to compile the SDK from source using Bun.

1. Make sure you have [Bun](https://bun.sh/) installed.
2. Clone the SDK repository and run the following command:
```bash
   bun install && make install

MacOS Note: lstat is not present in MacOS. You will need to create a symlink to stat in /usr/local/bin by running:

Bash
sudo ln -s /usr/bin/stat /usr/local/bin/lstat
Test the SDK installation by running:

Bash
course-sdk --version
How to Use This Repository
Pick a Language: Choose your preferred programming language from the starter_templates/ directory.

Follow the Stages: Review the stage_descriptions/ to understand the goal of each step. The first major milestone is setting up the network layer to bind a port and listen for TCP traffic.

Build and Test: Write your engine logic in your chosen template folder and test it using the SDK.

Reference Solutions: If you get stuck on a complex protocol detail, compare your logic against the reference implementations in the solutions/ folder.

License
Please refer to the LICENSE file for distribution rights and limitations.
