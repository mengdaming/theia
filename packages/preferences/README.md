# Theia - Preferences Extension

Preferences implementation for the preferences-api defined in core. This provides two preference providers, one for the user home directory, and one for the workspace, which has precedence over the previous one. To set preferences, create or edit a `settings.json` under the `theia` folder located either in the user home, or the root of the workspace.

Example of a `settings.json` below:

```typescript
{
    // Enable/Disable the line numbers in the monaco editor
	"editor.lineNumbers": "off",
    // Tab width in the editor
	"editor.tabSize": 4,
	"files.watcherExclude": "path/to/file"
}
```

## License
[Apache-2.0](https://github.com/theia-ide/theia/blob/master/LICENSE)