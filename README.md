# Test Bug

NX Report 
```

 NX   Report complete - copy this into the issue template

Node           : 22.13.0
OS             : darwin-arm64
Native Target  : aarch64-macos
pnpm           : 9.15.3

nx                     : 20.4.6
@nx/js                 : 20.4.6
@nx/jest               : 20.4.6
@nx/eslint             : 20.4.6
@nx/workspace          : 20.4.6
@nx/devkit             : 20.4.6
@nx/eslint-plugin      : 20.4.6
@nx/module-federation  : 20.4.6
@nx/react              : 20.4.6
@nx/rspack             : 20.4.6
@nx/web                : 20.4.6
typescript             : 5.7.3
---------------------------------------
Registered Plugins:
@nx/js/typescript
```

Pull down this PR

1. execute: pnpm i
2. execute pnpm nx run shell_v1:serve
3. click on the link to open the web browser
4. click on the header component
5. you should see an error