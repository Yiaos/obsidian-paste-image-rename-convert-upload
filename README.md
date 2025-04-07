# Paste Image Rename Convert Upload

Created with Cursor and Claude AI, I know nothing about TypeScript

## Overview

This plugin is inspired by and based on the following repositories:

1. [obsidian-paste-image-rename](https://github.com/reorx/obsidian-paste-image-rename)
2. [obsidian-paste-png-to-jpeg](https://github.com/musug/obsidian-paste-png-to-jpeg)

For detailed usage instructions, please refer to their READMEs.

## Why This Plugin?

I created this plugin to address the following needs:

1. Automatically rename images when pasted into notes - perfectly addressed by [obsidian-paste-image-rename](https://github.com/reorx/obsidian-paste-image-rename)
2. Compress images to take up less space - well satisfied by [obsidian-paste-png-to-jpeg](https://github.com/musug/obsidian-paste-png-to-jpeg)
3. Automatically upload renamed images to Cloudflare R2 object storage

- [obsidian-image-auto-upload-plugin](https://github.com/renmu123/obsidian-image-auto-upload-plugin) + PicGo can meet this need, but I wanted to achieve this without using additional tools like PicGo

So, with the help of Cursor + Claude, I combined these repository functionalities into a single plugin.

## Limitations

There are likely bugs since I only spent half a day on this and haven't thoroughly tested it.

Code readability and extensibility may be limited, even though I asked Claude to optimize the code according to requirements when add new features.
