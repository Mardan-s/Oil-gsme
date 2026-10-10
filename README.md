# Permian Wildcatter

A mobile oil-patch tycoon game. You start as a lease hound with $40,000 and a beat-up pickup in Reeves County, Texas. Sweet-talk ranchers into signing leases, drill wells, sell crude when WTI spikes, survive blowouts and lawsuits, and grow into a basin king.

It's one HTML file with no build step and no dependencies. Open `index.html` in any phone browser. Use "Add to Home Screen" to run it full screen. Progress saves on the device.

## What's in it

- **A living oilfield.** Each county is an animated isometric scene: pumpjacks nodding, derricks going up, tanker trucks on caliche roads, cattle, a windmill, tumbleweeds and dust devils, and a day-night cycle with gas flares glowing after dark. Every basin looks different: Permian desert, Eagle Ford oaks, Bakken snow and Gulf platforms. Hit + to zoom in and drag to look around. A classic plat map view is still there if you want it.
- **A 10-chapter story.** Your mentor Cal Brewer, a crew that joins as you go (Rosa the tool pusher, Skeeter the roughneck, June the pumper, Doc the geologist), a Fort Worth banker, the county sheriff, and Vivian Ashby of Ashby Petroleum, a rival who leases land out from under you. Each crew member gives a permanent perk, and they all talk to you while you play.

## How to play

1. **Lease.** Tap a section on the plat map. Survey it to learn the geology, then talk to the owner. Raise the per-acre bonus or give a bigger royalty (1/8 up to 1/4). Small talk, brisket and hardball can move them, but their patience runs out.
2. **Drill.** Choose vertical, or horizontal once you've unlocked it. Tap **Push** to make hole faster. Rich rock gives big wells and sometimes gushers. Poor rock gives dry holes.
3. **Sell.** Oil fills your tanks, and once they're full the extra spills. Tap **SELL** when the price is good, or build a pipeline that sells automatically above a floor price you set.
4. **Manage.** Wells decline like real shale wells. Refrac tired wells, fix breakdowns, and handle field events like kicks, haboobs, H2S alarms, Railroad Commission inspectors and royalty lawsuits.
5. **Expand.** Open new basins: Midland, Eagle Ford, Bakken, then deepwater Green Canyon.
6. **Sell the company.** After $25M in earnings you can sell to a major for Legacy points. Each point gives +8% income permanently. Then do it again, bigger.

Wells keep pumping for up to 8 hours while you're away.

## Sound

All sound is generated live with Web Audio. There are no audio files. That includes plucked-guitar stings for leases, gushers and new fields, a cash register with coins, diesel rigs, clanking pipe, owners who babble in their own voices, alarms, blowouts, and ambient prairie wind with pumpjacks nodding in the background. Sound effects, ambience and volume are in Company → Settings. On iPhone, turn off the silent switch to hear the game.

## Play it online

Enable GitHub Pages for this repo (Settings → Pages → deploy from branch, root). The game is then served at `https://<user>.github.io/Oil-gsme/`.
