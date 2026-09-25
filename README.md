# The Fox & the Fiddle

An original third-person 3D rubber-hose-style boss duel and companion experimental WebXR mode. Entire game and three.js runtime are bundled inline into each standalone HTML file. No Cuphead assets or characters are used. No remote script dependencies; optional remote web fonts fall back to local Georgia/sans-serif.

- `index.html` desktop edition: WASD or arrows move, Space or click shoots, Shift dashes, E parries pink shots.
- `vr.html` experimental WebXR edition: enter immersive VR with the browser's button; triggers shoot, grips dodge/parry. Desktop fallback has the same keyboard controls. WebXR needs HTTPS, a compatible headset/browser, and a secure context. Not headset-tested in this environment.

Desktop verified in local Chrome/SwiftShader at 1440 × 900: canvas rendered, original stage and characters inspected, firing hit the boss, health meter and score updated, no page errors. VR button detected in desktop browser as "VR NOT SUPPORTED"; immersive headset path is unverified. Served as static files with no server backend. No cost-bearing dependencies.
