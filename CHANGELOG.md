1.9.3
------
* Upgrade of Redline to 1.1.15 (Thanks to @merscwog for tracking down)
* Support version constraints on depends in DEBs
* BREAKING: Enforce that there's no commas in a required package name. It will now fail instead of allowing a borked package to be created.
* Add RPM aliases to DEBs too
* Fix postUninstalls being treated as preUninstalls (Thanks to @ngutzmann)
* Use @Input for incremental task execution, so now more elements of a package will  be used to determine if a task is up-to-date.
* Add support for prefixes (Thanks to @merscwog)

1.9.2
------
* Using nebula-plugin-plugin for build and deploy
