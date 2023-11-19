Have you ever wanted to play some of the biggest slaughter maps ever conceived but the maps are just too laggy, even without mods on GZDoom?
Maps such as Oreo Cake Massacre, Okuplok, Profane Promiseland, Dimensions and more?
You've come to the right place.

# Maphancer
## The GZDoom Map Optimizer

This is a community driven mod where people can submit WADs (or PK3s, the type doesn't matter) that have a lot of monsters in them, where the team will investigate and add the maps in manually.
As a result, some maps may not even be added yet - but you can help change that by submitting the map by creating a new issue and providing the download page for it.

### How does it work?
Optimizing occurs in one of two ways:
* Freezes monsters entirely so they cannot act at all
-- OR --
* Despawns monsters

### What engines does this work on?
Only on GZDoom and any port based off of it, i.e. VKDoom.

### What maps don't work?
A large number of maps aren't allowed for a variety of reasons, including but not limited to the most prominent:

* The lag can be caused by having a very high vertex/line/sector count. An example of this is S.U.P.E.R. Natural's radio tower and power generator base, almost entirely deserted with < 10 monsters at all times.
* The map has ACS code that checks certain thing(s) health. With the Despawn option, those scripts will break immediately.
* The map is still in active development or is less than 6 months old
