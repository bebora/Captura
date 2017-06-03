---
layout: page
title: Translation
permalink: Translation/
---

Captura is localized using Culture-specific RESX files.

Currently supported locales:

Name                        | Culture ID | Contributor
----------------------------|------------|----------------
**English (United States)** | en-US      | Mathew Sachin
Malayalam (India)           | ml-IN      | Mathew Sachin

## Contributing Translations
- Fork the repository.
- Create a new branch.
- Create a copy of the `Resources.resx` file in `Captura.Core` project's `Properties` folder.
- Rename it to `Resources.[CultureID].resx`. e.g. `Resources.en-US.resx`.
- Do translation only if you know the language. Don't rely solely on some tool like Google Translate.
- Commit, Push, Create Pull Request.