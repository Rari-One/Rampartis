# Rampartis Privacy Notice

This notice describes Rampartis v1.0.0.

## The short version

Rampartis works on your machine, on files you choose. Rari.One has
no server that receives your files, your file lists, or your usage. The
sections below explain what stays on your machine and what happens when
you contact support or use GitHub.

## The desktop application

- **Local processing.** Backup, verification, restoration, storage analysis,
  and duplicate finding all run locally on files and folders you select.
- **Backup destinations.** Backups are written only where you point them:
  local or external drives, or supported network shares via a direct UNC
  path. On a network share, Windows
  connects using your own credentials and normal Windows networking;
  Rari.One is not a party to that connection and receives nothing from it.
- **Settings and history.** The application stores its settings, preferences,
  and run history locally, under your Windows user profile
  (`%LOCALAPPDATA%\one.rari.rampartis`). Scheduled backups are
  registered with Windows Task Scheduler on your machine, and their run
  history is shown in the application. Uninstalling offers optional deletion
  of this local data; backups themselves are independent files and are never
  removed by uninstalling.
- **Telemetry and analytics.** Rampartis does not add its own telemetry,
  analytics, advertising identifiers, or usage-data uploads.
- **Crash reporting.** Rampartis does not add its own crash-upload service.
  Microsoft WebView2 diagnostics are described separately below.
- **Updates.** You can check for updates from Settings. Checks happen only
  when you request them. Downloading and installing an update requires
  separate approval. Update checks and approved downloads contact GitHub,
  which processes those requests under its own privacy practices.
  Approved updates stage verified installation files in local temporary
  folders under the application data directory before Windows Setup runs.
- **Microsoft WebView2.** Rampartis uses Microsoft WebView2 to display its
  interface. WebView2 may send diagnostic information to Microsoft under
  Microsoft's privacy practices, including required diagnostic data.
  Optional diagnostic collection and crash reporting are subject to
  applicable Microsoft and Windows privacy settings. This is separate from
  Rampartis's locally stored backup diagnostics and user-selected exports.
- **Diagnostics.** Rampartis keeps limited network backup diagnostics
  locally. When available, you can choose to export a redacted copy. Review
  the export before sharing it. There is no automatic diagnostic upload.
- **Install-time exception.** If Microsoft Edge WebView2 is missing, the
  installer may download that Microsoft component from Microsoft during
  installation. That is a download from Microsoft, under Microsoft's terms.

## Support email

If you write to dev.rarione@pm.me, we receive your email address
and whatever you include. Please don't send backup contents, credentials, or
other private files — a description of the problem is enough. Support
correspondence is retained for 30 days after an issue is resolved, or after
the last interaction on a closed issue, and then deleted. While an issue is
actively being handled, the correspondence for it may remain available; that
does not extend retention for abandoned requests.

## GitHub and other external services

If you use GitHub Issues, read documentation, or download a release on GitHub, GitHub processes
your activity under GitHub's own privacy policy. Anything you post publicly
there is public — don't post private file paths, backup contents, or
credentials in a public issue.

## Retention, deletion, and questions

- You may ask what support information Rari.One holds about you, or ask for
  its deletion, at dev.rarione@pm.me.
- Application data on your own machine is yours to delete at any time (see
  Settings and history above).

## Security and changes

If this notice changes materially, the new version will be published where
this one appears, with its date.
