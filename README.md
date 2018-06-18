Repository for Environment Configurator
===

Automate bootstrapping new Symfony Flex applications.

## Install

```bash
composer global require covex-nn/environment
composer global require covex-nn/environment-repository
```

## Usage

Install Symfony Templating and enable `templating` in `config/packages/framework.yaml`:

    composer env:apply templating

Install Sonata Admin with FOSUserBundle and user management:

    composer env:apply admin

Create `docker-compose` local environment:

    composer env:apply docker-compose

Install `docker-composer` environment, equal to [covex-nn/docker-symfony](https://github.com/covex-nn/docker-workflow-symfony)

    composer env:apply docker-ci

