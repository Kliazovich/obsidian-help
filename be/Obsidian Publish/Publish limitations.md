---
aliases:
  - Publish Limitations
---

> [!tip] Members of our awesome community have devised workarounds for some of these limitations. For more information, please visit our [Publish Resources](https://forum.obsidian.md/t/obsidian-publish-resources/74582) thread on the Obsidian forums.

## Community plugins

Obsidian Publish has minimal support for [[Плагіны супольнасці]]. 

Plugins which output in raw markdown, such as the Waypoint plugin, are compatible with Publish because they do not require the application to render their data. 

Whereas a plugin that requires a plugin codeblock to render, such as Dataview or Fantasy Statblocks, will not work by default in Publish. 


## Graph

Publish offers basic color customization for its graph view using CSS. You can modify the node colors in your `publish.css` file by utilizing the [Graph View CSS variables](https://docs.obsidian.md/Reference/CSS+variables/Plugins/Graph).

Note that the published graph does not support the comprehensive sorting and viewing options available in the application's [[Graph view]].


## Search

Publish has basic support for searching plain text in published content. Preference for search results is given to:

- File names
- Aliases
- Header names

After searching the above for matches, the search will then include plain text of the published notes.

To improve the searchability of your published site, it is recommended to use descriptive file names, incorporate multiple aliases, and select header names that accurately reflect the content.

