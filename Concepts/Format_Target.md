# Format and Target

Models store your information in an abstract structured form. However, in many cases it is not the most convenient way to see and edit it, and it is often not the form in which your computer systems and applications understand.

That's where *formats* come in the play. They are special models (yes!) that transform information stored in the model in a form that is easy for your and for computers to work with.

There are two types of formats:

* *Editor* format describes how you want to see the model on the screen when you edit it - e.g. as a form, or text, or tree of elements, or perhaps a diagram.
* *Output*, or *generator*, format describes how to transform your model into something that computers can understand - e.g. configuration file or executable script.

For the same model (or, rather, its grammar) a developer can implement several alternative ways of representing it in an editor or generating its output. For example, one of your systems may need this model in a form of a data document, while another one might prefer a program that it can run. Such outputs generated from the model with some output format are called *targets*.
