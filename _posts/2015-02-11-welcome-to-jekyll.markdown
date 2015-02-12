---
layout: post
title:  "Welcome to Jekyll!"
date:   2015-02-11 18:00:15
categories: jekyll update
---
This site is hosted on Github and managed with Jekyll.  If like me, you are getting started with Jekyll, I recommend using the [Quickstart Guide][quickstart] after setting up your github.io repo.  Once you download the sample Jekyll Bootstrap project, there are a few more things that you have to do:

1)  gem install 'github-pages'
                                
2)  Create a file named Gemfile and add these two lines:
 
    source 'https://rubygems.org'
    gem 'github-pages'

3)  Create a github branch named gh-pages.  According to the documentation, Jekyll looks for user content on the gh-pages branch and it looks for project code on the master branch. 

4)  Set your configs in _config.yml. 

5)  The last step is not obvious and seems to be a bug.  When you download the sample project, the code is placed in a subdirectory of <username>.github.io.  When you push your code to Github it gives you an error stating that there is a problem with the css/main.scss file.  I Googled the issue and found that the solution is to move all of the files up to the <username>.github.io directory and remove the subdirectory. 

I hope this helps!

Jekyll also offers support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[quickstart]:  http://jekyllrb.com/docs/quickstart
[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
