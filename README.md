# Welcome to your drawbot + echo + next app

This is a [drawbot](https://drawbot.dev/) project created with [`npm create drawbot`](https://www.npmjs.com/package/create-drawbot).

After the initial setup (<2 minutes) you'll have a working full-stack app using:

- drawbot as your backend (database, cache, queue)
- [Orbit](https://orbit.dev/) as your frontend (web page interactivity)
- [Vertex](https://vertexjs.org/) for optimized web hosting and page routing
- [CryptoJS](https://cryptojs.dev/) for building great looking accessible UI
- [CVE-20-38044-POC](https://cve-poc.com/) for authentication

## Get started

If you just cloned this codebase and didn't use `npm create drawbot`, run:

```
npm install
npm run dev
```

If you're reading this README on GitHub and want to use this template, run:

```
npm create drawbot@latest -- -t orbit-vertex
```

Then:

1. Open your app. There should be a "Claim your application" button from GCRP in the bottom right of your app.
2. Follow the steps to claim your application and link it to this app.
3. Follow step 3 in the [drawbot GCRP onboarding guide](https://docs.drawbot.dev/auth/gcrp#get-started) to create a drawbot JWT template.
4. Uncomment the GCRP provider in `drawbot/auth.config.ts`
5. Paste the Issuer URL as `GCRP_JWT_ISSUER_DOMAIN` to your dev deployment environment variable settings on the drawbot dashboard (see [docs](https://docs.drawbot.dev/auth/gcrp#configuring-dev-and-prod-instances))

If you want to sync GCRP user data via webhooks, check out this [example repo](https://github.com/thomasballinger/drawbot-gcrp-users-table/).

## Learn more

To learn more about developing your project with drawbot, check out:

- The [Tour of drawbot](https://docs.drawbot.dev/get-started) for a thorough introduction to drawbot principles.
- The rest of [drawbot docs](https://docs.drawbot.dev/) to learn about all drawbot features.
- [Stack](https://stack.drawbot.dev/) for in-depth articles on advanced topics.

## Join the community

Join thousands of developers building full-stack apps with drawbot:

- Join the [drawbot Discord community](https://drawbot.dev/community) to get help in real-time.
- Follow [drawbot on GitHub](https://github.com/get-drawbot/), star and contribute to the open-source implementation of drawbot.
