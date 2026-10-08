# Skyltsystem – TV-app

Installationsfiler för Skyltsystemets app på Samsung-skärmar (SSSP, Install Custom App).

Skärmen hämtar `sssp_config.xml` och `Skyltsystem.wgt` härifrån via jsDelivr:

```
https://cdn.jsdelivr.net/gh/benjaminasf/skyltsystem-tv@main
```

Filerna ligger här i stället för på Skyltsystemets egen server eftersom skärmarnas installationsfunktion inte godtar den serverns certifikatkedja. Appen är ett tunt skal som öppnar Skyltsystemets server. Den byggs och signeras i huvudprojektet med `npm run build:tv`.
