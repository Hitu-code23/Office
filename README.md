# Velorien Agent Office

An interactive 3D concept demo by **[Velorien Creative Studio](https://velorienstudiocreative.com/)**, Dubai.

Twenty-seven AI agents in nine teams, led by Director Harsh, work in a three-floor office on a floating island at sunset, with an island on each side: one for the academy, sports, events and a marina, and one for Client Street, a beach club, villas, a power tower, the Booking Tower and a farm. Six teams (Scouts, Research, Writers, Sending, Replies, Booking) take a lead from *Found* to *Booked*, Design and Delivery build and launch the client's website, and Marketing runs their social media, Google ranking and ads.

**Live demo:** https://hitu-code23.github.io/Office/

> **Concept demo.** Every lead, business name, number and message is simulated. Nothing here is real client data, and no real emails are sent.

## What you can do

- **Watch the pipeline:** leads fly between the teams as glowing cubes, and bookings set off a celebration.
- **Tap anyone or anything:** agents, staff, the café, the meeting room, the Lead Vault, the client lounge, the chill zone and the terrace each have their own card.
- **Explore the office:** a client lounge with a big screen showing new websites, a chill zone with ping pong, beanbags and an arcade, and a terrace with a lit pool and loungers. Upstairs: the Marketing team, a content studio, a gym and a dining hall, reached by stairs. Out front: a gate, driveway, parking and a fountain garden.
- **Third floor:** a glass penthouse with the AI lab (a hologram of the Shared Brain, GPU racks, a robot arm) and the boardroom (its screen shows the live pipeline), plus a rooftop garden next to the helipad.
- **The annex island:** an academy tower (coworking downstairs, a classroom upstairs) joined to the office by a glass sky bridge; a padel court and cricket nets with live play; an events stage with a big screen and coloured beams at night; and a marina with a pier, the Marina Café and a yacht that goes for a loop and brings VIP clients.
- **The east island:** Client Street (seven shops, each window showing a client's website; tap a shop to open the live site), a beach club (pool bar, cabanas, beach volleyball, a putting green, jet skis), three villas whose windows light up when the team goes home, a power tower with solar panels, wind turbines and an energy beam to the AI lab, the Booking Tower (one floor lights up per meeting booked, fireworks when all 24 are lit), greenhouses with a produce cart, a football pitch and a running track. A second sky bridge joins it to the office.
- **Office life:** clients arrive by car and are shown to the lounge, birthday cake and a team photo, a Friday pizza drone, a night guard with a torch and a cleaning robot. Writers look stressed when replies are slow, and the whole floor cheers when a meeting is booked.
- **More spaces:** a helipad on a glass deck above the studio (reached by a glass lift, where a helicopter lands now and then), a podcast booth, a server room that flashes when emails go out, a library upstairs and a kids' corner in the lounge.
- **Change the mood:** a day-to-night slider, midday sun, weather (rain, dust storm, mist), and occasions (UAE National Day, Ramadan with an iftar table, Eid, Diwali, autumn leaves, a Christmas tree in reception). Occasions switch on by date.
- **Real Dubai time:** in Live mode the sun follows its real path over Dubai, so it rises in the east, sits high at midday and sets in the west, and night falls when it really does. The clock shows the time in Dubai. Drag the slider to pick any time yourself.
- **Realistic details:** smooth cars with tinted glass, alloy wheels and lights; people with rounded heads, eight hair styles, shoes and knees that bend as they walk and sit; glass and car paint that reflect the world around them; a pool that mirrors the sky, ripples in the wind, shows light patterns on its floor and glows at night.
- **Wind and storms:** before rain the wind picks up, so trees bend, the flags at the gate flap and the pool ripples. Heavy rain brings lightning and thunder.
- **Hidden roof:** it lives underground. When rain starts, posts and beams rise out of the floor and glass slides across the top to keep the office dry. When the rain stops, it slides back and sinks out of sight.
- **Watch mode:** the camera cuts between live shots by itself.
- **Build your own office:** rebrand it (name, colour, logo, team names), then copy a share link that opens the office with that brand, or download a branded copy.

## Controls

| Action | Mouse | Touch |
| --- | --- | --- |
| Rotate | Drag | Drag |
| Zoom | Scroll | Pinch |
| Select | Click | Tap |
| Move around the islands | W A S D or arrow keys | Joystick (bottom right) |

The menu (☰) holds Tour, Watch, Sound, Photo, speed, time of day, quality, weather, occasions, camera controls and the activity feed.

## Link options

| Add to the link | What it does |
| --- | --- |
| `?lite=1` | Lighter build for slow devices |
| `?fx=1` | Always use the full effects |
| `?time=17:30` | Starts the clock at that Dubai time (handy for showing a sunset) |
| `#office=…` | Opens a branded office (made with Copy share link) |

## Editing the Client Street shops

The shop names, notes, colours and links are in the `CLIENTS` list near the top of the script in `index.html`. Leave `url` empty if a site has no link yet, and set `soon:true` to show "Coming soon" in the window.

## Built with

A single `index.html` file: HTML, CSS and JavaScript with [Three.js](https://threejs.org/) r128. It works on desktop and mobile.

## Notes

- © Velorien Creative Studio. All rights reserved.
