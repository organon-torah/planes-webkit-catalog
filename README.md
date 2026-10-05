# planes-webkit-catalog

Public GitHub Pages catalog for the private `planes-webkit` UI library.

The synthetic catalog previews a **2.0.0 development candidate**. The candidate adds standard CSS for ordinary HTML, typography-based quotations and square document tables/code, Drawer navigation with flat search results, and notification queue control through Toast (items/onDismiss). This preview does not publish or release the private library; the released packages remain at 1.4.0.

The updated preview aligns the catalog open/close controls, keeps Drawer links at their label width, shows an icon-only Markdown picker, and sizes mobile Modal/Dialog windows to their content with the footer at the bottom. It also preserves single disabled-control opacity and keyboard access to Accordion/contenteditable content in Drawers.

Opening the icon picker focuses its Close button. Select the search field with a tap or Tab to search; canceling or inserting returns to the editor with its selection/history preserved.

Examples contain no private OCR text/images, package tarballs or source maps. The existing static Pages workflow is preserved.
The 55 component samples now include Panel, an additive section component with separate header/body slots and 20px padding (16px on screens up to 640px). Its ui-panel classes leave consumer-owned panel classes unchanged; consumers adopt the component explicitly.

https://organon-torah.github.io/planes-webkit-catalog/

The revised preview keeps the Toast queue/deadlines and adds shared spacing:16px between document/editor/code blocks and ordinary table/form content,6px within ordinary labels, and comfortable separation between native buttons. MarkdownSourceEditor and its composed preview no longer touch. These are synthetic examples of the2.0.0 candidate; the released private packages remain1.4.0.
