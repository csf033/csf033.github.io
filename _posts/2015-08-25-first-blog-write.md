---
layout: post
title:  "第一篇博客"
date:   2015-08-25 22:10:00
categories: 生活
excerpt: 首次搭建博客，随便写写
---

* content
{:toc}

## 第一篇博客

一直都想写博客，但是中途老是放弃，现在自己搭建博客，一次鞭策自己的学习，学习才能进步

---
{% highlight ruby %}  
def foo  
  puts 'foo'  
end  
{% endhighlight %}

{% highlight java %}  
static class MyViewHolder extends AnimateViewHolder {

        public MyViewHolder(View itemView) {
            super(itemView);
        }

        @Override
        public void animateRemoveImpl(ViewPropertyAnimatorListener listener) {
            ViewCompat.animate(itemView)
                    .translationY(-itemView.getHeight() * 0.3f)
                    .alpha(0)
                    .setDuration(300)
                    .setListener(listener)
                    .start();
        }

        @Override
        public void preAnimateAddImpl() {
            ViewCompat.setTranslationY(itemView, -itemView.getHeight() * 0.3f);
            ViewCompat.setAlpha(itemView, 0);
        }

        @Override
        public void animateAddImpl(ViewPropertyAnimatorListener listener) {
            ViewCompat.animate(itemView)
                    .translationY(0)
                    .alpha(1)
                    .setDuration(300)
                    .setListener(listener)
                    .start();
        }
    } 
 {% endhighlight %}
