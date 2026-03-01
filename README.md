# Course Prerequisites

## Mandatory Setup – To Be Completed Before Day 3 of Class

All students must complete the following setup before the third day of class.

The course is hands-on and lab-intensive. Without this setup, participation in practical sessions will not be possible.

---

# 1. Install Required Core Software

## 1.1 Install Visual Studio Code

Download and install Visual Studio Code from the official website:

[https://code.visualstudio.com/](https://code.visualstudio.com/)

Follow the installation instructions step by step according to your operating system (Windows, macOS, or Linux).

After installation:

* Open Visual Studio Code.
* Verify that it launches correctly.
* Familiarize yourself with:

  * The Extensions panel
  * The Integrated Terminal
  * The Command Palette (Ctrl+Shift+P or Cmd+Shift+P)

---

## 1.2 Install Docker Desktop

Docker is mandatory for this course.

Download Docker Desktop from:

[https://www.docker.com/products/docker-desktop/](https://www.docker.com/products/docker-desktop/)

Carefully follow the official installation guide for your operating system.

After installation:

1. Start Docker Desktop.
2. Wait until Docker Engine is running.
3. Open a terminal (PowerShell, Bash, or VS Code Terminal).
4. Execute:

```bash
docker --version
docker compose version
```

If both commands return a version number, Docker is correctly installed.

Important:

If Docker cannot be installed or does not run properly:

* You may use Google Colab as a temporary alternative.
* However, your practices will be limited.
* Another valid alternative is to work with a classmate whose Docker environment works correctly.

---

## 1.3 Install Markdown Support

You must understand and use Markdown throughout the course.

Read and understand:

[https://www.markdownlang.com/intro/](https://www.markdownlang.com/intro/)

You are expected to:

* Write Markdown files.
* Structure documentation properly.
* Use headers, lists, code blocks, tables, and links.

---

# 2. Install Mandatory Visual Studio Code Extensions

Open Visual Studio Code and go to the Extensions panel.

Install the following extensions (copy and search each ID exactly as written):

```
bierner.markdown-mermaid
github.copilot-chat
github.vscode-pull-request-github
hashicorp.terraform
ms-azuretools.vscode-containers
ms-azuretools.vscode-docker
ms-python.debugpy
ms-python.python
ms-python.vscode-pylance
ms-python.vscode-python-envs
ms-toolsai.jupyter
ms-toolsai.jupyter-keymap
ms-toolsai.jupyter-renderers
ms-toolsai.vscode-jupyter-cell-tags
ms-toolsai.vscode-jupyter-slideshow
ms-vscode-remote.remote-containers
openai.chatgpt
redhat.vscode-yaml
yzane.markdown-pdf
```

After installation:

* Restart Visual Studio Code.
* Verify there are no extension errors.
* Ensure Python and Docker extensions are properly activated.

---

# 3. GitHub Account (Mandatory)

You must have a GitHub account.

If you do not have one, create a free account here:

[https://github.com/](https://github.com/)

The free plan is sufficient.

Once your account is created:

1. Log in.
2. Ensure your profile is properly configured.
3. Send your GitHub username to request access to the course organization.

You must request access to:

[https://github.com/MAHG-Enterprise-Data-Lab](https://github.com/MAHG-Enterprise-Data-Lab)

Access to the organization repositories is required for labs and assignments.

---

# 4. Recommended Additional Tools

## 4.1 draw.io (Highly Recommended)

For architecture diagrams and reference designs:

[https://www.drawio.com/](https://www.drawio.com/)

If possible, install the desktop version on your laptop.

---

## 4.2 Mermaid Documentation

For diagram-as-code:

[https://mermaid.js.org/](https://mermaid.js.org/)

You are expected to generate diagrams directly in Markdown using Mermaid.

---

## 4.3 Iconify Icon Library

For technical documentation and UI consistency:

[https://icon-sets.iconify.design/](https://icon-sets.iconify.design/)

---

# 5. Terminal Familiarization (Mandatory)

You must become comfortable using:

* PowerShell (Windows)
* Bash (macOS / Linux)
* VS Code Integrated Terminal

You should be able to:

* Navigate directories
* Execute CLI commands
* Run Docker commands
* Run Python scripts
* Execute Git commands

Practice basic commands such as:

```bash
cd
ls
dir
mkdir
git clone
docker ps
docker images
```

---

# 6. Familiarize Yourself with Visual Studio Code

Before Day 3, ensure you understand:

* How to open a folder as a workspace
* How to use the integrated terminal
* How to install extensions
* How to manage Python environments
* How to work with Docker containers
* How to open and execute Jupyter notebooks
* How to use Git integration inside VS Code

---

# 7. Verification Checklist

Before Day 3, you must confirm:

* Visual Studio Code installed and working
* All required extensions installed
* Docker Desktop installed and running
* GitHub account created
* Access requested to MAHG-Enterprise-Data-Lab
* Markdown basics understood
* Terminal usage familiarity achieved

If any of these items are incomplete, resolve them before the third day session.
