---
layout: post
title:  "zsh – jak načíst .zshrc bez rebootu"
date:   2020-02-10 21:12:03 +0200
categories:
permalink: /about/2020-02-10-zsh-jak-nacist-zshrc-bez-rebootu/ 
---
Když uděláte nějaké změny v  .zshrc, například si nakonfigurujete aliasy atd. tak se změny neukáží hned. Je potřeba zmovu načíst .zshrc. To se dá udělat několika způsoby:
* reboot
* odhlásit a přihlásit se
* vynutit znovunačtení .zshrc


Třetí způsob je nejlepší, protože kdo by se chtěl odhlašovat, nebo rebootovat. Pusťte si terminál a použijte následující příkazy:

{% highlight bash %}
jndm@Macbook ~ % source ~/.zshrc
{% endhighlight %}

nebo kratší:

{% highlight bash %}
jndm@Macbook ~ % . ~/.zshrc
{% endhighlight %}