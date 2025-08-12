# License Compliance Checklist

This checklist ensures the Element Insight IntelliJ Plugin maintains proper license compliance.

## ✅ Pre-Distribution Checklist

### License Files
- [x] `THIRD_PARTY_LICENSES.md` contains all required license texts
- [x] `ATTRIBUTION.md` provides proper attribution for all libraries
- [x] `RUST_THIRD_PARTY_LICENSES.md` contains Rust crate licenses
- [x] All license files are included in plugin distribution
- [x] Main plugin license is properly documented

### Copyright Notices
- [x] Gson copyright notice included (Google Inc.)
- [x] Apache HttpClient copyright notice included (The Apache Software Foundation)
- [x] Playwright copyright notice included (Microsoft Corporation)
- [x] Python copyright notice included (Python Software Foundation) - Optional
- [x] lxml copyright notice included (Infrae and contributors) - Optional
- [x] Node.js copyright notice included (Node.js contributors)
- [x] npm copyright notice included (npm, Inc. and Contributors)
- [x] JUnit copyright notice included (Various contributors)
- [x] Kotlin copyright notice included (JetBrains s.r.o.)
- [x] IntelliJ Platform copyright notice included (JetBrains s.r.o.)
- [x] Rust binaries copyright notices included (see RUST_THIRD_PARTY_LICENSES.md)

### License Texts
- [x] Apache 2.0 license text included for Gson
- [x] Apache 2.0 license text included for Apache HttpClient
- [x] Apache 2.0 license text included for Playwright
- [x] PSF License text included for Python (Optional)
- [x] BSD License text included for lxml (Optional)
- [x] MIT license text included for Node.js
- [x] Artistic License 2.0 text included for npm
- [x] Eclipse Public License 1.0 text included for JUnit
- [x] Apache 2.0 license text included for Kotlin
- [x] Apache 2.0 license text included for IntelliJ Platform
- [x] Rust crate licenses included (see RUST_THIRD_PARTY_LICENSES.md)

### Documentation
- [x] README.md includes licensing section
- [x] Links to all license files provided
- [x] Third-party library list documented
- [x] License compatibility explained
- [x] Rust dependencies properly documented

## 🔄 Maintenance Checklist

### When Adding New Dependencies
- [ ] Check license type and compatibility
- [ ] Add to `THIRD_PARTY_LICENSES.md`
- [ ] Add to `ATTRIBUTION.md`
- [ ] Update main plugin documentation
- [ ] Verify license compatibility with MIT
- [ ] If Rust dependency, update `RUST_THIRD_PARTY_LICENSES.md`

### When Updating Dependencies
- [ ] Verify license hasn't changed
- [ ] Update version numbers in documentation
- [ ] Check for new copyright holders
- [ ] Verify license compatibility
- [ ] Update Rust license information if needed

### Before Each Release
- [ ] Verify all license files are current
- [ ] Check that all files are included in distribution
- [ ] Test plugin distribution contents
- [ ] Verify copyright notices are accurate
- [ ] Ensure Rust licenses are up to date

## 📋 Compliance Verification

### License Compatibility Matrix

| Your License | MIT Libraries | Apache 2.0 Libraries | EPL Libraries | PSF Libraries | BSD Libraries | Artistic Libraries | GPL Libraries |
|--------------|---------------|----------------------|---------------|---------------|---------------|-------------------|----------------|
| MIT + Attribution | ✅ Compatible | ✅ Compatible | ✅ Compatible | ✅ Compatible | ✅ Compatible | ✅ Compatible | ❌ Incompatible |

### Required Actions by License Type

#### MIT License
- ✅ Include copyright notice
- ✅ Include permission notice
- ✅ No additional restrictions

#### Apache 2.0 License
- ✅ Include full license text
- ✅ Include copyright notice
- ✅ Include license URL reference
- ✅ State changes made (if any)

#### Eclipse Public License 1.0
- ✅ Include full license text
- ✅ Include copyright notice
- ✅ Include license URL reference
- ✅ State changes made (if any)

#### PSF License
- ✅ Include full license text
- ✅ Include copyright notice
- ✅ Include license URL reference
- ✅ State changes made (if any)

#### BSD License
- ✅ Include full license text
- ✅ Include copyright notice
- ✅ Include license URL reference
- ✅ State changes made (if any)

#### Artistic License 2.0
- ✅ Include full license text
- ✅ Include copyright notice
- ✅ Include license URL reference
- ✅ State changes made (if any)

#### GPL License
- ❌ **NOT COMPATIBLE** with MIT
- ❌ **DO NOT USE** in this plugin
- ❌ Would require GPL licensing for entire plugin

## 🚨 Compliance Issues to Watch

### High Risk
- **Missing License Texts**: Could result in license violation
- **Missing Copyright Notices**: Could result in copyright infringement
- **Incompatible Licenses**: Could require license change
- **Missing Rust Licenses**: Could violate Rust crate licenses

### Medium Risk
- **Outdated License Information**: Could miss license changes
- **Missing Attribution**: Could appear unprofessional
- **Incomplete Documentation**: Could confuse users
- **Outdated Rust License Info**: Could miss Rust crate updates

## 📚 Current Dependencies Summary

### Production Dependencies
- **Gson** (Apache 2.0) - JSON processing
- **Apache HttpClient** (Apache 2.0) - HTTP communication

### External Tool Requirements
- **Playwright** (Apache 2.0) - Web automation
- **Python** (PSF) - XPath generation (optional)
- **lxml** (BSD) - XML/HTML parsing (optional)
- **Node.js** (MIT) - Runtime environment
- **npm** (Artistic 2.0) - Package management

### Development Dependencies
- **JUnit** (EPL 1.0) - Testing framework
- **Kotlin** (Apache 2.0) - Programming language
- **IntelliJ Platform** (Apache 2.0) - Plugin platform

### Binary Dependencies
- **Rust Binaries** - See RUST_THIRD_PARTY_LICENSES.md for complete list
