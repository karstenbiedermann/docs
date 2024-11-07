# Mintlify Starter Kit

Click on `Use this template` to copy the Mintlify starter kit. The starter kit contains examples including

- Guide pages
- Navigation
- Customizations
- API Reference pages
- Use of popular components

### Prerequisites

- Install [Node.js](https://nodejs.org/) (version 19 or higher)

### Clone the repository

To clone the repository from GitHub, follow these steps:

1. Navigate to the repository on GitHub.
2. Click on the "Code" button and copy the repository URL.
3. Open your terminal and run the following command:

```
git clone <repository-url>
```

Replace `<repository-url>` with the URL you copied in step 2.

### Configure the project

1. Navigate to the root of your cloned repository:

```
cd <repository-name>
```

Replace `<repository-name>` with the name of your cloned repository.

2. Install the project dependencies:

```
npm install
```

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

### Deploy changes

Install our Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard.

### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
