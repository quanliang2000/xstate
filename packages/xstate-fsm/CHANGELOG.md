# @xstate/fsm

## 1.3.0

### Minor Changes

- 3c10215: A `config` property got exposed on created machines. It's the same object which got passed in as argument.

### Patch Changes

- a337473: Fixed entry actions defined on an initial state not being executed.

## 1.2.0

### Minor Changes

- 3cda398: The `assign()` action creator is now strongly-typed, and takes the context and event types as generic parameters, just like in XState core.
- 61ccfbd: Make `interpret` default for `TEvent` type parameter more strict. It's now `EventObject` instead of `any` and it matches the default on `createMachine`.

### Patch Changes

- 15fc24c: Export `Typestate` type.
