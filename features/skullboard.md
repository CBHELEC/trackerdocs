# Skullboard

The skullboard module allows your server to highlight and remember those funny, out of context messages and moments which are the best.

Skullboard is essentially a reskinned starboard, if you know what that is. If you don't, it's basically skullboard but the skull is a star and its meant to basically forward the good moments to a channel. Skullboard is just for when its stupid and out of context and you want to frame it.

Skullboard is activated when any message in a channel Tracker has access to gets 3 reactions with a '💀' emoji. It then, if configured, sends it to the skullboard channel.

In summary, here's how skullboard is triggered:

{% stepper %}
{% step %}
### Send a message
{% endstep %}

{% step %}
### 3x 💀 reactions on thus message
{% endstep %}

{% step %}
### Tracker forwards to the skullboard channel
{% endstep %}
{% endstepper %}
