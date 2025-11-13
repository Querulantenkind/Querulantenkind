# 🚀 Querulantenkind

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║           💻  Developer & Linux Administrator                ║
║           🐧  Clean Code | Security | Best Practices         ║
║           🎯  Building robust, maintainable solutions        ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

**Welcome!** This is a space for learning, experimentation, and building solid software foundations.

---

## 🎯 About This Repository

A personal learning hub dedicated to **clean code**, **secure systems**, and **professional development practices**.

I focus on:
- ✨ Writing readable, maintainable code
- 🔒 Security-first mindset
- 🐧 Linux systems & administration
- 🚀 DevOps fundamentals
- 📚 Best practices & design patterns

---

## 🛠️ Tech Stack

<table>
  <tr>
    <td align="center" width="33%">
      <b>🔧 Languages</b><br/>
      Python • Bash<br/>
      Java • Markdown
    </td>
    <td align="center" width="33%">
      <b>🐧 Systems</b><br/>
      Linux Administration<br/>
      Shell Scripting<br/>
      SSH & Networking
    </td>
    <td align="center" width="33%">
      <b>📦 Tools</b><br/>
      Git • Docker<br/>
      CI/CD • DevOps<br/>
      Security Tools
    </td>
  </tr>
</table>

---

## 💡 Development Principles

| Principle | Focus |
|-----------|-------|
| 🎯 **KISS** | Simplicity over cleverness |
| 🔄 **DRY** | Don't repeat yourself |
| ⚡ **YAGNI** | You aren't gonna need it |
| 📖 **Readability** | Code for humans first |
| 🔒 **Security** | By design, not by accident |
| ✅ **Validation** | Defensive programming |

---

## 📂 Repository Structure

```
Querulantenkind/
│
├── 🐍 python/              Python scripts & projects
├── 🔨 bash/                Bash utilities & automation
├── ☕ java/                Java programs & exercises
│
├── 🐧 linux/               Linux administration
│   ├── system-admin/       Users, groups, permissions
│   ├── networking/         Network configuration
│   ├── security/           Hardening & SSH setup
│   └── monitoring/         Logs & system health
│
└── 🚀 devops/              DevOps & containerization
```

---

## 🎓 Learning Focus Areas

### 💻 Software Development
- ✅ PEP 8 standards & Type Hints (Python)
- ✅ Exception handling & input validation
- ✅ Design patterns & SOLID principles
- ✅ Code documentation & comments
- ✅ Defensive programming techniques

### 🐧 Linux Administration
- ✅ User & permission management
- ✅ File systems & ownership
- ✅ SSH configuration & key management
- ✅ Log analysis & troubleshooting
- ✅ Shell scripting automation
- ✅ Security hardening practices

---

## 📝 Code Style Guide

### Python
```python
def process_data(input_value: str) -> dict:
    """
    Process and validate input data.

    Args:
        input_value: The value to process

    Returns:
        A dictionary with processed data
    """
    if not input_value:
        raise ValueError("Input cannot be empty")

    return {"status": "success", "data": input_value}
```

### Bash
```bash
#!/bin/bash
set -euo pipefail  # Exit on error, undefined vars, pipe failures

function validate_input() {
    local input="${1:-}"
    [[ -z "${input}" ]] && echo "Error: empty input" && return 1
    echo "Input valid: ${input}"
}

validate_input "test"
```

### Java
```java
/**
 * Processes data with proper error handling.
 * @param data The input data to process
 * @return The processed result
 */
public class DataProcessor {
    private final String data;

    public DataProcessor(String data) {
        this.data = data;
    }
}
```

---

## 🔐 Security Principles

Every project follows these security guidelines:

```
✓ No hardcoded secrets or credentials
✓ Environment variables for sensitive data
✓ Input validation on all user input
✓ SSH keys instead of passwords
✓ Principle of least privilege
✓ Regular security audits
```

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/Querulantenkind/Querulantenkind.git
cd Querulantenkind

# Run Python scripts
python3 python/main.py

# Execute bash utilities
bash bash/script.sh

# Linux administration examples
bash linux/system-admin/user-management.sh

# Compile and run Java
javac java/Example.java && java Example
```

---

## 📊 Growth Path

```
🌱 Phase 1: Fundamentals
├─ Programming basics & syntax
├─ Linux command line
└─ Scripting foundations

📈 Phase 2: Mastery
├─ Advanced patterns & OOP
├─ System administration
└─ Professional tooling

🚀 Phase 3: Integration
├─ DevOps practices
├─ Security implementations
└─ Automation frameworks
```

---

## 💬 Let's Connect

- 🔗 **GitHub:** [Querulantenkind](https://github.com/Querulantenkind)
- 💡 **Open to:** Feedback, code reviews, collaboration
- 🎯 **Philosophy:** Always learning, always improving

---

### Philosophy

> *"The best code isn't the fastest—it's the **most readable** and **most secure**."*

---

<div align="center">

**Last Updated:** November 2025 | **Status:** 🔄 Continuously Learning

⭐ If you find something useful, feel free to explore!

</div>