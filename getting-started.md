Download & install node & npm: http://nodejs.org/download/
Verify installation: 
  echo "var http = require('http');
  http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Hello Node.js\n');
  }).listen(8124, "127.0.0.1");
  console.log('Server running at http://127.0.0.1:8124/');" > hello_node.js
  node hello_node.js

Grab latest source for webtorrent: git clone https://github.com/feross/webtorrent.git
