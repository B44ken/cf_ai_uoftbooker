# yet another course scheduler

this is a fork of [yacs](https://github.com/b44ken/yacs) - i made it for cloudflare swe intern but alas i can't change the link on my app

## features
- [x] static site (cloudflare pages)
- [ ] courses database (cloudflare d1)
- [ ] ai parse course from image (cloudflare workers)
- [ ] ai chat (cloudflare workers ai)

## build
`npm run dev`, then localhost:3000

or `npm run build` then push to git -> cloudflare ci/cd takes over

## ai usage
used pretty heavily. `refactor this component for me`, `write this component for me`, other rudimentary code monkey tasks
