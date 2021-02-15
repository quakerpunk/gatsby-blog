---
title: "My Leisure Time"
date: 2021-02-15
description: "Personal projects I have my eye on."
---

Let’s digress for a moment. Here are some projects that are underway or in the planning stages.

## The Smartening of My New House

I mean, a brand-spanking new house needs some kind of smart capability, right?

One rule: the missus and I don’t want to farm this out to the cloud. That means no Amazon, no Google, no Nest, no Google, nothing. I've already set up [Home Assistant](https://www.home-assistant.io/) and established a new Z-Wave network with a smart plug that powers a standing floor lamp. My first automation switches the light on if I'm out shortly before sunset. 

Why Z-Wave? Sure, it’s a proprietary protocol, but I’ll know that these devices will have no trouble taking with one another. I could have saved a little bit of coin by going with Zigbee, but it turns out that compatibility among devices is not a certainty. The mesh networking capabilities is handy

We've almost been in the house for a year and in that time, I've gotten an idea of which switches we use the most. I'll look to update those with Z-Wave switches as soon as I can.

I’ve also wanted a massive home server. The plan is for a server based on [OpenMediaVault](https://www.openmediavault.org/) with services running in Docker. Those services would include:

- Home Assistant
- [Jellyfin](https://jellyfin.org)
- [Huginn](https://github.com/huginn/huginn)? Eh, maybe on its own machine.
- Maybe [Nextcloud](https://nextcloud.com)
- Something for automated backups (a la Time Machine)
- Something to store video captured from security cameras
- Other Docker utilities, such as Portainer and Watchtower

I've also set up a Pi-Hole on a spare Raspberry Pi 3 I had lying around.

Speaking of security cameras...

## The Security of My New House 

[Events in 2020 and 2021](covid-chronicles) have shown me that it’s appropriate to I invest in security measures for my family and new home. Now I’m not trying to turn our happy home into a prepper’s bunker, but we are talking security cameras outside and a comfortable environment inside, along with some other creature comforts:

- The missus has talked about a whole house backup generator. Do we invest in that?
- Our neighbor has a solar cell array. Do we keep up with the Jones and invest in that?
- Do I slap a UV light on the air intake of our A/C units? It kills germs. Probably some really nasty ones.

## Netlify to Discord

Someday, I will give money to Netlify. But until and even then, it would be nice to set up a bot of some kind to notify me on Discord when a build on the blog has completed or failed. 

## A New Programming Language

One of my goals for 2021 is to learn a new programming language. Ater, it's a good idea. I was torn earlier this year between Go and Rust, but settled on learning Go (I'll likely follow up with Rust at some point). So far, so good, I've completed the [initial code tutorial on golang.org](https://golang.org/doc/tutorial/getting-started), and now I'm working my through [A Tour of Go](https://tour.golang.org/list). I'm seeking ideas for my first project once I'm finished with the tour. Right now, I'm looking at building a Discord bot or contributing to a open source project, but if some need comes up, I can always tackle it with Go.
