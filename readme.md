A typescript template repo

- circular dependency check ran at build time
- absolute imports supported (`import foo from 'bar/baz'` vs `import foo from '../../bar/baz'`)
- `npm run util:rimraf` to clear node modules
- `npm run util:circular` to check for circular deps
