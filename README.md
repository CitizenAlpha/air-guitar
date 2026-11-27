# Air instruments

Two camera-played toys. Single static pages, no build step, no server. Tracking (MediaPipe) runs on the device; sound is synthesised with Web Audio.

## Air Guitar (`/`)
Draw strings of light with your fingers and play them, using the front camera.
- Pinch and drag to stretch a string (or pinch with both hands and pull apart).
- Flick your index finger through a string to play it. Longer strings play lower notes.

## Ba-Dum (`/drums/`)
A drum kit you play from across the room with full-body tracking.
- Prop the phone sideways, step back until head, shoulders and hands are in the mirror.
- Hold hands over the drums for 3 seconds to line up the kit, then strike down to play.
- Hands up for cymbals, low and central (or stamp your foot) for the bass drum.
- Loop records two bars to jam over. Touch and keyboard (Space F H J K L G ;) also work.

## H & H Europe Trucking Sim (`/trucks/`)
A 3D truck game (three.js). Home menu, Settings, Customise (colours and company name), Truck garage, then a Europe map to pick a country, truck and job.
- Drive in cab or outside view; forward, reverse, steering, brake, lights, hazards, parking brake, horn, made-up radio stations.
- Follow the sat-nav to the green zone, stop, press Release cargo. Earnings are saved in the browser.
- Keys: arrows/WASD, Space brake, P parking brake, L lights, H hazards, R radio, B horn, C view, E release.
- Truck makers are invented (Scanner, Dan, Mammoth, Bolt, Nordic); no real brands or logos.
- Skies are photographed HDRIs from Poly Haven (CC0), with trees and buildings painted out so only the sky remains (`trucks/sky/`).
- Ground, road, gravel, rock and wall grain come from Babylon.js Assets textures (grass, rockyGround, sand), CC BY 4.0, https://github.com/BabylonJS/Assets, turned into tileable detail maps (`trucks/tex/`).
- The previous version is kept playable at `/trucks-classic/`.

Hosted with GitHub Pages from `main`, root folder.
