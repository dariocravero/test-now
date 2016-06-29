```
test-now $ now
> Enter your email: dario@uxtemple.com
> Please follow the link sent to dario@uxtemple.com to log in.
> Waiting for confirmation.....
> Deploying "/Users/craverod/opensource/panels/test-now"
> Error! Missing `start` (or `now-start`) script in `package.json`. See: https://docs.npmjs.com/cli/start.
test-now $ vi start
test-now $ vi package.json
test-now $ now
> Deploying "/Users/craverod/opensource/panels/test-now"
> Using Node.js 6.2.1 (default)
> Ready! https://test-now-rcchcanmoo.now.sh (copied to clipboard) [1s]
> Upload [====================] 100% 0.0s
> Sync complete (389B) [999ms]
> Initializing…
> Building
> ▲ npm install
> Error { Error: ENOENT: no such file or directory, scandir '/home/nowuser/src/node_modules'
>     at Error (native)
>   errno: -2,
>   code: 'ENOENT',
>   syscall: 'scandir',
>   path: '/home/nowuser/src/node_modules' }
> ▲ npm start
> Deployment complete!
```
