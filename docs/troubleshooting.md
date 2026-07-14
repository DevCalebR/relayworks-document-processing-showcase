# Evaluation troubleshooting

## The sample ZIP does not download from the README

Open [`../sample-output/relayworks-sample-output-pack.zip`](../sample-output/relayworks-sample-output-pack.zip) from the repository file view and use GitHub's raw download action.

## The ZIP cannot be extracted

Verify the archive with `unzip -t sample-output/relayworks-sample-output-pack.zip`. Do not bypass operating-system warnings if the checksum or archive structure differs from the repository version.

## Screenshots do not match every PDF

The screenshots demonstrate the workflow, not guaranteed extraction quality. Results depend on source structure and third-party parsing behavior.

## The application cannot be started from this repository

That is expected. This public repository excludes the commercial source. Installation and setup instructions are distributed with the purchased package.

## Marker setup fails after purchase

Use the version and platform guidance included with the paid kit, then confirm the CLI works independently before starting the application. Marker is a separate third-party dependency.
