# Global Services for Local Development

This project contains a composition of services for local development.

## 🚀 Overview

The links in this instruction are set to default. If you have changed the settings, you need to make the appropriate
adjustments.

* [Proxy (traefik)](https://proxy.localhost).
* [Docker management admin panel (portainer)](https://portainer.localhost).
* [Database management admin panel (pgadmin)](https://pgadmin.localhost).
* [Redis management admin panel (redisinsight)](https://redis.localhost).
* [SMTP server for testing and viewing emails (mailpit)](https://mails.localhost).

## 🚀 Deployment

1. **Clone the repository:**
   ```bash
   git clone git@github.com:zhuolyan/local-global-env.git
   ```
2. **Enter the cloned directory:**
   ```bash
   cd local-global-env
   ```
3. **Create a configuration file from the example file:**
   ```bash
   cp .env.example .env
   ```
4. **(If necessary) Modify settings:**
   Ensure that all settings have the required values.
5. **Up the environment.**
   ```bash
   docker compose up -d
   ```

## 🛠️ Traefik

Currently requires no additional actions.

## 🛠️ Portainer

Upon first login, you need to set a password for the administrator role and configure it as needed.
[More about Portainer](https://docs.portainer.io).

## 🛠️ Pgadmin

Upon first login, you need to add the necessary database servers and configure them as needed. Default credentials:

* **Логін:** admin@localhost
* **Пароль:** Admin1234

## 🛠️ Redisinsight

Upon first login, you need to add the necessary database servers and configure them as needed.
[More about Redisinsight](https://redis.io/insight/).

## 🛠️ Mailpit

Currently requires no additional actions.
[More about Mailpit](https://mailpit.axllent.org/).
