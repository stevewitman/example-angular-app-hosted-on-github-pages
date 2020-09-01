# Example App: Host Angular app on GitHub Pages

Create a GitHub repo for the project and add a remote.

```
git remote add origin git@github.com:stevewitman/example-angular-app-hosted-on-github-pages.git
```

Commit and Push Angular app to GitHub.

Add `angular-cli-ghpages` to your project.

```
ng add angular-cli-ghpages
```

If you are not using a custom domain, run ng deploy and specify the base href with the name of the **repo-name** between two forward slashes to build and deploy.  Use repo name, which may be different different than the project name.

```
ng deploy --base-href=/ex-github-pages-hosting/
```

To use a custom domain, see docs ...

NPM package: [angular-cli-ghpages](https://www.npmjs.com/package/angular-cli-ghpages)

## To run this example

With [Angular CLI](https://github.com/angular/angular-cli) version 9.1.9 installed ...

Clone or download this repo and run `npm install`

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. 

The app will automatically reload if you change any of the source files.

## Demo

Unless you are using a custom domain, you can see your deployed page at https://<user_name>.github.io/<repo_name>/.

Example URL: https://stevewitman.github.io/example-angular-app-hosted-on-github-pages/


