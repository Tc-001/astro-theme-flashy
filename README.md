# Astro theme "flashy"

This is a simple and minimalistic astro theme taking advantage of [XElement](https://www.npmjs.com/package/astro-xelement) for smooth and seamless page transitions.

![Screenshot 2022-05-15 at 16-31-46 Astro](https://user-images.githubusercontent.com/55956895/168475500-45733ec1-2a1c-44cb-8641-bad180e80a21.png)

## Nav
You can change your nav pages by:
- Adding a new page in `./src/pages`
- Changing the relevant entry in `./src/config.ts`
	- Title: What the user sees
	- URL: Where the nav should point to
	- Color: What color should the nav be in that page
	- Icon: What icon should the spinner show

## Blog
You can add a blog entry by creating a new markdown file in `./src/blog`. It should follow the naming `<number>-<name>.md`, where a higher number should appear first.
