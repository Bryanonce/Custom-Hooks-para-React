<h2>Use Fetch</h2>
<p>La forma de utilizar este hook es la siguiente:</p>
<p>El hook recibe unja url y entrega un arreglo con 2 variables</p><br><br>
<h2>const url = //LINK DE LA API QUE SE DESEA CONSUMIR//</h2>
<h2>const [data, setUrl] = useFetch(url)</h2><br><br>
<p>La variable "data" es la respuesta entregada por la API, mientras que la variable "setUrl" es una función capáz de actualizar la variable "data", ejemplo:</p><br><br>
<h2>setUrl(//LINK DE LA API QUE SE DESEA CONSUMIR//)</h2>

