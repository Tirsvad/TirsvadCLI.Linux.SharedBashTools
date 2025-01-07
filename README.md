[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<br />
<div align="center">
    <a href="https://github.com/TirsvadCLI/Linux.Distribution">
        <img src="logo/logo.png" alt="Logo" width="80" height="80">
    </a>
</div>

# Shared Bash Tools

Collection of bash tools

## Table of Contents

- [Download Dependencies](#download-dependencies)
  - [Features](#features)
  - [Prerequisites](#prerequisites)
  - [Usage](#usage)
- [License](#license)
- [Contributors](#contributors)

## Download Dependencies

`DownloadDependencies.sh` is a Bash script designed to automate the process of downloading and managing project dependencies from GitHub. The script ensures that the necessary dependencies are retrieved and properly set up in the specified vendor directory.

### Features

- Downloads dependencies using a package manager from GitHub.
- Extracts the required files to the appropriate directory.
- Verifies the existence of necessary scripts post-download.
- Logs actions and errors in the terminal.

### Prerequisites

- Ensure that `curl` is installed on your system.
- Set the `TCLI_PATH_VENDOR` environment variable to the target directory for storing dependencies.
- Optionally, have logging setup with `TCLI_LINUX_LOGGER_LOADED`.

### Usage

To download a dependency, use the following command:

```bash
download_dependencies <dependency_name> <script_name>
```

## License

This project is licensed under the GNU GPL 3 License. See the [LICENSE](LICENSE) file for more details.

## Contributors

See the [CONTRIBUTING.md](CONTRIBUTING.md) file for information on how to contribute to this project.

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/TirsvadCLI/Linux.SharedBashTools?style=for-the-badge
[contributors-url]: https://github.com/TirsvadCLI/Linux.SharedBashTools/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/TirsvadCLI/Linux.SharedBashTools?style=for-the-badge
[forks-url]: https://github.com/TirsvadCLI/Linux.SharedBashTools/network/members
[stars-shield]: https://img.shields.io/github/stars/TirsvadCLI/Linux.SharedBashTools?style=for-the-badge
[stars-url]: https://github.com/TirsvadCLI/Linux.SharedBashTools/stargazers
[issues-shield]: https://img.shields.io/github/issues/TirsvadCLI/Linux.SharedBashTools?style=for-the-badge
[issues-url]: https://github.com/TirsvadCLI/Linux.SharedBashTools/issues
[license-shield]: https://img.shields.io/github/license/TirsvadCLI/Linux.SharedBashTools?style=for-the-badge
[license-url]: https://github.com/TirsvadCLI/Linux.SharedBashTools/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/jens-tirsvad-nielsen-13b795b9/
