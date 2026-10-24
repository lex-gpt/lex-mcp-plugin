# Lex MCP

Research Polish law with legislation, judgments, tax interpretations and professional regulations from the Lex MCP index. This plugin supplies a research skill and connects to the remote Lex MCP service. Indexed coverage and versions may be incomplete; verify the sources and dates before relying on a legal conclusion.

## Connect

Install the plugin in your host app, connect the Lex MCP connector, sign in with your Lex-GPT account and approve access on the Lex MCP consent page. The remote server is `https://api.lex-mcp.pl/mcp/catalog/messages`. OAuth uses PKCE; no API key belongs in this package or in a chat. Availability in public directories depends on review and publication; this package does not itself imply a public listing.

For Claude, the package includes `.claude-plugin/plugin.json` and `.mcp.json`. For OpenAI's portable plugin format, it includes `plugin.json` and `mcp.json`. The same research skill is shared by both. Existing API-key integrations keep their current endpoints and keys.

## Use

Ask for a provision, relevant judgments, a tax interpretation or a professional regulation. For example: “Znajdź art. 415 Kodeksu cywilnego i pokaż tekst źródłowy.” Give a legal date when researching a historical state. The skill searches, reads the relevant text and cites returned identifiers; it reports gaps instead of inventing sources.

## Access and data

The connection reads public legal sources. It does not grant access to private Lex-GPT conversations or user documents and cannot file or send legal documents. Account limits apply. Search terms, tool arguments and requested identifiers go to Lex MCP; its infrastructure processes and logs requests and diagnostic information. Results return to the host app. Avoid unnecessary personal or confidential details. The package executes no local programs and installs no dependencies.

Revoke access at [Connected applications](https://lex-mcp.pl/connections). See [privacy](https://lex-mcp.pl/privacy), [terms](https://lex-mcp.pl/terms) and [support](https://lex-mcp.pl/support). Publisher: Lazy Evaluated Solutions Piotr Kosecki. Contact: kontakt@lex-gpt.pl.

## License

MIT applies only to the files in this plugin folder (manifests, skill, documentation and asset). It grants no rights to the hosted server implementation, accounts, service or third-party legal source material.
