# Protocol

Protocol is a [Tailwind UI](https://tailwindui.com) site template built using [Tailwind CSS](https://tailwindcss.com) and [Next.js](https://nextjs.org).

## Getting started

Video: [https://www.youtube.com/watch?v=tLQPuy2L8Vw&feature=youtu.be](https://www.youtube.com/watch?v=tLQPuy2L8Vw&feature=youtu.be)

To get started with this template, first install the yarn dependencies:

```bash
yarn
cp .env.example .env.local
```

Next, run the development server:

```bash
yarn dev
```

Finally, open [http://localhost:3000](http://localhost:3000) in your browser to view the website.

__CREATE YOUR FIRTS PAGE DOCUMENTATION__
Into src/pages create or edit the pages in whick you work

don´t forget export a const description into your mdx page and the title'page

it must looks like:

```mdx
export const description = 'YOUR_DESCRIPTION_HERE'

# YOUR_TITLE_HERE

...

SOME WHEREVER ELSE

```


## Customizing

You can start editing this template by modifying the files in the `/src` folder. The site will auto-update as you edit these files.

## Global search

By default this template uses [Algolia DocSearch](https://docsearch.algolia.com) for the global search. DocSearch is free for open-source projects, and you can sign up for an account on their website. Once your DocSearch account is ready, update the following [environment variables](https://nextjs.org/docs/basic-features/environment-variables) in your project with the values provided by Algolia:

```
NEXT_PUBLIC_DOCSEARCH_APP_ID=
NEXT_PUBLIC_DOCSEARCH_API_KEY=
NEXT_PUBLIC_DOCSEARCH_INDEX_NAME=
```

## License

This site template is a commercial product and is licensed under the [Tailwind UI license](https://tailwindui.com/license).

## Learn more

To learn more about the technologies used in this site template, see the following resources:

- [Tailwind CSS](https://tailwindcss.com/docs) - the official Tailwind CSS documentation
- [Next.js](https://nextjs.org/docs) - the official Next.js documentation
- [Headless UI](https://headlessui.dev) - the official Headless UI documentation
- [Framer Motion](https://www.framer.com/docs/) - the official Framer Motion documentation
- [MDX](https://mdxjs.com/) - the official MDX documentation
- [Algolia Autocomplete](https://www.algolia.com/doc/ui-libraries/autocomplete/introduction/what-is-autocomplete/) - the official Algolia Autocomplete documentation
- [Zustand](https://docs.pmnd.rs/zustand/getting-started/introduction) - the official Zustand documentation
