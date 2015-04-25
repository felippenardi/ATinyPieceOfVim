Quick question: what was the first three commands
you learned in Vim?

I'd be surprise if one of them wasn't the save
command ":w".

And it is probably the command that we most use.
It sounds counterintuitive in the beginning.
Altough we get used to it, it still
counterintuitive. Three keystrokes for one of the
most used commands sounds like a good opportunity
for optmization.

I learned this tip with a friend that I turned out
to love: binding Return key to :w

This is the snippet you need to add on your vimrc
to bind Return to ":w"

```
snippet
```

Now if you want to increment that, you could bind
a quick double hit on Return to "wa", to save all
open buffers. If you want to try that, you'll nee
da different snippet:

```
# Alternative snippet
```
