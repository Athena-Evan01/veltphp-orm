# Velt ORM

Active record ORM, relations and model layer for the Velt PHP framework.

## Role

This package starts in Module 3. It builds on `veltphp/database` and exposes the expressive model API used by applications:

```php
User::find(1);
User::where('email', $email)->first();
$user->save();
```

## Scope

- Active record base model.
- Object hydration and persistence.
- Minimal mass assignment protection.
- Relations such as `hasMany` and `belongsTo`.
- Pagination result objects.

## Boundaries

- SQL primitives, query builder, schema builder, migrations and seeders start in `veltphp/database`.
- CLI commands for migrations and seeders live in `veltphp/cli`.
- Package assembly and compatibility documentation live in `veltphp/framework`.

## Module 3 Issues

- Issue 01: create the active model layer.
- Issue 02: add relations and pagination.
