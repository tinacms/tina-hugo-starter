This is a [Tina CMS](https://tina.io/) project for Hugo.

## Local Development
 
This starter assumes that you have Hugo installed on your local machine. If not, reference [this guide](https://gohugo.io/getting-started/installing/).

Install the project's dependencies:

```
yarn install
```

Run the project locally:

```
yarn dev
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
yarn build
```

## Learn More

To learn more about Tina, take a look at the following resources:

- [Tina Docs](https://tina.io/docs)
- [Getting started guide](https://tina.io/guides/tinacms/non-react-based-ssg/guide/)

You can check out [Tina Github repository](https://github.com/tinacms/tinacms) - your feedback and contributions are welcome!
