# sample.aya

A sample aya package that defines angle conversion utilities


## Package Structure

  - `init.aya`: The entrypoint for the package. This file should bring package variables into scope. It should generally only have import/require statements in it
  - `package.json`: Package metadata
    - `name`: The package name
    - `version`: Version is `major.minor.patch` format
    - `author`: Package author
  - `src/`: Location of aya source files
  - `test/`: Location of aya test files. All aya files in this folder will be ran when using `pkg.test`


## Installation Options

### 1. Package Manager (CLI)

If you have `aya` on your system path, install with `aya pkg`

```
aya pkg add aya-lang/sample.aya
```

### 2. Package Manager (`pkg`)

From within aya,

```
import pkg
"aya-lang/sample.aya" pkg.add

```

### 3. Manual

Clone or download this package direcctly into the `pkg` directory of your aya installation.



