# PokeFate BLUE para Foundry VTT 14

Sistema base en español, versión 0.1.0: fichas de entrenador y Pokémon, casillas HP/MP, entradas editables para movimientos, habilidades, proezas y objetos, tiradas Fate e iniciativa. Incluye el manual PDF original completo.

## Instalación con enlace

En Foundry VTT 14, abre **Sistemas de juego → Instalar sistema** y pega esta URL en **URL del manifiesto**:

```
https://raw.githubusercontent.com/Yotok798/PokeFate-Blue-Foundry-VVT/main/system.json
```

Pulsa **Instalar**. Después crea un mundo nuevo y selecciona **PokeFate BLUE**. Entra como director para que se cree el diario del manual.

El manifiesto público apunta a una revisión fija del ZIP para mantener estable esta descarga. No uses la URL de la página de GitHub ni el JSON del manual como manifiesto de instalación.

## Instalación manual

Descarga `PokeFateBLUE_Foundry14_v0.1.0.zip`, cierra Foundry y extrae la carpeta `pokefate-blue` dentro de `Data/systems/`. Debe quedar `Data/systems/pokefate-blue/system.json`. Reinicia Foundry y crea el mundo.

## Alcance y validación

Es una versión inicial con automatización parcial. Captura, evolución, entrenamiento, tipos, daño y efectos se resuelven manualmente; no incluye una Pokédex de actores ni un catálogo completo de objetos arrastrables. El contenido íntegro del libro se consulta en el manual.

Se ha validado la estructura del ZIP, los archivos JSON, la sintaxis JavaScript y las plantillas. **Todavía no se ha probado dentro de una instancia real de Foundry VTT 14.** No se declara compatibilidad verificada. Si aparece un error, registra la compilación completa de Foundry y el mensaje de consola.

El archivo `PokeFateBLUE_Manual_Foundry.json` es solamente un diario importable. El ZIP es el sistema de juego.

El LEEME incluido en el ZIP describe su preparación original, anterior a esta publicación. Para la URL de instalación vigente, usa este README y el `system.json` de la raíz del repositorio.

## Créditos

Contenido del PDF PokeFate BLUE 1.0.3 facilitado por el usuario; contacto indicado en el libro: Discord @Daluck98. Obra de fans, no comercial y no afiliada a Nintendo, Game Freak ni The Pokémon Company. Se conservan todos los créditos y condiciones del PDF, incluidos los de Fate y Evil Hat Productions y la prohibición indicada de venta o uso con fines de lucro.
