# Open Bank Project related nodes

Currently, there is one node: obp:-adapter-start
It can select one connector method, to generate an endpoint for MethodRouting.

## Publish a new version to npm and Node-red
1. you should have npm account
2. execute the follow commands:
   ```
   > npm login
   > npm publish
   ```
3. add `node-red-contrib-obp` to node-red flows lib:
  - go to this page: [https://flows.nodered.org/](https://flows.nodered.org/)
  - click the '+' button at the top of page, click `Node` area, navigate to a new page
  - fill in `node-red-contrib-obp`, click `add node` button
  
4. after about 10 minutes, the node can be queried in node-red Palette

## Usage
 Please refer to this video: [https://vimeo.com/452236076](https://vimeo.com/452236076)