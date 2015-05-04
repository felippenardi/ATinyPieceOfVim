{% if subscriber.first_name %}
Hello {{ subscriber.first_name }},
{% else %}
Hello,
{% endif %}

Hope you are doing great today. I've got a new Vim
tip for you. I wont promise it will be extremely
useful, but it will definitely impress your
friends. :)

Vim has a built-in command to increase and
decrease numbers. But today I want to show you
something more advanced. We are going use Vim to
calculate math expressions.

Next time you think of reaching your phone
calculator, keep your hands on the keyboard and do
the following:

```
!!bc
```

You don't need to hit the colon key. Typing
exclamation mark twice will automatically enter
command mode. It will send anything you type next
to the bash, piping whatever is in the current
line to it.

In this case, we are piping the current line to
bc—a programming language that calculates
mathematic expressions and is already built-in
Linux and Mac.

It is the same thing as running
`echo "1+1" | bc` in your terminal.

Hope your learned something new.

{% if subscriber.first_name %}
Stay curious {{ subscriber.first_name }},
{% else %}
Stay curious,
{% endif %}
Felippe Nardi
