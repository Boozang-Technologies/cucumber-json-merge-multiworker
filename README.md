# junit-merge
NodeJS CLI for merging JUnit XML test results

[![CircleCI](https://circleci.com/gh/drazisil/junit-merge.svg?style=shield)](https://circleci.com/gh/drazisil/junit-merge) [![Coverage Status](https://coveralls.io/repos/github/drazisil/junit-merge/badge.svg?branch=master)](https://coveralls.io/github/drazisil/junit-merge?branch=master)

### Installation

    npm install -g junit-merge

Or just download the repository and include it in your `node_modules` directly.

### Usage

 ```
  Usage: junit-merge [options] <xmlFile1.xml> [xmlFile2.xml..]

  Options:

    -h, --help              output usage information
    -V, --version           output the version number
    -d, --dir <path>        merge all results in directory
    -r, --recursive         pass to recursively merge all results in directory
    -o, --out <mergedfile>  file to output to
```

### Contributing

Feel free to submit issues and/or PRs!  In lieu of a formal style guide, 
please follow existing styles.
