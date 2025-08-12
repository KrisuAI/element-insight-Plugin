# Element Insight - IntelliJ Plugin

A powerful IntelliJ plugin for web element analysis, locator generation, and framework code export.

## Features

- **Web Page Scanning**: Scan web pages using Playwright for element discovery
- **Element Locator Generation**: Generate reliable locators for web elements
- **Framework Code Export**: Export code for Selenium, Playwright, Cypress, and more
- **Multiple Export Formats**: JSON, CSV, and framework-specific code generation
- **Tag-based Filtering**: Filter elements by HTML tags for focused analysis
- **License Management**: Built-in license validation and management

## Installation

### Prerequisites

1. **IntelliJ IDEA** (Community or Ultimate Edition) version 2023.1 or later
2. **Java 17** or later
3. **Node.js** (for Playwright functionality)

### Installation Steps

1. **Download the Plugin**
   - Download `element-insight-plugin-1.0.0.zip` from the releases
   - Or build from source using the instructions below

2. **Install in IntelliJ**
   - Open IntelliJ IDEA
   - Go to `File` → `Settings` (or `IntelliJ IDEA` → `Preferences` on macOS)
   - Navigate to `Plugins`
   - Click the gear icon and select `Install Plugin from Disk...`
   - Select the downloaded `element-insight-plugin-1.0.0.zip` file
   - Click `OK` and restart IntelliJ when prompted

3. **Install Playwright** (Required for web scanning)
   - Open the Element Insight tool window: `Tools` → `Element Insight: Open Tool Window`
   - Click `Install Playwright` in the tool window
   - Wait for the installation to complete

4. **Install Playwright Browsers** (Required for web scanning)
   - In the Element Insight tool window, click `Install Playwright Browsers`
   - Wait for the browser installation to complete

## Usage

### Opening the Tool Window

- Go to `Tools` → `Element Insight: Open Tool Window`
- Or use the keyboard shortcut: `Ctrl+Alt+E` (Windows/Linux) or `Cmd+Alt+E` (macOS)

### Scanning a Web Page

1. **Select Framework**: Choose your target framework from the dropdown
2. **Enter URL**: Input the URL of the web page you want to scan
3. **Configure Tags** (Optional): Select specific HTML tags to focus on
4. **Click Scan**: The plugin will launch a browser and scan the page
5. **Review Results**: View the discovered elements and their locators

### Exporting Results

After a successful scan, you can export the results in multiple formats:

- **JSON Export**: Export raw element data in JSON format
- **CSV Export**: Export element data in CSV format for analysis
- **Framework Code**: Generate framework-specific code for your selected elements

### Tag Selection

Use the tag selection panel to focus on specific types of elements:
- **Common Elements**: Buttons, links, forms, inputs
- **Custom Tags**: Any HTML tag you want to focus on
- **Multiple Selection**: Select multiple tags for comprehensive analysis

## Configuration

### Framework Support

The plugin supports multiple testing frameworks:
- **Selenium**: Java, C#, Python, JavaScript
- **Playwright**: JavaScript, Python, C#, Java
- **Cypress**: JavaScript
- **And more...**

### Locator Strategies

Multiple locator strategies are available:
- **CSS Selectors**: Most reliable and maintainable
- **XPath**: Powerful but more complex
- **ID-based**: Fast but less flexible
- **Text-based**: Good for user-facing elements

## Troubleshooting

### Common Issues

1. **Playwright Not Installed**
   - Use the `Install Playwright` action in the tool window
   - Ensure Node.js is properly installed

2. **Browsers Not Available**
   - Use the `Install Playwright Browsers` action
   - Check your internet connection

3. **Scan Fails**
   - Verify the URL is accessible
   - Check that Playwright and browsers are installed
   - Review the status messages for specific error details

4. **Export Buttons Disabled**
   - Ensure a successful scan has been completed
   - Check that elements were found during the scan

### Getting Help

- Check the status messages in the tool window
- Review the IntelliJ event log for detailed error information
- Ensure all prerequisites are met

## Development

### Building from Source

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd element-insight-plugin
   ```

2. **Build the Plugin**
   ```bash
   ./gradlew buildPlugin
   ```

3. **Find the Output**
   - The built plugin will be in `build/distributions/`
   - Look for `element-insight-plugin-<version>.zip`

### Project Structure

```
src/main/kotlin/com/krisu/elementinsight/
├── actions/          # IntelliJ actions and menu items
├── components/       # Project and application components
├── models/          # Data models and state management
├── services/        # Core business logic services
└── ui/             # User interface components
```

## License

This plugin is distributed under the MIT License. For complete license information and third-party attributions, see:

- [LICENSE](LICENSE) - Main plugin license
- [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md) - Complete third-party licenses
- [ATTRIBUTION.md](ATTRIBUTION.md) - Third-party library attributions
- [RUST_THIRD_PARTY_LICENSES.md](RUST_THIRD_PARTY_LICENSES.md) - Rust crate licenses
- [COMPLIANCE_CHECKLIST.md](COMPLIANCE_CHECKLIST.md) - License compliance checklist

### Third-Party Dependencies

The plugin uses the following third-party libraries:
- **Gson** (2.10.1) - Apache 2.0 License (Google Inc.)
- **Apache HttpClient** (4.5.14) - Apache 2.0 License (The Apache Software Foundation)
- **Playwright** - Apache 2.0 License (Microsoft Corporation)
- **Python** - PSF License (Python Software Foundation) - Optional
- **lxml** - BSD License (Infrae and contributors) - Optional
- **Node.js** - MIT License (Node.js contributors)
- **npm** - Artistic License 2.0 (npm, Inc. and Contributors)
- **JUnit** (4.13.2) - Eclipse Public License 1.0 (Various contributors)
- **Kotlin** (1.9.0) - Apache 2.0 License (JetBrains s.r.o.)
- **IntelliJ Platform** (1.17.0) - Apache 2.0 License (JetBrains s.r.o.)
- **Rust Binaries** - Various licenses (see RUST_THIRD_PARTY_LICENSES.md)

All third-party libraries are compatible with our license and properly attributed.

## Support

For support and feature requests, please contact the development team.

## Changelog

### Version 1.0.0
- Initial release
- Web page scanning with Playwright
- Element locator generation
- Framework code export
- Tag-based filtering
- License management
- IntelliJ 2023.1+ compatibility
