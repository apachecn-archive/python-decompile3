---
name: Bug report
about: Tell us about Mythril bugs to help us improve

---

__Note:__ Have you read [How to report a Bug](https://github.com/rocky/python-uncompyle6/blob/master/HOW-TO-REPORT-A-BUG.md)?

Please remove any of the optional sections if they are not applicable.

## Prerequisites

* Make sure the bytecode you have can be disassembled with a disassembler.
* Don't put bytecode and corresponding soruce code on any service that requires registration to download.
* When you open a bug report there is no privacy. If the legitimacy of the activity is deemed suspicous, I may
  flag it as suspicious, making the issue even more easy to detect.

Bug reports that violate a prerequisite may be discarded.

Note that there are way more bug-fix requestors than there are bug
fixers. If you want you need more immediate, confidential or urgent assistance

[Crazy Compilers](http://www.crazy-compilers.com/decompyle/) offers a
byte-code decompiler service for versions of Python up to 2.6.

## Description

Replace this text with a clear and concise description of the bug.

## How to Reproduce

Please show both the input you gave and the
output you got in describing how to reproduce the bug:

or give a complete console log with input and output

```console
$ uncompyle6 <command-line-options>
==== Exception state ====
Type: ...
Contract: ...
Function name: ...
...
$
```

If there is a Solidity source code, a truffle project, or bytecode
that is involved, please provide that or links to it.

## Expected behavior

A clear and concise description of what you expected to happen.

## Environment

_This section sometimes is optional but helpful to us._

Please modify for your setup

- Uncompyle6 version: output from  `uncompyle6 --version` or `pip show uncompyle6`
- Python version: `python -V`
- OS and Version: [e.g. Ubuntu bionic]

## Additional Environment or Context

_This section is optional._

Add any other context about the problem here or special environment setup