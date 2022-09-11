---
sidebar_position: 2
#
# This file is autogenerated. DO NOT MODIFY DIRECTLY
#
---

import ScriptEventPreview from '@site/src/components/ScriptEventPreview';

# Ekran

## Ekran: wyczyszczenie
Fade the scene from a blank screen.
<ScriptEventPreview title={"Ekran: wyczyszczenie"} fields={[{"key":"speed","label":"Szybkość","description":"The speed of the fade animation.","type":"fadeSpeed","defaultValue":"2"}]} />

- **Szybkość**: The speed of the fade animation.  

## Ekran: pojawienie
Fade the scene to a blank screen.
<ScriptEventPreview title={"Ekran: pojawienie"} fields={[{"key":"speed","label":"Szybkość","description":"The speed of the fade animation.","type":"fadeSpeed","defaultValue":"2"}]} />

- **Szybkość**: The speed of the fade animation.  

## Narzuta: schowaj (nie widzialna)
Hides the screen overlay.
<ScriptEventPreview title={"Narzuta: schowaj (nie widzialna)"} fields={[{"label":"Schowanie nakładanego okna na ekranie."}]} />


## Narzuta: przesuń
Moves the overlay to a new position on the screen.
<ScriptEventPreview title={"Narzuta: przesuń"} fields={[{"type":"group","fields":[{"key":"x","label":"X","description":"The horizontal position.","type":"number","min":0,"max":20,"defaultValue":0,"width":"50%"},{"key":"y","label":"Y","description":"The vertical position.","type":"number","min":0,"max":18,"defaultValue":0,"width":"50%"}]},{"key":"speed","label":"Szybkość","description":"The movement speed.","type":"cameraSpeed","defaultValue":"0"}]} />

- **X**: The horizontal position.  
- **Y**: The vertical position.  
- **Szybkość**: The movement speed.  

## Narzuta: pokaż (widzialna)
Show either a black or white window over the top of the current game screen. Can be used to obscure and then reveal parts of the scene background for example on the sample project logo screen.
<ScriptEventPreview title={"Narzuta: pokaż (widzialna)"} fields={[{"key":"color","label":"Fill Color","description":"The color to fill the overlay with, either black or white.","type":"overlayColor","defaultValue":"black"},{"type":"group","fields":[{"key":"x","label":"X","description":"The horizontal position.","type":"number","min":0,"max":20,"defaultValue":0,"width":"50%"},{"key":"y","label":"Y","description":"The vertical position.","type":"number","min":0,"max":18,"defaultValue":0,"width":"50%"}]}]} />

- **Fill Color**: The color to fill the overlay with, either black or white.  
- **X**: The horizontal position.  
- **Y**: The vertical position.  
