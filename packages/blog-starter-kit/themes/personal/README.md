# A statically generated blog example using Next.js, Markdown, and TypeScript with Hashnode 💫

This is the existing [blog-starter](https://github.com/vercel/next.js/tree/canary/examples/blog-starter) plus TypeScript, wired with [Hashnode](https://hashnode.com).

We've used [Hashnode APIs](https://apidocs.hashnode.com) and integrated them with this blog starter kit.

## Want to have your own?

Fork it and change the environment variable `NEXT_PUBLIC_HASHNODE_PUBLICATION_HOST` to your host (engineering.hashnode.dev is the host in the example) and deploy it to Vercel. That's it! You now have your own frontend. You can still use Hashnode for writing your Articles.

Demo of the `personal` theme: [https://sandeep.dev/blog](https://sandeep.dev/blog).

## Running Locally

- cd into either packages/blog-starter-kit/themes/enterprise, or packages/blog-starter-kit/themes/hashnode or packages/blog-starter-kit/themes/personal
- Copy .env.example to .env.local
- pnpm install
- pnpm dev

Visit http://localhost:3000!
