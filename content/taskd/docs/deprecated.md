---
title: "Taskserver - Deprecated Features"
---
{{< alert >}}Taskserver is deprecated and only compatible with Taskwarrior 2.x.{{< /alert >}}

# Deprecated Features

Taskwarrior, Taskserver, Tasksh, and Timewarrior have many features.
With each release new features are added, and sometimes features are removed.
A feature may be removed if it has been superseded by something better, is no longer relevant, or is very troublesome.

With the Taskwarrior command line syntax becoming more formal and regular with every release, there will be a corresponding set of changes that remove ambiguous command line syntax, and add consistent syntax.

Before a feature is removed, it is deprecated, where possible.
This means that it will appear on this list, in one release, and be removed in an unspecified later release.
Deprecation acts as an early warning for disappearing functionality, giving users time to adapt or complain.

When a feature is removed, any related configuration settings are also removed.

## Taskserver

NOTE: Taskserver itself is deprecated and only compatible with Taskwarrior 2.x.

### Client Allow/Deny List [removed in 1.1.0]

Taskserver initially supported the `client.allow` and `client.deny` settings which filtered connections.
The intention was to be able to decline misbehaving clients.
This has proved to be a configuration problem for some, and the mechanism is easily spoofed, so it will be removed.

