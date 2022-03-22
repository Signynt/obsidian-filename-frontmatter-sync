# Obsidian Filename Frontmatter Sync

> This project is a minor modification of [Obsidian Filename Heading Sync](https://github.com/dvcrn/obsidian-filename-heading-sync) by @dvcrn

This is a Obsidian plugin to keep the filename and the first heading of a file in sync

**Note**: This plugin will overwrite your first frontmatter field called `title:` the moment you open it, so this can be considered _destructive_.

## Features

- When renaming the current file -> will update the frontmatter
- When opening a file that doesn't have a frontmatter `title:` field yet -> will insert one
- When opening a file with a different `title` than the current file name -> will update the `title`
- When updating the frontmatter of a file -> will rename the file

## Current limitations and to do

- When renaming a file that isn't the current file, nothing will happen. The heading will get updated the next time the file is opened in edit mode
- [Special characters](https://github.com/dvcrn/obsidian-filename-header-sync/blob/bc3a1a7805f2b63ad5767c3d01dcef7b65b1aebd/main.ts) that obsidian can't handle will get auto-stripped

## LICENSE

MIT

> For more details please see [Obsidian Filename Heading Sync](https://github.com/dvcrn/obsidian-filename-heading-sync)
