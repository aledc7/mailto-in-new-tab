# Mail en un nuevo Tab

[![aledc.com](https://github.com/aledc7/Scrum-Certification/blob/master/recursos/aledc.com.svg)](https://aledc.com)
[![License](https://github.com/aledc7/Scrum-Certification/blob/master/recursos/mit-license.svg)](https://aledc.com)
[![GitHub release](https://github.com/aledc7/Scrum-Certification/blob/master/recursos/release.svg)](https://aledc.com)
[![Dependencies](https://github.com/aledc7/Scrum-Certification/blob/master/recursos/dependencias-none.svg)](https://aledc.com)


El siguiente código sirve para insertar en un sitio web en donde se requiera que al dar click en una dirección de mail nos abra una nueva pestaña con la cuenta de correo electrónico predeterminada


```js
<span style="font-size: 1.2em;">
<a onClick="javascript:window.open('mailto:info@aledc.com?
subject=Mail generado desde aledc.com&body=Escriba acá su consulta',
'mail');event.preventDefault()"  href="mailto:info@aledc.com">
<strong><img class="alignnone size-full wp-image-565" 
src="https://aledc.com/wp-content/uploads/2018/11/info@aledc.png" 
alt="" width="20" height="20" /> info@aledc.com</strong></a></span>
```


el codigo esta probado y en funcionamiento en mi sitio web

http://aledc.com

