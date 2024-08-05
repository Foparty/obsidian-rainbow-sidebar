# The BEST Obsidian Colored Sidebar

A simple sass snippet to modify the look of your Obsidian Sidebar just changing a few values

![image](/img/CleanShot%202024-08-05%20at%2013.27.59@2x.png)

## How to use

---

1. Fork this repo or if you are not very tech savvy, download the zip file and extract it into your `.obsidian/snippets` folder.

this will create a folder called `obsidian-rainbow-sidebar` in your `.obsidian/snippets` folder

2. Open the obsidian-rainbow-sidebar folder in your text editor of choice... for most people VSCode.

3. Make sure there is a "dev" command on your `package.json` file.

4. Install the dependencies by running the command `npm install` or `yarn install` / `bun install` (whatever you use)

5. Run the command `npm run dev` or `yarn dev` / `bun dev` (whatever you use) to compile the sass file into a css file, that will be outputted to your `.obsidian/snippets/`

6. Open your Obsidian settings and go to the `Appearance` tab.

7. Turn on the CSS snippets, and turn on the snippet `rainbow-sidebar` if you havent changed the name.

8. On your text editor, you can modify the SCSS file as much as you want, but if you don't really know how to use SCSS, just modify the variable on the top of the file.

   8.1: $iterations = NUMBER OF FOLDERS THAT YOU HAVE (you can set it as 3000 but this will output a lot of unused CSS)

   8.2: $base-hue = NUMBER THAT YOU WANT TO START FROM THE COLOR PALETTE. 0 will be red, 220 blue... you play around with it.

   8.3: $max-lightness = how light the color palette will be. 50% leaves it pretty good, i will not go highrt than 65%, or lower that 30%.

   8.4: $factor = this is a multiplier that will change the color palette. (if you set it as 0, all colors will be the same, if 1, the change will be almost none, I RECOMMEND GOING FROM 5 TO 15 you can set this with decimal numbers if needed).

   NOTE: the other variables are there just for future development of my main idea. witch was also adding gradient inside the folders. The problem for now is that i need to revisit my SCSS lessons cause if I do it now, the number of lines on the final CSS file goes over 160k.

   enjoy!

comparation between what you get now and what I want to achieve:

![image](/img/CleanShot%202024-08-05%20at%2013.28.44@2x.png)
![image](/img/CleanShot%202024-08-05%20at%2013.29.26@2x.png)
