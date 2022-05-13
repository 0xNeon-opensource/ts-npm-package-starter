# TypeScript NPM Package Starter Kit
A forkable starter kit for building, testing, and publishing an NPM package in TypeScript

After forking, make sure to change the values in `package.json` for name, description, and github URL.

# Publishing

First, make sure you're logged into NPM (create an account if youu don't have one):
```
npm login
```

To publish for the first time, run:
```
npm publish
```

When you're ready to release a new version, use:
```
npm pushNextVersion
```
