# sf-gha-bump-patch-version

Github Action for å bumping patch versjonen i sfdx-project.json basert på en kommaseparert liste

## Usage

<!-- Start usage -->
```yaml
- uses: navikt/sf-gha-bump-patch-version@main
    with:
        # Comma separated list of package names: "packageA,packageB,packageC"
        # Required: true
        # Default: ''
        package_names: ''
```
<!-- end usage -->

## Henvendelser

Spørsmål knyttet til koden eller prosjektet kan stilles som issues her på GitHub.

## For NAV-ansatte

Interne henvendelser kan sendes via Slack i kanalen #platforce.
