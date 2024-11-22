# Dopsctl
A comprehensive tool for swiftly deploying Rancher products (RKE, RKE2, K3s, Rancher), while also managing DevOps operations like DNS servers, proxy servers, local image registries, and more.


## Description

A comprehensive tool for swiftly deploying Rancher products (RKE, RKE2, K3s, Rancher), while also managing DevOps operations like DNS servers, proxy servers, local image registries, and more. It utilizes the GitHub API to fetch and deploy the latest or selected releases, while offering advanced features such as cluster data retrieval for health verification and a menu-driven command-line utility for TCP dump packet capture.

## Goals

The goal of the project is to simplify the deployment of required products and enable easy replication of environments with exact product versions. Assist engineers in efficiently troubleshooting live Kubernetes environments.
Features

**Quick Deployment:** Simplifies the deployment of Rancher products (RKE, RKE2, K3s, Rancher) and supporting tools like Helm and kubectl on Ubuntu OS.

**Version Fetching:** Utilizes the GitHub API to fetch and deploy the latest or selected releases.

**Menu-Driven Interface:** Provides an intuitive, menu-driven CLI for easy installation and configuration.

**Architecture Detection:** Automatically detects system architecture (AMD or ARM) and deploys compatible products.

**Installation Validation:** Ensures the successful completion of installations with built-in checks.

**Live Environment Troubleshooting:** Facilitates troubleshooting by analyzing cluster health, fetching logs for specific time windows, and understanding network status using a TCP dump utility.

**Future Enhancements:** Plans to introduce more options and extend features for greater flexibility.

