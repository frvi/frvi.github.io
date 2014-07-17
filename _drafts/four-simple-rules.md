---
layout: post
title:  Four Rules of Simple Design
---

# {{ page.title }}

*15 May 2014 - Stockholm, Sweden*

## Understanding the Four Rules of Simple Design

<https://leanpub.com/4rulesofsimpledesign>


{% highlight ruby linenos %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}
