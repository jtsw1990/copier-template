# copier-template

Testing repo for copier templating

## Initial setup

- `pip install pipx` for standalone tool downloads
- `pipx ensurepath` to set any pipx installation to PATH
- `pipx install poetry` for dependency management

- `winget install --id Casey.Just --exact`

## Copying template 

- Run `copier copy --vcs-ref develop https://github.com/jtsw1990/copier-template.git path_to_copy`
- Answer prompts
- Navigate to repository folder
- Run `just init-poetry` to install dependencies