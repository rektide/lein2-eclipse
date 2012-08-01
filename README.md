# lein2-eclipse

lein2-eclipse is a [Leiningen2][1] plugin that automates the generation of [Eclipse][2]
project setup.

It provides the `eclipse` command to generate `.project` and `.classpath` files.

[1]: https://github.com/technomancy/leiningen
[2]: http://eclipse.org


## Usage

To use lein2-eclipse, add it as a plugin to your `project.clj` file or
your global profile:

    :plugins [[lein2-eclipse "2.0.0"]]

When this is set, you can use the `lein eclipse` command to generate project files.
