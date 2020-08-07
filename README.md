service-worker-cache-from-zip
=============================

This is a modified version of the "cache-from-zip" example at https://github.com/mozilla/serviceworker-cookbook with the
following changes:

- The "index.html" page has been simplified
- The "worker.js" has been rewritten to use async functions
- All libraries have been rolled into "worker.js"

This was initially meant as an experiment on whether an ESP32 could
use a service worker to serve up a zip file, but I found out it would
require HTTPS to work. So this project has been shelved for now.