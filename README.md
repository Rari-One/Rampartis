# Rampartis

**Backup • Preserve • Restore**

Rampartis is a free, local-first Windows utility for file backup,
verification, restoration, and storage analysis, published by Rari.One.
See [GitHub Releases](https://github.com/Rari-One/Rampartis/releases) for
installer availability and checksums.

This repository is for Rampartis's public documentation, releases, and
support.

## What it does

- **Back up folders** to a local drive or a network share you choose, on
  demand. Optimized repositories also support scheduled backups.
- **Verify** a backup's contents against its built-in integrity records
  to check for missing or changed data before you need to restore it.
- **Restore** a full backup or selected files and folders to a new location.
  Restores never merge into or overwrite an existing folder.
- **Analyze storage** to see what is using space, and **find duplicate
  files** — with safeguards that refuse to clean up files belonging to a
  backup.

## Install and uninstall

Download the Windows x64 installer from the [official Releases page](https://github.com/Rari-One/Rampartis/releases) and run it under the Windows account that will use Rampartis. The installer is digitally signed; release checksums are provided for verification. If Microsoft Edge WebView2 is missing, the installer may download it from Microsoft.

To uninstall, close Rampartis and use **Windows Settings → Apps → Installed apps**. Leave the optional app-data deletion checkbox unchecked if you want to retain settings and schedule history. Backup repositories are stored independently of the application.

## Updates

Check for updates from **Settings**. Checks are manual, and downloading and installing an update require separate approval. Update checks and approved downloads contact GitHub; see the [Privacy Notice](PRIVACY.md).

## How backups are stored

Rampartis does not lock your files inside a proprietary container, and it
does not encrypt or compress them. That is deliberate: a backup should
outlive the software, a forgotten password, and us.

- **Standard backups** are ordinary folders: your files under a `files\`
  directory in their original folder structure, plus a small JSON record
  (`harborlight.json`) listing each file's size and BLAKE3 hash. You can open
  and copy a standard backup's files with Windows Explorer or any standard
  tool, without Rampartis installed. Keep the JSON record with the backup —
  it is what verification checks against.
- **Optimized repositories** store each unique file's bytes once, under its
  content hash, with per-backup records that reference them. This saves
  space when backups overlap, while the stored bytes remain plain and
  uncompressed.

## Please know

- A backup on the same drive as the original is not protection against that
  drive failing. Keep backups on a separate device.
- Run a verification after backing up, and test a restore before you need
  one.
- Restoring copies the bytes that were backed up; it cannot repair a file
  that was already damaged before the backup was made.
- Your originals and your backups are independent copies. Deleting one does
  not delete the other.

## Storage requirements and limitations

- Rampartis backs up files and folders you select. Disk imaging, system
  state, and bare-metal recovery are outside its scope.
- Processing runs locally. Backups go to the destination you choose.
  Rari.One does not receive your files.
- Use a direct UNC path such as `\\server\share\Backups` for an SMB
  repository. Mapped-drive repositories are unsupported. For background
  backups, enable them in **Scheduled Backups** and keep Windows signed in,
  the computer awake, and the destination connected.
- Use non-cloud folders. Cloud-synced folders are unsupported, including
  cloud-only placeholders and files that remain managed by a sync provider.
  Copy files to a regular local folder before backing them up, and use a
  regular local folder for restores.
- Metadata preserved: modification times, folder structure, and read-only
  flags (plus Windows hidden/system/archive attributes). Creation times,
  permissions/ACLs, alternate data streams, and hardlink identity are not
  preserved.

## Support and security

See [SUPPORT.md](SUPPORT.md) for how to get help, and [SECURITY.md](SECURITY.md)
for how to report a security issue privately.

See the [Software Terms](EULA.md) and [Privacy Notice](PRIVACY.md).

Copyright © 2026 Rari.One. All rights reserved.
Rampartis is proprietary software; this repository contains documentation
only and grants no license to any source code.
