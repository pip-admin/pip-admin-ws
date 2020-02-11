# <img src="https://github.com/pip-webui/pip-webui/raw/master/doc/Logo.png" alt="Pip.WebUI Logo" style="max-width:30%"> <br/> Workspace for Pip.Admin tools

This is a workspace for [Pip.Admin](https://gitlab.com/pip-admin/pip-admin-ws)Pip.Admin tools:

The workspace enables build, test, and release across the following projects:

* **pip-admin-shell** - Shell for Pip.Admin applications and samples
* **pip-admin-system** - System administration module
* **pip-admin-content** - Content management module
* **pip-admin-support** - Product support module
* **pip-admin-app** - Generic Pip.Admin application

## Installation

- Clone this workspace to local disk
```bash
> git clone https://www.gitlab.com/pip-admin/pip-admin-ws.git
```

- Clone components and initialize the workspace
```bash
> pipuse <Path to this workspace>
> piptask init -workspace
```

## Usage

- Setting default workspace
```bash
> pipuse <Path to this workspace>
```

- Build all components
``` bash
> piptask test -all
```

- Test all components
``` bash
> piptask test -all
```

- Check out changes from remote repository
```bash
> piptask pull -all
```

- Check in changes to remote repository
```bash
> piptask push -m <Changes comment> -all
```

## Acknowledgements

The Pip.Admin workspace is created and maintained by **Sergey Seroukhov**