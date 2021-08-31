# Welcome to MathLingua

This template repository is designed to help you quickly and easily get started with a new collection of mathematical knowledge written in the [MathLingua](http://www.mathlingua.org) language.

To get started, run

```
./mlg
```

which will download the latest version of the MathLingua toolchain, print information about its usage, and create a `content` directory.

Place your files written in the MathLingua language in the `content` directory and use the `.math` file extension.

See the [MathLingua](http://www.mathlingua.org) homepage for more information about the language.

## Note:

The `mlg` executable currently only supports Unix based operating systems.

For other systems, manually create the `content` directory at the root of this repository, download the latest MathLingua release from the [MathLingua GitHub page](https://github.com/DominicKramer/mathlingua/releases) as a jar file, and run

```
java -jar mathlingua-<version>.jar
```

to use the MathLingua tooling.
