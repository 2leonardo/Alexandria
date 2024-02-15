# Dev Handover (1.0.4) [project name]

## Changelog:
### 1.0.4 (February '24)
*   Add images for blocks under blocks definitions
*   Add new icon 🆕 for new blocks (when working on an inherited or reworked site)
*   Add new icon ♻️ for new (recycled) blocks (when working on an inherited or reworked site)
### 1.0.3 (December '23)
*   Add template to [Alexandria](https://github.com/2leonardo/Alexandria)
*   Add Layout info (e.g. Footer, Header)
### 1.0.2 (November '23)
*   Add site name in Document Title (e.g. \[Site Name\])
*   Add Design Links (e.g. Figma, XD)
*   Add layout definition on block specs
### 1.0.1 (October '23)
*   Add new icon 📮
*   Post types moved closer to components
*   Use new syntax for repeater (e.g. 3:3)
*   Add site's setup
*   Add Self/Peer review info
*   Add base flow
## Design Links
## Site's setup
The site will use the latest version of the new sb-starter theme:
[https://github.com/SoBold/sb-starter/archive/refs/tags/1.0.1.zip](https://github.com/SoBold/sb-starter/archive/refs/tags/1.0.1.zip)

## Base
## Layout
### Header
### Footer
## Blocks
### Glossary for blocks
🔗 Block has components\
🔒 Block has no components\
🧩 Block has components used by other blocks\
⚡ Block has AJAX\
📮 Block uses one or more post-types\
🆕 New block - This is only relevant when working on an existing site (either inherited or reworked)\
♻️ Old block - This is only relevant when working on an existing site (either inherited or reworked

Whenever a block can have its acf field type easily inferred (e.g. text, textarea), its type will be omitted.\
When a field has multiple types inferred it will be left to the discretion of the dev to decide its type.\
CTA is always acf: link.\
Clones on page builder do not have to be prefixed, as they are found in loop context.
## Post Types
## Components
## Site's Schema
