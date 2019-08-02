---
title: WPF
redirect_from:
  - /WPF/
  - /WPF_ImplementationNotes/
---

At this point, no group in the Mono project has plans to implement Windows Presentation Foundation APIs as part of the project.

We do not have any plans because the project is too large and there has not been any serious interest from the community to make this effort move forward.

Some bits have been implemented for WindowsBase and they are distributed with Mono (mostly because System.IO.Packaging is part of WindowsBase). Various classes and stubs were developed and live in the [Olive](/archived/olive) module.

Anyone interested in contributing should follow the guidelines in the [Contributing](/community/contributing/) page.

At this point, we strongly suggest that users interested in WPF adopt Silverlight instead as it can now be used outside of the browser and offers a rich set of cross platform APIs and features.

Alternatives
============

Currently [AvaloniaUI](https://avaloniaui.net/) is an initiative that is focused to mirror the WPF project but is multi-platform and a dialect.

Silverlight implement a subset of the WPF APIs and is available on Windows, macOS and through our own open source effort [Moonlight](/docs/web/moonlight/) it is available on Linux and other Unix systems.

Silverlight does not have all the capabilities of WPF, but both technologies are converging API-wise.

Silverlight can now be used outside of the browser, and Moonlight can be configured to be used with the full .NET API outside of the browser.

[WPF_Notes](/docs/gui/wpf/)

