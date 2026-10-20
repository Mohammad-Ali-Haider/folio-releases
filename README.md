# Folio · Windows downloads

Public preview installers for Folio, a local document workspace with project libraries,
hybrid retrieval, and answers linked to supporting passages. The source repository is
kept private; this repository contains release information and binary downloads only.

## Download for Windows

Open **[Releases](https://github.com/Mohammad-Ali-Haider/folio-releases/releases)**,
choose the newest published Windows preview, and download **Folio-Setup.exe** under
**Assets**. Download **SHA256SUMS.txt** to verify the executable. GitHub's automatic
source-code ZIP/TAR downloads are not the installer. If no published release appears,
the installer is still being tested and is not yet available.

## What to expect

- Windows 10/11 x64; .NET Framework 4.8. Unsigned preview, published by Mohammad Ali Haider.
- Online setup downloads Python and locked dependencies; models download on first use.
- Several GB of free space required. Your library starts empty: add your own documents.
- Search and source-excerpt answers work without an OpenAI account.
- ChatGPT subscription sign-in is **disabled** pending the supported integration.
- Optional generated answers use your own OpenAI API key and separate API billing.
- No automatic updates, paid entitlements, OCR/figure interpretation, or production-readiness claim.

See the release notes for installation steps, tested behavior and limitations.
Never upload your documents, API keys, `.env` or account sessions to this repository.
Use Issues for reproducible application bugs; remove sensitive material from reports.
