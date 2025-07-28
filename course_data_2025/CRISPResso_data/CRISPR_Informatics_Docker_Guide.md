
<img src="https://coursesandconferences.wellcomeconnectingscience.org/wp-content/themes/wcc_courses_and_conferences/dist/assets/svg/logo.svg" width="300" height="50">

# CRISPR Informatics 2025 – Course Setup & Docker Installation Guide

## Welcome Message for Participants

We'll be using **GitHub** throughout the CRISPR Informatics course to access all practical materials, including datasets, code notebooks, and slides. GitHub is an online repository system—think of it as a central storage and sharing platform for everything you'll need.

You do **not need a GitHub account** to access the materials. Everything will be shared via direct links, and we will guide you during each session on how to navigate and use it, so there's no need to worry if you’re new to GitHub.

To get started, please read the following **Informatics Guide**, which outlines:
- Software installation requirements
- Datasets per session
- Daily preparation schedule

👉 [CRISPR Informatics 2025 – Informatics Guide](https://github.com/WCSCourses/CRISPR_informatics_2025/blob/main/InformaticsGuide.md)

### Installation Notes
- We recommend installing software **in advance or at least a day before your session**.
- Some software (like Docker or SnapGene Viewer) **requires admin privileges**, so please check with your IT support if needed.
- **Wait to download datasets until the day of the session**, to avoid filling up your device’s storage unnecessarily.
- You’ll receive **daily reminders** about what needs to be done.
- If you encounter installation issues, we’ll be available to help during the **morning break each day**.

---

## Docker Installation Guide

Docker is required if you wish to run CRISPResso analysis locally. Below are step-by-step instructions for installing Docker on Windows, macOS, and Linux systems.

### Common Pre-requisites
- A stable internet connection  
- Administrative privileges on your computer  
- Basic familiarity with the terminal or command-line interface (CLI)

---

### Installing Docker on Windows

1. Visit: [Install Docker on Windows](https://docs.docker.com/desktop/install/windows-install/)
2. Use **Windows 10/11 Pro, Enterprise, or Education** (WSL2 required).
3. Enable virtualization in BIOS and install WSL2: [WSL2 Setup](https://docs.docker.com/desktop/windows/wsl/)
4. Download and install Docker Desktop.
5. Restart your computer if prompted.
6. Open PowerShell and run:

   ```bash
   docker run hello-world
   ```

---

### Installing Docker on macOS

1. Visit: [Install Docker on Mac](https://docs.docker.com/desktop/install/mac-install/)
2. Select version based on chip (Apple Silicon or Intel).
3. Download and drag Docker Desktop into Applications.
4. Open Docker Desktop.
5. Verify installation in Terminal:

   ```bash
   docker run hello-world
   ```

---

### Installing Docker on Linux (Ubuntu/Debian)

1. Visit: [Install Docker on Ubuntu](https://docs.docker.com/engine/install/ubuntu/)
2. In terminal, add Docker’s official GPG key and repo.
3. Install Docker Engine via `apt`.
4. (Optional) Add your user to `docker` group to avoid using `sudo`.
5. Verify installation:

   ```bash
   docker run hello-world
   ```

---

## Additional Resources

- [Docker Curriculum for Beginners](https://docker-curriculum.com/)
- [Getting Started – Official Docs](https://docs.docker.com/)
- [YouTube: Docker Tutorial (Beginner Friendly)](https://www.youtube.com/watch?v=b0HMimUb4f0)
- [How to Install Docker on Windows (2025)](https://www.youtube.com/watch?v=ZyBBv1JmnWQ)
- [Install Docker on Windows 11 – Updated](https://www.youtube.com/watch?v=JBEUKrjbWqg)
- [Install Docker on Ubuntu (Video)](https://www.youtube.com/watch?v=cqbh-RneBlk)
- [Install Docker on macOS](https://www.youtube.com/watch?v=-EXlfSsP49A)

---

**Note:** If you are using a workplace-managed device, make sure to contact your IT team in advance to get installation permissions or assistance.
