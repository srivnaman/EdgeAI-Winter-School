# EdgeAI Winter School – Repository Usage Guide

This repository contains the code and resources used for the **Edge AI Winter School**.
All environment setup, dependency management, and configuration are handled **automatically** using the **uv** package manager.

---

## Prerequisites

Before proceeding, ensure the following are available on your system:

* **Python 3.11+**
* **uv package manager**

If `uv` is not installed, follow the official installation instructions:
[https://docs.astral.sh/uv/](https://docs.astral.sh/uv/)

---

## Step 1: Clone the Repository

Clone the repository using SSH:

```bash
git clone git@github.com:srivnaman/EdgeAI-Winter-School.git
```

Navigate into the project directory:

```bash
cd EdgeAI-Winter-School
```

---

## Step 2: Sync the Environment Using `uv`

Once inside the repository, run:

```bash
uv sync
```

This command will automatically:

* Create an isolated virtual environment
* Install all required dependencies
* Resolve and lock package versions
* Apply all necessary configuration

No manual setup is required.

---

## Configuration Management

✔ All environment variables
✔ Dependency versions
✔ Runtime configuration

are **handled automatically** as part of the `uv sync` process.

You **do not** need to:

* Create virtual environments manually
* Install dependencies using `pip`
* Set up configuration files

---

## Running the Project

After a successful sync, you can start using the project as instructed during the Winter School sessions.
Any runnable scripts, notebooks, or services will work out of the box once the environment is synced.

(Refer to session-specific instructions if provided.)

---

## Troubleshooting

If you face issues:

1. Ensure `uv` is correctly installed:

   ```bash
   uv --version
   ```
2. Ensure you are using a supported Python version:

   ```bash
   python --version
   ```
3. Re-run:

   ```bash
   uv sync
   ```

---

## Support

For issues, questions, or clarifications related to this repository, please  contact the Winter School organizers.

