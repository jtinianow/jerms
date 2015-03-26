---
layout: post
title:  "Web Design on the Bus"
subtitle: "Why I Designed and Built my Site on the Bus"
excerpt: "I&rsquo;m busy. No, really  &mdash;  I&rsquo;m not trying to impress anyone. I spend about 60 hours a week making things. On top of that, my daily commute Monday through Friday is about 2&ndash;3 hours each day."
date:   2015-03-14 09:11:03
---

I could get there and back faster if I drove, but I haven’t got a car. Even if I could drive, it wouldn’t be much faster and I’d be paying for gas. Students get free bus rides, but that’s not all. With a busy schedule, working on the bus has given me some admittedly expected and some surprising benefits.

## Efficiency

### No PSD Workflow

> &ldquo;Designers should be close to the means of production&rdquo;
>> [&ndash; Matter](http://www.morematter.com/designandprinting.php)

I’m just one person, and I don’t want to make my personal site into some big bloated monster of a project. Instead of going research, sketch, mockup, prototype, implement, I’ve elected to give a different workflow a try: research, implement, research, implement, etc…

This keeps me focused on two things. First, keeping the site lightweight and easily maintainable. I don’t need a database and, as much as I love Wordpress, I just don’t need all of those features for a project this small. Second, keeping things realistic. There’s no pixel-perfection followed by “Oh Shit” moments where something breaks in the built site.

This approach isn’t good for every type of project. I have found it very useful for a simple personal site.

### Here’s My Commute

1. 15 Minutes – Capitol Hill to Union Station (Bike)
2. 45—1 Hour – Union Station to Boulder Transit Center (Bus)
3. 15 Minutes – Boulder Transit Center to BDW Studio (Bike)

AKA

1. 15 Minutes – Exercise (Bike)
2. 45 Minutes—1 Hour – Work (Bus)
3. 15 Minutes – Exercise (Bike)

In other words, I’m not spending any time *just* commuting. Every minute is leveraged for more than one purpose. I like to call this “good multitasking”.

## Thoroughness

### The Escalator Principle

> “An escalator can never break: it can only become stairs.”
>> – Mitch Hedberg

My site (as well as many sites today) rely on external resources to function well and appear as they’re intended. Hooked up to high-speed wifi, everything is well and good. But what if your user is on a shitty connection? What if they’re accessing the site you built on 3G (yes, 3G is still around)? God forbid Typekit’s CDN fails entirely or, more likely, takes more than 3 seconds to load.

There’s nothing wrong with external resources, but things don’t always play out in the real world as they do in our studios. I’ve often worried about this on previous sites. What if so-and-so who’s hiring goes to look at my site on a slow connection and it doesn’t look right? How would I ever know?

### Because the Bus doesn’t have Wifi.

Working in a wifi-less environment helps me sleep at night. I know what this site looks like when Typekit doesn’t load. I know  that every part of the site is accessible if jQuery fails to load and my fancy full-screen menu breaks.

Of course, I could simply go into airplane mode and work wherever. If I’m being honest with myself, that wouldn’t likely happen. I’ll use externally imposed restrictions over self-discipline any day of the week.

## Downsides

No process is perfect, and my process is no exception. There are a couple of issues I’ve noticed over the last couple weeks.

### Load Time = Super Fast

Working with (almost) entirely local files makes load time appear incredibly fast. Even if I’m pulling a huge image, it pops up in no time at all. In the wild, this wouldn’t happen every time, and I’d need either some feedback for the user to know that the page is loading, or better optimized images (or more likely a combination of both).

It would be great to find a middle ground here. Some way to regulate connection speed and ratchet download time way up. Honestly, I haven’t done my homework on this and I’m open to suggestions.

### No Wifi = No view on mobile

I love being able to look at sites I’m working on on my phone while they’re hosted locally. I don’t trust emulators and I’d rather see how the site plays out on an actual device in my hand. I’ve got a nice old iPhone 4S with a tiny screen that offers a lot of restriction when I’m designing for mobile. On the wifi-less bus, I’m simply unable to see my work live on a phone.

### 90% on the Bus

To compensate for the downsides, I end up doing about 90% of the work on the bus. Accurately gauging load time and seeing how the site looks on mobile are all that I really need wifi for, so I do those tasks in the studio or once I’m home. I prefer building a site that only requires wifi for a couple of things over building one that requires wifi for most of its functionanality.

## Here’s the Site

<a href="http://jtinianow.com" target="_blank">
	<img src="/content/2015-03-14-web-design-on-the-bus/site.png" alt="">
</a>


