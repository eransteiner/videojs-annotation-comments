---
layout: default
---

### Background

This plugin was conceived and initially developed as a Hack Week project at [Contently](http://www.contently.com) by [Evan Carothers](http://www.github.com/ecaroth) and [Jack Pope](http://www.github.com/jackpope). With our continuing focus and commitment to multimedia support at Contently, it was further productized and bulletproofed by our entire team, as a flexible solution for use in our product and other open-source use cases.

### Goals

- **USEFUL** - Provide useful collaboration features including annotations, comments/replies, ranged time markers, and more. All with intuitive controls.
- **SIMPLE & LIGHTWEIGHT** - Everything is contained within the plugin and player element. There is no need to build additional UI components. Just install VideoJS, register the plugin, setup whatever backend storage you wish, and start collaborating.
- **EXTENSIBLE** - The plugin can be integrated with existing commenting systems, and makes very few assumptions about how you store your comments/annotations. Custom events are available for communicating with external APIs, providing support for on-page interactions and data persistence. Simple CSS overrides can also allow for branding customizations with minimal effort, or completely custom UI/UX.


### Add it to your VideoJS player

```javascript
var player = videojs('video-id');
var plugin = player.annotationComments({})
```

[VideoJS Annotation Comments is fully documented on Github](https://github.com/contently/videojs-annotation-comments).

#### License

This plugin is [licensed](license.md) under the Apache License, Version 2.0, which is the same license used by Video.js
