# Distru `eslint`


### Install package:

`npm i -D eslint-config-distru`

---


### Install dependencies:

`npm i -D eslint-config-distru eslint eslint-plugin-react eslint-plugin-babel babel-eslint`

**Note**: When using `syntastic` with `vim`, run the following command as well:

`npm i -g eslint-config-distru eslint eslint-plugin-react eslint-plugin-babel babel-eslint`


---

### Gotcha:

ESLint will sometimes have trouble finding `babel-eslint` or other modules when using `extends` in
your `eslintrc`. This can cause in-editor linting to not work properly. In order to avoid
this, it's best to also install any ESLint dependencies globally as well,

`npm i -g eslint-config-distru eslint eslint-plugin-react eslint-plugin-babel babel-eslint`


---

### `.eslintrc` Configuration:

Create a `.eslintrc` file in the root of the project directory:

```
{
  "extends": "eslint-config-distru"
} 
```
