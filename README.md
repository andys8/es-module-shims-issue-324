# es-module-shims issue #324 reproducer

## Instructions

- Serve this repository with a http server: `npx http-server`
- Open the project with Chrome/Chromium 87 or Firefox 103
- Error `Uncaught TypeError: Cannot read property 'head' of null at HTMLIFrameElement.n.onload` should show up (ignore all other errors)
