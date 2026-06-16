# Git Branching Practice

## Hotfix Notes
A hotfix is a small urgent fix made from main.

## Feature Notes
A feature branch is where I work on a change without touching main directly.


## Pull Request Notes
A pull request is a proposed change from one branch into another branch.

A good PR explains what changed, why it changed, and how someone can review it.

## GitHub Dependency Graph and SBOM Notes

GitHub's dependency graph shows the packages a repository depends on. It can export that dependency information as an SBOM.

An SBOM is a Software Bill of Materials: a machine-readable list of software components and dependencies.

GitHub's SBOM export is useful because it gives me a repo-level dependency inventory. GitHub's export is SPDX JSON.

For Concert practice, the more important path is the package SBOM path, which uses CycloneDX.

Plain-English difference:
- GitHub export = SPDX SBOM from the repository dependency graph.
- Concert package SBOM path = CycloneDX SBOM used for package/software composition analysis.

Today's takeaway:
GitHub's export helps me understand SBOMs, but it is not the main Concert ingestion format I should practice. For Concert, I should pay more attention to CycloneDX package SBOMs.

