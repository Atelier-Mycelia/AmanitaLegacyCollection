# Amanita Legacy Collection
Preserving the past, supporting the present! This is a curated archive of inherited features from [Amanita](https://github.com/Atelier-Mycelia/Amanita), maintained for compatibility but separated for clarity.

## Why the Split?
Amanita is focused on being a toolkit for:
- Story-centric games such as Visual Novels (e.g., *Clannad*) and Point-and-Clicks (e.g., *King’s Quest*)
  - Especially cutscenes, progression flags, and other systems close to delivering the story
- Bridging core systems and UI
  - For example, displaying how much gold the player has

Some features inherited from [Fungus](https://github.com/snozbot/fungus) aren’t central to these goals. To keep Amanita lean and organized, we’ve moved them here.

## Scope
This collection includes legacy variable types, helpers, and other systems that may still be useful in certain projects but aren’t part of Amanita’s core narrative toolkit. Mainly:
- Working with Unity's built-in physics system
- Using the old audio system
- Using Collections

## Who or What Should Use This?
- Projects that rely on legacy features inherited from Fungus that are no longer in Amanita's core
- Developers migrating older Amanita-based projects who need continuity
- Anyone who wants access to these features without bloating the main Amanita package

## Handling of Updates
We will maintain compatibility with the latest versions of Amanita, including bugfixes and migrations. For example, variable types here will continue to support RowVisualHandlers for use in the updated visual-scripting system.

This package is in **maintenance mode**: updated for compatibility, but not expanded with new features unless necessary. If Amanita evolves in ways that make these features more relevant again, we may revisit their role.
