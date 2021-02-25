---
title: "My Leisure Time"
date: 2021-02-15
description: "Personal projects I have my eye on."
---

Let’s digress for a moment. I've got some projects that are underway or in the planning stages. Have a look.

## The Smartening of My New House

I mean, a new house needs some kind of smart capability, right?

One rule: the missus won’t allow me to farm this out to the cloud. That means no Amazon, no Google, no Nest, nothing. I've already set up [Home Assistant](https://www.home-assistant.io/) and established a new Z-Wave network with a smart plug that powers a standing floor lamp. My first automation switches the light on if I'm out shortly before sunset. 

Why Z-Wave? Sure, it’s a proprietary protocol, but I’ll know that these devices will have no trouble talking with one another. I could have saved a little bit of coin by going with Zigbee, but it turns out that compatibility among these devices is not a certainty. Plus, it creates its own mesh network that is sure to come in handy as we spread devices throughout the house. Since living here, I've gotten an idea of which switches we use the most. I'll look to update those with Z-Wave switches soon.

## A File Server and a Pi-Hole

Of course, a smart home also needs a massive home server, I think. The server I've built is based on [OpenMediaVault](https://www.openmediavault.org/) with services running in Docker. Those services include:

- Home Assistant
- [Jellyfin](https://jellyfin.org)
- Other Docker utilities, such as Portainer and Watchtower

I may add the following:

- [Huginn](https://github.com/huginn/huginn)
- [Nextcloud](https://nextcloud.com)
- Something for automated backups (a la Time Machine)
- Something to store video captured from security cameras
- Other Docker utilities, such as Portainer and Watchtower

I've also set up a [Pi-Hole](https://pi-hole.net/) on a spare Raspberry Pi 3 I had lying around.

Speaking of security cameras...

## The Security of My New House 

Events in 2020 and 2021 are proof that it’s necessary to invest in security measures for my family and new home. I’m not trying to turn our happy home into a prepper’s bunker, but I am talking about installing security cameras outside and a comfortable environment inside, along with some other creature comforts:

- The missus has talked about a whole house backup generator. Do we invest in that?
- Our neighbor has a solar cell array. Do we keep up with the Jones and invest in that?
- Do I slap a UV light on the air intake of our A/C units? It kills germs. Some really nasty ones.

## Netlify to Discord

Someday, I will give money to Netlify. But until and even then, it would be nice to set up a bot of some kind to notify me on Discord when a build on the blog has completed or failed. 

## A New Programming Language

One of my goals for 2021 is to learn a new programming language. I was torn earlier this year between Go and Rust, but settled on learning Go (I'll likely follow up with Rust at some point). So far, so good, I've completed the [initial code tutorial on golang.org](https://golang.org/doc/tutorial/getting-started), and now I'm working my through [A Tour of Go](https://tour.golang.org/list). I'm seeking ideas for my first project once I'm finished with the tour. I'm looking at building a Discord bot (maybe the aforementioned Netlify Notifier) or contributing to a open source project. But if some need comes up, I can always tackle it with Go.
