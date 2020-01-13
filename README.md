# `@magnal/prettier-config`

My personal shared prettier config.

## How to use in a project

- install: `npm i @magnal/prettier-config prettier pretty-quick husky --save-dev`
- create `.prettierrc` in project root with content `"@magnal/prettier-config"`
- add to `package.json`:

```
  "husky": {
    "hooks": {
      "pre-commit": "pretty-quick --staged"
    }
  },
```

- done
