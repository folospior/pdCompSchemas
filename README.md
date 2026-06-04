# pdCompSchemas
![GitHub License](https://img.shields.io/github/license/folospior/pdCompSchemas)

Schemas for pdComp charges, citations, and court personnel.

This gives you nice completions in your editor, as well as some validation for enums.

Makes for a much comfier editing experience.

# How to use:

In your `.json` files, specify the schema by the raw link provided by GitHub:

- `charges.json`:

```json
{
  "$schema": "https://raw.githubusercontent.com/folospior/pdCompSchemas/refs/heads/main/charges.schema.json"
}
```

- `citations.json`:

```json
{
  "$schema": "https://raw.githubusercontent.com/folospior/pdCompSchemas/refs/heads/main/citations.schema.json"
}
```

- `court_personnel.json`:

```json
{
  "$schema": "https://raw.githubusercontent.com/folospior/pdCompSchemas/refs/heads/main/court_personnel.schema.json"
}
```
