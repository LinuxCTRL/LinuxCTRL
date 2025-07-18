<div align="center">
<img src="https://github.com/LinuxCTRL/LinuxCTRL/blob/main/banner.png" alt="Developer Toolkit Builder - Human + AI Collaboration" width="100%" />
  </div>
<div align="center">

# 👋 Hi there! I'm building the future, one utility at a time

[![GitHub followers](https://img.shields.io/github/followers/LinuxCTRL?style=social)](https://github.com/LinuxCTRL)
[![Twitter Follow](https://img.shields.io/twitter/follow/am49811?style=social)](https://twitter.com/am49811)

</div>

## 🚀 About Me

I'm a passionate developer who believes in creating **small but powerful tools** that make developers' lives easier. My mission is to build a collection of high-impact, compact utilities that solve real-world problems with elegant solutions.

## 🤖 Meet My AI Development Partner - Rovo Dev

This incredible collection of utilities wouldn't exist without my amazing AI development partner - **Rovo Dev**! 🎉

Rovo Dev is not just any AI assistant - they're a brilliant coding companion who:

- 🧠 **Understands complex requirements** and translates ideas into production-ready code
- 🎨 **Designs beautiful CLI interfaces** with user experience in mind
- 🔧 **Implements best practices** including virtual environments, proper error handling, and comprehensive documentation
- 📚 **Creates professional documentation** that makes projects accessible to everyone
- 🚀 **Thinks like a developer** - suggesting improvements, optimizations, and real-world considerations
- ⚡ **Works at lightning speed** - turning concepts into working software in minutes
- 🎯 **Focuses on user experience** - every tool is designed to be intuitive and helpful

**Together, we make an unstoppable team:** I bring the vision and ideas, Rovo Dev brings the technical expertise and implementation magic. Every line of code, every feature, and every improvement is a result of our collaborative partnership.

**What makes Rovo Dev special:**

- 💡 **Creative Problem Solving** - Finds elegant solutions to complex challenges
- 🛠️ **Full-Stack Implementation** - From CLI tools to web interfaces
- 📖 **Documentation Master** - Creates README files that actually help people
- 🔍 **Attention to Detail** - Considers edge cases and error handling
- 🌟 **Innovation Driver** - Suggests features I never thought of

> _"The best tools are the ones that people actually use. Start small, focus on user experience, and iterate based on feedback."_ - Our shared philosophy

## 💡 Current Projects & Ideas

I'm working on a comprehensive collection of **developer utilities** - each designed to be lightweight, powerful, and incredibly useful. Here's what we're building:

### 🚀 **File & Directory Management**

<table>
<tr>
<td width="50%">

#### 🔍 Smart Search Tools ✅ **COMPLETED**

_Enhanced file and content search with beautiful colorized output_

```bash
smart-search filename.txt              # Find files by name
smart-search --content "function"      # Search content in files
smart-search --type py --recursive     # Search Python files recursively
```

[🔗 View Project](https://github.com/LinuxCTRL/smart-find)

#### 📦 Smart Backup Tool 

_One-command incremental backups with compression_

```bash
smart-backup create /home/user --destination /backup --compress
smart-backup restore /backup/2024-01-15 --target /home/user
smart-backup list --show-sizes
```
[🔗 View Project](https://github.com/LinuxCTRL/smart-backup)
#### 🔍 Duplicate File Finder ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Find and manage duplicate files with size/hash comparison_

```bash
dup-finder scan /home/user --min-size 1MB
dup-finder remove --interactive --keep-newest
dup-finder report --export csv
```

</td>
<td width="50%">

#### 🗂️ Smart File Organizer ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Auto-organize files by type, date, or custom rules_

```bash
file-organizer auto /Downloads --by-type
file-organizer custom /Photos --rule "date:YYYY/MM"
file-organizer preview --dry-run
```

#### 🔐 Secure File Shredder ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Permanently delete sensitive files with military-grade overwriting_

```bash
secure-delete file.txt --passes 7
secure-delete /tmp/* --recursive --confirm
secure-delete --wipe-free-space /home/user
```

#### 📊 Directory Analyzer ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Visualize disk usage with interactive charts_

```bash
disk-analyzer /home/user --chart
disk-analyzer --largest-files --limit 20
disk-analyzer --export html
```

</td>
</tr>
</table>

### 🌐 **Network & System Tools**

<table>
<tr>
<td width="50%">

#### 🌐 Network Speed Monitor ✅ **COMPLETED**

_Track internet speed over time with alerts and beautiful reports_

```bash
speed-monitor start --interval 30m --alert-threshold 50Mbps
speed-monitor report --last-week --export png
speed-monitor test --servers closest
```

[🔗 View Project](https://github.com/LinuxCTRL/network-speed-monitor)

#### 🔍 Port Scanner & Service Checker ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Check what's running on your system/network_

```bash
port-check localhost --common-ports
port-check 192.168.1.0/24 --port 22,80,443
port-check --services --show-processes
```

#### 📊 System Health Dashboard ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_CPU, memory, disk usage in a clean terminal UI_

```bash
health-check        # Show CPU, RAM, disk, network
health-check --alert # Set up monitoring alerts
health-check --web   # Web dashboard interface
```

</td>
<td width="50%">

#### 📝 Log Aggregator ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Tail and search multiple log files simultaneously_

```bash
log-watch /var/log/*.log --filter ERROR
log-watch --config logwatch.yml --dashboard
log-watch --export --since "1 hour ago"
```

#### 🔒 SSL Certificate Monitor ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Track SSL certificate expiration dates_

```bash
ssl-monitor add example.com --alert-days 30
ssl-monitor check-all --export csv
ssl-monitor dashboard --web
```

#### 🌍 DNS Toolkit ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Comprehensive DNS analysis and monitoring_

```bash
dns-toolkit lookup example.com --all-records
dns-toolkit monitor --check-propagation
dns-toolkit benchmark --servers 8.8.8.8,1.1.1.1
```

</td>
</tr>
</table>

### 📊 **Productivity & Development Tools**

<table>
<tr>
<td width="50%">

#### 🤖 Smart Git Commit Tool ✅ **COMPLETED**

_AI-powered automatic commit message generation using Google Gemini_

```bash
smart-commit                    # Auto-generate commit message
smart-commit --review          # Review changes before commit
smart-commit --push            # Commit and push in one command
```

[🔗 View Project](https://github.com/LinuxCTRL/smart-commit)

#### ⏰ Time Tracker ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Simple CLI time tracking with project categorization_

```bash
time-track start "Project Alpha" --category development
time-track stop --note "Implemented user authentication"
time-track report --this-week --by-category
```

#### ✅ Task Manager ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Lightweight todo list with priorities and due dates_

```bash
task add "Fix bug #123" --priority high --due tomorrow
task list --filter @work --sort priority
task complete 5 --note "Deployed to production"
```

</td>
<td width="50%">

#### 📝 Note Organizer ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Markdown-based note system with tagging and search_

```bash
notes new "Meeting Notes" --tags work,planning
notes search "authentication" --in-content
notes export --format pdf --tag work
```

#### 🔧 Environment Manager ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Manage development environments and configurations_

```bash
env-manager create nodejs-project --template react
env-manager switch python-3.9 --with-packages requirements.txt
env-manager backup current --name "stable-config"
```

#### 📈 Git Statistics ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Beautiful git repository analytics_

```bash
git-stats --commits-by-author --chart
git-stats --activity-heatmap --export png
git-stats --code-frequency --since "6 months ago"
```

</td>
</tr>
</table>

### 🔧 **System Utilities**

<table>
<tr>
<td width="50%">

#### 🚀 Deployment Helper ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Streamline deployment workflows_

```bash
deploy-helper init --platform heroku
deploy-helper check --environment production
deploy-helper rollback --to-version v1.2.3
```

#### 🧹 System Cleaner ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Clean temporary files, caches, and optimize system_

```bash
system-cleaner scan --show-savings
system-cleaner clean --safe-mode
system-cleaner schedule --weekly
```

#### 🔋 Battery Monitor ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Track battery health and usage patterns_

```bash
battery-monitor status --detailed
battery-monitor history --chart --last-week
battery-monitor alert --low-battery 20%
```

</td>
<td width="50%">

#### 🖥️ Process Manager ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Advanced process monitoring and management_

```bash
process-manager top --sort memory
process-manager kill --pattern "chrome.*"
process-manager monitor --alert-cpu 80%
```

#### 📱 Device Manager ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Manage connected devices and peripherals_

```bash
device-manager list --type usb
device-manager monitor --auto-mount
device-manager eject --safe-removal
```

#### 🔐 Password Generator ![Coming Soon](https://img.shields.io/badge/Status-Coming%20Soon-yellow)

_Generate secure passwords with custom rules_

```bash
password-gen --length 16 --include-symbols
password-gen --passphrase --words 4
password-gen --batch 10 --export secure.txt
```

</td>
</tr>
</table>

## 🛠️ **Tech Stack & Philosophy**

### Languages & Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

### Operating System & Environment

![Arch Linux](https://img.shields.io/badge/Arch%20Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)
![CachyOS](https://img.shields.io/badge/CachyOS-Performance%20Optimized-FF6B35?style=for-the-badge&logo=linux&logoColor=white)

### Currently Learning

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)

### Design Principles (Powered by Human + AI Collaboration)

- 🎯 **Single Purpose** - Each tool does one thing exceptionally well
- 🚀 **Performance** - Lightweight and fast execution
- 🎨 **User Experience** - Beautiful CLI interfaces with helpful output
- 🔧 **Reliability** - Robust error handling and edge case management
- 📚 **Documentation** - Comprehensive guides and examples
- 🧪 **Testing** - Thorough testing for production readiness
- 🤖 **AI-Enhanced** - Leveraging AI for better code quality and innovation

## 🐧 **Powered by CachyOS**

Running on **CachyOS** - the performance-optimized Arch Linux distribution that makes everything blazingly fast! 🚀

_Because when you're building developer tools, every millisecond counts._

## 📈 **GitHub Stats**

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=LinuxCTRL&show_icons=true&theme=radical)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=LinuxCTRL&layout=compact&theme=radical)

</div>

## 🎯 **Current Focus**

🔥 **Recently Completed:**

- 🌐 **Network Speed Monitor** - ✅ **COMPLETED** - Track internet speed with beautiful reports and alerts
- 🤖 **Smart Git Commit Tool** - ✅ **COMPLETED** - AI-powered automatic commit message generation
- 🔍 **Smart Search Tools** - ✅ **COMPLETED** - Enhanced file and content search with beautiful output

🚧 **Currently Working On:**

- 📊 **System Dashboard** - Real-time system monitoring web interface
- 🔐 **Secure File Shredder** - Military-grade file deletion

📋 **Next Up:**

- 📦 **Smart Backup Tool** - Intelligent incremental backups
- ⏰ **Time Tracker** - CLI time tracking with project categorization

## 🤝 **The Dream Team**

**Human Vision + AI Implementation = Unstoppable Results**

- 💭 **I provide**: Ideas, requirements, user experience insights, and real-world testing
- 🤖 **Rovo Dev provides**: Technical implementation, best practices, documentation, and optimization
- 🚀 **Together we create**: Production-ready tools that developers actually want to use

## 🤝 **Let's Connect!**

I'm always excited to collaborate on interesting projects and discuss new ideas!

- 💬 **Ask me about**: CLI tools, system utilities, developer productivity, AI-assisted development
- 🌱 **Currently learning**: Go for system programming, Rust for performance-critical applications
- 🐧 **Daily driver**: CachyOS (because performance matters!)
- ⚡ **Fun fact**: I believe the best software is invisible - it just works
- 🤖 **AI Partnership**: Proud to work with Rovo Dev to build amazing tools
- 🌍 **Mission**: Control the world through better developer tools! 😎
- 📫 **How to reach me**: [sofalcons@outlook.com](mailto:sofalcons@outlook.com)

### Find me around the web 🌐

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/soufiane-amediaz-681976364/)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/am49811)
[![Dev.to](https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white)](https://dev.to/soufiane_amediaz_882ed41d)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@amediazsoufian)

---

<div align="center">

**⭐ Star my repositories if you find them useful!**

_Building tools that developers love, one commit at a time_ 🚀

**Powered by Human Creativity + AI Excellence** 🤖❤️👨‍💻

**LinuxCTRL - Controlling the world through better developer tools!** 🌍💪

</div>
