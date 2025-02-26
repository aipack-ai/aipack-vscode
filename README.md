# AIPack VSCode Extension

This is the first version of the [AIPACK](https://aipack.ai) VSCode extension.

[AIPACK](https://aipack.ai) - RUN, BUILD, SHARE AI packages

## AIPack Extension Features

Currently, there are very few features, but more are coming.

- File mapping: `.aip` files will be mapped as `markdown` to follow the AIPack format.
- Snippets
    - `aip-agent-min`: The minimum agent .aip example

## Requirements

This extension assumes AIPack is installed locally.

Currently, the simplest way to install it is via the Rust language with:

- `cargo install aipack`

- Then `aip init`
    - To initialize the current directory as the AIPACK workspace (with the `.aipack` directory).
    - And initialize/update the `~/.aipack-base` directory.

## What is AIPACK?

AIPACK is a command-line/runtime utility that allows you to run, build, and share AI Packages.

For example:

- Run `aip run demo@proof -f ./README.md` to run the AIPACK `proof` in the `demo` namespace.
- Or run `aip run demo@craft/code` to request and write some code in a single `_craft_code.md` file.
- Or run any `.aip` file directly, like `aip run my-agent.aip`.
