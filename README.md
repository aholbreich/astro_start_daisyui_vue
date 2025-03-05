# Astro + Daisy IU + Vue.js project stater

A minimalistic but opinionated Astro + Vue project starter. Particularly its bases on Astro 5, Tailwind 4, Daisy UI 5 and of course Vue.js

The purpose is to be the pre-configured project starter for this particularly very successful tech stack. 
The project also, includes a few example components. 

If you not intend to do very dynamic components. 

TODO. [Live Demo](https://todo)

Also see AlpineJS alternative [aholbreich/astro_start_tailwind](https://github.com/aholbreich/astro_start_tailwind)

## Usage

Bootstrap your new project using this template with:

```bash
pnpm create astro@latest --template aholbreich/astro_start_daisyui_vue
```

Alternatively clone this repo and just start coding. The following commands should be helpful:

### Commands

All commands are run from the root of the project, from a terminal:
I'm in favor of `pnpm` but `npm` and yarn would work as well.

| Command                 | Action                                           |
| :---------------------- | :----------------------------------------------- |
| `pnpm install`          | Installs dependencies                            |
| `pnpm dev`              | Starts local dev server at `localhost:3000`      |
| `pnpm build`            | Build your production site to `./dist/`          |
| `pnpm preview`          | Preview your build locally, before deploying     |
| `pnpm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `pnpm run astro --help` | Get help using the Astro CLI                     |

if  `pnpm preview`  is not working for you, you can workaround with:

```bash
pnpm build
pnpm dlx serve dist
```

## Dependencies

- Astro 5.4
- Astro Icon
- Astro SEO
- Astro MDX
- Tailwindcss 4
- Daisy UI 5!
- VueJS

- Netlify

## Collaboration

Feel free to provide your feedback or feature requirements.