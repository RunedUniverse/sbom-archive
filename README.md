# SBOM Archive of RunedUniverse

Here we store SBOM reference files of our published artifacts.

This Repository can be used with the CycloneDX Validator of our [maven-repo-project](https://github.com/RunedUniverse/maven-repo-project).

## Structure

The repository's content follows the path schema: `<category>/<groupId>/<artifactId>/<version>/[<classifier>.]<type>.xml`

 Folder | Description
---|---
 maven-ext | Components which are Maven Core Extensions (some are also Maven Plugins)
 maven-plugin | Components which are Maven Plugins
 maven-lib | Components which are distributed primarily via Maven but are not Maven Plugins/Extensions

