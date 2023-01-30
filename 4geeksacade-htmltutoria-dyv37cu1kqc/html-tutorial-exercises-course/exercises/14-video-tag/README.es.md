# `14`  Video tag

El tag de `<video>` se utiliza para incluir un contenido de video dentro de un documento.

> Nota: Aquí puedes leer sobre los tags de video: [Html Video Tags](https://www.w3schools.com/tags/tag_video.asp)

## 📝 Instrucciones:

1. Usa el tag `<video>` para incluir este video en el sitio web: [https://assets.breatheco.de/apis/video/why-pair-programming](https://assets.breatheco.de/apis/video/why-pair-programming).

2. El video debe cubrir todo el sitio web, para ello vamos a aplicarle un `width="100%"` y un `height="100%"`.

3. El video debe reproducirse automáticamente, haz uso del atributo: `autoplay`.

4. El video debe estar silenciado al principio, utiliza el atributo: `muted`.

> Nota: El video NO DEBE tener controles: play, pausa, etc.

## 💡 Pistas:

+ Algo así deberia de ser tu código.

```html
<video width="X" height="X" muted autoplay>
	<source src="aquí va la URL del video"/>
</video>
```

+ Lee más sobre esto aquí: [https://stackoverflow.com/questions/34764876/html-5-video-autoplay-not-automatically-starting-in-chrome](https://stackoverflow.com/questions/34764876/html-5-video-autoplay-not-automatically-starting-in-chrome).