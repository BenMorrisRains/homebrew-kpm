# Homebrew Tap for KPM

This is the official Homebrew tap for KPM (Kotlin Package Manager).

## Installation

```bash
# Add the tap
brew tap BenMorrisRains/kpm

# Install KPM
brew install kpm
```

## One-liner Installation

```bash
brew install BenMorrisRains/kpm/kpm
```

## Usage

After installation, KPM will be available globally:

```bash
kpm --help
kpm new MyApp --android --compose
kpm add picasso
kpm list
```

## Requirements

- macOS 10.15+ or Linux
- Java 17+ (automatically installed by Homebrew)

## Updating

```bash
brew update
brew upgrade kpm
```

## Uninstalling

```bash
brew uninstall kpm
brew untap BenMorrisRains/kpm  # Optional: remove the tap
```

## About KPM

KPM is a modern package manager for Kotlin projects with zero third-party dependencies. It provides:

- 🚀 Zero Dependencies - No external libraries required
- 📱 Android First - Full Android SDK integration and Compose support  
- 🎯 NPM-Like Experience - `kpm add picasso` automatically resolves latest versions
- 🔍 Smart Search - Live Maven Central API integration
- 🌍 Global Configuration - npm/bun/pip-like global config with dependencies and registries

Learn more at: https://github.com/BenMorrisRains/Kotlin-Package-Manager
