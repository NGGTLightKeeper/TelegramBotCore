# TelegramBotCore
This repository contains **TelegramBotCore**, a foundation for building Telegram bots in Python, integrated with a Django backend for robust API and authentication capabilities.

## Core Versions

  1.  **CORE_MIN (Minimal)**
      *   A lightweight version that includes the essential components: `pyTelegramBotAPI` for interacting with the Telegram API, and a Django backend with Django Rest Framework, Djoser for authentication (JWT support), and social network integration.
      *   **Feature**: It is database-agnostic, allowing you to choose and install the appropriate database connector for your needs (e.g., for PostgreSQL, SQLite, etc.).
  
  2.  **CORE (Standard)**
      *   Includes all the features of `CORE_MIN` with added out-of-the-box support for **MySQL**.
      *   This is the recommended version for most projects that require a Telegram bot with a standard web backend using MySQL.
  
  3.  **CORE_FULL (Full)**
      *   The most comprehensive version, containing all components from `CORE`.
      *   Additionally, it includes:
          *   `numpy` and `numba` for high-performance computing.
          *   `Flask` as an additional lightweight web framework.
          *   `yt_dlp` for video downloading capabilities.
      *   This version is designed for complex bots that require intensive data processing, scientific calculations, or advanced media handling.

## Included Libraries

  1.  **CORE_MIN (Minimal)**:
      *   asgiref==3.9.1
      *   bleach==6.2.0
      *   certifi==2025.8.3
      *   cffi==1.17.1
      *   channels==4.3.1
      *   charset_normalizer==3.4.3
      *   cryptography==45.0.7
      *   datetime==5.5
      *   defusedxml==0.7.1
      *   django==5.2.6
      *   django-cors-headers==4.7.0
      *   djangorestframework==3.16.1
      *   djangorestframework-simplejwt==5.5.1
      *   djoser==2.3.3
      *   idna==3.10
      *   llvmlite==0.44.0
      *   markdown==3.9
      *   martor==1.7.15
      *   oauthlib==3.3.1
      *   pillow==11.3.0
      *   pycparser==2.22
      *   pyjwt==2.10.1
      *   pyTelegramBotAPI==4.29.1
      *   python3-openid==3.2.0
      *   pytz==2025.2
      *   requests==2.32.5
      *   requests-oauthlib==2.0.0
      *   setuptools==80.9.0
      *   six==1.17.0
      *   social-auth-app-django==5.5.1
      *   social-auth-core==4.7.0
      *   sqlparse==0.5.3
      *   tzdata==2025.2
      *   ua-parser==1.0.1
      *   ua-parser-builtins==0.18.0.post1
      *   urllib3==2.5.0
      *   user-agents==2.2.0
      *   webencodings==0.5.1
      *   wheel==0.45.1
      *   zipp==3.23.0
      *   zope.interface==7.2
  
  3.  **CORE (Standard)**
  - Includes all from `CORE_MIN`
  - Additionally libraries:
      *   mysql==0.0.3
      *   mysql-connector-python==9.4.0
      *   mysqlclient==2.2.7
  
  4.  **CORE_FULL (Full)**
  - Includes all from `CORE`
  - Additionally libraries:
      *   blinker==1.9.0
      *   click==8.2.1
      *   colorama==0.4.6
      *   flask==3.1.2
      *   flask_cors==6.0.1
      *   itsdangerous==2.2.0
      *   jinja2==3.1.6
      *   markupsafe==3.0.2
      *   numba==0.61.2
      *   numpy==2.2.6
      *   Werkzeug==3.1.3
      *   yt_dlp==2025.9.5

## Requirements
  - Python 3.13

## Supported Platforms
  - Windows
  - Linux
  - macOS (Not Tested)

## Installation and Usage
  
  1.  Clone the repository to your local machine:
      ```bash
      git clone https://github.com/NGGTLightKeeper/TelegramBotCore.git
      cd TelegramBotCore
      ```
  2.  Choose the core version you need (`CORE_MIN`, `CORE`, or `CORE_FULL`).
  3.  Navigate to the corresponding directory. For example, for the standard version:
      ```bash
      cd CORE
      ```
  4.  Run the installation script corresponding to your operating system:
      *   **For Windows:**
          ```bash
          install_core.bat
          ```
      *   **For Linux/macOS:**
          ```bash
          chmod +x install_core.sh
          ./install_core.sh
          ```

## License
This project is licensed under the [MIT License](LICENSE.md).
