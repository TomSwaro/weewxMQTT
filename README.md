<h1>
  <a href='http://www.weewx.com'>WeeWX</a>
</h1>
<p><i>Open source software for your weather station</i></p>

<h2>Description</h2>
<p>An extension of weewx to add a driver which gets data via an MQTT subscription. Also will shortly add the software from the other side of the MQTT broker
</p>

<p>Works well with the <a href='https://mosquitto.org/'>Mosquitto</a> MQTT message broker.</p>
<h2>Features</h2>
<ul>
  <li>If a message provides 0 as the timestamp or does not provide a timestamp, the driver uses the time on the weewx host.</li>
  <li>Consolidates asynchronous readings from more than one device into one stream of periodic weewx records.</li>
</ul>



<p>
   Community support for weewx can be found at:
<p style='padding-left: 50px;'>
  <a href="https://groups.google.com/group/weewx-user">https://groups.google.com/group/weewx-user</a>
</p>

<h2>Licensing</h2>

<p>weewxMQTT is licensed under the GNU Public License v3.</p>
