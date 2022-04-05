# Jsyn Experiements

Some musical experiments using the [jsyn](https://github.com/philburk/jsyn) library in Java.

While JSyn can manipulate audio of any frequency, we have created a few classes to simplify playing musical tones from the classical Western system:

- `Tone.java`: a representation of a tone, including its symbol, e.g. "`B♭`", and its frequency, e.g. `466.1638`.
- `SoundMaker.java`: a wrapper around instances of JSyn's Synthesizer and LineOut objects to make it easy to turn on and off the sound, and play tones.

## Technical requirements

This project depends upon the [JSyn](https://github.com/philburk/jsyn) library. The `.jar` files for this dependency are included within the `lib` directory.

## Folder structure

This project has several important directories:

- `src` - contains the Java source code for the project (i.e. `.java` files)
- `bin` - contains the compiled code (i.e. `.class` files)
- `lib` - contains any dependencies (other libraries of code that the project depends upon to work)

If your project has no dependencies and has not been compiled, you may not see the `lib` or `bin` directories.
