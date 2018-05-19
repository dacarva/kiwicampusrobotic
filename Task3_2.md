---


---

<h1 id="real-time-factor">Real Time Factor</h1>
<p>El <strong>Real Time Factor (RTF)</strong> es una medida de cómo se relaciona el tiempo en la simulación con respecto al tiempo real.<br>
Esta medida se obtiene mediante la multiplicación del <strong>step_time</strong> y el <strong>update_rate</strong>; siendo el <strong>step_time</strong> la cantidad de tiempo que pasa entre cada iteración de la simulación <strong>update_rate</strong> la tasa a la cual se actualiza la simulación.<br>
De esta forma, si se tiene un step_time de 1ms y un update_rate de 1000; el <strong>RTF</strong> equivaldría a 1 segundo. Es decir, que el tiempo transcurrido en la simulación es idéntico al transcurrido en el mundo real.</p>
<p>En ciertos casos se requieren RTF mayores a 1 para simular un fenómeno a una mayor velocidad o menores que 1 para observar un fenómeno “en cámara lenta”</p>
<p>En Gazebo se busca que el tiempo de simulación sea cercano a 1 para mejorar la respuesta entre los medios de control (teclado, joystick) y el robot.</p>

