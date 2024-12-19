# TypeScript Optional Property Handling

This example demonstrates a common error in TypeScript related to handling optional properties in objects. The `printCoord` function assumes that the input object always has `x` and `y` properties, but if these are omitted, a runtime error occurs. The solution shows how to safely handle optional properties using optional chaining or the `?` operator.