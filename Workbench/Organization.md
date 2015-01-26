# Workbench Organization

Workbench consists of one or more main views, such as model editor, surrounded by panels.

[![Workbench](../img/Workbench.png)](img/Workbench.png)

Panels are organized into panel bars. If minimized, they will temporarily expand when you hover mouse over or click on them. You can lock them in place by clicking on their toolbar or expand them even more by double-clicking on it.

Individual panels can be activated by clicking on their toggles in the panel bar.

The main view usually shows the document you have opened for editing.

Additional views, when applicable, can be added by clicking on their toggles in the right top corner on the main toolbar. The toolbar on the top shows the content related to the view that has focus.


## Explorer

Explorer is a panel on the left side that shows contents of your repository and has buttons at the bottom for creating a new document and for simultaneously publishing/reverting changes made to multiple documents.

By using the *Organize* menu in the Explorer panel you can organize your repository view in different ways:

* *Group by grammars* - groups all documents created from the same grammar into one folder, using grammar name as a name of the folder.
* *Group by tags* - uses document tags as folder/subfolder names. For example, if a document has tags `foo`, `bar`, `baz`, the explorer tree will shown a chain of nested folders `foo/bar/baz`.

To the left of the model name you can see an icon that depicts its type:

- **G** - for grammars;
- **F** - for formats;
- **M** - for all other model types.

Names of new and locally modified documents are shown in _italics_ until you publish them from your private workspace into the main repository by clicking on the checkbox in the explorer or on the toolbar.

While your latest changes are auto-saved to the workspace, an indicator `*` is briefly added to the model name to indicate that this model is being saved on the server. Sometimes there may be server communication problems and the indicator may stay for longer than usual.

## Views

There are several content view types in the workbench. They are activated by the view toggle buttons on the main toolbar:

- **M** is for regular documents (models);
- **G** is for grammars;
- **F** is for formats (editor and generator);
- **R** is for viewing generated results.

All of these views are related to each other. For example, when editing a grammar, the model and format views only show documents related to that grammar. Similarly, the result view shows only results generated from the model opened in the **M** view.

## Other Panels

In addition to the Explorer and content views there are several other panel types in the workbench. They can be activated by clicking on the panel toggle button in the panel bar.

- *Alerts* shows validation alerts for the currently active document. If you click on an alert the corresponding element in the document editor will be highlighted.
- *Discuss* shows a discussion panel where you can share comments for the currently opened document.
- *Table of Contents* provides a quick way to navigate through the document.
- *Console* shows code generation-related errors and other messages.
