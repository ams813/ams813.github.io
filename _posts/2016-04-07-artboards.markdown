---
layout: post
title:  On board with artboards
source: Cognition
source-url: http://cognition.happycog.com/article/on-board-with-artboards
date:   2016-04-07
categories:   article
---

Over the past nine months, our design team has been using Photoshop CC’s artboards feature (new with CC 2015). If you’re not familiar, artboards allow you to create multiple canvases within a single Photoshop file. While we had used artboards in Illustrator, the shift in Photoshop wasn’t a breeze. In the short term, artboards disrupted our keyboard-shortcut habits and file management workflow. Multiple design concepts and dozens of artboards later, they’re a part of every new design system we create.

The greatest virtue of artboards is they allow us to work simultaneously (and reuse patterns) across canvases for different screen sizes. We’ve also used artboards as a quick mockup tool to detail states of a user flow. No more hidden folders or layer comps—we now visualize everything in artboards. Artboards have also led to fewer files, making sharing our PSDs with developers and clients simpler.

If you’re still getting up to speed in CC 2015 or haven’t yet embraced artboards, here are a few tips to get fully on board.

## Creating artboards

You can create an artboard-based file two ways:

1. When creating a new file, select Artboard as the Document Type, and choose a specific Artboard Size. (This method is more applicable if you’re designing to a particular device.) Artboards are transparent by default, so if you don’t want a transparent design, you’ll need to introduce a filled layer to serve as your background.
2. Or, first create a custom-sized file and then use the Artboard Tool (stored with the Move Tool) to draw an artboard around your canvas. Get this over with first thing. It will speed up Photoshop—which seems to be optimized for artboards—and save you from losing your context when you create a second comp in the same file. (Photoshop will assume it’s your first artboard—not second—and leave your existing layers homeless.) If you follow this method, Photoshop will automatically transfer your background layer to your first artboard, but you’ll have to create your own background fills for any artboards thereafter.
Regardless of how you create artboards, you can always resize them to accommodate your content. Drag from any edge or corner using the Artboard Tool, or enter specific dimensions in the tool options bar at the top of your screen. Resizing artboards is very different from editing your Canvas Size (under Image)—a moot option once you’re in artboardland.

## Naming

You can name your artboards (e.g. Desktop and Mobile, Listing and Detail) by double-clicking the name of each artboard in the Layers panel. Names also appear as small labels above the upper left corner of your boards. If you’re storing multiple artboards in a single file, naming will not only make navigating your Layers panel easier, but also help you jump more accurately between artboards in [Adobe’s Preview app])(https://itunes.apple.com/us/app/adobe-preview-cc/id973272286?mt=8).

## Showing guides

Guides, admittedly, are more confusing in artboard-based PSDs. The trick is that Photoshop manages guides at the document/canvas-level as well as the artboard-level. You’ll use canvas guides to align items across boards, and artboard-specific guides to align items within boards. Depending on how you orient your boards, you may only use horizontal or vertical canvas guides—likely not both.

To show a specific artboard’s guides, you’ll first need to select a layer in that artboard. Then, type command/ctrl + colon twice. The first time will show your canvas guides (even if you don’t have any), and the second time will show your artboard-specific guides. If a particular artboard layer isn’t selected, you’ll only be able to turn on/off your canvas guides.

The easiest way to tell what type of guide you’re creating is to color your guides. Under the Photoshop CC menu, navigate to Preferences > Guides, Grid & Slices, and set more distinct colors or line types for your canvas and artboard guides.

## Moving and duplicating

To iterate on an existing artboard—for example, to show multiple states using the same navigation—you’ll want to move and duplicate your artboards with ease. To duplicate an existing artboard (similar to duplicating a layer or folder), right-click that artboard’s name in the Layers panel and select Duplicate Artboard. When you duplicate an artboard within your file, the new artboard will position itself to the right of the original and appear immediately above it in the Layers panel.

If your new artboard overlaps another (duplicating doesn’t pay mind to where existing artboards live), you can select the duplicated artboard’s name label on the canvas and drag the artboard to its new home. The Artboard Tool will always select the artboard that’s higher up in the Layers panel, so pay mind to the order and name your artboards before moving things around.

## Working across artboards

What happens when your art falls beyond the frame of an artboard? Moving assets across artboards requires a little Photoshop finesse, so keep in mind the following:

* Moving a layer from artboard to artboard on the canvas will automatically relocate that layer to the top of the new-home-artboard’s folder in the Layers panel.
* Turning off layer auto-selection in the tool options bar will help you keep track of any layer(s) you’re moving.
* Avoid reordering layers across artboards using just the Layers panel. Doing so can change the relative position of your artwork if the artboards aren’t the same size.
* Moving a layer off your artboard area will automatically relocate the layer to the top of your Layers panel, outside of any artboard folder. You can prevent this auto-nesting by clicking the artboard-shaped icon in your Layers panel right next to the lock.

## Exporting

Lastly, when you’re ready to export your work, rather than save the entire file for web, you’ll need to export each artboard individually. While this sounds time consuming, specifying your Quick Export settings can speed up this process immensely.

1. Under the Photoshop CC menu, navigate to Preferences > Export.
2. Under Quick Export Format, set whether you’d like to export your artboards as a PNG, JPG, GIF, or SVG, and whether you’d like your transparent background maintained. You can even automate artboards to always save to a certain folder.
3. Whenever you’re ready to export an artboard, right-click its name in the Layers panel and select Quick Export. Your Finder window will quickly pop open once the export has saved. Even better, if you’ve named your artboards, Photoshop will name your files accordingly.

I wouldn’t recommend Quick Export for creating production-ready assets (better to optimize using other methods), but Quick Export will speed up the process if you’re saving artboards for internal or client presentation at the same scale as your work in Photoshop.

How have you or your team adjusted to Photoshop’s artboards? What shortcuts and tricks have you found helpful?
