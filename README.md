<p align="center">
    <h1 align="center">
        Dataverse DevTools
    </h1>
    <h3 align="center">
        The all-in-one tool to develop code for Dataverse/Dynamics 365!
    </h3>
    <p align="center">
        This repo is an open-source project that provides a code for a Dataverse DevTools VS Code Extension that helps you connect to a Dataverse environment, generate TypeScript definitions for entities, create different type of Dataverse-specific projects, upload web-resources right from VS Code and much more.
    </p>
</p>

<p align="center">
    <a href="https://github.com/Power-Maverick/DataverseDevTools-VSCode/actions/workflows/build.yml" alt="Build">
      <img src="https://github.com/Power-Maverick/DataverseDevTools-VSCode/actions/workflows/build.yml/badge.svg?branch=main"/>
    </a>
    <a href="https://github.com/Power-Maverick/DataverseDevTools-VSCode/actions/workflows/release.yml" alt="Release">
      <img src="https://github.com/Power-Maverick/DataverseDevTools-VSCode/actions/workflows/release.yml/badge.svg?branch=main"/>
    </a>
    <a href="https://github.com/Power-Maverick/DataverseDevTools-VSCode/blob/master/LICENSE" alt="License">
      <img src="https://img.shields.io/github/license/Power-Maverick/DataverseDevTools-VSCode"/>
    </a>
</p>

<p align="center">
    <a href="https://img.shields.io/visual-studio-marketplace/d/danish-naglekar.dataverse-devtools" alt="Visual Studio Marketplace Downloads">
      <img src="https://img.shields.io/visual-studio-marketplace/d/danish-naglekar.dataverse-devtools" />
    </a>
    <a href="https://marketplace.visualstudio.com/items?itemName=danish-naglekar.dataverse-devtools" alt="Visual Studio Marketplace Version">
      <img src="https://img.shields.io/visual-studio-marketplace/v/danish-naglekar.dataverse-devtools?label=vscode%20marketplace" />
    </a>
    <a href="https://github.com/Power-Maverick/DataverseDevTools-VSCode" alt="GitHub Stars">
      <img src="https://img.shields.io/github/stars/Power-Maverick/DataverseDevTools-VSCode?label=github%20stars" />
    </a>
</p>

<p align="center">
    <a href="https://github.com/sponsors/Power-Maverick" alt="Sponsor">
      <img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub" />
    </a>
    <a href="https://twitter.com/DanzMaverick" alt="Twitter Follow">
      <img src="https://img.shields.io/twitter/follow/DanzMaverick?style=social" />
    </a>
</p>

<h3 align="center">
  <a href="https://github.com/Power-Maverick/DataverseDevTools-VSCode/issues/new?assignees=Power-Maverick&labels=enhancement%2Ctriage&template=issues-form-feature-request.yaml&title=%5BFeature%5D%3A+">Feature request</a>
  <span> · </span>
  <a href="https://github.com/Power-Maverick/DataverseDevTools-VSCode/issues/new?assignees=Power-Maverick&labels=bug%2Ctriage&template=issue-form-bug.yaml&title=%5BBug%5D%3A+">Report a bug</a>
  <span> · </span>
  <a href="https://github.com/Power-Maverick/DataverseDevTools-VSCode/discussions/categories/q-a">Support</a>
</h3>

> Do check-out the [planned features](#-planned-features) list.

> **Dataverse DevTools Microsoft Login Prompt for connection is not fully functioning and it is been worked upon.**

**Table of contents**

- [⚙ Features](#-features)
  - [Connect to your Dataverse environment](#connect-to-your-dataverse-environment)
  - [Remembers the connected environment per workspace](#remembers-the-connected-environment-per-workspace)
  - [See connection and entity details (with copy feature)](#see-connection-and-entity-details-with-copy-feature)
  - [Initialize TypeScript project & add TS File](#initialize-typescript-project--add-ts-file)
  - [Generate Typings](#generate-typings)
  - [Intellisense for type generated](#intellisense-for-type-generated)
  - [Upload Web Resources](#upload-web-resources)
  - [Filter by solution](#filter-by-solution)
    - [Entities](#entities)
    - [Web Resources](#web-resources)
  - [Smart Match Web Resources](#smart-match-web-resources)
- [🔥 Using Typings](#-using-typings)
- [⌨ Keyboard Shortcuts](#-keyboard-shortcuts)
- [🎁 Early-Access Preview](#-early-access-preview)
- [💭 Planned Features](#-planned-features)
- [✨ Contributing](#-contributing)
- [🔉 Discussions](#-discussions)
- [📃 License](#-license)
- [💙 Big Thanks](#-big-thanks)
- [✍ Credits](#-credits)

## ⚙ Features

### Connect to your Dataverse environment

![Create & Connect](https://github.com/Power-Maverick/DataverseDevTools-VSCode/blob/main/assets/Create&Connect.gif?raw=true)

### Remembers the connected environment per workspace

![Silent Connection Reload](https://github.com/Power-Maverick/DataverseDevTools-VSCode/blob/main/assets/RememberConnection.gif?raw=true)

### See connection and entity details (with copy feature)

![See Details](https://github.com/Power-Maverick/DataverseDevTools-VSCode/blob/main/assets/Connection&EntityDetails.gif?raw=true)

### Initialize TypeScript project & add TS File

Instantiates with following setup:

-   [`@types/xrm`](https://www.npmjs.com/package/@types/xrm)
-   [`WebPack`](https://www.npmjs.com/package/webpack)
-   [`ESLint`](https://www.npmjs.com/package/eslint)
-   [`Prettier`](https://www.npmjs.com/package/prettier)

![TypeScript Project](https://github.com/Power-Maverick/DataverseDevTools-VSCode/blob/main/assets/TypeScriptInitialization.gif?raw=true)

![TypeScript File](https://github.com/Power-Maverick/DataverseDevTools-VSCode/blob/main/assets/AddNewTSFile.gif?raw=true)

### Generate Typings

**Typings are also integrated with [`@types/xrm`](https://www.npmjs.com/package/@types/xrm)**

![Typings](https://github.com/Power-Maverick/DataverseDevTools-VSCode/blob/main/assets/GenerateTypings.gif?raw=true)

### Intellisense for type generated

![IntellisenseTypeScript](https://github.com/Power-Maverick/DataverseDevTools-VSCode/blob/main/assets/IntellisenseForTypeScript.gif?raw=true)

### Upload Web Resources

![WebResourceUpload](https://github.com/Power-Maverick/DataverseDevTools-VSCode/blob/main/assets/WebResourceUpload.gif?raw=true)

### Filter by solution

#### Entities

![FilterEntities](https://github.com/Power-Maverick/DataverseDevTools-VSCode/blob/main/assets/FilterEntitiesBySolution.gif?raw=true)

#### Web Resources

![FilterWRs](https://github.com/Power-Maverick/DataverseDevTools-VSCode/blob/main/assets/FilterWRBySolution.gif?raw=true)

### Smart Match Web Resources

![SmartMatch](https://github.com/Power-Maverick/DataverseDevTools-VSCode/blob/main/assets/SmartMatchScreen.gif?raw=true)

## 🔥 Using Typings

1. Go to **Dataverse DevTools** from the _Activity Side Bar_.
2. From the list of entities, right-click the entity for which you want to create a typing and choose `Generate Typings` option. You can also filter the list of entities by clicking the filter button on the Entities panel as shown [here](#filter-by-solution).
3. Create a onLoad function in your TypeScript file with parameter as `executionContext: Xrm.Events.EventContext`.
4. Initialize your `FormContext` global variable casting it with `Xrm.<entity name>`.

For example:
If you wanted to use _Accounts_ entity typings in your TypeScript file then after the typings are generated the code in your TypeScript file will look as shown below:

```TypeScript
export function onLoad(executionContext: Xrm.Events.EventContext) {
    const formContext: Xrm.Account = executionContext.getFormContext();
    formContext.getAttribute("accountnumber").getValue();
}
```

In the above code snippet, `Xrm.Account` is a typing generated by Dataverse DevTools to provide intellisense specific to the **Account** entity.

## ⌨ Keyboard Shortcuts

| Command                   | Keyboard Shortcut    |
| ------------------------- | -------------------- |
| Create TypeScript project | `Ctrl + D, Ctrl + T` |

## 🎁 Early-Access Preview

This list showcases the features that are build and ready but not fully tested to be released. You can enable these features by navigating to `File` > `Preferences` > `Settings` and search for `Dataverse DevTools` and make sure `Enable Early Access Preview` is **checked**.

| Preview Feature                | Details                                                                                                                                                                                                                                                                        |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Login using Client Id & Secret | You can now use your own Client Id & Secret. When you want to use thise feature please make sure on the Azure AD Registered App under **Authentication** you have added **Platform** as `Single-page application` with **Redirect URI** as `http://localhost:29827/callback/`. |

## 💭 Planned Features

-   Integrate with [Dataverse-ify](https://github.com/scottdurow/dataverse-ify/).
-   Initiate plugin project.

## ✨ Contributing

Before creating the pull request for contributing, please read the [Contributing Guidelines](CONTRIBUTING.md).

We encourage you to pitch in, join the team and showcase your name on this repo. If you are unsure how you can contribute, please reach out to [Power Maverick](https://twitter.com/DanzMaverick).

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://powermaverick.dev/"><img src="https://avatars.githubusercontent.com/u/36135520?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Danish Naglekar</b></sub></a><br /><a href="#question-Power-Maverick" title="Answering Questions">💬</a> <a href="https://github.com/Power-Maverick/DataverseDevTools-VSCode/commits?author=Power-Maverick" title="Code">💻</a> <a href="#content-Power-Maverick" title="Content">🖋</a> <a href="#design-Power-Maverick" title="Design">🎨</a> <a href="https://github.com/Power-Maverick/DataverseDevTools-VSCode/commits?author=Power-Maverick" title="Documentation">📖</a> <a href="#infra-Power-Maverick" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#security-Power-Maverick" title="Security">🛡️</a> <a href="https://github.com/Power-Maverick/DataverseDevTools-VSCode/commits?author=Power-Maverick" title="Tests">⚠️</a> <a href="#tool-Power-Maverick" title="Tools">🔧</a> <a href="#tutorial-Power-Maverick" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/mohsinonxrm"><img src="https://avatars.githubusercontent.com/u/21046804?v=4?s=100" width="100px;" alt=""/><br /><sub><b>mohsinonxrm</b></sub></a><br /><a href="#question-mohsinonxrm" title="Answering Questions">💬</a> <a href="https://github.com/Power-Maverick/DataverseDevTools-VSCode/issues?q=author%3Amohsinonxrm" title="Bug reports">🐛</a> <a href="https://github.com/Power-Maverick/DataverseDevTools-VSCode/commits?author=mohsinonxrm" title="Code">💻</a> <a href="#example-mohsinonxrm" title="Examples">💡</a> <a href="#ideas-mohsinonxrm" title="Ideas, Planning, & Feedback">🤔</a> <a href="#plugin-mohsinonxrm" title="Plugin/utility libraries">🔌</a> <a href="#research-mohsinonxrm" title="Research">🔬</a> <a href="#userTesting-mohsinonxrm" title="User Testing">📓</a></td>
    <td align="center"><a href="https://github.com/JoshSmithXRM"><img src="https://avatars.githubusercontent.com/u/6895577?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Josh Smith</b></sub></a><br /><a href="https://github.com/Power-Maverick/DataverseDevTools-VSCode/issues?q=author%3AJoshSmithXRM" title="Bug reports">🐛</a> <a href="#maintenance-JoshSmithXRM" title="Maintenance">🚧</a> <a href="#userTesting-JoshSmithXRM" title="User Testing">📓</a></td>
    <td align="center"><a href="https://github.com/P-focT"><img src="https://avatars.githubusercontent.com/u/81171713?v=4?s=100" width="100px;" alt=""/><br /><sub><b>P-focT</b></sub></a><br /><a href="https://github.com/Power-Maverick/DataverseDevTools-VSCode/issues?q=author%3AP-focT" title="Bug reports">🐛</a> <a href="#maintenance-P-focT" title="Maintenance">🚧</a> <a href="#userTesting-P-focT" title="User Testing">📓</a></td>
    <td align="center"><a href="https://benediktbergmann.eu/"><img src="https://avatars.githubusercontent.com/u/9703748?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Benedikt Bergmann</b></sub></a><br /><a href="#example-BenediktBergmann" title="Examples">💡</a> <a href="#ideas-BenediktBergmann" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/filcole"><img src="https://avatars.githubusercontent.com/u/6078398?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Phil Cole</b></sub></a><br /><a href="https://github.com/Power-Maverick/DataverseDevTools-VSCode/issues?q=author%3Afilcole" title="Bug reports">🐛</a> <a href="#ideas-filcole" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/improving-jeffd"><img src="https://avatars.githubusercontent.com/u/1213947?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jeff Dodds</b></sub></a><br /><a href="#mentoring-improving-jeffd" title="Mentoring">🧑‍🏫</a></td>
  </tr>
  <tr>
    <td align="center"><a href="http://www.powerapps.com/"><img src="https://avatars.githubusercontent.com/u/10568244?v=4?s=100" width="100px;" alt=""/><br /><sub><b>MattB</b></sub></a><br /><a href="#mentoring-MattB-msft" title="Mentoring">🧑‍🏫</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

## 🔉 Discussions

If you want to have any discussions on any feature, please use the [Discussion Board](https://github.com/Power-Maverick/DataverseDevTools-VSCode/discussions).

## 📃 License

This software is released under [MIT License](http://www.opensource.org/licenses/mit-license.php)

## 💙 Big Thanks

[Magnus Gether Sørensen](https://www.linkedin.com/in/xrmwizard/) for helping in providing insights for XrmDefinitelyTyped.

[Temmy Raharjo](https://www.linkedin.com/in/temmy-wahyu-raharjo/) for encouraging me to start using `pac cli command` to generate Plugin project.

## ✍ Credits

Icons sourced from - [https://icon-sets.iconify.design](https://icon-sets.iconify.design/)

JSON to TypeScript conversions - [https://quicktype.io/typescript](https://quicktype.io/typescript)
