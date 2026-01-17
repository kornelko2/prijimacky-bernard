# Přehled dat — spuštění

Tento jednoduchý HTML soubor načítá data z `lycemoum_2025.json` přes HTTP. Prohlížeče většinou zakazují fetch lokálních souborů přes `file://`, proto spusťte malý lokální server.

Spuštění rychlého serveru (PowerShell):

```powershell
python -m http.server 8000
```

Po spuštění otevřete v prohlížeči:

```
http://localhost:8000/index.html
```

Alternativa (Node):

```bash
npx http-server -p 8000
```
