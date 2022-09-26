# A copy of the MapComplete Schemas relevant for Theme editing

Copy and run those lines from within this folder.

```
wget -O LayerConfigJson.schema.json \
  https://raw.githubusercontent.com/pietervdvn/MapComplete/develop/Docs/Schemas/LayerConfigJson.schema.json
wget -O LayoutConfigJsonJSC.ts \
  https://raw.githubusercontent.com/pietervdvn/MapComplete/develop/Docs/Schemas/LayoutConfigJsonJSC.ts

wget -O LayerConfigJson.schema.json \
  https://raw.githubusercontent.com/pietervdvn/MapComplete/develop/Docs/Schemas/LayerConfigJson.schema.json
wget -O LayerConfigJsonJSC.ts \
  https://raw.githubusercontent.com/pietervdvn/MapComplete/develop/Docs/Schemas/LayerConfigJsonJSC.ts

npx prettier "./" --write

echo $(date +'%Y-%m-%d') > last-updated-at.log
```
