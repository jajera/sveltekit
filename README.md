# sveltekit

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

## About The Project
My personal wiki notes on sveltekit implementation

### Built With
[![kit.svelte.dev][kit.svelte.dev]][svelte-url]


## Getting Started

### Prerequisites

* Grant permission to main branch to allow it to deploy to gh-pages branch.

  * Go to Settings page of the repository, click Environments tab and select github-pages environment then click on Edit button.

  * Under Deployment branches, click Add deployment branch rule and enter main on the Branch name pattern text then click Add rule button to apply the changes.

### Installation

1. Create a new repository.
2. Clone the newly created repository.

    ``` bash
    git clone git@github.com:<username>/<repository>.git
    ```

3. Change directory to the local repository path.
4. Create new Svelte project

    ``` bash
    npm create svelte@latest
    ```

5. Install dependencies.

    ``` bash
    npm install
    ```

### Developing

1. Run development server.

```bash
npm run dev
```

2. Install static adapter

```bash
npm install @sveltejs/adapter-static --save-dev
```

### Building

1. Create production version.

```bash
npm run build
```

2. Preview production build

```bash
npm run preview
```

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/jajera/jekyll.svg?style=for-the-badge
[contributors-url]: https://github.com/jajera/jekyll/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/jajera/jekyll.svg?style=for-the-badge
[forks-url]: https://github.com/jajera/jekyll/network/members
[stars-shield]: https://img.shields.io/github/stars/jajera/jekyll.svg?style=for-the-badge
[stars-url]: https://github.com/jajera/jekyll/stargazers
[issues-shield]: https://img.shields.io/github/issues/jajera/jekyll.svg?style=for-the-badge
[issues-url]: https://github.com/jajera/jekyll/issues
[license-shield]: https://img.shields.io/github/license/jajera/jekyll.svg?style=for-the-badge
[license-url]: https://github.com/jajera/jekyll/blob/master/LICENSE.txt
[kit.svelte.dev]: https://img.shields.io/badge/SvelteKit-C7C7C7?style=for-the-badge&logo=svelte&logoColor=FF470C
[svelte-url]: https://kit.svelte.dev
