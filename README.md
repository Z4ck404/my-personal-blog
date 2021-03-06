[![Netlify Status](https://api.netlify.com/api/v1/badges/04cfb908-682c-4469-b894-7bfdc949cc37/deploy-status)](https://app.netlify.com/sites/spectacular-crane-a9daf/deploys)

# Run it locally 

1. Install [Node.js and npm](https://nodejs.org/en/)

1. Install npm dependencies:

        npm install

1. Get "stackbit-api-key" from project menu in [Stackbit dashboard](https://app.stackbit.com/dashboard)

1. Run the following command to assign this key to `STACKBIT_API_KEY` environment variable:

        export STACKBIT_API_KEY={stackbit_netlify_api_key}

1. Run the following command to fetch additional site contents from Stackbit if needed:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://api.stackbit.com/pull/5f6a9dafbad7da001cf817f5

1. Start a local development server:

        npm run develop

1. Browse to [http://localhost:8000/](http://localhost:8000/)

# Built using : 

- This site was generated by [www.stackbit.com](https://www.stackbit.com), v0.3.23.

- Stackbit Vanilla Theme original README is located [here](./README.theme.md).
- hosted by Netlify. 
