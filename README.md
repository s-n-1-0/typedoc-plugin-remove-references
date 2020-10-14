[typedoc](https://github.com/TypeStrong/typedoc) plugin to remove re-exports references. Look into the [issue](https://github.com/TypeStrong/typedoc/issues/1271).

## Usage

```bash
npm i typedoc-plugin-remove-references
```

Add `typedoc-plugin-remove-references` to typedoc [options](https://typedoc.org/guides/options/#plugin).

```typescript
{
  plugin: ['typedoc-plugin-remove-references']
}
```