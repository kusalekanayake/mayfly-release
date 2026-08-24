# Mayfly releases

Notarised builds of Mayfly, and the Sparkle appcast that points at them.

This repository holds no source — only the built app and `appcast.xml`. It is public because
Sparkle fetches the feed without credentials; an updater that needs a token is an updater that
cannot run.

## Installing

Download the newest zip from [Releases](../../releases), unzip it, and drag **Mayfly.app** into
**/Applications**. Keep it there — Sparkle replaces the app in place and cannot write to a folder
it does not own.

Updates after that are automatic: Mayfly checks on launch and daily, tells you when a build is
available, and installs when you say so. It never installs on its own.
