# Changelog

This file includes a history of past releases. Changes that were not yet added to a release are in the [changelog.d/](./changelog.d) folder.

<!--
⚠️ DO NOT ADD YOUR CHANGES TO THIS FILE! (unless you want to modify existing changelog entries in this file)
Changelog entries are managed by scriv. After you have made some changes to this plugin, create a changelog entry with:

    scriv create

Edit and commit the newly-created file in changelog.d.

If you need to create a new release, create a separate commit just for that. It is important to respect these
instructions, because git commits are used to generate release notes:
  - Modify the version number in `__about__.py`.
  - Collect changelog entries with `scriv collect`
  - The title of the commit should be the same as the new version: "vX.Y.Z".
-->

<!-- scriv-insert-here -->

<a id='changelog-16.0.9'></a>
## v16.0.4 (2024-03-12)

- [Bugfix] Fix a 403 error on exporting course content when the minio plugin is enabled. (by @FahadKhalid210)

<a id='changelog-16.0.3'></a>
## v16.0.3 (2023-12-15)

- [Bugfix] Make LMS/Studio connnect to the right port in dev mode. (by @ormsbee)

<a id='changelog-16.0.2'></a>
## v16.0.2 (2023-12-08)

- [Improvement] Added Typing to code, Makefile and test action to the repository and formatted code with Black and isort. (by @CodeWithEmad)

<a id='changelog-16.0.1'></a>
## v16.0.1 (2023-06-15)

- [Bugfix] Fix "'type' object is not subscriptable" error. (by @regisb)
- [Improvement] Add a scriv-compliant changelog. (by @regisb)
