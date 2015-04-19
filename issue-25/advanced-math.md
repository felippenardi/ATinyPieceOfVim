{% if subscriber.first_name %}
Hello {{ subscriber.first_name }},
{% else %}
Hello,
{% endif %}

Hope you are doing great today. I've got a new Vim
tip for you. I can't promise it will be extremely
useful, but it will be guaranteed to impress
your friends. :)

A few emails ago I showed a Vim built-in command
to increase and decrease numbers. Today I want to
show you something more advanced. We are going use
Vim to calculate math expressions.

Next time you think of reaching your phone's
calculator, keep your hands on the keyboard and do
the following:

```
!!bc
```

The double exclamation marks will send anything
you type next to the bash, piping whatever is in
the current line to it.

In this case, we are piping the current line to
bc—a programming language that calculates
mathematic expressions and is already built-in
Linux and Mac.

This is the same thing as running
`echo "1+1" | bc` in your terminal.

Hope your learned something new.

{% if subscriber.first_name %}
Stay curious {{ subscriber.first_name }},
{% else %}
Stay curious,
{% endif %}
Felippe Nardi
