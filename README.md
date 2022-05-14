












*Psst — looking for a more complete solution? Check out [SvelteKit](https://kit.svelte.dev), the official framework for building web applications of all sizes, with a beautiful development experience and flexible filesystem-based routing.*

*Looking for a shareable component template instead? You can [use SvelteKit for that as well](https://kit.svelte.dev/docs#packaging) or the older [sveltejs/component-template](https://github.com/sveltejs/component-template)*

---

# svelte app

This is a project template for [Svelte](https://svelte.dev) apps. It lives at https://github.com/sveltejs/template.

To create a new project based on this template using [degit](https://github.com/Rich-Harris/degit):

```bash
npx degit sveltejs/template svelte-app
cd svelte-app
```

*Note that you will need to have [Node.js](https://nodejs.org) installed.*


## Get started

Install the dependencies...

```bash
cd svelte-app
npm install
```

...then start [Rollup](https://rollupjs.org):

```bash
npm run dev
```

Navigate to [localhost:8080](http://localhost:8080). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.

By default, the server will only respond to requests from localhost. To allow connections from other computers, edit the `sirv` commands in package.json to include the option `--host 0.0.0.0`.

If you're using [Visual Studio Code](https://code.visualstudio.com/) we recommend installing the official extension [Svelte for VS Code](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode). If you are using other editors you may need to install a plugin in order to get syntax highlighting and intellisense.

## Building and running in production mode

To create an optimised version of the app:

```bash
npm run build
```

You can run the newly built app with `npm run start`. This uses [sirv](https://github.com/lukeed/sirv), which is included in your package.json's `dependencies` so that the app will work when you deploy to platforms like [Heroku](https://heroku.com).


## Single-page app mode

By default, sirv will only respond to requests that match files in `public`. This is to maximise compatibility with static fileservers, allowing you to deploy your app anywhere.

If you're building a single-page app (SPA) with multiple routes, sirv needs to be able to respond to requests for *any* path. You can make it so by editing the `"start"` command in package.json:

```js
"start": "sirv public --single"
```

## Using TypeScript

This template comes with a script to set up a TypeScript development environment, you can run it immediately after cloning the template with:

```bash
node scripts/setupTypeScript.js
```

Or remove the script via:

```bash
rm scripts/setupTypeScript.js
```

If you want to use `baseUrl` or `path` aliases within your `tsconfig`, you need to set up `@rollup/plugin-alias` to tell Rollup to resolve the aliases. For more info, see [this StackOverflow question](https://stackoverflow.com/questions/63427935/setup-tsconfig-path-in-svelte).

## Deploying to the web

### With [Vercel](https://vercel.com)

Install `vercel` if you haven't already:

```bash
npm install -g vercel
```

Then, from within your project folder:

```bash
cd public
vercel deploy --name my-project
```

### With [surge](https://surge.sh/)

Install `surge` if you haven't already:

```bash
npm install -g surge
```

Then, from within your project folder:

```bash
npm run build
surge public my-project.surge.sh
```


# 따라하기 시작
###    (https://www.youtube.com/watch?v=CmaUDwVCTy8)


    1. npx degit sveltejs/template svelte-gh-pages

        C:\job\front-end\svelte>npx degit sveltejs/template svelte-gh-pages
        Need to install the following packages:
        degit
        Ok to proceed? (y)
        > cloned sveltejs/template#HEAD to svelte-gh-pages

        C:\job\front-end\svelte>dir
        C 드라이브의 볼륨에는 이름이 없습니다.
        볼륨 일련 번호: 86F5-86F2

        C:\job\front-end\svelte 디렉터리

        2022-05-14  오전 02:16    <DIR>          .
        2022-05-14  오전 02:16    <DIR>          ..
        2022-05-12  오후 10:09    <DIR>          svelte-app     
        2022-05-14  오전 02:16    <DIR>          svelte-gh-pages
                    0개 파일                   0 바이트      
                    4개 디렉터리  297,403,723,776 바이트 남음

    2. cd svelte-gh-pages
        C:\job\front-end\svelte>cd svelte-gh-pages

    3. dir
        C:\job\front-end\svelte\svelte-gh-pages>dir
        C 드라이브의 볼륨에는 이름이 없습니다.
        볼륨 일련 번호: 86F5-86F2

        C:\job\front-end\svelte\svelte-gh-pages 디렉터리

        2022-05-14  오전 02:16    <DIR>          .
        2022-05-14  오전 02:16    <DIR>          ..
        2022-01-07  오전 04:34                41 .gitignore
        2022-01-07  오전 04:34               550 package.json
        2022-05-14  오전 02:16    <DIR>          public
        2022-01-07  오전 04:34             3,515 README.md
        2022-01-07  오전 04:34             1,841 rollup.config.js
        2022-01-07  오전 04:34    <DIR>          scripts
        2022-05-14  오전 02:16    <DIR>          src
                    4개 파일               5,947 바이트
                    5개 디렉터리  297,403,723,776 바이트 남음

    4. code .
        C:\job\front-end\svelte\svelte-gh-pages>code .


    5. yarn install

        C:\job\front-end\svelte\svelte-gh-pages>yarn install
        yarn install v1.22.18
        info No lockfile found.
        [1/4] Resolving packages...
        [2/4] Fetching packages...
        [3/4] Linking dependencies...
        [4/4] Building fresh packages...

        success Saved lockfile.
        Done in 13.56s.

        C:\job\front-end\svelte\svelte-gh-pages>



    7. yarn dev


        C:\job\front-end\svelte\svelte-gh-pages>yarn dev
        yarn run v1.22.18
        $ rollup -c -w
        rollup v2.73.0
        bundles src/main.js → public/build/bundle.js...
        LiveReload enabled
        created public/build/bundle.js in 217ms     

        [2022-05-14 10:02:31] waiting for changes...

        > svelte-app@1.0.0 start        
        > sirv public --no-clear "--dev"


        Your application is ready~! 🚀

        - Local:      http://localhost:8080     
        - Network:    Add `--host` to expose    

        ────────────────── LOGS ──────────────────

        [10:02:35] 200 ─ 3.90ms ─ /
        [10:02:35] 200 ─ 0.93ms ─ /global.css      
        [10:02:35] 200 ─ 1.53ms ─ /build/bundle.css
        [10:02:35] 200 ─ 2.69ms ─ /build/bundle.js



    8. 크롬 확인
        http://localhost:8080/




    9. 리포지토리 생성
        https://github.com/king-garlic/svelte-gh-pages


    10. 아래 명령 실행
        echo "# svelte-gh-pages" >> README.md
        git init
        git add README.md
        git commit -m "first commit"
        git branch -M main
        git remote add origin https://github.com/king-garlic/svelte-gh-pages.git
        git push -u origin main"# svelte-gh-pages" 



    11. 위 명령 실행 결과


        C:\job\front-end\svelte\svelte-gh-pages>echo "# svelte-gh-pages" >> README.md

        C:\job\front-end\svelte\svelte-gh-pages>git init
        Initialized empty Git repository in C:/job/front-end/svelte/svelte-gh-pages/.git/

        C:\job\front-end\svelte\svelte-gh-pages>git add README.md
        warning: LF will be replaced by CRLF in README.md.
        The file will have its original line endings in your working directory

        C:\job\front-end\svelte\svelte-gh-pages>git commit -m "first commit"
        [master (root-commit) 27a42dd] first commit
        1 file changed, 241 insertions(+)
        create mode 100644 README.md

        C:\job\front-end\svelte\svelte-gh-pages>git branch -M main

        C:\job\front-end\svelte\svelte-gh-pages>git remote add origin https://github.com/king-garlic/svelte-gh-pages.git

        C:\job\front-end\svelte\svelte-gh-pages>git push -u origin main
        Enumerating objects: 3, done.
        Counting objects: 100% (3/3), done.
        Delta compression using up to 8 threads
        Compressing objects: 100% (2/2), done.
        Writing objects: 100% (3/3), 2.85 KiB | 2.85 MiB/s, done.
        Total 3 (delta 0), reused 0 (delta 0), pack-reused 0     
        To https://github.com/king-garlic/svelte-gh-pages.git
        * [new branch]      main -> main
        Branch 'main' set up to track remote branch 'main' from 'origin'.

        C:\job\front-end\svelte\svelte-gh-pages>        



    12. C:\job\front-end\svelte\svelte-gh-pages\.gitignore 주석처리

        # /public/build/

    13. C:\job\front-end\svelte\svelte-gh-pages\public\index.html path 수정 - . 추가


        <link rel="icon" type="image/png" href="./favicon.png" />
        <link rel="stylesheet" href="./global.css" />
        <link rel="stylesheet" href="./build/bundle.css" />

        <script defer src="./build/bundle.js"></script>


    14.
    15.
    16.
    17.
