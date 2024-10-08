# Modding Introduction

This is an introduction guide for Minecraft modders coming to Minetest.

## What is Minetest?

[Minetest](https://www.minetest.net/) is an open-source voxel engine focused on modding, you have games and mods for these games, something that Minecraft proposed in the past but never did.

The main advantage of Minetest is that it's open-source and written in C++, thus having true freedom and high-performance.

While on Minecraft you need dozens of mods to have good FPS, on Minetest no changes are needed.

## What is a game on Minetest?

It's a modpack on Minetest, on Minecraft you call it a "modpack" and we call a "game".

## How similar it is compared to Minecraft?

The default game is similar, but if you want the exact Minecraft experience, you should use the [VoxeLibre](https://content.minetest.net/packages/Wuzzy/mineclone2/) game, it's a Minecraft clone for Minetest.

## What is the problem with Minecraft modding?

As you may know, the modding API breaks on every new release, even bug fixes!

Breaking many mods and making mod combinations very hard and boring to configure.

On Minetest the modding API rarely breaks, most mods were updated to the 5.3 version and will work without modifications in the next versions.

## What about Minetest problems?

The main problem in Minetest mods is incompatibility with some game, as the Minetest Game is the most used, but many mods are compatible with the game MineClone2.

## Which are the rules?

You should keep your mods compatible with the "VoxeLibre" game to have the same experience, open the [VoxeLibre repository](https://git.minetest.land/VoxeLibre/VoxeLibre) for more information.

## How can I start?

Open [this](https://www.minetest.net/get-involved/) link and read the "Programmers" and "Artists" items in the "Contribute" category.

## Tools

You can use these tools to improve your mods or help your modding workflow:

- [modlib](https://github.com/appgurueu/modlib) - General-purpose Minetest Modding Library
- [controls](https://github.com/mt-mods/controls) - Utility library for control press/hold/release events
