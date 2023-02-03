# Halfstack

This project demonstrates creating your own stack - for a talk for HalfStack Conf 2023 in Phoenix, AZ.

[HalfStack link](https://halfstackconf.com/phoenix/)

## Try It Yourself

To create your own "zack stack app" run:

```bash
npx nx g @halfstack/zack-stack:app foo
```
^ replacing `foo` with the desired name for your application.

Then to run this app in dev mode, run the command:

```bash
npx nx serve-fullstack foo-web
```
^ Again replacing `foo-web` with `your-name-web`.


## Understand this workspace

Run `nx graph` to see a diagram of the dependencies of the projects.

## Remote caching

Run `npx nx connect-to-nx-cloud` to enable [remote caching](https://nx.app) and make CI faster.

## Further help

Visit the [Nx Documentation](https://nx.dev) to learn more.
