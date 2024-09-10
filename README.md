# Dataform examples

## Debugging Dataform JavaScript

Debugging JavaScript

## External clients

This example shows the basics of how to define constant variables within the includes directory and how to reference them.

We can reference them both within a SQLX or directly in a JavaScript file.

```ps1
dataform compile
Compiling...

Do not need a SQLX
{ name: 'test-01' }
{ name: 'test-02' }
Within a SQLX
{ name: 'test-01' }
{ name: 'test-02' }
Compiled 1 action(s).
1 operation(s):
  dataform.external
```
