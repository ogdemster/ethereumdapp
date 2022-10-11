This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Article

On Git-hub
create repository on Git-Hub with default settings and give a meaningfull name
ON CMD
cd to folder then
npx create-next-app@latest
give same name that you gave on github then wait until its being intalled. Then
cd your_file_name
code .

On VSCode
Go to terminal > new Terminal at the menu. After new teminal opened set the git remote by
git remote add origin https://github.com/[GITHUB_USERNAME]/[YOUR_REPOSITORY_NAME].git
git branch -M main
git push -u origin main
create .github|workflows\node.js.yml and set it up
create pages/.nojekyll empy file.
next.config.js add lines.
package.json add scritps > "export": "next export",
Commit all changes
On Git-Hub
create branch on Git-Hub with name gh-pages
Go to settings > pages then set the Branch gh-pages
Link for your dapp will shown top of page

if any trouble with installing on Git-Hub side delete package-lock.json and node_modules then npm install again. that will create node_modules and proper package-lock.json
