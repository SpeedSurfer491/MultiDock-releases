# MultiDock

En docka för varje skärm på macOS. Här finns de färdiga versionerna av MultiDock att ladda ned.

## Installera

1. Ladda ned den senaste `MultiDock-<version>.dmg` under [Releases](https://github.com/SpeedSurfer491/MultiDock-releases/releases/latest).
2. Öppna DMG-filen och dra MultiDock till Program-mappen.
3. Starta MultiDock från Program-mappen.

MultiDock är gratis och inte notariserad av Apple, så första gången säger macOS att appen inte kan kontrolleras för skadlig programvara. Det betyder bara att Apple inte har granskat den. Gör så här en gång:

1. Klicka på **Klar** i varningen, inte på "Flytta till papperskorgen".
2. Öppna **Systeminställningar → Integritet & säkerhet** och rulla ned till avsnittet **Säkerhet**.
3. Klicka på **Öppna ändå** vid MultiDock och bekräfta med ditt lösenord eller Touch ID.
4. Klicka på **Öppna** i rutan som visas.

Föredrar du Terminal kan du i stället ta bort nedladdningsmarkeringen, så att varningen inte visas alls:

```bash
xattr -dr com.apple.quarantine /Applications/MultiDock.app
```

MultiDock ber sedan om behörighet för **Hjälpmedel** (för att flytta och hålla reda på fönster) och, om du slår på bilder i förhandsgranskningen, för **Skärminspelning**.

## Uppdateringar

MultiDock uppdaterar sig själv. Den kollar en gång per dygn efter en ny version här och frågar om den ska installeras, och du kan också välja "Sök efter uppdateringar…" i menyradsmenyn. Uppdateringarna är signerade, och en automatisk uppdatering behöver inte godkännas med Öppna ändå.

Har du version 1.0.18 eller äldre installerar du den senaste versionen för hand en gång, enligt anvisningen ovan.

## Källkod

Källkoden till MultiDock är inte offentlig. Arkiven "Source code (zip)" och "Source code (tar.gz)" under varje version skapas automatiskt av GitHub och innehåller bara den här texten. Det är `.dmg`-filen du ska ladda ned.

Kräver macOS 27.
