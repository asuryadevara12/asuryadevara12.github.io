---
layout: default
title:  "My first blog post!"
date:   2020-12-9
categories: jekyll update
---
**_Working with Jekyll, git, and atom_**


*12/2/20 meeting:*

1. Worked with jekyll
2. Created my own repository

I know that isn't descriptive at all, but as I am writing this a week after the meeting, it's quite vague.

*12/9/20 meeting*

1. Troubleshooting problems in atom
  * I had to change the url of my blog
  * I could not push, so I had to clone the repository again and that fixed the issue.
2. I worked on editing this first blog post, and using "bundler exec jekyll serve" I could preview my edits at http://localhost:4000/
3. I read through the "Master Markdown" guide again to understand how to properly created unordered and order lists. https://guides.github.com/features/mastering-markdown/

*Guidelines/tips:*

`bundle exec jekyll serve`,
which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number,
`MONTH` and `DAY` are both two-digit numbers,
and `MARKUP` is the file extension representing the format used in the file.
After that, include the necessary front matter.
Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll.
File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh].
If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
