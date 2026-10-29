# Extension recommendations via `devfile.yaml`

Recommendations are declared under `metadata.attributes['.vscode/extensions.json']`.

There is **no** committed `.vscode/extensions.json` file.

IDs match the lab test plugin-registry allowlist:
- `dbaeumer.vscode-eslint`
- `esbenp.prettier-vscode`
- `redhat.vscode-yaml`

## Try it

1. Create a Dev Spaces workspace from this Git URL.
2. Open with the **Dev Spaces Local/Remote Connector**.
3. Expect VS Code to prompt for recommended extensions (install from the cluster plugin-registry).
