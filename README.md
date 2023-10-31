
### Setup

```sh
npx gatsby new dob-home https://github.com/eif0/dob-home
```


```sh
cd dob-home
```

### Run

Start: `npm run develop`.

Browse `http://localhost:8000`

## Use and modify

this [shorter](https://www.gatsbyjs.com/docs/how-to/plugins-and-themes/using-a-gatsby-theme/) or [longer](https://www.gatsbyjs.com/tutorial/using-a-theme/) tutorial. The tutorials don't exactly apply to this starter however the concepts are the same.

This guide [Shadowing in Gatsby Themes](https://www.gatsbyjs.com/docs/how-to/plugins-and-themes/shadowing/) helps understand how to customize the underlying theme

This project creates a new Gatsby site that installs and configures the theme [`@lekoarts/gatsby-theme-cara`](https://github.com/LekoArts/gatsby-themes/tree/main/themes/gatsby-theme-cara).

Check README and other files to see available options and how to shadow the various components including Theme UI. Generally speaking your files should go in `src/@lekoarts/gatsby-theme-cara/` to shadow/override files. The Theme UI config can be configured by shadowing its files in `src/gatsby-plugin-theme-ui/`.

### Custom content

The content of this project is defined in four `.mdx` files inside the theme's `sections` folder. You can override the files `intro.mdx`, `projects.mdx`, `about.mdx` and `contact.mdx`. This starter has overridden all files for you already.

You have to use the `<ProjectCard />` component inside `projects.mdx` to display the cards. Example:

```md
## Projects

<ProjectCard title="Freiheit" link="https://www.behance.net/gallery/58937147/Freiheit" bg="linear-gradient(to right, #D4145A 0%, #FBB03B 100%)">
This project is my entry to Adobe's #ChallengeYourPerspective contest.
</ProjectCard>
```

### Change the `static` folder

The `static` folder contains the icons, social media images and `robots.txt`. Don't forget to change these files, too! You can use [Real Favicon Generator](https://realfavicongenerator.net/) to generate the image files inside `static`.


## Gatsby

Full documentation for Gatsby lives [on Gatsby's website](https://www.gatsbyjs.com/).

### Themes

To learn more about Gatsby themes specifically. Check out the [theme docs](https://www.gatsbyjs.com/docs/themes/).

### General

- Starting with the [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.com/docs/tutorial/).

- For code samples: [Gatsby's documentation](https://www.gatsbyjs.com/docs/). In particular, check out the How-to Guides and Reference items in the primary navigation.

## Thanks

All rights on the Gatsby theme used in dob-home goes to [Lekoarts](https://twitter.com/lekoarts_de).
Please consider joining his [sponsors](https://github.com/sponsors/LekoArts).
