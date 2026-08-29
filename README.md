# awesome-vault-tools with stars

Awesome tools around HashiCorp Vault

# UI

* <https://github.com/Caiyeon/goldfish> ⚠️ Archived - A HashiCorp Vault UI panel written with VueJS and Vault native Go API.
  * Demo: <https://vault-ui.io>
* <https://github.com/djenriquez/vault-ui> ⚠️ Archived Vault-UI — A beautiful UI to manage your Vault, written in React.
* <https://github.com/adobe/cryptr> ⚠️ Archived - Cryptr is a GUI for Hashicorp's Vault.
* <https://github.com/nyxcharon/vault-ui> ⚠️ Archived -  A webapp for working with Hashicorp's Vault.

# Plugins

* <https://github.com/sethvargo/vault-secrets-gen> ⚠️ Archived - A Vault secrets plugin for generating high entropy passwords and passphrases.
* <https://github.com/martinbaillie/vault-plugin-secrets-github> ⭐ 318 | 🐛 10 | 🌐 Go | 📅 2025-11-13 - A Vault secrets plugin for creating ephemeral, finely-scoped GitHub access tokens.
* <https://github.com/sethvargo/vault-auth-slack> ⚠️ Archived - The Vault Auth Slack method is a Vault auth method plugin for authenticating users via Slack. The plugin can run in multiple different "modes" depending on your desired user workflow and risk tolerance. This is both a real custom Vault auth method, and an example of how to build, install, and maintain your own Vault auth plugin.
* <https://github.com/fcantournet/kubernetes-flexvolume-vault-plugin> ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2019-06-10 - A kubernetes flexvolume plugin that injects vault tokens at pod creation
* <https://github.com/idcmp/vault-plugin-secrets-webhook> ⭐ 14 | 🐛 1 | 🌐 Go | 📅 2018-06-17 - Use Vault ACLs to control access to other REST APIs.
* <https://github.com/gites/vault-auth-file> ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2025-07-02 - HashiCorp Vault authentication plugin for authenticating via Unix password like file.
* <https://github.com/nhuff/vault-plugin-auth-chefnode> ⭐ 4 | 🐛 1 | 🌐 Go | 📅 2020-12-08 - The "chef-node" auth backend allows Nodes registered with a Chef server to authenticate using their private keys.
* <https://github.com/criteo/vault-auth-plugin-chef> ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2021-10-15 - Vault Authentication plugin for Chef.
* <https://github.com/svagner/vault-auth-chef> ⭐ 0 | 🐛 2 | 🌐 Go | 📅 2019-08-27 - Chef authorization plugin for Hashicorp Vault.

# Ops

* <https://github.com/spectralops/teller> ⭐ 3,226 | 🐛 51 | 🌐 Rust | 📅 2026-01-27 - secrets management tool for developers, integrate Vault with any other secret and key store
* <https://github.com/starkandwayne/safe> ⭐ 421 | 🐛 19 | 🌐 Go | 📅 2024-02-16 - A Vault CLI.
* <https://github.com/avantoss/vault-infra> ⭐ 228 | 🐛 0 | 🌐 HCL | 📅 2026-04-29 -  Packer and Terraform to create a fully automated and HA Vault deployment.
* <https://github.com/seatgeek/hashi-helper> ⭐ 185 | 🐛 12 | 🌐 Go | 📅 2024-06-25 - A tool meant to enable Disaster Recovery and Configuration Management for Consul and Vault clusters, by exposing configuration via a simple to use and share hcl format.
* <https://github.com/jaxxstorm/hookpick> ⚠️ Archived - A tool to manage some operational concepts of Hashicorp Vault.
* <https://github.com/jaxxstorm/unseal> ⚠️ Archived - **\[deprecated]** A command line tool to unseal multiple Hashicorp Vault servers quickly.
* <https://github.com/bincyber/pkictl> ⭐ 59 | 🐛 0 | 🌐 Python | 📅 2019-11-19 - CLI tool for declaratively configuring and provisioning PKI secrets in HashiCorp Vault via Yaml.
* <https://github.com/cloudwatt/vault-sync> ⭐ 31 | 🐛 3 | 🌐 Go | 📅 2017-09-19 - Vault-sync is a command line utilty for provisioning a Hashicorp's Vault from configuration files. Essentially it was written so we could source control our users, policies, backends and secrets, synchronize the vault against them and rebuild on-demand if required.
* <https://github.com/UKHomeOffice/vaultctl> ⭐ 30 | 🐛 2 | 🌐 Go | 📅 2016-03-16 - Vaultctl is a command line utilty for provisioning a Hashicorp's Vault from configuration files. Essentially it was written so we could source control our users, policies, backends and secrets, synchronize the vault against them and rebuild on-demand if required.
* <https://github.com/martinbaillie/vaultsign> ⭐ 30 | 🐛 12 | 🌐 Rust | 📅 2023-03-11 - Sign and verify `git` commits and tags using Vault.
* <https://github.com/hootsuite/vault-ctrl-tool> ⭐ 27 | 🐛 6 | 🌐 Go | 📅 2023-08-30 - Outsource authentication, secrets fetching, and lease management for services.
* <https://github.com/paywithcurl/vault-update> ⭐ 5 | 🐛 1 | 🌐 Go | 📅 2018-02-15 - Tool for updating a single key in vaullt secret.
* <https://gitlab.com/msvechla/vaultbot> - A certbot like tool to provision certificates from a Vault managed CA.

# Users

* <https://github.com/Lingrino/vaku> ⭐ 160 | 🐛 1 | 🌐 Go | 📅 2026-08-24 - Vaku is a CLI and Go API that extends the official Vault CLI and API with useful high-level functions such as the ability to copy, move, and search vault paths and folders.
* <https://github.com/apptio/breakglass> ⚠️ Archived - Breakglass is a tool that will make API calls to Hashicorp Vault servers and then retrieve credentials for you. It's designed to ease the process of getting elevated login credentials for a variety of servers. It currently supports MySQL servers and SSH Command line access.
* <https://github.com/Mykolaichenko/vaulter> ⭐ 26 | 🐛 2 | 🌐 Go | 📅 2020-01-14 - Vaulter extends default Hashicorp Vault client, implements additional methods like list all backend path, dynamically read value, search in all backend and so on.
* <https://github.com/ilijamt/vht/> ⭐ 8 | 🐛 8 | 🌐 Go | 📅 2026-04-03 - vht extends the functionality of Vault and adds searching, tree and recursive deletes.

# K8s

*Note: There is now official plugin for k8s: <https://www.vaultproject.io/docs/auth/kubernetes.html>*

* <https://github.com/Boostport/kubernetes-vault> ⚠️ Archived - The Kubernetes-Vault project allows pods to automatically receive a Vault token using Vault's AppRole auth backend.
* <https://github.com/ricoberger/vault-secrets-operator> ⭐ 685 | 🐛 15 | 🌐 Go | 📅 2026-08-13 - Create Kubernetes secrets from Vault for a secure GitOps based workflow.
* <https://github.com/kelseyhightower/vault-controller> ⭐ 443 | 🐛 11 | 🌐 Go | 📅 2019-10-04 - The Vault Controller automates the creation of Vault tokens for Kubernetes Pods. This repo includes a set of hands-on tutorials and example programs you can use to try out the Vault Controller.
* <https://github.com/cruise-automation/daytona> ⭐ 326 | 🐛 17 | 🌐 Go | 📅 2025-04-28 - This is intended to be a lighter, alternative, implementation of the Vault client CLI primarily for services and containers. Its core features are the ability to automate authentication, fetching of secrets, and automated token renewal. Supports K8s, AWS IAM and GCP IAM auth methods.
* <https://github.com/sethvargo/vault-kubernetes-authenticator> ⚠️ Archived - An app and container for authenticating services to HashiCorp Vault's via the Kubernetes auth method.
* <https://github.com/UKHomeOffice/vault-sidekick> ⭐ 194 | 🐛 21 | 🌐 Go | 📅 2026-07-03 - Vault Sidekick is a add-on container which can be used as a generic entry-point for interacting with Hashicorp Vault service, retrieving secrets (both static and dynamic) and PKI certs. The sidekick will take care of renewal's and extension of leases for you and renew the credentials in the specified format for you.
* <https://github.com/uswitch/vault-creds> ⭐ 84 | 🐛 7 | 🌐 Go | 📅 2026-07-22 - Sidecar container for requesting dynamic Vault database secrets.
* <https://github.com/postfinance/vault-kubernetes> ⭐ 79 | 🐛 11 | 🌐 Go | 📅 2026-07-03 - Authenticate services to @hashicorp Vault via the Kubernetes auth method.
* <https://github.com/uswitch/vault-webhook> ⭐ 25 | 🐛 0 | 🌐 Go | 📅 2026-04-27 - Kubernetes Mutating Webhook to inject Vault-Creds Sidecar into pods.
* <https://github.com/postfinance/kubectl-vault_sync> ⚠️ Archived - Kubernetes plugin to synchronize secrets from vault as kubernetes secrets.
* <https://github.com/banzaicloud/bank-vaults> ⚠️ Archived - A Vault swiss-army knife: Go client with automatic token renewal, Kubernetes support, dynamic secrets, multiple unseal options and more. A CLI tool to init, unseal and configure Vault (auth methods, secret engines). A K8s operator.
* <https://github.com/keyparty/vault-init> ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2017-01-15 - K8s Init Container for Vault Token Generation and Retrieval.

# Other

* <https://github.com/channable/vaultenv> ⭐ 466 | 🐛 18 | 🌐 Haskell | 📅 2026-06-04 - Launch processes with Vault secrets in the environment.
* <https://github.com/asteris-llc/vaultfs> ⭐ 131 | 🐛 6 | 🌐 Go | 📅 2016-11-29 - VaultFS mounts arbitrary Vault prefixes in a FUSE filesystem. It also provides a Docker volume plugin to the do the same for your containers.
* <https://github.com/joemiller/vault-token-helper> ⭐ 117 | 🐛 17 | 🌐 Go | 📅 2023-04-05 - Vault Token Helper for macOS, Linux and Windows with support for secure token storage and multiple Vault instances
* <https://github.com/gites/vault-cert-helper> ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2019-01-13 -
  Vault-cert-helper is a simple tool intended to help you provision certificates from on-premises Vault to services running in AWS and GCE (or any other S3 compatible cloud).
* <https://github.com/SorsOps/vault-env> - A config based token retrieval system

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-29._
