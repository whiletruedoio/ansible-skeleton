<!--
reference: https://www.makeareadme.com/
reference: https://commonmark.org/
-->

[![Cirrus CI - Base Branch Build Status](https://img.shields.io/cirrus/github/whiletruedoio/ansible-skeleton?logo=Cirrus-ci)](https://cirrus-ci.com/github/whiletruedoio/ansible-skeleton)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/whiletruedoio/ansible-skeleton?logo=GitHub&label=Release&sort=semver)](https://github.com/whiletruedoio/ansible-skeleton/releases)
[![GitHub issues](https://img.shields.io/github/issues/whiletruedoio/ansible-skeleton)](https://github.com/whiletruedoio/ansible-skeleton/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/whiletruedoio/ansible-skeleton)](https://github.com/whiletruedoio/ansible-skeleton/pulls)
[![GitHub license](https://img.shields.io/github/license/whiletruedoio/ansible-skeleton)](https://github.com/whiletruedoio/ansible-skeleton/blob/main/LICENSE)

# Ansible Skeleton

Skeletons to be used to create new Ansible collections and roles.

## Motivation

Creating new Ansible collections and roles requires some boilerplate. The
default skeletons are sufficient for small collections, but lack a lot of
possibibilities and guidance. As a developer, I want to get started without
copy/pasting lots of content from another repository and maintain a common
design of collections and roles.

## Description

The repository provides skeletons, which can be used from the `ansible-galaxy`
command to create new collections and roles. For now, the design allows roles
to be created as part of a collection. You can also find lots of documentation
and guidance in the skeletons to get started with your first collection or
role.

## Usage

We are really happy, that you consider using our software. In case you want to
install and run the code on your machine, please check out this section.

### Requirements

The collection and role skeleton are designed to be used with Ansible >= 2.10.
Older versions may work, but lack certain features like argument specifications.

### Install

To use the skeletons, you need to clone the repository or download a
[release](https://github.com/whiletruedoio/ansible-skeleton/releases) and unpack
it to your desired directory.

```sh
# Clone the repository
$ git clone https://github.com/whiletruedoio/ansible-skeleton.git
```

Now, change to your project directory and create a new collection or role.

```sh
# Create a collection
$ ansible-galaxy collection init --collection-skeleton /path/to/skeleton/collection collection_name

# Create a role
$ ansible-galaxy role init --role-skeleton /path/to/skeleton/role role_name
```

Unfortunately, there is no easy way to persist this for now. Please check the
[issue #76643](https://github.com/ansible/ansible/issues/76643) for more
information.

### Documentation

You can also have a look at the upstream documentation for some more detailed
information about skeletons.

- [Developing Collections](https://docs.ansible.com/ansible/latest/dev_guide/developing_collections.html)
- [Creating Collections](https://docs.ansible.com/ansible/latest/dev_guide/developing_collections_creating.html)
- [Creating Roles](https://galaxy.ansible.com/docs/contributing/creating_role.html)
- [Ansible Galaxy CLI](https://docs.ansible.com/ansible/latest/cli/ansible-galaxy.html)

## Contribute

Thank you so much for considering to contribute! We are happy, when someone is
joining the hard work.

### Issues

Issues and Pull Requests are handled on a regular basis. Please be aware, that
we may reach out to you, ask you to provide additional resources or want to
discuss the issue a little, before planning it.

- [Bugs and Feature Requests](https://github.com/whiletruedoio/ansible-skeleton/issues)
- [Pull Requests](https://github.com/whiletruedoio/ansible-skeleton/pulls)

### Develop

Providing code to this repository is pretty straight forward. Open an issue,
so we can discuss the bug/feature and start working on it afterwards. You just
need to open the pull request afterwards and that's it.

It is also strongly recommended to read the
[Contribution Guideline](https://github.com/whiletruedoio/.github/blob/main/docs/CONTRIBUTING.md)
beforehand.

### Changelog

We are maintaining a [changelog](CHANGELOG.md) for repositories. Normally, the
developers will update the changelog, according to
[keepachangelog.com](https://keepachangelog.com/).

### Test

To ensure a high quality and functionality, we want to carefully test our
software. The provided code is automatically tested as described in the
[.cirrus.yml](.cirrus.yml).

## License

Except otherwise noted, all work is [licensed](LICENSE) under a
[BSD-3-Clause License](https://opensource.org/licenses/BSD-3-Clause).

## Contact

Please feel free to reach out to us and the community. We also recommend to read
and understand the
[Code of Conduct](https://github.com/whiletruedoio/.github/blob/main/docs/CODE_OF_CONDUCT.md)
beforehand.

- Site: <https://while-true-do.io>
- Blog: <https://blog.while-true-do.io>
- Code: <https://github.com/whiletruedoio>
- Chat: [libera.chat #whiletruedoio](https://web.libera.chat/gamja/#whiletruedo)
- Mail: [hello@while-true-do.io](mailto:hello@while-true-do.io)
