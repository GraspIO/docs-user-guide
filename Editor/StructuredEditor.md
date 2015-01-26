# Structured Editor

Structured, or projectional, editor is as a combination of a text document and a form. It shows your model as a formatted text document, but if you click on any part of it, you will see a highlighted block that selectes an element or a field that is a part of your document's structure. Click on it once more or just start typing and it becomes editable.

Even though the document in the editor may often look like a regular formatted text, it represents a hierarchical element structure.

This means that sometimes you won't be able to delete or rewrite any arbitrary part of the document simply by rewriting its text. You will have to select fields or elements and then delete them, copy/paste and so on.

In return you get better contextual support and peace of mind from knowing that your document will stay free of syntactical errors or you will be explicitly notified about them.

## Editing

When you begin editing empty model document, it will initially show just an empty "Add content" field, which on click may open a list of allowed element types. Once you select the type of an element that you want to add, that element will be created and the editor will transform itself so that you will be able to see and edit element's attributes.


In order to edit existing element or attribute in your document, you need to select it first first by clicking on it or moving existing selection with arrows. You can also select multiple elements by clicking on the first one and then clicking on the last element while pressing  down **Shift** button.

> Selected element is marked by a different background color and have command wheel next to it for most frequently used operations.

To start editing selected element or attribute, you can click on it once more, or press **Enter**, or simply start typing new value.

To finish editing you can click outside of the field editor or in some cases press **Enter**.

To cancel editing of the field without saving your changes press **Esc**.

Some elements and attributes are required, some are optional, and some can contain multiple values. After selecting an element or attribute you will often see little clickable **&#10753;** icons surrounding it. By clicking on them you can add another value before or after the selected one.

You can  deleted selected element or value by clicking on the **&#9421;** icon.

Instead of deleting, you can also temporary 'comment out' the element or value by selecting **Toggle Comment** command from the context menu or pressing **Ctrl**+**/**  (**&#8984;**+**/**) on the keyboard.

Elements and attributes can be reordered by cutting them out and pasting into a different place in the model. Some of them are draggable - look for mouse cursor to turn into **&#10021;** while hovering over element's name.

Optional attributes in an element may not be initially visible until you select that element. Once you put values in them, they will remain visible.

The actual way how the editor for the selected value will look like depends on the value's type and constraints: e.g. it could be a text field, a dropdown, a file selector, or a calendar. Dropdowns may contain a full list of allowed values, or just a starting set and you will be able to type few letters to see the value that match your filter.

Such purpose-built field editors, their underlying constraint rules, as well as informational popups and validation alerts are designed to give you a clear idea of what structure and values you can set in your document.

## Navigating

In order to see which parts of the document belong to the same element, and which parts are editable, you can move mouse cursor to stay on top of the element and they will be highlighted after a short delay.

While hovering over an element or attribute you will also be able to see an informational popup that may contain short description of its type and purpose.

If your model contains invalid elements or values (including missing fields), their placeholders will be highlighted with red color, and when you hover over them you will see description of the error. The same description will also appear in the *Alerts* tab.

Some of the attributes contain references to other elements in the same or different model. For local element reference you can see where it points at by holding down **Ctrl** (**&#8984;**) key and moving mouse cursor over it. In order to jump to the definition of that element in the same or different model, click on the reference while holding down the same key.

Elements can be collapsed ('folded') and expanded to hide/show their internal structure. You can quickly collapse an element with all its subelements by selecting it and pressing **Ctrl**+**Shift**+**&#11013;** (**&#8984;**+**Shift**+**&#11013;**) and expand them again with **Ctrl**+**Shift**+**&#10145;** (**&#8984;**+**Shift**+**&#10145;**).




