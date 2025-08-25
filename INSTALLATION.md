# Installation Guide - Element Insight IntelliJ Plugin

**Complete installation guide for the Element Insight IntelliJ Plugin**

## 🚀 Quick Installation

### **From IntelliJ Plugin Manager (Recommended)**

1. **Open IntelliJ IDEA**
2. **Go to**: `File → Settings → Plugins` (Windows/Linux) or `IntelliJ IDEA → Preferences → Plugins` (macOS)
3. **Click**: `Marketplace` tab
4. **Search for**: `Element Insight`
5. **Click**: `Install`
6. **Restart**: IntelliJ IDEA when prompted

### **From Plugin File (.jar)**

1. **Download**: Element Insight plugin JAR file
2. **Open IntelliJ IDEA**
3. **Go to**: `File → Settings → Plugins` (Windows/Linux) or `IntelliJ IDEA → Preferences → Plugins` (macOS)
4. **Click**: `⚙️` (gear icon) → `Install Plugin from Disk...`
5. **Select**: Downloaded JAR file
6. **Click**: `OK`
7. **Restart**: IntelliJ IDEA when prompted

---

## 📋 Prerequisites

### **Required Software**

#### **IntelliJ IDEA**
- **Version**: 2023.1 or later (Build 231+)
- **Edition**: Community or Ultimate
- **Platform**: Windows, macOS, or Linux

#### **Java Runtime**
- **Version**: Java 17 or later
- **Distribution**: OpenJDK or Oracle JDK
- **Verification**: `java -version` in terminal

#### **Node.js**
- **Version**: 18.0.0 or later
- **Purpose**: Playwright runtime environment
- **Verification**: `node --version` in terminal

### **System Requirements**

#### **Minimum Requirements**
- **RAM**: 4 GB available memory
- **Storage**: 2 GB free disk space
- **Network**: Internet connection for initial setup

#### **Recommended Requirements**
- **RAM**: 8 GB or more available memory
- **Storage**: 5 GB free disk space
- **Network**: Stable internet connection
- **OS**: Latest stable version of your operating system

---

## 🔧 Post-Installation Setup

### **Step 1: Install Playwright**

1. **Open Element Insight**: `Tools → Element Insight: Open Element Insight` or `Ctrl+Alt+E`
2. **Click**: `Install Playwright` button or use `Tools → Element Insight: Install Playwright`
3. **Wait**: Installation completes (may take 2-5 minutes)
4. **Verify**: Check status shows "Playwright installed successfully"

### **Step 2: Install Playwright Browsers**

1. **Click**: `Install Browsers` button or use `Tools → Element Insight: Install Browsers`
2. **Wait**: Browser download and installation (may take 5-15 minutes)
3. **Verify**: Check status shows "Browsers installed successfully"

### **Step 3: Accept License Agreement**

1. **Click**: `Show License Agreement` or use `Tools → Element Insight: Show License Agreement`
2. **Read**: Complete license terms and privacy policy
3. **Accept**: Click "Accept" to continue using the plugin

---

## 🎯 First-Time Usage

### **Quick Start Workflow**

1. **Open Tool Window**: `Ctrl+Alt+E` or `Tools → Element Insight: Open Element Insight`
2. **Enter URL**: Type the website URL you want to scan
3. **Select Tags**: Choose HTML elements to focus on (optional)
4. **Click Scan**: Start the scanning process
5. **Review Results**: Examine detected elements
6. **Export**: Choose your preferred export format

### **Keyboard Shortcuts**

| Shortcut | Action | Description |
|----------|--------|-------------|
| `Ctrl+Alt+E` | Open Element Insight | Opens the main tool window |
| `Ctrl+Alt+S` | Quick Scan | Starts scan with default settings |
| `Ctrl+Alt+X` | Export Last Result | Exports the most recent scan |
| `Ctrl+Alt+P` | Install Playwright | Installs Playwright runtime |
| `Ctrl+Alt+B` | Install Browsers | Installs Playwright browsers |
| `Ctrl+Alt+L` | Show License | Displays license agreement |
| `Ctrl+Alt+H` | Show Help | Opens help and documentation |

---

## 🔍 Verification & Testing

### **Installation Verification**

#### **Plugin Status**
- **Check**: `File → Settings → Plugins`
- **Verify**: Element Insight shows as "Installed" and "Enabled"
- **Status**: Should show version 1.0.0

#### **Tool Window Access**
- **Verify**: `Tools → Element Insight` menu appears
- **Check**: Tool window opens with `Ctrl+Alt+E`
- **Confirm**: UI loads without errors

### **Functionality Testing**

#### **Basic Operations**
- **Tool Window**: Opens and displays correctly
- **Menu Items**: All Element Insight actions are available
- **Keyboard Shortcuts**: All shortcuts work as expected

#### **Advanced Features**
- **Playwright Installation**: Completes successfully
- **Browser Installation**: Downloads and installs browsers
- **Web Scanning**: Can scan a test website
- **Export Functions**: Can export in different formats

---

## 🚨 Troubleshooting

### **Common Installation Issues**

#### **Plugin Not Appearing**
- **Solution**: Restart IntelliJ IDEA completely
- **Check**: Verify plugin is enabled in settings
- **Alternative**: Try installing from disk

#### **Playwright Installation Fails**
- **Check**: Node.js is installed and in PATH
- **Verify**: Internet connection is stable
- **Solution**: Try manual installation via npm

#### **Browser Installation Fails**
- **Check**: Sufficient disk space (5+ GB)
- **Verify**: Stable internet connection
- **Solution**: Try installing browsers individually

#### **Permission Errors**
- **Windows**: Run IntelliJ as Administrator
- **macOS**: Check System Preferences → Security & Privacy
- **Linux**: Verify file permissions and ownership

### **Performance Issues**

#### **Slow Installation**
- **Check**: Internet connection speed
- **Verify**: Available disk space
- **Solution**: Close other applications during installation

#### **Memory Issues**
- **Increase**: IntelliJ memory allocation
- **Check**: Available system RAM
- **Solution**: Restart IntelliJ after installation

---

## 🔄 Updates & Maintenance

### **Plugin Updates**

#### **Automatic Updates**
- **Check**: `File → Settings → Plugins`
- **Look for**: Update notifications
- **Install**: Click "Update" when available

#### **Manual Updates**
- **Download**: Latest version from marketplace
- **Install**: Follow installation steps
- **Restart**: IntelliJ IDEA when prompted

### **Dependency Updates**

#### **Playwright Updates**
- **Check**: `npm list playwright` in terminal
- **Update**: `npm update playwright`
- **Verify**: Plugin recognizes updated version

#### **Browser Updates**
- **Automatic**: Browsers update with Playwright
- **Manual**: Reinstall browsers if needed
- **Verify**: Test scanning functionality

---

## 📚 Additional Resources

### **Documentation**
- **User Guide**: https://www.krisu.ai/guide/intellij-plugin
- **API Reference**: https://www.krisu.ai/api/intellij-plugin
- **Examples**: https://www.krisu.ai/examples/intellij-plugin

### **Support**
- **Email**: support@krisu.ai
- **Website**: https://www.krisu.ai/support
- **Documentation**: https://www.krisu.ai/docs

### **Community**
- **GitHub**: https://github.com/KrisuAI/element-insight-intellij
- **Discussions**: https://github.com/KrisuAI/element-insight-intellij/discussions
- **Issues**: https://github.com/KrisuAI/element-insight-intellij/issues

---

## 🌟 Installation Success Checklist

- ✅ **Plugin Installed**: Element Insight appears in plugins list
- ✅ **Tool Window Accessible**: `Ctrl+Alt+E` opens tool window
- ✅ **Playwright Installed**: Runtime environment ready
- ✅ **Browsers Installed**: Web automation ready
- ✅ **License Accepted**: Terms and conditions agreed to
- ✅ **Basic Scan Works**: Can scan a test website
- ✅ **Export Functions**: Can export in different formats
- ✅ **Keyboard Shortcuts**: All shortcuts working
- ✅ **Help System**: Documentation accessible

---

**🎉 Congratulations! You're ready to use Element Insight for professional web testing automation.**

**Element Insight by KrisuAI** - Professional Web Testing Automation for IntelliJ
