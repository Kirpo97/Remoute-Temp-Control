# Remoute-Temp-Control
**Remoute-Temp-Control** - минипроект для мониторинга температуры с диспетчирезацией.

+ Связь между датчиками и платой управления релизованна по протоколу ModbusRTU

<a>Стек TCP/IP</a>
-

<table>
	<style>
		table, th, td {
			border: 1px solid black;
			border-collapse: collapse;
		}
		.tr1{
			background-color: #d6fef0;
		}
	</style>
	<tbody>
	  <thead>
	    <tr CLASS="tr1">
			<th scope="col">No</th>
			<th scope="col">уровень</th>
			<th scope="col">протокол</th>
	    </tr>
	  </thead>
		<tr>
	      <th scope="row">4</th>
	      <td>уровень приложений</td>
	      <td>Modbus</td>
	    </tr>
		<tr>
	      <th scope="row">3</th>
	      <td>транспортный уровень</td>
	      <td>-</td>
	    </tr>
		<tr>
	      <th scope="row">2</th>
	      <td>сетевой уровень</td>
	      <td>-</td>
	    </tr>
		<tr>
	      <th scope="row">1</th>
	      <td>канальный уровень</td>
	      <td>RS485, 802.11 b/g/n</td>
	    </tr>
	</tbody>
</table>

<a>Схема соединений</a>
--
<canvas id='example'>Обновите браузер</canvas>
		<script>
			var example = document.getElementById("example"),
			    ctx     = example.getContext('2d');
			example.height = 480;
			example.width  = 640;
			ctx.strokeStyle = '#B70A02'; // меняем цвет рамки
			ctx.strokeRect(15, 15, 266, 266);
			ctx.strokeRect(18, 18, 260, 260);
			ctx.fillStyle = '#AF5200'; // меняем цвет клеток
			ctx.fillRect(20, 20, 256, 256);
			for (i = 0; i < 8; i += 2)
				for (j = 0; j < 8; j += 2) {
					ctx.clearRect(20 + i * 32, 20 + j * 32, 32, 32);
					ctx.clearRect(20 + (i + 1) * 32, 20 + (j + 1) * 32, 32, 32);
				}
		</script>
        

	-------			-----------------
	|SHT20|	-----> 	|
	-------			|
					|	
	-------			|
	|SHT20|	-----> 	|
	-------			|


<table>
	<style>
		table, th, td {
		  border: 1px solid black;
		  border-collapse: collapse;
		}
	</style>
  <caption>
    Front-end web developer course 2021
  </caption>
  <thead>
    <tr>
      <th scope="col">Person</th>
      <th scope="col">Most interest in</th>
      <th scope="col">Age</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">Chris</th>
      <td>HTML tables</td>
      <td>22</td>
    </tr>
    <tr>
      <th scope="row">Dennis</th>
      <td>Web accessibility</td>
      <td>45</td>
    </tr>
    <tr>
      <th scope="row">Sarah</th>
      <td>JavaScript frameworks</td>
      <td>29</td>
    </tr>
    <tr>
      <th scope="row">Karen</th>
      <td>Web performance</td>
      <td>36</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <th scope="row" colspan="2">Average age</th>
      <td>33</td>
    </tr>
  </tfoot>
</table>
