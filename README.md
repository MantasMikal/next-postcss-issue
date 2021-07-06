<h1>IRL</h1>

## Commands

`npm install some_pkg -w web` - install package to workspace

<h2>Branching rules</h2>

Please work on one task at a time!\
When done with the task - write it off, add new ones.

`master` contains the latest production release\
`develop` contains the latest dev release

**The order of developing**

1. Create a new `feature`/`fix`/`update` branch 
2. Develop changes 
3. When done merge the branch to `develop` 
4. Get somebody else to test 
5. If everything is okay merge to `master`
6. Create a `tag` and a `release`

<h2>Resources</h2>

- [x] CI setup
- [x] Deployment - Vercel/Heroku?

## Resources
- [Rehydration](https://www.joshwcomeau.com/react/the-perils-of-rehydration/)
- [Dynamic imports](https://nextjs.org/docs/advanced-features/dynamic-import)
- [Expected server HTML to contain a matching...](https://github.com/vercel/next.js/discussions/17443)
- [Next.js Auth implementation (on the server)](https://nextjs.org/docs/authentication)
- [Auth with Strapi](https://strapi.io/blog/user-authentication-in-next-js-with-strapi)
- [Strapi docs](https://strapi.io/documentation/developer-docs/latest/getting-started/quick-start.html#_1-install-strapi-and-create-a-new-project)
- [JWT, JWE with private/public keys](https://medium.com/nerd-for-tech/jwt-jws-and-jwe-in-nodejs-7595542565d0)
- [JWT. JWE with API key](https://www.npmjs.com/package/jwt-token-encrypt)

<h2>In Real Life tasks</h2>

- [x] CI setup
- [x] Deployment - Vercel/Heroku?
- [x] Add Strapi
- [ ] Create signup system
- [x] Create signup system in frontend
- [ ] Create login system
- [x] Create login system in frontend
d