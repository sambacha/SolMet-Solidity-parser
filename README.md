# SolMet

SolMet is a static analysis based metric calculator tool for Solidity smart contract programs.
It is a * Work In Progress *, supporting the following size and complexity metrics
* SLOC - number of source code lines
* LLOC - number of logical code lines (lines without empty and comment lines)
* CLOC - number of comment lines
* NF - number of functions
* WMC - weighted sum of McCabe's style complexity over the functions of a contract
* NL - the deepest nesting level of control structures in functions summed for a contract

## Building the tool

You can build the tool with Maven.

## Using the tool

Usage is very simple, the built jar is executable.
It requires two parameters: i) a Solidity file or a folder containing Solidity files ii) an output csv file path.

## Output

The output is a comma separated file containing the values of the calculated metrics for each analyzed contracts/libraries/interfaces.

## Credits

The parser is based on the excellent antlr4 grammar available at https://github.com/solidityj/solidity-antlr4.