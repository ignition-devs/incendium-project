# incendium-project

<!--- Badges --->
[![GitHub contributors](https://img.shields.io/github/contributors/thecesrom/incendium)](https://github.com/thecesrom/incendium/graphs/contributors)
![GitHub total downloads](https://img.shields.io/github/downloads/thecesrom/incendium/total)
![GitHub last commit (project)](https://img.shields.io/github/last-commit/thecesrom/incendium/project)
[![GitHub release (latest)](https://img.shields.io/github/v/release/thecesrom/incendium)](https://github.com/thecesrom/incendium/releases/latest)
[![time tracker](https://wakatime.com/badge/github/thecesrom/incendium.svg)](https://wakatime.com/badge/github/thecesrom/incendium)
[![Sourcery](https://img.shields.io/badge/Sourcery-enabled-brightgreen)](https://sourcery.ai)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Imports: isort](https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336)](https://pycqa.github.io/isort/)
[![Imports: flake8](https://img.shields.io/badge/%20imports-flake8-%231674b1?style=flat&labelColor=ef8336)](https://flake8.pycqa.org/en/latest/)
[![Imports: pydocstyle](https://img.shields.io/badge/%20imports-pydocstyle-%231674b1?style=flat&labelColor=ef8336)](https://www.pydocstyle.org/en/stable/)
[![linting: pylint](https://img.shields.io/badge/linting-pylint-yellowgreen)](https://github.com/PyCQA/pylint)
[![Join us on GitHub discussions](https://img.shields.io/badge/github-discussions-informational)](https://github.com/thecesrom/incendium/discussions)

(/inˈken.di.um/)

_noun_.

1. A fire, inferno, conflagration; heat; torch.
1. (heat of) passion, vehemence

:package: Package that extends and wraps some functions from Ignition's Scripting API.

For more information, please refer to the [Wiki](https://github.com/thecesrom/incendium/wiki).

## Installing `incendium` as a Project on your Gateway

To install `incendium` on your Gateway follow these steps:

1. Download **incendium.x.x.x.zip** from the [latest release](https://github.com/thecesrom/incendium-project/releases/latest) or from [Ignition Exchange](https://inductiveautomation.com/exchange/2104)
1. Browse to your Ignition Gateway (version 8.0+)
1. Go to **Config > Projects** and click on **Import project...**
1. Click on **Choose File** and select the downloaded ZIP file
1. Enter **incendium** as the **Project Name**
    - If you're replacing a previous version, make sure to check Allow Overwrite
1. Click on **Import**

Alternatively you could follow the instructions for cloning the `project` branch directly into `$IGNITION_DIR/data/projects` found [here](#cloning-this-repo).

## Cloning this repo

If you would like to clone this repo to get the latest version directly under `$IGNITION_DIR/data/projects`, follow these steps:

1. Open your Terminal
1. Switch to `$IGNITION_DIR/data/projects`
1. Run any of the following commands

    - HTTPS

        ```bash
        git clone https://github.com/thecesrom/incendium-project.git incendium
        ```

    - SSH

        ```bash
        git clone git@github.com:thecesrom/incendium-project.git incendium
        ```

    - GitHub CLI

        ```bash
        gh repo clone thecesrom/incendium-project incendium
        ```

1. And `git pull` to get the latest changes

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md).

## Contributors

Thanks to everyone who has contributed to this project.

Up-to-date list of contributors can be found [here](https://github.com/thecesrom/incendium-project/graphs/contributors).

## License

See the [LICENSE](https://github.com/thecesrom/incendium-project/blob/HEAD/LICENSE).

## Code of conduct

See [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md).
