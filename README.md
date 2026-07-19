# ThreatLens Privacy Policy

Last updated: July 19, 2026

ThreatLens is a file reputation and file attribute utility for iPhone. It helps you check selected files using VirusTotal and inspect extended attributes on files you choose.

## What ThreatLens Collects

ThreatLens does not create user accounts, show ads, use analytics SDKs, track users, or sell personal data.

ThreatLens stores your VirusTotal API key locally on your device using the iOS Keychain. The API key is used only to authenticate requests to VirusTotal.

## Files and Hashes

When you choose a file, ThreatLens first calculates a SHA-256 hash of the file on your device. ThreatLens sends that hash to VirusTotal to check whether an existing report is available.

If VirusTotal already has a report for the file hash, ThreatLens displays that report and does not upload the file.

If VirusTotal does not have an existing report, ThreatLens may upload the selected file to VirusTotal for analysis. Before uploading files over 10 MB on mobile data, ThreatLens asks for your confirmation.

ThreatLens does not upload files automatically in the background without a scan request from you.

## File Attributes

ThreatLens can inspect and clear extended attributes from files you choose through the iOS file picker. This processing happens on your device.

ThreatLens stores a recent local history of files whose attributes were cleared, including file name, file size when available, clear time, and the names of cleared attributes. ThreatLens does not upload extended attribute values or recently cleared history to its own servers.

## VirusTotal

VirusTotal is a third-party service operated by Google. Files, hashes, API keys, IP addresses, and scan requests sent to VirusTotal are handled under VirusTotal's and Google's terms and privacy notices.

Files uploaded to VirusTotal may be retained and may be shared with security vendors and the security community. Do not upload confidential, private, sensitive, or proprietary files unless you are comfortable with VirusTotal receiving and processing them.

You can review VirusTotal and Google policies here:

- VirusTotal: https://www.virustotal.com/
- Google Cloud Security Operations Privacy Notice: https://cloud.google.com/terms/secops/privacy-notice
- Google Cloud Terms: https://cloud.google.com/terms

## Data Stored by ThreatLens

ThreatLens stores the following on your device:

- Your VirusTotal API key, if you enter one
- The currently selected file reference while using the app
- Recent scan history, including file name, file size, scan time, verdict, and engine counts
- Recently cleared attribute history, including file name, file size when available, clear time, and cleared attribute names
- Temporary upload data while preparing a VirusTotal upload

ThreatLens does not store scan history or cleared attribute history on its own servers. This history is stored locally on your device. ThreatLens does not operate any server for this app.

## Network and Mobile Data

ThreatLens uses the network only to communicate with VirusTotal. Uploading files can use significant data. If a file is larger than 10 MB and an upload is required while you are on mobile data, ThreatLens asks for confirmation before uploading.

## Children

ThreatLens is not directed to children and does not knowingly collect personal information from children.

## Your Choices

You can avoid uploading a file by not continuing when ThreatLens indicates that no existing VirusTotal report is available.

You can remove your VirusTotal API key by editing the API key field in the app and clearing it.

You can avoid using the file attribute tools by not selecting files in the Attributes tab or by not confirming attribute removal.

You can delete the app to remove locally stored app data from your device. iOS may retain Keychain items according to system behavior.

## Changes

This policy may be updated when ThreatLens changes how it handles data. The latest version should be made available through the App Store privacy policy link.

## Contact

For privacy questions, contact:

naz.ext@icloud.com
