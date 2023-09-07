# vscode

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/vscode)
[![General Workflow](https://github.com/rolehippie/vscode/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/vscode/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/vscode/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/vscode/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/vscode/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/vscode/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/vscode)](https://github.com/rolehippie/vscode/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.vscode-blue)](https://galaxy.ansible.com/rolehippie/vscode)

> [!IMPORTANT]
> This role have been archived because of the lack of maintenance and because
> we are not actively using it anymore. If you are using this role feel free
> to fork and maintain it on your own. Maybe we will unarchive this repository
> in the future at some point, maybe not... Who knows...

Ansible role to install vscode editor.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [vscode_extra_users](#vscode_extra_users)
  - [vscode_general_users](#vscode_general_users)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### vscode_extra_users

List of extra users to install extensions

#### Default value

```YAML
vscode_extra_users: []
```

### vscode_general_users

List of general users to install extensions

#### Default value

```YAML
vscode_general_users: []
```

## Discovered Tags

**_vscode_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
