# .github Repository Usage Guide

## Purpose
The `.github` directory within a GitHub repository serves as a special storage space for community health files and various resources that guide contributions and support for the project. This includes issue templates, pull request templates, code of conduct, and more.

## Visibility
If you create a `.github` repository and include issue templates, these will be automatically applied to all repositories that do not have their own `.github` directory. For example, a generic bug report template in your `.github` repo will be utilized in any other repository without its own `.github` setup.

## Organizations
Organizations can also utilize the `.github` repository functionality similarly to individual repos. Additionally, organization profiles can be customized by adding a README that appears on the organization page on GitHub. This README should be placed in the `.github-private` repository under `/profile/README.md`.

## Customization
To customize your organization's profile with an internal README visible only to members, create a file named `README.md` within the `.github-private` directory, specifically located at `/profile/README.md`. This ensures that the README is accessible only to organization members.

## Usage
Effectively utilize the `.github` repository by adding necessary files such as issue templates, pull request templates, and code of conduct. These can be placed either in the root `.github` directory or within the shared `.github` repository for broader application.