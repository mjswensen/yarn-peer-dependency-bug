1. `cd main`
2. `yarn upgrade themer`

This will upgrade `themer` from `2.0.0` to `2.1.0`. Note that `a` has a `peerDependency` on `themer@^2`. Even though the upgraded version of `themer` still satisfies that peer dependency, yarn 0.20.3 throws an unmet peer dependency warning.
