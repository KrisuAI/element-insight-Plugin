# Attribution and Acknowledgments

This file provides proper attribution and acknowledgment for all third-party libraries and components used in the Element Insight IntelliJ Plugin.

## Third-Party Libraries

### Production Dependencies

#### Gson (2.10.1)
- **Author**: Google Inc.
- **License**: Apache 2.0
- **Homepage**: https://github.com/google/gson
- **Repository**: https://github.com/google/gson
- **Usage**: JSON serialization and deserialization for data exchange
- **Attribution**: This plugin uses Gson for efficient JSON processing when communicating with backend services and storing configuration data.

#### Apache HttpClient (4.5.14)
- **Author**: The Apache Software Foundation
- **License**: Apache 2.0
- **Homepage**: https://hc.apache.org/
- **Repository**: https://github.com/apache/httpclient
- **Usage**: HTTP client for backend API communication and data synchronization
- **Attribution**: This plugin uses Apache HttpClient for making HTTP requests to backend services and managing network communication.

### External Tool Requirements

The following tools are required for the plugin to function but are not Java dependencies:

#### Playwright
- **Author**: Microsoft Corporation
- **License**: Apache 2.0
- **Homepage**: https://playwright.dev/
- **Repository**: https://github.com/microsoft/playwright
- **Usage**: Web page scanning, browser automation, and code generation
- **Attribution**: This plugin uses Playwright for web page scanning and generates Playwright code for users. Playwright is installed and managed via Node.js.

#### Python (Optional)
- **Author**: Python Software Foundation
- **License**: PSF License
- **Homepage**: https://www.python.org/
- **Repository**: https://github.com/python/cpython
- **Usage**: XPath locator generation, enhanced accuracy
- **Attribution**: This plugin recommends and supports Python for enhanced XPath locator generation, but it's not a required dependency.

#### lxml (Optional)
- **Author**: Infrae and contributors
- **License**: BSD License
- **Homepage**: https://lxml.de/
- **Repository**: https://github.com/lxml/lxml
- **Usage**: XML/HTML parsing, XPath evaluation
- **Attribution**: This plugin recommends lxml for improved XPath locator accuracy, but it's not a required dependency.

#### Node.js
- **Author**: Node.js contributors
- **License**: MIT
- **Homepage**: https://nodejs.org/
- **Repository**: https://github.com/nodejs/node
- **Usage**: Runtime environment for Playwright functionality
- **Attribution**: This plugin requires Node.js as the runtime environment for executing Playwright scripts and managing browser automation tasks.

#### npm
- **Author**: npm, Inc. and Contributors
- **License**: Artistic License 2.0
- **Homepage**: https://www.npmjs.com/
- **Repository**: https://github.com/npm/cli
- **Usage**: Package management, dependency installation
- **Attribution**: This plugin uses npm to install and manage Playwright dependencies.

### Rust Binaries and Libraries

For a comprehensive list of all Rust crates and their licenses used in the `element-insight-binary` and `framework-export-binary` components, please refer to:

- [RUST_THIRD_PARTY_LICENSES.md](./RUST_THIRD_PARTY_LICENSES.md)

This document provides detailed attribution, license texts, and usage information for all Rust dependencies.

### Development Dependencies

#### JUnit (4.13.2)
- **Author**: Various contributors
- **License**: Eclipse Public License 1.0
- **Homepage**: https://junit.org/
- **Repository**: https://github.com/junit-team/junit4
- **Usage**: Unit testing framework for plugin functionality
- **Attribution**: This plugin uses JUnit for comprehensive testing of core functionality and ensuring code quality.

#### Kotlin (1.9.0)
- **Author**: JetBrains s.r.o. and Kotlin Programming Language contributors
- **License**: Apache 2.0
- **Homepage**: https://kotlinlang.org/
- **Repository**: https://github.com/JetBrains/kotlin
- **Usage**: Primary programming language for plugin development
- **Attribution**: This plugin is built using Kotlin, providing modern language features and seamless integration with the IntelliJ platform.

#### IntelliJ Platform Plugin (1.17.0)
- **Author**: JetBrains s.r.o. and other contributors
- **License**: Apache 2.0
- **Homepage**: https://plugins.jetbrains.com/
- **Repository**: https://github.com/JetBrains/intellij-platform-plugin-template
- **Usage**: Platform for developing IntelliJ IDEA plugins
- **Attribution**: This plugin is built on the IntelliJ platform, leveraging the robust plugin architecture and development tools provided by JetBrains.

## Built-in IntelliJ Platform Components

The following IntelliJ platform components are used in this plugin:

- **Project Model API** - Project structure and module management
- **UI Components** - User interface elements and layouts
- **File System API** - File and directory operations
- **Editor API** - Text editor integration
- **Tool Window API** - Custom tool window implementation
- **Action System** - Menu items and keyboard shortcuts
- **Settings API** - Configuration management
- **Notification API** - User notifications and feedback

These components are part of the IntelliJ platform and are licensed under the Apache 2.0 License by JetBrains s.r.o.

## License Compatibility

All third-party libraries used in this plugin are compatible with our MIT license:

- **Apache 2.0**: Gson, HttpClient, Kotlin, IntelliJ Platform, Playwright
- **Eclipse Public License 1.0**: JUnit
- **MIT**: Node.js
- **PSF License**: Python (optional)
- **BSD License**: lxml (optional)
- **Artistic License 2.0**: npm

## Changes Made

No modifications have been made to any third-party libraries. All libraries are used as-is from their official distributions.

## Support and Feedback

For support, feature requests, or bug reports related to this plugin:

- **Website**: https://www.krisu.ai
- **Documentation**: https://www.krisu.ai/guide/intellij-plugin
- **Support Portal**: Available after sign-up at https://www.krisu.ai
- **Email**: support@krisu.ai

## Legal Information

This plugin is distributed under the MIT License with proper attribution to all third-party components. All copyright notices and license requirements are strictly followed to ensure legal compliance.

For licensing inquiries: legal@krisu.ai

---

**Last Updated**: August 2024  
**Version**: 1.0.0  
**Maintained By**: Krisu.ai Development Team
