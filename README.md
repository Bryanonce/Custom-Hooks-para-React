<h2>Use Fetch</h2>
<p>La forma de utilizar este hook es la siguiente:</p>
<p>El hook recibe unja url y entrega un arreglo con 2 variables</p><br><br>
<h3>const url = //LINK DE LA API QUE SE DESEA CONSUMIR//</h3>
<h3>const [data, setUrl] = useFetch(url)</h3><br><br>
<p>La variable "data" es la respuesta entregada por la API, mientras que la variable "setUrl" es una función capáz de actualizar la variable "data", ejemplo:</p><br><br>
<h3>setUrl(//LINK DE LA API QUE SE DESEA CONSUMIR//)</h3>

