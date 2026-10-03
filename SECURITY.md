# Security Policy

## Scope

ACE reads an iPhone backup that is already on your computer, including encrypted backups when you supply the password, and writes its results to your own user folder. Your messages are never uploaded. ACE goes online only to check for updates and, when you agree, to download the media converter it needs to play some voice messages.

Because it handles private messages and updates itself, these are the kinds of problems worth reporting:

- anything that could expose message content, attachments, or a backup password outside your user folder
- a way to make ACE install an update that Web Friendly Help did not publish
- tampered downloads, or a release whose `.sha256` file does not match
- unsafe handling of data read from a backup, such as file paths or attachment names, that could write outside the intended folder or run code
- vulnerabilities in third-party components ACE ships

## Supported versions

Only the latest released version gets security fixes. Use Check for updates in the Help menu to make sure you are current.

## Reporting a vulnerability

Do not open a public GitHub issue for a suspected security problem. Report it privately by email instead:

- help@webfriendlyhelp.com

Helpful to include:

- the ACE version, which is shown on the About item in the Help menu
- your Windows version
- a short summary of the issue
- steps to reproduce, if known
- impact

Do not send your backup or any real message content. A description of the problem, or a test backup made for the purpose, is enough.

If you are not sure whether something is a security issue or a regular bug, report it privately first.

## What happens next

I will acknowledge the report, decide whether it is in scope, and coordinate a fix if it is confirmed. This is a one-person shop, so response times vary. Good-faith reports are appreciated.

## Disclosure

Please give me time to ship a fix before sharing details publicly.
