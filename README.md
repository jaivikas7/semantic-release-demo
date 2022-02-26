# semantic-release-demo
This is just a repo to try and test semantic release

{
  "name": "platform-shared",
  "private": true,
  "devDependencies": {
    "semantic-release-docker": "2.2.0",
    "@semantic-release/commit-analyzer": "8.0.1",
    "@semantic-release/exec": "5.0.0",
    "@semantic-release/npm": "7.1.1",
    "@qiwi/multi-semantic-release": "3.14.0",
    "serverless": "1.67.0",
    "snyk": "1.541.0",
    "yarn": "1.22.4"
  },
  "scripts": {
    "clean": "rm -rf ./node_modules",
    "release": "multi-semantic-release --execasync"
  },
  "workspaces": [
    "env/*",
    "deploy",
    "operations-pod",
    "opensearch-admin"
  ]
}

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