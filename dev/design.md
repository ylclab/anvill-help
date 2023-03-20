---
title: Design Review
description: 
published: true
date: 2021-06-15T14:17:59.624Z
tags: dev, design, redesign
editor: markdown
dateCreated: 2020-09-03T16:51:37.728Z
---

# Current Task

# Norman Tasks

- Collage allows direct image uploads, needs to use UOMS.
- ~~CKEditor toolbar placement in VB message modal is hidden by iOS keyboard.~~
- Make settings modal on mobile not be full page?
- ~~Add tiny to ckeditor.~~
- H5P Column resizing with just one audio media item.
- Fix app icon (more padding ~3-5px) and test
	- Waiting on this to resolve: https://github.com/ionic-team/cordova-res/issues/118
- ~~Move vertical tabs on settings and add media below close button and divider.~~
- ~~Check file permissions and locations for uploading using Cordova recorder.~~
- ~~Login requiring two calls to complete (possibly state isn't updated after login).~~
- ~~Make sure all buttons don’t require double tap.~~
- ~~Add loading indicator during login and logout.~~
- ~~Fix login appearing during initialization.~~
- ~~Add a show password option.~~
- ~~Suppress undefined:undefined error message during cancel recording.~~
- ~~Look at VB message posting, why spinner is not stopping.~~
- ~~Mockup top loader to see if we like it.~~

# TBD Tasks

- Possibly use miro.com style hover for activities examples and documentation. See VB Test message. Possibly do once we have language oriented language examples.

# Martha Tasks

# Discussion

## General

- Better way to handle multiple dialogs to prevent overlay black screen? Yes we should for as much as we can, but not VB.

## Voiceboards

- Is a reddit like VB view necessary?
- How often has it been requested?
- What issues would it be solving?
- How to deal with scrolling and limited size?
- Loading placeholder takes up too much room? Should no content be labeled?

## Lesson Tags

- Is folders and tagging a frequently requested feature? 
- How would it be used? For search? For sequencing? For grouping?

## Accessibilty

- Placeholder text is too low contrast.
- Favicon invisible on white backgrounds.

## Lessons

- If image header, header stays normal height.
- If no image header, header shrinks to title.

## Dashboard

- Remove owned and shared lesson distinction
- Possibly remove the icon?
- Move badge somewhere.

## Media

- Media player doesn't match theme
- Remove timeline bar during playback.
- Change audio & video blue to primary green.
- Use Martha's mockup for audio player everywhere.

## UI

- Folders/Drawer issues? We need to clarify what this is.

# Completed Tasks

- ~~VB description placeholder doesn't match placeholder default style.~~
- ~~Combine Media Url and Media Upload~~
- ~~Have all media add buttons use tabbed UI except VB messages.~~
- ~~Move all body text back to 20px.~~
- ~~Add tooltips to activities in create with description and example.~~
- ~~Add categories to lesson activities types. (Wait for Jeff's input).~~
- ~~VB title text is too light, looks like placeholder text.~~
- ~~Filter search boxs should have 1px gray border lightest or lighter.~~
- ~~Fix focus on switches to be match figma.~~
- ~~Add a body (small) (regular) (large) typography to ckeditor.~~
- ~~Simplify tooltip to use only summary.~~
- ~~Add link to ANVILL documentation at top of create add dialog.~~
- ~~Add normal padding under search and filter row.~~
- ~~Make activity category headers more visible.~~
- ~~Change Utility to Design and add Accessibility to Design (change name).~~
- ~~Add documenation to VB and Media in creation window.~~
- ~~Use green chips in filters.~~
- ~~Add Accessibility meta category.~~
- ~~Move Accessibility cat to WCAG 2.1 Compliant~~
- ~~Tooltip missing arrow in categories.~~
- ~~Fix VB double scroll.~~
- ~~Add back upload validation check to upload widget.~~
- ~~Check that documents will display properly and that image upload is restricting by type.~~
