# DO NOT REMOVE. CLOUDLINUX PASSENGER CONFIGURATION BEGIN
PassengerAppRoot "/home/serwer240722/staff"
PassengerBaseURI "/staff"
PassengerNodejs "/home/serwer240722/nodevenv/staff/20/bin/node"
PassengerAppType node
PassengerStartupFile app.js
# DO NOT REMOVE. CLOUDLINUX PASSENGER CONFIGURATION END
Header always set Content-Security-Policy "frame-ancestors 'self' https://impan.smarthost.pl"



const oauth = oauth1a({
  consumer: {
    key: '82xwD377tKqEjGm8fCDj',
    secret: 'DvtbWdfBdryLkCLCcQrPdLC9zbDPGgmfpz5u6Wch',
  },
  signature_method: 'HMAC-SHA1',
  hash_function(base_string, key) {
    return crypto
      .createHmac('sha1', key)
      .update(base_string)
      .digest('base64');
  },
});
b89153329@gmail.com 



var http = require('http');
var server = http.createServer(function(req, res) {
    res.writeHead(200, {'Content-Type': 'text/plain'});
    var message = 'It works!\n',
        version = 'NodeJS ' + process.versions.node + '\n',
        response = [message, version].join('\n');
    res.end(response);
});
server.listen();

