---
layout: tutorial
title: Installing FlashPunk
category: getting-started
---

FlashPunk is an ActionScript 3 library, meaning it is not a piece of software or single program, but rather a huge collection of ActionScript 3 (.as) files that contain helpful code for setting up your games, rendering different types of graphics, resolving in-game collisions between objects, and much, much more. In order to use it, you're doing to have to download the library and import it into your projects.

## Contents

<ul class="nav nav-pills nav-stacked">
    <li><a href="#download-flashpunk">1. Download FlashPunk</a></li>
	<li><a href="#start-creating">2. Start Creating!</a></li>
</ul>

<h2 id="download-flashpunk">1. Download FlashPunk</h2>

So your first step is to actually get the FlashPunk source files.

[Download FlashPunk][home]

If you've followed the [Setting up FlashDevelop][setting-up-flashdevelop] tutorial, you know how to start a new basic AS3 Project and compile it. To add FlashPunk into your current project, first extract the archive you downloaded. Contained should be a folder called net; everything within that folder is FlashPunk. So copy that whole net folder into your project next to your Main.as class. Once you've done that, your project directory (relative to Main.as) should look like this:

    net/
    	flashpunk/
    		debug/
    		graphics/
    		masks/
    		tweens/
    		utils/
    		Engine.as
    		Entity.as
    		FP.as
    		...etc.
    Main.as

<h2 id="start-creating">Start Creating!</h2>

Once you've got that all set up, you're ready to proceed to [FlashPunk Basics][basics]!

[home]: http://useflashpunk.net/ "FlashPunk Homepage"
[setting-up-flashdevelop]: {% post_url 2000-01-01-setting-up-flashdevelop %} "Setting Up FlashDevelop"
[basics]: {% post_url 2001-01-01-flashpunk-basics %} "FlashPunk Basics"
