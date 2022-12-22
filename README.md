# JsonKeyFindNReplace
This code can perform search and replace in JSON keys. It can handle array of JSON as well.


Input to this program can be in the following way :

    If you have to process only a single JSON object , then run with input args in order => <absoulte path of input file> <absolute path of output file>
    ex: input file contains something like [{}]

    If you have to process array of JSON objects , then your input file should look like : [{},{}]

It can search all keys with the character mentioned in constant charToSearch. Then it will replace it with character mentioned in constant charToReplace

For a sample demonstration, I have chosen to replace . with ~ character in Keys.
