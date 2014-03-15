Bastion
=======

A minecraft mod designed for use with /r/civcraft

Features:
 * Destroys blocks placed in a cylinder of configurable radius starting just above a reinforced target block (Bastion block) at the price of a configurable amount of reinforcement if the placer is not a member of the reinforcing group
 * Prevents dispensers dispensing water, lava, and flint and steel if the owner of there reinforcement is not allowed to place blocks
 * Prevents pistons pushing into the Bastion field (Area where block placement is restricted) if the owner of the reinforcement would not be allowed to place there.
 * Prevents teleportation through the the Bastion field by non-members (Note this is highly experimental and may be better disabled)

Modes:
 * INFO
  * When clicking a block inside a Bastion field tells you if you have access
  * When clicking a bastion block gives some basic information on it
 * DELETE
  * When a Bastion block is clicked remove the bastion field while maintaing the reinforcement
 * NORMAl
  * Defualt clicking on blocks does nothing

Commands:
 * /bsi Puts the player into info mode. Right clicking a block will, if the block was a Bastion block display its maturity or dev text if the user has Bastion.dev. If the block was to a Bastion block, but the block oposite the face clicked is inside a Bastion field it will report wether block placement is allowed.
 * /bsd Puts the player into delete mode. Right clicking a Bastion block that you could destroy removes the Field while leaving the block and the reinforcement
 * /bso Puts the player into normal mode

Maturity:
 * When a bastion is first created it starts much weaker
 * While it matures any blocks placed within the field do much more damage
 * Until mature ender pearls are not blocked.
 * INFO mode gives some information on the time till maturity

To install:
  * Add Bastion.jar to the server /plugins directory
  * Confirm that Citadel is also installed
  * Launch the server or copy the default configuration file
  * Create a Mysql database and account for the plugin
  * Specify in the configuration file
  * Relaunch the server

There's only one permission that may need changed: Bastion.dev. It currently just controls the text from the info command.

To compile:
 * Download Bukkit
 * Download Citadel
 * Download Humbug
 * Link to Bukkit, Citadel, and Humbug then compile
