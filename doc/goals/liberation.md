# Liberation

> ℹ This goal is designed to be played in teams

## Description

A medium complex game mode. Dead players are teleported to a jail (dedicated to their own team). 
Other team member of jailed players can liberate them by clicking on a button, giving them one life back.

## Setup

You have to add spawns for the jails, set them with command [`/pa <arena> spawn set jail <team>`](../commands/spawn.md).

Then you have to set a button, at the outside of the jail, that will trigger the liberation of jailed players. To do 
that:
- place a **button** where you want
- type `/pa <arenaname> button set <teamname>` (to open selection mode)
- do a left-click on your button

<br>

> 🚩**Important precision**
> 
> A jail bound to a team will receive players of this team.  
> So when they are killed, **blue** players are teleported to **blue** jail. And free **blue** players must click on the
> **blue** button to free jailed players.  
> That's implies **blue** jail **should not be near blue** spawn.

## Config settings

- `llives` \- the lives players have before being put to prison (default: 3)
