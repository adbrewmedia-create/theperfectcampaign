# 8-0: The Perfect Campaign (static site)

Single-file static site. No build step, no dependencies.

## Deploy with the Vercel CLI
    npm i -g vercel
    cd this-folder
    vercel          # preview deployment
    vercel --prod   # production

When asked: framework = Other, build command = none, output directory = ./ (root).

## Deploy from Git
Push this folder to a repo, then Vercel > Add New > Project > Import.
Framework preset: Other. Leave build command and output directory empty.

## What works on Vercel
Stable draft game, Festival Challenge demo, About section, share buttons and result links, dummy ad slots.

## What does not work yet
The leaderboard and sign-up. They depend on the claude.ai artifact runtime and stay hidden here.
Needs a real backend (API routes plus a database) before launch. See the build spec.
