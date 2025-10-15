# ⚙️ .NET Configuration Hub — Yogesh Madhukar Borse

Welcome to `dotnet-config` — my curated setup for managing .NET SDK versions, global tools, and runtime consistency across development environments. This repo is part of my broader portfolio that blends backend precision with cloud scalability.

---

## 👨‍💻 About Me

**Yogesh Madhukar Borse**  
MSc Computer Science | Full-stack Developer | AI & Cloud Enthusiast  
🔗 [GitHub](https://github.com/Yogesh-borse) • 💼 [LinkedIn](https://linkedin.com/in/yogesh-borse-035750245) • 📧 [Email](mailto:yogeshborse422@gmail.com)

---

## 🧭 Purpose

This repository ensures:
- ✅ Consistent .NET SDK usage across machines and CI/CD pipelines  
- 🛠️ Global tool management for CLI workflows  
- 🔐 Secure and optimized NuGet package sourcing  
- 🚀 Seamless onboarding for new developers and environments

---

## 📁 Contents

| File               | Purpose                                                                 |
|--------------------|-------------------------------------------------------------------------|
| `global.json`      | Locks the SDK version for consistent builds                             |
| `dotnet-tools.json`| Defines globally installed CLI tools                                    |
| `NuGet.config`     | Customizes package sources and authentication                           |
| `README.md`        | Documentation and usage instructions                                    |

---

## 🚀 Usage

```bash
# Clone the repo
git clone https://github.com/Yogesh-borse/dotnet-config.git

# Link SDK version to your project
cd your-project
dotnet new globaljson --sdk-version <version>
