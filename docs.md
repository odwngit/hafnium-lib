# Documentation
This is a very basic document which explains the Hafnium format.
## Syntax
- Values in Hafnium are defined starting with a `:` (colon). Example:
> :value
- Lists in Hafnium are defined starting the lines with a `[`, and ending the lines with a `]`. Example:
```
[
value1
value2
value3
]
```
- Notes for the reader/user of the document are defined starting with a `;` (semicolon). Example: [^1]
> ;This shouldn't be read by the compiler.
- At the start of every Hafnium file, is the identifier. This tells the computer what Hafnium format it is, which shows how to read it. Example:
`<identifier>`

[^1]: Remember, Hafnium's purpose is to make it easy for both the computer and human reading the file.
