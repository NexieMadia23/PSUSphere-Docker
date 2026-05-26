# PSUSphere - Containerized Deployment Activity

This repository contains the independent Docker infrastructure blueprints to run the PSUSphere application environment seamlessly on any system.

## Project Structure Overview
 Root files Used for building, managing, and updating development layers.
 `for_client` Contains the localized client deployment template using cloud image pulling.

## Deployment Setup for ProductionClient Machines
To spin up the functional web dashboard from scratch without the raw Django source files, execute the following actions

1. Enter the target client runtime directory
   ```bash
   cd for_client