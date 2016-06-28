---
layout: post
title:  "Twitter API course by Codecademy"
date:   2016-06-28
categories: jekyll update
---
Codecademy has a nice set of API courses tucked away on their own [webpage][API-courses], separate from the [main course offerings][main-courses]. I had been eyeing the [**Twitter API** course][Twitter-API-course] for a while, but it is Ruby-based, so first I wanted to learn how to program in Ruby. I finished Codecademy's [Ruby course][Ruby-course] last month, so as a reward, I could take the Twitter API course armed with my newly-acquired Ruby syntax knowledge.

The first unit of the course introduced HTTP, REST (**Re**presentational **S**tate **T**ransfer), HTTP methods, responses, and status codes, XML, and JSON.

The second unit covered four of the Twitter REST APIs (and how to parse their responses): [GET account/verify_credentials][verify], [GET statuses/show/:id][show], [GET statuses/user_timeline][timeline], and [POST statuses/update][send-tweet]

Notes to self for continuing the learning:

- take a look at the docs for the [oauth][oauth] and [json][json] gems (Ruby packages)
- Twitter offers over 90 [REST APIs][REST-APIs], including their [Search API][Search-API]. Lots of possibilities here for fun projects.
- Twitter also has [Streaming APIs][Streaming-APIs] and a set of mobile development tools called [Fabric][Fabric].



[API-courses]: https://www.codecademy.com/apis
[main-courses]: https://www.codecademy.com/learn
[Twitter-API-course]: https://www.codecademy.com/en/tracks/twitter 
[Ruby-course]: https://www.codecademy.com/learn/ruby
[verify]: https://dev.twitter.com/rest/reference/get/account/verify_credentials
[show]: https://dev.twitter.com/rest/reference/get/statuses/show/%3Aid
[timeline]: https://dev.twitter.com/rest/reference/get/statuses/user_timeline 
[send-tweet]: https://dev.twitter.com/rest/reference/post/statuses/update
[oauth]: http://www.rubydoc.info/gems/oauth/0.5.1
[json]: http://flori.github.io/json/doc/index.html
[REST-APIs]: https://dev.twitter.com/rest/public
[Search-API]: https://dev.twitter.com/rest/public/search
[Streaming-APIs]: https://dev.twitter.com/streaming/public
[Fabric]: https://docs.fabric.io/