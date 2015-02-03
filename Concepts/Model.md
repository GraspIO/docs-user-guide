# Document Model

Document models, or simply models, contain hierarchical data structures or structured documents. They consist of elements, simple or complex attributes and references to other elements.

As a user you will view and change them via a projectional (structured) editor that converts their hierarchical data structure into what looks like, well, a document.

While you edit such document, one or more generators may work behind the scenes to translate it into different forms such as code.

## Grammar

Grammar is a special kind of model that describes a schema for other models. Sometimes it is also called metamodel. Grammar defines classes for model elements.

Thanks to a grammar, your documents will contain only the right fields with the right values in them, and this will make it easy to translate your input into other representations.

## Format and Target

Format is a special kind of model that transforms information stored in a structured document into a user-readable ot machine-readable form.

There are two types of formats:

* Editor format describes how to present the document in an editor.
* Output format, also called generator, describes how to transform your model into something that computers can understand, i.e. turn it into a code.

Same model type can have multiple alternative ways of representing it in an editor and generating its output. Each of them will have its own format.

The results of code generation from a model by an output format are called targets. They can be saved locally or instantly delivered to the applications that need them.
