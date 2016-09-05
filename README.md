# jd-cmd - Command line Java Decompiler

jd-cmd is a command line Java Decompiler which uses [JD Core from Java Decompiler](http://jd.benow.ca/) project. 

## Download

Find latest bits in **[GitHub Releases](https://github.com/kwart/jd-cmd/releases/latest)**.

## Requirements

[Java runtime](http://java.com/en/download/) is required in version 6 or newer.

## Usage - Command line

You can use the `jd-cli.bat` (Windows) or `jd-cli` (Linux/Unix) scripts to run the the JAR file.

    Usage: java -jar jd-cli.jar [options] [Files to decompile]
      Options:
        --displayLineNumbers, -n
           displays line numbers in decompiled classes
           Default: false
        --dontMergeEmptyLines, -dm
           disables merging multiple empty lines into one in the decompiled classes
           Default: false
        --escapeUnicodeCharacters, -eu
           escape unicode characters in decompiled classes
           Default: false
        --help, -h
           shows this help
           Default: false
        --logLevel, -g
           takes [level] as parameter and sets it as the CLI log level. Possible
           values are: ALL, TRACE, DEBUG, INFO, WARN, ERROR, OFF
           Default: INFO
        --outputConsole, -oc
           enables output to system output stream
           Default: false
        --outputDir, -od
           takes a [directoryPath] as a parameter and configures DIR output for this
           path
        --outputZipFile, -oz
           takes a [zipFilePath] as a parameter and configures ZIP output for this
           path
        --realignLineNumbers, -rn
           realign line numbers in decompiled classes
           Default: false
        --showDefaultConstructor, -dc
           show default constructor in decompiled classes
           Default: false
        --showLocation, -l
           displays Location info in decompiled classes metadata part
           Default: false
        --showPrefixThis, -st
           prefix with 'this' where possible in decompiled classes
           Default: false
        --skipMetadata, -sm
           skips metadata in decompiled classes
           Default: false
        --skipResources, -sr
           skips processing resources
           Default: false

## Credits

This project was originally forked from [JDCommandLine](https://github.com/betterphp/JDCommandLine). 

## License

* jd-cmd is licensed under [GPLv3](http://www.gnu.org/licenses/gpl-3.0.html) as the original JD-Core library.# JD-cmd
