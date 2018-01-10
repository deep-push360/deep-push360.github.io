Under construction
Type code in md: 
```{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}```

Convert ipynb to md : `ipython nbconvert jekyll_test.ipynb --to markdown`

