# Fabric Modding for Beginners (WIP)

## About
This is a tutorial on how you can start making fabric mods for Minecraft with little to no experience. The aim of this tutorial is not to merely provide documentation and descriptions, but also to provide explanations for people who may not understand it. Things are explained with simple language and it is easy to understand. 
I am also not too experienced with modding, so some explainations may be inaccurate. Please correct them if you can see any. 

## Introduction
### What is a Minecraft mod?
A mod is a program that can modify the behavior of a game. In Minecraft, mods can add new items, blocks, mobs, user interfaces and entirely new mechanics. Since Minecraft does not support mods by default, mods rely on third-party mod loaders, which patch the game to make various changes such that modding is easier. The most popular ones are Forge and Fabric. There is also server software such as Bukkit and Spigot which supports "plugins" which allow serverside modification. 

### Installing a mod
Before creating a mod, how about learn how to use one first? 
[Fabric Wiki](https://fabricmc.net/wiki/install)

Basically, a mod is a jar file to the end user. It is put into the "mods" folder after installing the mod loader. 

### Prerequisites
You need to have basic understanding of Java programming, the programming language that you will be developing mods with. This is also the language Minecraft is  developed with. 

### General Tips
#### The black box method
When you develop Minecraft mods, you will be dealing with many things that you do not understand yet. You can simply treat code that you don't understand as a "black box". You do not need to worry as long as you know what it does and how it is used. You do not need to know how it is done behind the scenes. 
#### Reading vanilla Minecraft code
A lot of the time when you are stuck on a problem that you do not know how to solve, you might want to copy other's work. This happens a lot in coding. When modding Minecraft, specifically, it is a very good idea to check "how vanilla Minecraft does it" to solve your problem. 

## Getting Started
### Software needed
#### Java Development Kit
JDK(Java Development Kit) is used to develop Java programs. The version you should use depends on the Minecraft version. 
| MC Version | Java Version |
|------------|--------------|
| 1.16-      | Java 8       |
| 1.17       | Java 16      |
| 1.18+      | Java 17      |
#### Notepad++
https://notepad-plus-plus.org/
#### IntelliJ IDEA
https://www.jetbrains.com/idea/
##### plugins
Its is recommended to get the Minecraft Development Plugin for IntelliJ
#### paint.net
Paint.net is a good program to use for texturing. 

### Structure

### Generating the mod with Minecraft Development Plugin
### Creating a GitHub Repository
### Adding content to Minecraft
### What is a registry?
### Reading Minecraft code
### Getting Minecraft resources

## Resource Packs
### Language
### Texturing
### Custom model
### Blockbench

## Datapacks
### Crafting recipes
### Block tags
### Loot tables

## Items
### Adding an item
#### Item class
#### Item settings
##### Item group
##### Food component
#### Registration
### Adding custom gear
### Modifying item behavior
### Nbt data
### Model predicates

## Blocks
### Adding a Block
### Custom voxel shape
### Modifying Block Behavior
### Blockstates
### Water logging
### Custom crop
### Block entities

## Fluids
### Adding a fluid
### Adding a fluid renderer

## Custom Commands

## Events

## Mixins
### Why use mixins?
### Making your first mixin
### Examples
#### Water in the nether
#### Endless tnt and projectiles

## World Generation
