# Happy Packet Switching Slides

PechaKucha slideshows for the Happy Packet Switching event at King's
College London on 6 November 2019.

## Live URL

Visit [Gitlab Pages](https://klinamen0.gitlab.io/happy-packet-switching/).

## Quick Start

1. Clone this repository, 
   ```
   git clone git@gitlab.com:klinamen0/happy-packet-switching.git
   ```
2. Talks are stored in the /talks/ directory. To add a new talk,
   create a new directory for each speaker. This is where we'll keep
   their html and images.
   ```
   cd talks
   mkdir licklider
   cp nemenyi/index.html licklider/
   ```
3. Edit the .slides div. Every `<section>` creates a new slide. Ensure
   that images have the class stretch, so that they go full screen. It
   might look something like this.
   
   ```
	   <div class="slides">
		   <section>
			   <h1>Dr Daniel Nemenyi</h1>
			   <h3>Cybernetic Guerilla Warfare</h3>
		   </section>
			<section><img class="stretch" src="01.png"></section>
			<section><img class="stretch" src="02.png"></section>
			<section><img class="stretch" src="03.png"></section>
			</div>
   ```
   
4. Link the speaker's `index.html` name to the root `index.html`.

5. Push changes to gitlab, and bear in mind it can take a few minutes
   for Gitlab Pages to update.
