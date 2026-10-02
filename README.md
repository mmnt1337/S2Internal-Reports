# S2Internal — bug reports

**English** | [Русский](README.ru.md)

Bug reports and logs for the S2Internal mod.

**[Report a problem](https://github.com/mmnt1337/S2Internal-Reports/issues/new?template=bug-en.yml)** · [Existing reports](https://github.com/mmnt1337/S2Internal-Reports/issues)

## How to report

1. Sign in to GitHub or create a free account.
2. Click **Report a problem** and give it a short title, such as “ESP stops updating”.
3. Describe what you did, what went wrong, and what you expected.
4. Enter the mod version or the name of the archive you downloaded, and attach logs using the instructions below.
5. Click **Submit new issue** to send the report.

Example: “I enabled ESP and the minimap. After a few minutes, ESP markers stopped updating. Turning ESP off and on did not help.”

Create a separate report for each problem. If the same problem is already reported, add your details and logs in a comment there.

## How to attach logs

**Attach logs from the time of the problem. Without them, we usually cannot determine the cause.**

1. Press **Win + R** — the Windows-logo key and R.
2. Paste `%LOCALAPPDATA%\S2Internal` and press **Enter**.
3. Find **s2internal.log**. Windows may show it as **s2internal** with the extension hidden. If it is very large, use the most recently modified **s2internal_….log** file instead.
4. For a crash or freeze, also collect **crash_metrics_….log** files modified around the time of the problem. Sort by **Date modified** to find them.
5. Drag the files into the report's **Logs** field or click it to select them. Wait for the upload to finish.

If the launcher fails to start the mod, attach **launcher.log** from the folder containing **S2InternalLauncher.exe**. Copy it before trying again: the next launcher run replaces this file.

To attach several files together, select copies of them, right-click, and choose **Compress to ZIP file** (Windows 11) or **Send to → Compressed (zipped) folder** (Windows 10). Attach the ZIP.

## Details that help

Include whether you use the launcher or ReShade, which features were enabled, and how often the problem occurs. For low FPS, include approximate FPS before/after and your graphics card. Screenshots of the problem or error message can be attached in the **Details** field.

Reports and attachments are public. Check files for personal information before uploading.
