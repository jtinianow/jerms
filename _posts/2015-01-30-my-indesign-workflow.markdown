---
layout: post
title:  "My InDesign Workflow"
subtitle: ""
excerpt: "I get a lot of questions about workflow, and InDesign has been a particularly popular subject recently, so I&rsquo;ve put together a rundown of my page layout workflow."
date:   2015-01-30 09:11:03
---

This is just a brief overview of how I keep things efficient, consistent, and
easy to edit. I won’t get into too much detail about the nitty gritty of
InDesign’s massive feature set, and the project I’ll go over is pretty simple.
Nonetheless, this should give you an idea of some key best practices in page
layout.

_Disclaimer 1: I’m using InDesign CS6. I’m aware that CC has more features and
CS5 and earlier have fewer. I’ve included some resources at the end of this
article that are more up to date and contain info on past versions._

_Disclaimer 2: There are a thousand ways to skin a cat. I’m not claiming that
this workflow is perfect, and comments on how it could be improved are more
than welcome._

## First Things First

![Step One](/content/2015-01-30-my-indesign-workflow/step-01.jpg)

I prefer the Advanced workspace for this workflow. Don’t be daunted by the
name, it’s actually pretty simple.

## New Document

Before I start, I ask myself two questions.

- Will this be printed, or read on a screen?
- How many pages (roughly) do I need?

![Step Two](/content/2015-01-30-my-indesign-workflow/step-02.jpg)

Since I know this will be presented on a screen, I set the intent to “Web” and
the dimensions to match the pixel dimensions of the screen I’m presenting on
(1920px x 1080px). I know that I need about 8 pages, and I know that I’m not
using spreads (since it’s going to be read on screen), so “Number of Pages” is
set to 8, and “Facing Pages” is unchecked.

## Project Organization and Plain Text

![Step Three](/content/2015-01-30-my-indesign-workflow/step-03.jpg)

I keep all of the copy in a single plain text file with no additional hard
returns, and no formatting. Sometimes clients send me rich text documents with
image and graphic callouts. I’ll hold onto that, but make a plain text copy
without callouts or extra spacing. We’ll see why in just a moment.

![Step Four](/content/2015-01-30-my-indesign-workflow/step-04.jpg)

Also, I like to keep images in their own folder, usually within the project
folder since I tend to edit them down to the minimum size that they need to be
in the final product to keep file size reasonable.

## Typesetting

I always start with setting the text. This is generally the most complicated
part of the workflow, and the more figuring out can be done early in the
project, the better.

![Step Five](/content/2015-01-30-my-indesign-workflow/step-05.jpg)

Here’s our entire presentation in one box. Clearly, default settings are not
our friend.

![Step Six](/content/2015-01-30-my-indesign-workflow/step-06.jpg)

That’s a bit better. I switched the typeface, bumped up the size, and changed
the leading.

## Paragraph Styles FTW

Once I’ve figured out the font I’m using for body copy (usually this comes
from a style guide, in this case it’s just personal preference), it’s time to
set up a paragraph style.

![Step Seven](/content/2015-01-30-my-indesign-workflow/step-07.jpg)

Creating the new style pulls in whatever formatting is already applied. The
main thing to remember is always, ALWAYS set your “Kerning” to “Optical”.
Don’t ask why, just do it.

_Note on Styles: Whenever you create a new style, be absolutely sure to apply.
InDesign will not do this by default._

![Step Eight](/content/2015-01-30-my-indesign-workflow/step-08.jpg)

Good justification settings.

![Step Nine](/content/2015-01-30-my-indesign-workflow/step-09.jpg)

Good hyphenation settings.

To be honest, I don’t fully understand the justification engine or the theory
behind hyphenation practices, but these settings tend to lend better results
than the defaults.

![Step Ten](/content/2015-01-30-my-indesign-workflow/step-10.jpg)

Color should never be pure black on white for digital publishing. I stick with
92% black to keep my readers’ eyes happy.

![Step Eleven](/content/2015-01-30-my-indesign-workflow/step-11.jpg)

Another “Don’t ask why, just do it,” is to always turn on “Optical Margin
Alignment” in the “Story” panel. Notice how the verticals of the T’s (rather
than their crossbars) line up to the frame. This creates better visual
alignment.

## Working Up

It’s generally advisable to make all of your type decisions about the body
copy and move up the hierarchy from there. So rather that jump straight to the
main headings, I’ll set a subhead.

![Step Twelve](/content/2015-01-30-my-indesign-workflow/step-12.jpg)

In this case, it’s just a bolder stroke weight

### A Note on Line Length (AKA Measure)

Before we get much further, let’s check our line length. I can open the “Info”
panel and see that one of my lines of body has 90 characters. This is a bit
long for a short article, so I’ll pull it down.

<div class="animated-gif">
<!-- 	<img class="animated-gif--still" src="/content/2015-01-30-my-indesign-workflow/LineLength.jpg" alt="Line length animation" /> -->
	<img class="animated-gif--play" src="/content/2015-01-30-my-indesign-workflow/LineLength.gif" alt="Line length animation" />
</div>

Now we’re at 70 characters. This is a much better cadence for a short
presentation, so we’ll stick with it.

![Step Thirteen](/content/2015-01-30-my-indesign-workflow/step-13.jpg)

Here’s our top level heading. I prefer to set these as character styles rather
than paragraph styles, since I’m only changing the typeface, size, and color.

![Step Fourteen](/content/2015-01-30-my-indesign-workflow/step-14.jpg)

Here’s a variation on our top level heading. This isn’t always necessary, but
I’ve done it this way to call attention to the name of the each prompt.

## Gimme Some Space

This is looking a bit claustrophobic. No worries, we can just change our “Body
Basic” paragraph style to add some breathing room.

![Setting Space Before](/content/2015-01-30-my-indesign-workflow/SpaceBefore.gif)

Making the change here will carry over to our “Body Bold” style as well, since
we told InDesign to base the latter style on the former.

_Note: What I changed is the “Space Before” for the paragraph, not the
leading. This is an important distinction._

## Bullets

For bulleted lists, we want to use InDesign’s features, rather than try to
just add our own glyphs. Here’s how it works:

![Setting up Bullets](/content/2015-01-30-my-indesign-workflow/Bullets.gif)

Setting tabs is an unholy pain in the ass, but very important. If you do it
right, you only have to do it once and it can be reapplied as a paragraph
style.

We don’t want any spacing before in the list style, so I’ve removed it.

## Split It Up

A major reason for the plain text file is so that we can keep the copy in
order as we edit, but also split it up to suit the layout we want.

![Splitting up the layout](/content/2015-01-30-my-indesign-workflow/Layout.gif)

Here’s a pretty decent layout to start with. Since we’ll have three more pages
like this, we’ll make some changes to our A-Master page.

## Master Page

I don’t tend to go to hard with grids, especially for a project as small as
this one. The time it would take to develop a thorough grid system just
wouldn’t be worth it. Note: If I’m working on a 20+ page print document, I’ll
absolutely develop a proper grid.

![Setting the A-Master page](/content/2015-01-30-my-indesign-workflow/A-Master.gif)

I’m copying everything from the page we set up and pasting it in place on the
A-Master, than pulling out some guides to determine placement on other pages.
Finally, I’ll delete the content I copied so that it doesn’t show up on other
pages.

## Next Page

So it took us a while to set up that first page, but the second page is much
faster. All we have to do is pull the copy into new text boxes, use the guides
for alignment and line length, and apply our styles.

![Setting up page two](/content/2015-01-30-my-indesign-workflow/Page2.gif)

_Note: At this point, I noticed that my list items were hyphenated, which I
didn’t want. No worries, I just change a setting in the paragraph style and it
applies to everything assigned that style._

## Cover Page and Wrap Up

Now that our styles are pretty set, I’ve got a decent idea of how I want the
cover page and the final page to look.

![Setting up the cover page](/content/2015-01-30-my-indesign-workflow/Cover.gif)

Applying styles to a basic cover.

![Setting up the final page](/content/2015-01-30-my-indesign-workflow/End.gif)

Applying styles to the final page.

## Spellcheck!

This is another reason I like to work with all of the text pulled from a
single file. You can select everything and spellcheck (Cmd + I or Ctrl +I on
Windows).

## Bonus Round: Alternate Layouts

What if you need some pages to be different sizes than your document layout? I
ran into exactly that problem, and here’s how I solved it. Say I have an image
to take up the page after my first page of body copy, and I know that the
image is 1280px x 1721px, and I want to add a header that’s the same width and
72px tall. That’s 1280px x 1793px total.

![Creating an alternate layout](/content/2015-01-30-my-indesign-workflow/AltLayout.gif)

You can create an alternate layout by right-clicking the page that you want to
have different dimensions, and selecting “Create Alternate Layout”. Once
you’ve set the dimensions, just switch their places and add the images, copy,
graphics, etc…

![The align tool](/content/2015-01-30-my-indesign-workflow/Alignment.gif)

The “Align” tool is great for getting images to sit exactly where you want.

## Fin

So that’s the basics. In writing this, I’m realizing that there’s a lot more
to it than I thought. I’ve found that the best way to really get up to speed
with InDesign (or any software for that matter) is to just dive in and make
some stuff. I wouldn’t recommend re-reading this rundown a million times, and
don’t worry if your workflow is different or if your final product has some
flaws. Just get in there and make some shit.

### Helpful Resources:

- [http://indesignsecrets.com/](http://indesignsecrets.com/)
- [http://www.lynda.com/](http://www.lynda.com/)
- _A Type Primer_ by John Kane
- _The Elements of Typographic Style_ by Robert Bringhurst
- Google (especially if you know basic typographic vocabulary)


