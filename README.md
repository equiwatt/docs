# Equiwatt SaaS API 

Equiwatt SaaS API documentation

## Development

Install mintlify dev tool

```
npm i -g mintlify
```

Generate docs
```
mintlify dev
```

If openapi endpoints change
```
npx @mintlify/scraping@latest openapi-file api-reference/openapi.json
```
