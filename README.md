# GitHub-fetch
Macos上加速GitHub访问

目前Edge、Chrome都适用

启动命令：
open /Applications/Microsoft\ Edge.app --args --host-rules="MAP github.com octocaptcha.com, MAP github.githubassets.com yelp.com, MAP *.githubusercontent.com yelp.com" --host-resolver-rules="MAP octocaptcha.com 20.27.177.113, MAP yelp.com 199.232.240.116"

open /Applications/Google\ Chrome.app --args --host-rules="MAP github.com octocaptcha.com, MAP github.githubassets.com yelp.com, MAP *.githubusercontent.com yelp.com" --host-resolver-rules="MAP octocaptcha.com 20.27.177.113, MAP yelp.com 199.232.240.116"

灵感来自
https://github.com/feng2208/github-hosts.git
