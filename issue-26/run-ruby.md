{% if subscriber.first_name %}
Hello {{ subscriber.first_name }},
{% else %}
Hello,
{% endif %}

Have someone ever asked you why not using another
text editor with built-in Vim keybinds instead of
Vim itself? There are several answers for that.
Today's tip is one of the  good answers.

Last week you saw how to calculate a math
equantion inside Vim by using unix bc program. Vim
can be very powerful when you combine it with
external applications.

Another example is using it to run Ruby commands.
You just type the snippet and, if it is a
single-line, you just press `!!ruby`. That is it.

In case it is a multiple line command, you select
it, then type `!ruby`. Voulá.

{% if subscriber.first_name %}
Stay curious {{ subscriber.first_name }},
{% else %}
Stay curious,
{% endif %}
Felippe Nardi