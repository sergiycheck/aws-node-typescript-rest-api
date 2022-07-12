Esmodules is not supported by serverless

```log
GET /dev/books (λ: find)
✖ require() of ES Module /home/dev/projects/my_custom_own_projects/js_related/aws-node-rest-api-ts/.build/app/handler.js from /home/dev/projects/my_custom_own_projects/js_related/aws-node-rest-api-ts/node_modules/serverless-offline/dist/lambda/handler-runner/in-process-runner/InProcessRunner.js not supported.
  Instead change the require of handler.js in /home/dev/projects/my_custom_own_projects/js_related/aws-node-rest-api-ts/node_modules/serverless-offline/dist/lambda/handler-runner/in-process-runner/InProcessRunner.js to a dynamic import() which is available in all CommonJS modules.
✖ Error [ERR_REQUIRE_ESM]: require() of ES Module /home/dev/projects/my_custom_own_projects/js_related/aws-node-rest-api-ts/.build/app/handler.js from /home/dev/projects/my_custom_own_projects/js_related/aws-node-rest-api-ts/node_modules/serverless-offline/dist/lambda/handler-runner/in-process-runner/InProcessRunner.js not supported.
  Instead change the require of handler.js in /home/dev/projects/my_custom_own_projects/js_related/aws-node-rest-api-ts/node_modules/serverless-offline/dist/lambda/handler-runner/in-process-runner/InProcessRunner.js to a dynamic import() which is available in all CommonJS modules.
      at /home/dev/projects/my_custom_own_projects/js_related/aws-node-rest-api-ts/node_modules/serverless-offline/dist/lambda/handler-runner/in-process-runner/InProcessRunner.js:166:133
      at async InProcessRunner.run (/home/dev/projects/my_custom_own_projects/js_related/aws-node-rest-api-ts/node_modules/serverless-offline/dist/lambda/handler-runner/in-process-runner/InProcessRunner.js:166:9)

```
