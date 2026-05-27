# PSUSphere - Containerized Deployment Infrastructure

This repository houses the independent Docker infrastructure configurations required to deploy, run, and evaluate the PSUSphere application platform across isolated container environments.

## Folder Structure Components
* **Root Directory**: Contains the baseline build blueprints (`Dockerfile`, `docker-compose.yml`) used to compile local image layers.
* **`/for_client/`**: Houses the standalone deployment template configured for automated pulling from remote cloud registries.
* **`/for_client/sample_data.json`**: A comprehensive testing fixture dataset pre-filled with foundational colleges, specialized programs, student organizations, and profile data records.

## Running the Application (Target/Client Machine Mode)
To launch the active application web interface from scratch without copying over raw Django project development source code, complete the
