# StoreDot

StoreDot is an Israeli battery technology company founded in 2012 by Doron Myersdorf, Simon Litsyn and Gil Rosenman, headquartered in Herzliya with an advanced technology campus in Irvine, California. It develops extreme fast charging (XFC) lithium-ion cells built on proprietary silicon-dominant anode chemistry, targeting the range and charging anxiety that gate mainstream electric-vehicle adoption. Its "100inX" roadmap sets 100 miles of range charged in 5 minutes (2024), 3 minutes (2028) and 2 minutes (2032). Strategic investors and partners include Daimler/Mercedes-Benz, BP, VinFast, Volvo, Polestar, Ola Electric, Samsung Ventures, TDK and manufacturing partner EVE Energy.

- Website: https://www.store-dot.com/
- Technology: https://www.store-dot.com/technology
- Battery: https://www.store-dot.com/battery
- Knowledge base: https://www.store-dot.com/knowledge/blog
- Secondary market listing: https://forgeglobal.com/storedot_stock/

## API surface

StoreDot is a hardware, materials and cell-manufacturing business. As of 2026-08-02 it publishes **no public developer API** — no OpenAPI/Swagger, GraphQL, AsyncAPI, webhook catalog, MCP server or A2A agent card was found on any StoreDot host, no `/.well-known/` path returns a document, there is no `llms.txt`, and no `api`/`developer`/`docs`/`app`/`portal`/`status`/`trust` subdomain of `store-dot.com` resolves in DNS. See `well-known/storedot-well-known.yml` for the full probe record.

## Artifacts

| Path | Type | Method |
|---|---|---|
| `llms/storedot-llms.txt` | LLMsTxt | generated |
| `security/storedot-domain-security.yml` | DomainSecurity | probed |
| `well-known/storedot-well-known.yml` | (probe record — no discovery surface published) | probed |
