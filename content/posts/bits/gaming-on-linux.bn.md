---
title: "Gaming on Linux"
date: 2021-03-01T11:14:19+06:00
draft: false
aliases: '/bn/post/linux/gaming-on-linux/'
showtoc: false
categories:
- লিনাক্স
- টেকটক
tags:
- Linux
- Gaming
cover:
    image: "/img/gaming-on-linux.webp"
    alt: "Gaming on Linux"
    caption: "Gaming on Linux"
    relative: false
---
Valve এবং AMD'র কারণে লিনাক্স গেমিং আগের থেকে বেশ ভালো অবস্থানে আছে। স্টিম প্রোটন কম্প্যাটিবিলিটি লেয়ার দিয়ে অনেক গেম এখন আউট অব দ্য বক্স খেলা যাচ্ছে, আর CS:GO, Tomb Raider, Dota 2 এর মতন নেটিভ গেমস তো আছেই। Steam যে লিনাক্সে এভেলেবল সেটা অনেক পুরোনো খবর। Epic Games Launcher ও ব্যবহার করা যাচ্ছে বছর দুয়েক হলো। এছাড়াও সম্প্রতি Heroic Launcher নামে এপিক গেমস এর আরো একটা আনঅফিসিয়াল ক্লায়েন্ট পাবলিশ হয়েছে।

Valve ২০২২ সালে স্টিম ডেক রিলিজের ঘোষনা দিয়েছে যেটা চলবে আর্চলিনাক্স ভিত্তিক স্টিম ওএস এ। শতভাগ গেমকে প্রোটন কম্প্যাটিবিলিটির আওতায় আনার আশ্বাস দিয়েছে তারা। যদিও এটা বেশ শক্ত একটা কাজ, শতভাগ গেমকে প্রোটন কম্প্যাটিবল করা অত্যন্ত সময় স্বাপেক্ষ ব্যাপার। তবুও আশা করাই যায় বড় টাইটেলগুলো লিনাক্সে শীঘ্রই খেলা যাবে।

![Gaming-on-Linux](/img/gaming-on-linux.webp)

## কীভাবে গেমিং করা যাবে লিনাক্সে?

- [Steam](https://steampowered.com) : স্টিমে প্রচুর নেটিভ গেমস রয়েছে, সেগুলো মূলত স্টিম ওএস _(A Linux based gaming OS from Valve)_ এর জন্যে পোর্ট করা হয়। সেগুলো কোনো রকমের ইস্যু ছাড়াই খেলা যায়। এছাড়া নন-পোর্টেড গেমগুলোও বড়সড় কোনো টুইক করা ছাড়াই খেলা যায়। উদাহরণস্বরুপ, হালের Cyberpunk 2077 ও লেটেস্ট প্রোটন _(A compatibility layer that helps to run Windows game which comes with Steam launcher, developed by Valve)_ দিয়ে খেলা যাচ্ছে।
- [Lutris](https://lutris.net) : লু্ট্রিস একরকমের লঞ্চার যেটা বিভিন্ন প্লাটফর্মের গেইম রান করতে সাহায্য করে। যেখানে কোনো একটা গেম লিনাক্সে সেটাপ করার জন্যে অনেক রকমের টুইক করতে হতো, সেই টুইকগুলো লুট্রিস-ই করে দেয়। যে কারণে এক ক্লিকেই গেম ইন্সটল করা সম্ভব হয়। Steam, Epic Games, GOG, Humble Bundle এর মতন সোর্স থেকে গেম ইন্সটল করা যায়। এছাড়াও Lutris এর নিজস্ব লাইব্রেরি আছে যেখানে ভালো এমাউন্ট এর গেমস থাকছে, আর কাস্টম ইনস্টেলশন তো থাকছেই। Windows গেমস এর পাশাপাশি PPSSPP, PS2, PS3, Wii এর মতন কন্সোল গেমসও খেলা যায়।
- [PlayOnLinux](https://playonlinux.com) : প্লে অন লিনাক্স লুট্রিস এর মতন Wine কে কম্পাটিবিলিটি লেয়ার হিসেবে ব্যবহার করে গেম রান করে। অতিরিক্ত যা থাকছে সেটা হলো গেমস ছাড়াও এটা উইন্ডোজ সফটওয়্যার রান করতেও সাহায্য করে।
- [Epic Games Launcher](https://epicgames.com) : এপিক গেমস দুইভাবে ব্যবহার করা যাচ্ছে। লু্ট্রিস দিয়ে এবং [Heroic Launcher](https://heroicgameslauncher.com/) দিয়ে। Heroic এপিক গেমস লঞ্চার এর একটা আনঅফিসিয়াল ক্লায়েন্ট।
লিনাক্স এ গেমিং এর জন্যে এই কয়টাই সবথেকে সুবিধাজনক টুলস। উইন্ডোজ এর কোন গেমটি লিনাক্সে কতটা কম্পাটিবল সেটার একটা তালিকা পাওয়া যাবে ProtonDB এর ওয়েবসাইটে।

লিনাক্স ডিস্ট্রোগুলোতে কোন গেম কতটুকু কম্প্যাটিবল সেই সম্পর্কে বিস্তারিত জানা যাবে [ProtonDB](https://protondb.com) এর মাধ্যমে। ProtonDB তে গিয়ে গেমের নাম সার্চ করলেই রেজাল্টে দেখা যায় সেই গেম সম্পর্কে ইউজারদের রিভিউ। ব্রোন্জ, প্ল্যাটিনাম, গোল্ড ইত্যাদি ট্যাগ এর মাধ্যমে প্রতিটি গেমের কম্প্যাটিবিলিটি মার্ক করা হয় এখানে।
আশা করছি যারা লিনাক্স ইউজার আছেন তারা লিনাক্সে গেমিং সম্পর্কে মোটামুটি একটা ধারণা পেয়ে যাবেন।
