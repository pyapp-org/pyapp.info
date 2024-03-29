# pyApp - A python application framework

_Let us handle the boring stuff!_

[Documentation](https://docs.pyapp.info)

**So what do we handle?**
- Configuration - Loading, merging your settings from different sources
  - Python modules
  - File and HTTP(S) endpoints for JSON and YAML files.
- Instance Factories - Configuration of plugins, database connections, or just implementations of an ABC. Leveraging settings to make setup of your application easy and reduce coupling.
- Dependency Injection - Easy to use dependency injection without complicated setup.
- Checks - A framework for checking settings are correct and environment is operating correctly (your ops team will love you)?
- Extensions - Extend the basic framework with extensions. Provides deterministic startup, extension of the CLI and the ability to register checks and extension specific default settings.
- Application - Provides a extensible and simple CLI interface for running commands (including async), comes with built-in commands to execute check, setting and extension reports.
- Logging - Initialise and apply sane logging defaults.
- Highly tested and ready for production use.
