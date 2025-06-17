# JetStarter Template 🚀

_A clean, opinionated starter template for Jetpack Compose with built-in quality controls_

## ✨ Features

✅ **Code Quality Pre-Setup**

- **Spotless** (Ktlint + Prettier) for auto-formatting
- **EditorConfig** for cross-IDE consistency
- **Android Studio** code style configs included

✅ **GitHub Actions CI/CD**

- Format verification on every push
- On-demand debug/release builds
- No linters - just pure formatting

✅ **Zero Bloat**

- Single "Hello World" composable
- Minimal Gradle configuration
- Ready for Clean Architecture

## 🚀 Quick Start

1. **Create repo** → Click "Use this template"
2. **Configure** → Update `build.gradle` (package name, versions)
3. **Run** → `./gradlew assembleDebug`

**First-time setup:**

```bash
./gradlew spotlessApply  # formats kotlin and kts
npm i && npm run format # formats xml, json and markdown
```

## 🔧 Workflows

All workflows support **manual triggering** via GitHub UI:

| Workflow            | Trigger     | Action                            |
| ------------------- | ----------- | --------------------------------- |
| `format-check.yml`  | Push/PR     | Verifies Spotless formatting      |
| `debug-build.yml`   | Manual/Push | Builds debug APK                  |
| `release-build.yml` | Manual only | Generates unsigned release bundle |

## ⚙️ Customization

**1. Code Style**

- Android Studio > `config/codeStyles/Project.xml`
- Global settings > `.editorconfig`

**2. Formatter Rules**

- Prettier Config > `.prettierrc`
- Spotless > `build.gradle`

## 🤝 Contributing

PRs welcome! Requirements:

- All workflows must pass
- Follow existing formatting (no style debates)
- Keep the template minimal

🚀 **Build fearlessly** - Your Jetpack journey starts with perfect formatting out of the box!
