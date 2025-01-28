# Toolkit

A dual-language package (Go/Rust) for building and managing LLM function calling tools and toolkits

## Features

- Abstract Tool interface for implementing LLM-compatible functions
- Default tool implementation with required metadata
- Toolkit management for grouping related tools
- Functional options pattern for configuration (Go)
- Builder pattern for configuration (Rust)
- JSON schema support for function parameters and returns



## Usage

Both implementations provide similar functionality with language-specific idioms:

- Go uses the functional options pattern for configuration
- Rust uses the builder pattern for configuration
- Both support async execution of tools
- Both use JSON schemas for parameter and return type definitions
