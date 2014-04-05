---
layout: post
---

**freamework**  
- [https://github.com/mattcg/socks5-https-client](#)
- [https://github.com/zordius/https-scan](#)
- [https://github.com/pretorh/service-client](#)
- [https://github.com/TooTallNate/node-https-proxy-agent](#)
- [https://github.com/substack/https-browserify](#)
- [http://nodejs.org/api/https.html](#)
- [https://github.com/nategood/node-auth](#)

{% highlight PowerShell %}
var options = {
  hostname: 'encrypted.google.com',
  port: 443,
  path: '/',
  method: 'GET',
  key: fs.readFileSync('test/fixtures/keys/agent2-key.pem'),
  cert: fs.readFileSync('test/fixtures/keys/agent2-cert.pem')
};
options.agent = new https.Agent(options);

var req = https.request(options, function(res) {
  ...
}
{% endhighlight %}