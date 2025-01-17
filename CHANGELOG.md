### 1.1.11 2019-11-05

- fix generic type parameters of inline-imports

### 1.1.10 2019-10-03

- fix leading comments being removed from rendered chunks
- fix issues with multiple inline-imports

### 1.1.9 2019-10-03

- support `RestType` Nodes

### 1.1.8 2019-09-30

- make it compatible with `rollup@1.22`

### 1.1.7 2019-09-09

- make it compatible with `rollup@1.21`

### 1.1.6 2019-07-31

- further improve computed property handling
- add support for `bigint` type

### 1.1.5 2019-07-01

- properly handle computed properties

### 1.1.4 2019-06-21

- fix issues around default exports and overrides

### 1.1.3 2019-06-21

- fix duplicated definitions when having circular imports on windows

### 1.1.2 2019-06-18

- normalize directory separators on windows

### 1.1.1 2019-06-16

- correctly preserve tripleslash reference directives

### 1.1.0 2019-06-07

- Re-add support for directly using `.ts` files.
- Fix type parameters with `extends` constraints.

### 1.0.0 2019-06-05

- This release focuses on working with pre-generated `.d.ts` files.
- Thus, this release drops support for transpiling `.ts` -> `.js`.
- Support for namespace re-exports and dynamic imports of namespaces.
