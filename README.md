# TypeScript NPM Package Starter Kit
A forkable starter kit for building, testing, and publishing an NPM package in TypeScript

After forking, make sure to change the values in `package.json` for name, description, and github URL.

# Testing

Add your tests to a `*.spec.ts` file in the `__tests__` folder and run tests with:
```
npm test
```
or to have tests run when files are changed:
```
npm run test:watch 
```
For a test coverage report, run
```
npm run test:coverage
```
View interactive results by right clicking on the `/coverage/lcov-report/index.html` and selecting "Open with Live Server" if in VS Code.

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
