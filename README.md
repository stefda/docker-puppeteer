# Puppeteer Docker Image

A minimum image required to run [Puppeteer](https://www.npmjs.com/package/puppeteer) on Docker. It is intended to be
used as the base image for parser application and is derived from `node:10-jessie`.

## Running Puppeteer on Linux

When run on Linux, puppeteer must be run with the sandbox off. See puppeteer's
[troubleshooting](https://github.com/GoogleChrome/puppeteer/blob/master/docs/troubleshooting.md#setting-up-chrome-linux-sandbox)
tips for details.
