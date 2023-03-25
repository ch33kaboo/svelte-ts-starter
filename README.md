# svelte-ts-starter

<a href="https://svelte.dev/" target="_blank"> <img src="https://img.icons8.com/doodle/344/svetle.png" height="48" width="48"/> </a> &nbsp;&nbsp;
<a href="http://tailwindcss.com/" target="_blank"> <img src="https://img.icons8.com/color/48/000000/tailwindcss.png"/> </a> &nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://daisyui.com/" target="_blank"> <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f33c.png" height="48" width="48"/> </a> &nbsp;&nbsp;&nbsp;
<a href="https://vitejs.dev/" target="_blank"> <img src="https://camo.githubusercontent.com/61e102d7c605ff91efedb9d7e47c1c4a07cef59d3e1da202fd74f4772122ca4e/68747470733a2f2f766974656a732e6465762f6c6f676f2e737667" height="48" width="48"/> </a> &nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/kaisermann/svelte-i18n" target="_blank"> <img src="https://i.ibb.co/M1KjFS5/i18n.png" height="48" width="48"/> </a> &nbsp;&nbsp;&nbsp;&nbsp;<a href="https://prettier.io/" target="_blank"> <img src="https://cdn.freebiesupply.com/logos/large/2x/prettier-2-logo-svg-vector.svg" height="48" width="48"/> </a> &nbsp;&nbsp;&nbsp;&nbsp;<a href="https://prettier.io/" target="_blank"> <img src="https://lemariva.com/storage/temp/public/79e/a13/6b1/vscode__1024.png" height="48" width="48"/> </a> &nbsp;&nbsp;&nbsp;&nbsp;

This is a starter template for building and running an app using these techs:

-   [Svelte TypeScript](https://svelte.dev/blog/svelte-and-typescript) : Svelte-TS is a version of Svelte that supports TypeScript for type-checking and other TypeScript features.
-   [Tailwind CSS](https://tailwindcss.com/) : A utility-first CSS framework that provides a set of pre-defined classes for common styles (also the project uses `prettier-plugin-tailwindcss` to automatically sort Tailwind CSS classes in a consistent order.)
-   [daisyUI](https://daisyui.com/) : UI components for Tailwind CSS.
-   [Vite](https://vitejs.dev/) : Build tool and development server for modern web applications.
-   [svelte-i18n](https://github.com/kaisermann/svelte-i18n) : A package for Svelte that provides internationalization (i18n) features (also the starter project has `lokalise.i18n-ally` vscode extension setup.)
-   **Dark mode functionality** : The starter project includes functionality for toggling between light and dark mode, implemented using a Svelte store in `src/stores/darkModeStore.js`.
-   **Custom colors** : The starter project defines four custom colors in `tailwind.config.cjs` (`lightest`, `light`, `dark`, and `darkest`), which can be customized to match a given color palette.
-   **Prettier configuration** : The workspace includes a pre-configured Prettier setup for consistent code formatting.

## Project Initilization

Upon opening this repository in VS Code it will prompt you to install recommended extensions (Prettier, Tailwind CSS IntelliSense, Svelte language support, i18n extension .. etc)

## 🛠 Installation

To get going, make sure you have [NodeJS](https://nodejs.org/en/) and [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) installed on your machine.

1. clone project locally

    ```sh
    git clone 'https://github.com/ch33kaboo/svelte-ts-starter.git'
    ```

2. go to project directory

    ```sh
    cd svelte-ts-starter/
    ```

3. Install dependencies

    ```sh
    npm install
    ```

4. Start the development server

    ```sh
    npm run dev
    ```

## :grey_question: What to change in the starter

-   change the content of `title` tag in `index.html`.
-   change the hex codes of the colors in `tailwind.config.cjs`.
-   change the content of `README.md` file.
-   remove the directory .git from the root of the starter project, and initialize your own git repo.

## 🚀 Next steps

Go visit the [documentation page](https://svelte.dev/docs) for SvelteJS to start building! :smiley:

<!--
Made with 🖤 by ch33kaboo
-->
