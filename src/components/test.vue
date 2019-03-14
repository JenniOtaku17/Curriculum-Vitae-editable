
<template>

	
	<div id="contenedor">
		<h2>CURRICULUM EDITABLE</h2>
		<div id="cajon1">
		<h3 align="center">Formulario Editable</h3>
		<label>Nombre:</label>
		<input type="text" v-model="nombre" placeholder="nombre"><br><br>
		<label>Apellido:</label>
		<input type="text" v-model="apellido" placeholder="apellido"><br><br>
		<label>Fecha de Nacimiento:</label>
		<input type="text" v-model="fechanac" placeholder="fecha de nacimiento"><br><br>
		<label>Estado Civil:</label>
		<input type="text" v-model="estado" placeholder="estado civil"><br><br>
		<label>Nacionalidad</label>
		<input type="text" v-model="nacionalidad" placeholder="nacionalidad"><br><br>
		<label>Cedula:</label>
		<input type="text" v-model="cedula" placeholder="cedula"><br><br>
		<label>Nivel Academico:</label>
		<input type="text" v-model="nivel" placeholder="nivel academico"><br><br>
		<label>Primer Contacto:</label>
		<input type="text" v-model="contacto1" placeholder="primer contacto"><br><br>
		<label>Segundo Contacto:</label>
		<input type="text" v-model="contacto2" placeholder="segundo contacto"><br><br>
		<label>Tercer Contacto:</label>
		<input type="text" v-model="contacto3" placeholder="tercer contacto"><br><br>

	</div>
	<div id="cajon2">
		<h3 align="center">CURRICULUM VITAE</h3><br>
		<p><b>NOMBRE:</b> {{ nombre }}</p>
		<p><b>APELLIDO:</b> {{ apellido }}</p>
		<p><b>FECHA DE NACIMIENTO:</b> {{ fechanac }}</p>
		<p><b>ESTADO:</b> {{ estado }}</p>
		<p><b>NACIONALIDAD:</b> {{ nacionalidad }}</p>
		<p><b>CEDULA:</b> {{ cedula }}</p>
		<p><b>NIVEL ACADEMICO:</b> {{ nivel }}</p>
		<p><b>No.1 CONTACTO:</b> {{ contacto1 }}</p>
		<p><b>No.2 CONTACTO:</b> {{ contacto2 }}</p>
		<p><b>No.3 CONTACTO:</b> {{ contacto3 }}</p>
	</div>
	</div>
</template>

<script>
	export default{
		data() {
			return{
				nombre: 'Jennifer',
				apellido:'De Los Santos Lopez',
				fechanac:'17-04-1999',
				estado:'Soltera',
				nacionalidad:'Dominicana',
				cedula:'402-0074035-8',
				nivel:'Tecnologa',
				contacto1:'Loudes L. 809-645-3674',
				contacto2:'Juan B. 829-746-7364',
				contacto3:'Luis D. 849-836-2134'


			}
		}
}	
</script>

<style media="screen">
	#cajon1{
		float:left;
		margin:20px;
		margin-left:100px;
		text-align:left;
		padding:20px;
		background-color: white;
		border: solid #000;
	}
	#cajon2{
		float:right;
		margin:20px;
		margin-right:100px;
		text-align:left;
		padding:20px;
		border: solid #000;
		background-color: white;
	}
	body{
		background-image: url("http://www.exposolucionesempresariales.com/wp-content/uploads/2018/02/expo-soluciones-empresariales-fondo-azul-claro.jpg");
	}
	h2{
		background-color: white;
	}

</style>