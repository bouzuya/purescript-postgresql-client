# purescript-postgresql-client

purescript-postgresql-client is a PostgreSQL client library for PureScript.

## Install

To use this library, you need to add `pg` and `decimal.js` as an npm dependency. You can also
find this npm library on [https://github.com/brianc/node-postgres][pg].

## Preprocessing static SQL statements

The purspgpp preprocessor has been replaced by [sqltopurs], which is a code
generator instead of a preprocessor, and easier to use.

[sqltopurs]: https://github.com/rightfold/sqltopurs

## Testing

To run test you have to prepare "purspg" database and use standard command: `pulp test`
