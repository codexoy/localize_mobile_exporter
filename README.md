A localization export utility for mobile projects supporting iOS and Android platforms.

**Platform Support:**
- iOS via CocoaPods integration
- Android via Gradle task and shell script

**Installation:**

**iOS (CocoaPods):**
Add to Podfile:
```ruby
pod 'LocalizeMobileExporter'
```

**Configuration:**
1. Set LOCO_API_KEY in build settings
2. Add run script phase referencing auto_export.sh
3. Configure language mapping options

**Android:**
1. Download and extract utility to project
2. Create executable shell script
3. Configure Gradle task for pre-build execution

**Options:**
- `--key` - Project API key from localization service
- `--output` - Output directory path for localization files
- `--map` - Language code mapping (platform-specific)
- `--tags` - Comma-separated resource tags
- `--plurals` - Enable plural resource export
- `--name` - Strings file name (default: localizable)

**Usage:**
Configure automatic localization file updates during build process for both iOS and Android projects. Supports custom file naming for strings files.
