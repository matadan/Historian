# Historian

Historian is an app state viewer and manipulator for apps written in [Pointfree.co's Composable Architecture](https://www.pointfree.co/collections/composable-architecture).

For more information see this [introductory blog post](FIXME: add link).

## OS variants

The iOS and macOS apps are only minimally different and can probably be merged soon.

The main reason it's not the case yet is that using a single app target seems to make the whole app a catalyst app, even when using SwiftUI.

It would probably be possible to integrate both into single app even without doing so but since most of the code really sits in the dependency `HistoryView` and the apps are simple viewer shell it's likely more hassle that it's worth.