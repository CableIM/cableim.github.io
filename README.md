# Cable

## Introduction

Cable is an encrypted instant messaging and voice calling application
for Android. It uses the Internet to send one-to-one and
group messages, which can include images and video messages, and make
one-to-one voice calls. Cable uses standard phone numbers as
identifiers and end-to-end encryption to secure all communications to
other Cable users.

Cable is based on Signal, but has some different goals.

This is not a company or a startup, it's a project.

## The problems with Signal

These are the limitation of Signal this project tries to address:

- Signal is a centralized service, run by a single entity: Open Whisper Systems.
Cable aims to build a network of federated, independent servers.
- The Signal client has some proprietary dependencies, these are removed in Cable.
- Signal users Amazon S3 to store encrypted attachments. While everything
is always end-to-end encrypted, we avoid Amazon and prefer self-hosted or noncommercial solutions.
- Signal is not friendly towards third-party clients using their servers, Cable is.

## License

The clients are published as free and open-source software under the
GPLv3 license. The server code is published under the AGPLv3 license.
