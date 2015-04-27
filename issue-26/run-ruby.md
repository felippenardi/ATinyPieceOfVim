{% if subscriber.first_name %}
Hello {{ subscriber.first_name }},
{% else %}
Hello,
{% endif %}

Last week you saw how to calculate a math
equantion inside Vim by using unix bc program. Vim
can be very powerful when you combine it with
external applications.

Another example is using it to run Ruby commands.
You just type the snippet and, if it is a
single-line, you just press `!!ruby`. That is it.

In case it is a multiple lines command, then you
select it and , then type `!ruby`. Voulá.

{% if subscriber.first_name %}
Stay curious {{ subscriber.first_name }},
{% else %}
Stay curious,
{% endif %}
Felippe Nardi
