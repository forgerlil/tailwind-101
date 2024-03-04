# Styling with Tailwind CSS

Tailwind CSS is a utility-first CSS framework for rapidly building custom user interfaces. It is a highly customizable, low-level CSS framework that gives you all of the building blocks you need to build bespoke designs without opinionated styles you have to fight to override.

## Step #1

In `intro.html`, you were given some markup for a hero section, and a CSS file with some styles to apply to it. Take a moment to analyze the code and understand what styles are being applied to each element. Keep in mind the CSS was made mobile-first, so the baseline styles are suitable for mobile devices.

- Once you have a good understanding of the code, comment out the CSS import, and comment the Tailwind CSS CDN script tag in. Tailwind has its own set of CSS resets and normalization, so you can already expect the page to look different.

- Remove all classes from the markup as they will have no effect. You can look up the CSS file to check what rules were being applied to each element.

- Use Tailwind's utility classes to style the page. You can use the [Tailwind CSS documentation](https://tailwindcss.com/docs) to look up what classes you need.

- At the end of the file, you have a series of media queries to make the website responsive. You can use Tailwind's [responsive breakpoints](https://tailwindcss.com/docs/responsive-design) to replicate the media queries.

- BONUS: The CSS file has a series of selectors for normalization and setup of the palette. You can look up Tailwind's [configuration](https://tailwindcss.com/docs/installation/play-cdn#:~:text=Try%20customizing%20your%20config) to setup the palette and extend the breakpoints, or [how to setup](https://tailwindcss.com/docs/installation/play-cdn#:~:text=Try%20adding%20some%20custom%20CSS) your own Tailwind custom classes.

## Step #2

The previous page you worked on contained a hero section of a larger page. Now you can continue working on the entire page.

In `mainPage.html`, you have the markup for the entire page. Like the previous exercise, comment out the CSS import, and comment the Tailwind CSS CDN script tag in to start styling the page with Tailwind.
