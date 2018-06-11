# Magento 2 Example Custom Page Layout
This module shows you how you can add a new Page Layout. Instead of just defining the Page Layout, this module
makes the module also available under the **Design** section with products & categories (thanks to the
`layouts.xml` file). Also, the Page Layout is re-used in a regular layout, which is then made available for
widgets (through the `design_abstraction="page_layout"` attribute of the `page` node).
