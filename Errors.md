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

can not get response from **find** function

```log
START RequestId: b317f5af-cbab-461f-a30f-62abbfe84aa0 Version: $LATEST
2022-07-12T15:25:47.377Z	undefined	INFO	NODE_ENV dev
2022-07-12T15:25:47.377Z	undefined	INFO	process.env.DB_URL mongodb+srv://serhii_admin_user:serhii_pass_admin@cluster0.rh4he.mongodb.net/?retryWrites=true&w=majority
2022-07-12T15:25:47.378Z	undefined	INFO	process.env.DB_NAME study
END RequestId: b317f5af-cbab-461f-a30f-62abbfe84aa0
REPORT RequestId: b317f5af-cbab-461f-a30f-62abbfe84aa0	Duration: 10010.80 ms	Billed Duration: 10000 ms	Memory Size: 1024 MB	Max Memory Used: 94 MB	Init Duration: 604.69 ms
2022-07-12T15:25:57.414Z b317f5af-cbab-461f-a30f-62abbfe84aa0 Task timed out after 10.01 seconds
```
