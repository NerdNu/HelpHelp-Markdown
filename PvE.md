server: PvE

rev-number: 30

rev-date: 'Jun 1, 2024'

rev-post: 'https://nerd.nu/mc/pve'

====
## Default
`bukkit.command.help`
> Use `/help help` to learn about the help system. Read this help in your web browser at http://nerd.nu/help/pve.

* PvE
* Creative
* Features
* Rules
* FAQ
* Map
* Places
* ModReqs
* Stuck
* Locks
* Region Locks
* Claims
* Protection
* Towns
* Farms
* Grinders
* Iron Grinders
* Arenas
* Restarts
* Liquids
* Fire
* Portals
* Beds
* Spawn
* Custom Drops
* Doppelgangers
* Elytras
* Horses
* Minecarts
* MapWorld
* Teleports
* Lag
* Redstone
* Revisions
* Help
* Bans
* X-Ray
* Grief
* Web
* Servers
* Mumble
* Discord
* Steam
* Nerd
* Staff
* Donate
* Volunteer
* Plugins
* Commands
* Aliases

====

### Arenas
> About PvP arenas.

While PvP (player-vs-player combat) is disabled by default on PvE, you can build PvP
arenas where PvP will be enabled, subject to approval by the P admins. Once
you have completed your build, do a `/modreq` to ask for the PvP flag to be set.

To be approved, PvP arenas must be clearly marked, completely enclosed, and
access-restricted builds. The area must only be accessible via iron doors or redstone gates that
require a button press to enter. These entrances must be marked with signs
stating that it is a PvP area, and that players enter at their own risk. The
PvP-enabled area may not exceed 200x200 blocks, and may not interact with other
PvP areas in any way.

You may also use '/pvp on' to PvP outside PvP arenas.


### Bans
> If you are banned.

If you are banned, you will not be unbanned automatically. You must make a
written appeal asking to be unbanned at http://nerd.nu/appeal.

Do not play on the server using another account while
you are banned; that is against the rules.


### Beds
> About beds.

You can set your spawn point by clicking on a bed. If you do not sleep frequently, Phantoms may spawn in your proximity and attack you! If 60% of the players online sleep, night will pass.


### Claims
> Claiming land to build on.

Land claims indicate areas which you intend to build within. Once you have a rough claim fence installed /modreq to have a moderator create your claim. A build-allow region will then be created for your claim, which will allow for everyone to gather resources from the area but also make it clear that the area is claimed. If you want to find out if you are currently in a region, use /rg i. Claims should be rectangular with clearly marked corners and fences made from non-natural blocks. They do not need signs or for the fence to form a continuous wall. Claims should not be excessively large and, while not required, we recommend a buffer of 3-5 blocks between claims. Claims must be used within a reasonable timeframe and cannot encompass other claims.

Admins reserve the right to invalidate a claim for any of the following reasons: Being too large (larger than you will reasonably use), claiming an area solely for access to resource mining, encircling another claim in an effort to take over, an incomplete or poorly identifiable claim fence, or violating any other build rules currently in place.
Don't block waterways with your claim fence, place it one block above the waterline or place regular access points.
It is best practice to allow a three to five block buffer between your claim and the nearest claim fencing for server harmony.
Claims and the builds associated with them should not block off areas of the map.



### Commands
> Full list of commands.

The help system is still under development. A future version will show a full
command list here.

For now, try `/help Plugins` or `/help <command>`.


### Custom Drops
> Custom items dropped by mobs.


All hostile and passive mobs have a small chance of dropping their head when
killed by a player, or always when killed by a charged creeper. If Minecraft has a standard head for the mob (the dragon, skeletons, zombies and creepers) then that item will be dropped. Otherwise, it will be a
player head with a skin that matches the mob. For example, witches drop the
*MHF_Witch* player head.

The drop probabilities of these custom drops and the player skin names are
listed in the configuration of the GoneBatty plugin, at http://goo.gl/mJpFqy.

A Custom currency will randomly drop from items, blocks, and mobs. Items and blocks must be broken by the player, and mobs must be killed by the player for the chance of a drop. 

Heart fragments will drop from ocean related blocks and items. You can use heart-fragments to create a Heart of the Sea. 

Pokemine Cards have a chance to drop from most blocks, items, and mobs.



### Discord
> About Discord text and and voice chat.

Discord does text and voice chat in the browser, or with a downloadable client.
Check it out at https://discord.gg/dKFfHY3.

See also `/help Mumble`.


### Donate
> How to support the servers.

You can donate to help the server at http://nerd.nu/donate.


### Doppelgangers
> Custom summonable hostile mobs.

Doppelgangers are summonable, custom hostile mobs. In the current
configuration, they are extremely strong and well-armed wither skeletons.
They drop the player head of your choosing. To summon a doppleganger, name a
carved pumpkin after the player whose head you want, using an anvil. Then stack
two diamond blocks vertically and put the pumpkin on top, sort of like
summoning a snow golem. Note that you need to leave a one-block air gap on all
sides of the pillar of blocks.

The PvE server admins (P admins or Padmins) have special doppelgangers that
are twice as expensive as regular players' doppelgangers. To summon a Padmin
doppelganger, you must place the named pumpkin on a T shape built from four
diamond blocks, instead of two. Padmin doppelgangers are even stronger than
regular doppelgangers, always appear as a group of all current Padmins when
you summon any one of them, and the summoned Padmin drops the respective
Padmin's head. You can find a current list of Padmins on the
NerdNu staff page at http://nerd.nu/staff.




### Elytras
> How to get elytras.

All naturally generated elytra has been removed from the end ships.
One month after the start of the rev, elytra will be available by spawning the dragon in the end and successfully beating the multi-part dragon fight.



### Farms
> About farms.

There are many farms on the map where players can get food. If you harvest
crops, you must replant. Not replanting can result in a ban.

If you come across an un-replanted field, ModReq it for crop grief.


### FAQ
> Frequently-Asked Questions

#### Why doesn't my water/lava flow?

To prevent grief. You can make it flow with `/modreq flow`. See `/help Liquids`. You can also flow water inside a claim that you own by typing /flow and punching the top of the block the water is sitting on.

#### Why can't I open my chest/door/whatever?

You may be holding a wooden sword, which queries the WorldGuard region of
whatever you click on. Alternatively, maybe the chest is locked by someone
else? See `/help Locks`.

#### Why isn't my hopper working?

Run `/chopper on` and then punch the container (e.g. chest, furnace) that the
hopper is feeding into. That will probably fix it.

#### Why can't I build here?

You're in a protection region. See `/help Protection`. You may even still be
at spawn. Move further away and you will find unbuilt land.

#### How can I join a town?

Towns usually have a protection region that is the same as their name.

Try `/region info <town>`, and then contact one of the players listed as a
region owner.

#### What are the towns called?

Most towns have an associated _place_. See `/help Places`.

#### Why can't I light a portal?

Portals connect up weirdly in Minecraft when they are too close together.
The admins pre-make a number of portals when they build the map. To light a portal, you must build the portal frame, purchase 1 portal shard per portal space from the trader at spawn (a 2x3 portal would cost 6 shards), place those shards in a chest near the portal frame, then types /modreq please light this portal and name it …..

See `/help Portals`.

#### Can I get a teleport to _wherever_?

There is a sign at spawn that will teleport you to a random location. You cannot teleport to a specific location, you will need to walk, ride a vehicle or use a portal instead. 

#### Why does the server restart (so often)?

Minecraft and its plugins just run better when restarted every few hours.
See `/help Restarts`.

#### When is the next rev?

See `/help Revisions`.


### Features
> Special features of this server.

Many special features of PvE are discussed in the **PvE Rev ${rev-number} Info Post**
${rev-post}.

PvE is a substantially vanilla Minecraft survival mode server. Plugins have been added
to allow chests and other containers to be locked (`/help Locks`) and to
protect builds from unauthorized edits (`/help Protection`). To prevent
unauthorized edits using water or lava, liquids don't flow until requested by a
ModReq (`/help ModReq`, `/help Liquids`).

Private chat for self-managing groups of players is provided by NerdClanChat
(`/help NerdClanChat`).

Tamed horses cannot be ridden except by their owner, but can be shared with
commands (see `/help Horses`). Horses are improved through training, rather
than by breeding.

We have a Mumble server for voice chat. See `/help Mumble` and a discord for voice and chat. See /Discord. We also have a top-down dynamic map and an isometric cartograph. See `/help Map`.

You can build custom maps to place in item frames. See `/help MapWorld`.

PvP is allowed in designated PvP arenas. See `/help Arenas` or outside of arenas with /pvp on.


### Fire
> Using fire.

Fire spread is disabled on PvE. You can light your own fires with flint and steel.


### Grief
> Rules about unauthorized edits.

The word "grief" is used to refer to any unauthorized edits to the world. It
is against the rules to edit other players' builds without their permission.
You are allowed to harvest other players' farms, but you must replant.

You are also allowed to kill farm animals (sheep, pigs, cows and rabbits), but
you must leave a breeding pair of each color or type. It is against the
rules to kill tamed pets (cats, dogs) or trapped hostile mobs.


### Grinders
> About grinders.

You can build mob grinders around spawner blocks, in ocean monuments and using
various other game mechanics. If you find a spawner, you can ModReq to get it
protected against grief, even if you haven't built anything there yet.

You can also build dark room grinders, but the chances are they won't perform
as well on a multiplayer server as they would in the single player game.

There will no longer be any requirement to have 100% of the drops remain public
or any minimum percentage split. Exceptions are end grinders, guardian grinders, blaze grinders and the custom spawners, which must remain 100% public only at all times.


### Iron Grinders
> About Iron Grinders and costs.

Due to the relative ease that high speed golem farms can now be created, we are allowing players to create their own vanilla golem grinders. This is due to new designs requiring far less villagers than before. 

Please be efficient with your villager usage and don’t use too many. The PAdmins reserve the right to convert any and all golem grinders to spawners if it is deemed that they are causing excessive lag.


### Help
> How to use the help system.

* `/help` - show the topic index
* `/help <n>` - read page _\<n\>_ of the index
* `/help <text>` - show help about _\<text\>_. The _\<text\>_ can be a topic
  title, the name of a plugin, the name of a command beginning with '/', or just
  some arbitrary search term.
* `/help <text> <n>` - show page _\<n\>_ of the search results for _\<text\>_.

Example: `/help features 2` - read page 2 of the "Features" topic.

Note: searches are case-insensitive.


### Homes
> About the `/home` command.

The `/home` command is disabled. The only way to set your home on PvE is to
sleep in a bed.


### Horses
> About horses on PvE.

Any horses you tame are automatically locked by the `EasyRider` plugin and
cannot be ridden by anyone else without your permission. `EasyRider` also
handles locking of llamas.

On PvE, all horses spawned naturally or by breeding have very poor performance
attributes. Their attributes are _only_ improved by training:

 * _Speed_ is improved by total horizontal distance traveled while on the ground.
 * _Health_ is improved by total weight of gold consumed, in the form of golden
   carrots and golden apples.
 * _Jump Strength_ is improved by total horizontal distance traveled in the air.

The current performance of a horse in each of these three abilities is
characterized by a _level_ number. The attributes of a horse in a particular
ability only change when the _level_ increases to the next whole number, and
each ability has a _maximum level_ beyond which further training will not
improve that ability.

To see the current ability levels of a horse, use `/horse-info`. To see
how much training is required to attain a particular level, use
`/horse-upgrades`. To see who has the best horse in a specific ability,
use `/horse-top`.

You can see a list of all horses you own with `/horse-list`, and you can get
directions to a specific horse with `/horse-gps`.

For more information about these commands, see `/help EasyRider` or the
plugin home page, https://github.com/NerdNu/EasyRider.


### Lag
> Guidance on reducing lag.

Large numbers of mobs contribute to server lag. As a result we are running
`MobLimiter`, which only allows you to keep certain quantities of mobs
(type `/moblimiter limits` for additional details). MobLimiter culls excess
animals when the chunk is unloaded, but it will always leave at least two of
each type, including 2-4 of each wool color.

Minecraft implements redstone very inefficiently. Even small redstone devices
contribute disproportionately to server lag. You should strive to minimize the
length of redstone wires and the frequency of signal state changes. Redstone
clocks are allowed but should always include an off switch and they should
not activate every tick.

Large numbers of hoppers can also lag the server. Wherever possible, try to move
items with flowing water over ice instead.

If you have questions please contact a moderator. See also `/help Redstone`.


### Lava
> About lava.

See `/help Liquids`.


### Liquids
> Non-flowing water and lava.

On this server, any water or lava you place will not flow on its own. If you
want your liquid to flow, place it and then type `/modreq please flow this`
and a moderator will flow it as soon as they are able.

Region owners are also able to flow liquids in their own regions using the
`/flow` command. Type `/flow` for more information.


### Locks
> Commands for locking containers.

You can lock chests, trapped chests, furnaces, shulker boxes, skulls, beacons,
dispensers, droppers, jukeboxes, hoppers, conduits, turtle eggs, brewing stands, and bee hives.

Additionally, you can now lock your armor stands and item frames too!

All of these blocks automatically lock privately to you when you place them,
but you can change who can access them using the following commands:

 * `/cmodify public` - Allows anyone to access the contents but not break the
   chest. Useful for "Free Stuff" chests.
 * `/cmodify donation` - Allows people to open the chests and put items
   inside, but only the owner can remove items.
 * `/cmodify <name>` - Add players to the access list.
 * `/cmodify @<name>` - Add a player as a lock administrator: someone who
   can add other players.
 * `/cmodify -<name>` - Remove a player from the lock.
 * `/cmodify r:<region>` - Grant access to all members of the named
   WorldGuard region.
 * `/cremove` - Removes all locks from the block and allows anyone to break
   it. If you just want to make a chest public, use `/cmodify public` instead.
 * `/cprivate` - Lock a chest privately after it has been `/cremove`d. You
   can also use player `<name>` or `r:<region>` arguments, as with `/cmodify`.
 * `/cpublic` or `/cdonation` - Lock a chest as public or donation after you
   have `/cremove`d it.
 * `/cpersist` - Make a single LWC command apply to multiple containers.
 * `/chopper on` - Allow hoppers to insert items into a container (e.g. chest)
   that you punch.
 * `/lwc` - See a list of other commands related to locking.

To view the commands related to locking or accessing an armour stand or item frame,
type `/help ItemLocker`

It is your responsibility to secure your valuables. If someone takes something
from a chest you gave them access to, we can not return it.

See also `/help LWC`.


### Map
> About the current map.

The map is a 8000 x 8000 square and is vanilla generation. The nether is 3000 x 3000 and
the end is 5000 x 5000. The end is custom generated by cheezychicken.

A top-down live map of the overworld can be seen at http://nerd.nu/maps/pve/live
and an isometric cartograph can be viewed at http://nerd.nu/maps/pve/.
However, note that the map will not be visible for an initial period at the start of the rev
to allow for exploration.


### MapWorld
> About the MapWorld.

Mapworld is a world accessible at spawn with an empty inventory. People can create maps inside with the assistance of a creative mode inventory and limited world edit.
Mapworld has once more carried over from the prior revision!

To enter Mapworld there is a clickable sign at spawn to warp you, you will need to have an empty inventory to enter. Once in Mapworld you can start creating you artwork by locating an empty plot (which can easily be found from viewing the livemap) and typing /nerdplot claim while standing in the empty plot.

Once a map is completed, you can give yourself an empty map and right click to map out your plot, and acquire your map id by hovering your mouse over the tooltip. To enable advanced tooltips press F3 + H. Returning to your build in the Overworld, you can then rename your map to the id number of the map on an anvil, then place it in an item frame.

To exit Mapworld head back to the spawn location or use /spawn, a warp sign found here will put you back in the Overworld and clear your inventory.


### Minecarts
> Fast minecarts on PvE

HyperCarts has a faster-than-vanilla, default speed setting to help you traverse
 the map faster, and importantly, the ability for players to adjust
their personal cart speed to mitigate issues on slow connections.

Useful commands:

* /cart-speed help - Show usage help.
* /cart-speed - Show your current personal maximum minecart speed.
* /cart-speed <number> - Set a new personal maximum minecart speed.

You can also stack carts by placing single minecarts into a crafting inventory
or also by running /stackcarts, while having minecarts in your inventory.


### ModReqs
> Moderator Requests for assistance.

If you need assistance from a moderator, type `/modreq your message here`.
Your request will be added to a queue and a staff member will help you as soon
as possible. If you are stuck in a protected region, message a moderator
directly, rather than waiting for a ModReq. Do not use ModReqs to ask for help
with building or for simple questions about the game. Ask other players or
check the Minecraft wiki at http://minecraft.gamepedia.com.

You do not need to be online for your request to be fulfilled. The coordinates
where you ran `/modreq` are saved with your request. You typically use ModReqs
to make water/lava flow, report grief or other rule-breaking, or to get your
build protected.

You can see your open requests with `/check` or by visiting http://nerd.nu/modreq/pve.pl.
You can cancel a request with `/done <number>`.


### Mumble
> About our Mumble voice-chat system.

You can talk to other players and staff on our Mumble voice-chat server at
**mumble.nerd.nu**, port **6162**. Download a Mumble client for your system from
http://wiki.mumble.info/wiki/Main_Page. Please configure a push-to-talk key
rather than using voice activation.

We also support Discord for text and voice chat. See `/help Discord`.


### Nerd
> About the nerd.nu organization.

The nerd.nu organization is run entirely by volunteers and completely funded by
donations from players. You can find out more on the web. See `/help Web`.


### Pets
> About pets.

Pets are tamed animals such as cats and dogs, farm animals (e.g sheep) that
have been named with a nametag, or trapped hostile mobs. It is against the
rules to kill another player's pets. Note that hostile mobs will eventually
despawn unless named with a nametag.

Try /pinfo to see who a pet belongs to.


### Places
> Finding places using `/place`.

Places are points of interest on the server. Places are granted to the
following types of build:

* Nether and end portals.
* Developed builds with multiple contributors.
* Single player builds of significant work.
* Server-wide large building projects.
* Public quad+ grinders, blaze grinders, guardian grinders and special spawners.
* Other reasons at admin discretion.

You can see a list of places by typing `/place`. Type `/place <location>` to see
its coordinates and to be pointed in the right direction.

Type `/place endportal` or `/place netherportal` to see the _nearest_ end
or nether portal, respectively. You can find the place nearest to your current
location using `/nearest-place`.

Places are created when requested by ModReq, subject to admin approval.


### Plugins
> Descriptions of all server plugins.

Plugins can be listed with `/pl`. You can get help on a specific plugin with
`/help <plugin>`.

You can also find a complete list of plugin documentation on our wiki at
http://wiki.nerd.nu/wiki/Plugins.


### Portals
> About portals.

The revision will start with 8 hidden signs for netherpotals. The first player to find the sign will be allowed to create a portal for free within 100 blocks of the marker. Nether portals are also purchaseable by any player at  a cost of 64 Guilders per nether portal shard (enchanted amethyst bought at spawn). This means that the smallest 3x2 portal will cost 6 Portal Shards. Please build your portal frame from obsidian then place your portal shards in a chest and make a modreq. Your modreq should include the name you want for the portal. Once placed, portals will not be expanded or moved. If you want to expand your portal you must destroy it and replace it, paying again for all of the portal shards.

We ask that new overworld nether portals must not be within 100 blocks of an existing nether portal.


### Protection
> Protecting your builds.

Protections allow only you and those you add to permissions to build within an
area. Undeveloped land will not be protected. Only completed or mostly-completed
structures will be protected by moderators. Protections usually extend from
about 10 blocks below the lowest level of your build all the way to Y 255.

Protections can not be used to claim resources or land; they are only to
prevent griefing of your build. Large claims may not be granted protection in
their entirety, initially. Instead, staff will protect those parts of the
claim that have been built on.

You may request your build be protected using `/modreq`. In order to do this
place two blocks that are easily identifiable (colored wool works well) at the
two opposite corners of your build. Try to make it so that someone who does
not know what you are building will be able to identify the boundaries. Then
type `/modreq please protect my build marked with <block>` at one of the
corners and a moderator will create a protection for you.

Protections are implemented as WorldGuard regions, which have owners and
members. Members can build in the region, and owners can do everything
members can do as well as add other owners and members. You can find out
what region you are standing in with `/region info` (`/rg i` for short) or
you can right click on blocks with a wooden sword. You can add additional
members or owners to a protection region with `/rg addmember <region> <player>`
and `/rg addowner <region> <player>`, respectively.


### PvE
> About PvE, the game.

PvE stands for "Player vs. Environment". This means Survival mode, with the
hardest difficulty, and no PvP (Player vs. Player combat).


### Redstone
> About redstone devices.

Fast-running clocks or redstone devices with many hoppers, pistons or lamps can
have a disproportionately detrimental effect on server performance for their
size and may be disabled by staff at their discretion. Please endeavor to
design redstone devices with minimal numbers of hoppers and avoid fast clocks.
Consider replacing hopper chains with water flows over ice and replacing clocks
with daylight sensors or BUDs. See also `/help Lag`.


### Region Locks
> Shared locks for region members.

Containers (chests, furnaces, etc) can be privately locked, yet accessible to
all members of a WorldGuard region, using `/cmodify r:<region>`. You can
ModReq to create a 1x1x1 block region for the purpose of managing access to
shared containers, even if you have no substantial build for the region to
protect. See also `/help Locks`.


### Restarts
> About server restarts.

Every 4 hours our server restarts to help it run more smoothly. Players are
sent to the lobby. A warning will appear on your screen 1 minute before, as
well as a 10 second countdown. If you have your inventory open just before the
restart, you could lose items, so be careful! It is also recommended that you
dismount from a vehicle (horse / minecart) to avoid death or loss of vehicles.
When the restart has completed you can either fly through the "P" portal or
type `/pve` to return to the server. You can see when the next server restart
will happen with `/nextrestart`.


### Revisions
> About map revisions.

We start a new world, from scratch, typically every 6-8 months,
at the discretion of the P admins. This is called a "revision" or "rev". No
items are carried over into the new map. You start over with nothing. This
is PvE Revision ${rev-number}, which began on ${rev-date}. See ${rev-post} for
details. All previous map revisions are available for download. See `/help Web`.


### Rules
> The rules of PvE in brief.

* Be respectful to other players.
* No sexism, racism, homophobia, or other hate speech is allowed.
* No chat spam, advertising, or excessive trolling.
* Do not reveal personal information about other players.
* Absolutely no impersonation of staff is allowed.
* Do not grief, spam blocks, or harvest crops without replanting. See also
  `/help Farms`, `/help Grief`.
* Do not kill a player's trapped mobs or animals. See also `/help Pets`.
* If using another player's farm, remember to leave their breeding pair.
* Do not x-ray - you will lose all of your items and edits. See also
  `/help X-Ray`.
* Do not exploit bugs or glitches or attempt to circumvent our protection
  plugins including, but not limited to, LWC, WorldGuard, and NoCheatPlus.
* Do not use hacks or hacked clients; that will get you banned.
* No killing or trapping players except in clearly marked arenas.
* No "Not Safe For Work" (NSFW) builds or skins.
* Do not restrict access to builds, the map is considered open for exploration.
* Exceptions and additional rules can be found at http://nerd.nu/rules.

See also `/help Bans`.


### Servers
> About other nerd.nu servers.

There are three Minecraft servers currently active on the Nerd.Nu network: PvE,
Creative and Chaos. You can access them with `/pve`, `/creative`. Chaos (aka the snapshot server) is reached directly only at x.nerd.nu.


### Spawn
> About spawn.

Spawn is located at (0,0). Here you will find the rules and helpful tips for the server, any spawn traders and a Nether Portal.

Type `/place spawn` to be pointed in the right direction!


### Staff
> About the staff of nerd.nu.

At nerd.nu, as much as possible, all players are treated equally, so you won't
see special titles for staff names in chat. To see which staff are currently
in-game, use `/list` or `/modlist`. You can see the full list of all current
and past staff at http://nerd.nu/staff.


### Steam
> Find us on Steam.

Our steam group is http://steamcommunity.com/groups/nerdnu.


### Stuck
> Stuck in a protection?

Occasionally players find themselves stuck in a place where they can't dig or
place blocks to escape. In such circumstances, it is better to directly message
a moderator and ask for help, rather than waiting for a ModReq to be handled.


### Teleports
> Teleports, homes and warps.

Currently, teleporting is disabled on PvE. Use portals for fast travel.


### Towns
> Building with others in a town.

Towns are large builds shared by a group of players. By convention, towns share
a protection region, and the region owners are referred to as "mayors", since
only they can add new region members. Typically, towns will not be granted
protection over their whole claim area until substantial builds are present.
However, you can `/modreq` to ask for a small region to be made to lock
shared chests to all region members (see `/help Region Locks`).

Although mayors can set standards for builds within their town and even evict
members, it is against the rules to remove non-compliant builds against the
builder's wishes. Instead, do a ModReq asking an admin to move the build for you.


### Volunteer
> How to help the servers.

You can apply to be a moderator at http://nerd.nu/applyformod.
If you are a Java programmer, you can submit pull requests for our plugins.
Look for us on GitHub: https://github.com/NerdNu.


### Warps
> About the `/warp` command.

Warping is occasionally enabled on PvE to go to special events. But for the most
part, you must walk, use a vehicle, or use regular in-game nether portals and
end portals.


### Water
> About water.

See `/help Liquids`.


### Web
> Find us on the web.

++PvE Links++:
* http://nerd.nu/help/pve - this help text in your web browser
* http://wiki.nerd.nu/wiki/PvE_Information_Guide - Our Information Guide!
* http://nerd.nu/maps/pve - current isometric cartograph
* http://wiki.nerd.nu/carto/pve - cartographs of past revs
* http://nerd.nu/maps/pve/live - current top-down live map
* http://nerd.nu/modreq/pve.pl - check your ModReqs

++General Links++:
* http://nerd.nu - main site
* http://nerd.nu/forums - discussion forums
* http://nerd.nu/modreq - check your ModReqs
* http://nerd.nu/staff - staff list
* http://nerd.nu/logs - chat logs
* http://nerd.nu/donate - support us financially
* http://nerd.nu/appeal - appeal a ban here
* http://reddit.com/r/mcpublic - our subreddit
* http://wiki.nerd.nu - our wiki
* http://mcp-dl.com - download maps from past revisions
* https://github.com/NerdNu - our open-source plugins

See also: `/help Mumble`, `/help Discord`, `/help Steam`, `/help Twitter`.


### X-Ray
> Rules about seeing through opaque blocks.

Any mechanism that allows you to see through normally opaque blocks in order to
obtain an in-game advantage is against the rules. This includes x-ray client
mods, some vanilla contraptions (typically made using transparent blocks) and
some texture packs. Ore-radar mods that give you an awareness of ores nearby
are also against the rules.

X-raying is regarded as a serious offense. It deprives other players of the
opportunity to find resources through legitimate means. Any resources that
x-rayers find can be used to progress in the game faster than legitimate
players.

Accordingly, if you are caught x-raying, you will be banned for seven days if
it is your first xray offense across all alts. Subsequent xray bans will result
in a 30 day ban. All xray bans will result in your edits being un-done and all
of your items taken away.

Because all edits are logged, it is not necessary for staff to be on-line
during the act to catch an x-rayer. The majority of x-ray bans result from
investigations that happen several hours _after_ a player has x-rayed.


### XRay
> See `/help x-ray`.

### Mods
`modmode.toggle`
> Special information for moderators only.

Moderation Guides & How-To's: https://nerd.nu/doc/staff-information#modguides
