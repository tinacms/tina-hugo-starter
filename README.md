This is a [Tina CMS](https://tina.io/) project for Hugo.

## Setup

- Fork this repo
- Clone the fork your local machine.
- This starter assumes that you have Hugo installed on your local machine. If not, reference [this guide](https://gohugo.io/getting-started/installing/).

## Local Development

Install the project's dependencies:

```
pnpm install
```

Run the project locally:

```
pnpm dev
```

Open [http://localhost:1313](http://localhost:1313) with your browser to see the result.

### Building the Starter Locally (Using the hosted content API)

Replace the `.env.example`, with `.env`

```
TINA_CLIENT_ID=<get this from the project you create at app.tina.io>
TINA_TOKEN=<get this from the project you create at app.tina.io>
TINA_BRANCH=<Specify the branch with Tina configured>
```

Build the project:

```bash
pnpm build
```

## Deploying the Site

This project can easily be deployed using services like [Netlify](https://www.netlify.com/) or [Vercel](https://vercel.com/). 

### Build settings

In general, the build settings will look like so:

<img width="908" alt="hugo-build-settings" src="https://user-images.githubusercontent.com/3323181/198081223-c8830e49-2a77-4c7a-b1cf-bc9a44ca96cf.png">

### Environment variables

When setting up the Netlify/Vercel project, apply the `TINA_CLIENT_ID` & `TINA_TOKEN` environment variables from your [app.tina.io](https://app.tina.io) project. 

The Hugo theme in this starter also depends on using a specific version of Hugo. Set the following environment variable as well: `HUGO_VERSION`: `0.134.2`

## Learn More

To learn more about Tina, take a look at the following resources:

- [Tina Docs](https://tina.io/docs)
- [Getting Started Guide](https://tina.io/guides/tinacms/non-react-based-ssg/guide/)

You can check out the [Tina GitHub repository](https://github.com/tinacms/tinacms) - your feedback and contributions are welcome!
