# DevSecOps Lab

This repository is created for the AWS DevSecOps laboratory experiment.

## Tools Used

- AWS CodeBuild
- AWS CodePipeline
- GitHub
- Semgrep
- Trivy

## Security Scanning

The project uses:

- **Semgrep** for static application security testing (SAST)
- **Trivy** for vulnerability scanning

The `buildspec.yml` file contains the CodeBuild security scanning configuration.

## Project Purpose

The purpose of this project is to demonstrate security scanning and automated build processes using AWS DevSecOps services.
