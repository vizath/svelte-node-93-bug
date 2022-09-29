Using `yup` in an endpoint breaks starting in `@sveltejs/adapter-node` `@1.0.0-next.93`

Solutions to fix it:
- downgrade to `1.0.0-next.92`
- move `yup` from the devDependency to the dependencies array in package.json
