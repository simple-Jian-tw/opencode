# OpenCode

A flexible configuration management system for code projects.

## Overview

OpenCode provides a simple and consistent way to manage project configurations, including formatting rules, linting settings, build configurations, and development settings.

## Features

- **Project Settings**: Define project metadata and information
- **Code Formatting**: Configure code formatting rules (indentation, line length, etc.)
- **Linting**: Set up linting rules and ignore patterns
- **Build Configuration**: Manage build settings and output directories
- **Development Settings**: Configure development server and debugging options

## Configuration

The main configuration file is `config.yaml`. You can customize it to fit your project's needs.

### Example Configuration

```yaml
version: "1.0"

project:
  name: "my-project"
  description: "My awesome project"
  author: "Your Name"

formatting:
  indent_size: 2
  indent_style: "space"
  max_line_length: 100
  trim_trailing_whitespace: true
  insert_final_newline: true

linting:
  enabled: true
  strict_mode: false
  ignore_patterns:
    - "*.min.js"
    - "node_modules/*"

build:
  output_directory: "dist"
  source_directory: "src"
  include_tests: false

development:
  auto_reload: true
  debug_mode: false
  port: 3000
```

## Getting Started

1. Copy the example configuration:
   ```bash
   cp examples/example-config.yaml config.yaml
   ```

2. Edit `config.yaml` to match your project requirements

3. Use the configuration in your project

## Configuration Options

### Project Settings
- `name`: Project name
- `description`: Project description
- `author`: Project author

### Formatting Settings
- `indent_size`: Number of spaces for indentation
- `indent_style`: "space" or "tab"
- `max_line_length`: Maximum line length
- `trim_trailing_whitespace`: Remove trailing whitespace (true/false)
- `insert_final_newline`: Ensure files end with a newline (true/false)

### Linting Settings
- `enabled`: Enable/disable linting (true/false)
- `strict_mode`: Use strict linting rules (true/false)
- `ignore_patterns`: List of file patterns to ignore

### Build Settings
- `output_directory`: Build output directory
- `source_directory`: Source code directory
- `include_tests`: Include tests in build (true/false)

### Development Settings
- `auto_reload`: Enable auto-reload during development (true/false)
- `debug_mode`: Enable debug mode (true/false)
- `port`: Development server port

## Examples

See the `examples/` directory for sample configurations.

## License

MIT
