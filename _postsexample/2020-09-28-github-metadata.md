<<<<<<< HEAD
<<<<<<< HEAD:_posts/2020-09-28-github-metadata.md
=======
>>>>>>> 9b8f3de (testing deployment)
---
layout: post
title:  a post with github metadata
date: 2020-09-28 21:01:00
description: a quick run down on accessing github metadata.
<<<<<<< HEAD
categories: sample-posts external-services
=======
>>>>>>> 9b8f3de (testing deployment)
---

A sample blog page that demonstrates the accessing of github meta data.

## What does Github-MetaData do?
* Propagates the site.github namespace with repository metadata
<<<<<<< HEAD
* Setting site variables :
=======
* Setting site variables : 
>>>>>>> 9b8f3de (testing deployment)
  * site.title
  * site.description
  * site.url
  * site.baseurl
* Accessing the metadata - duh.
* Generating edittable links.

## Additional Reading
* If you're recieving incorrect/missing data, you may need to perform a Github API<a href="https://github.com/jekyll/github-metadata/blob/master/docs/authentication.md"> authentication</a>.
<<<<<<< HEAD
* Go through this <a href="https://jekyll.github.io/github-metadata/">README</a> for more details on the topic.
=======
* Go through this <a href="https://jekyll.github.io/github-metadata/" target="blank">README</a> for more details on the topic.
>>>>>>> 9b8f3de (testing deployment)
* <a href= "https://github.com/jekyll/github-metadata/blob/master/docs/site.github.md">This page</a> highlights all the feilds you can access with github-metadata.
<br />

## Example MetaData
* Host Name : {{ site.github.hostname }}
* URL : {{ site.github.url }}
* BaseURL : {{ site.github.baseurl }}
* Archived : {{ site.github.archived}}
<<<<<<< HEAD
* Contributors :
{% for contributor in site.github.contributors %}
  * {{ contributor.login }}
{% endfor %}
=======
---
layout: post
title:  a post with github metadata
date: 2020-09-28 21:01:00
description: a quick run down on accessing github metadata.
---

A sample blog page that demonstrates the accessing of github meta data.

## What does Github-MetaData do?
* Propagates the site.github namespace with repository metadata
* Setting site variables : 
  * site.title
  * site.description
  * site.url
  * site.baseurl
* Accessing the metadata - duh.
* Generating edittable links.

## Additional Reading
* If you're recieving incorrect/missing data, you may need to perform a Github API<a href="https://github.com/jekyll/github-metadata/blob/master/docs/authentication.md"> authentication</a>.
* Go through this <a href="https://jekyll.github.io/github-metadata/" target="blank">README</a> for more details on the topic.
* <a href= "https://github.com/jekyll/github-metadata/blob/master/docs/site.github.md">This page</a> highlights all the feilds you can access with github-metadata.
<br />

## Example MetaData
* Host Name : {{ site.github.hostname }}
* URL : {{ site.github.url }}
* BaseURL : {{ site.github.baseurl }}
* Archived : {{ site.github.archived}}
* Contributors : 
{% for contributor in site.github.contributors %}
  * {{ contributor.login }}
{% endfor %}
>>>>>>> e79e8a9 (WebsiteSetup):_postsexample/2020-09-28-github-metadata.md
=======
* Contributors : 
{% for contributor in site.github.contributors %}
  * {{ contributor.login }}
{% endfor %}
>>>>>>> 9b8f3de (testing deployment)
