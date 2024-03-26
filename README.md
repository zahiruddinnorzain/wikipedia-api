## WIKIPEDIA API

```
wikipedia_api('<person of interest>','<language>','<tag id html>');
```

### CDN:
```
<script src="https://code.jquery.com/jquery-3.7.1.min.js" integrity="sha256-/JqT3SQfawRcv/BIHPThkBvs0OEvtFFmqPF/lYI/Cxo=" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/gh/zahiruddinnorzain/wikipedia-api@v1.0.0/wikipedia-api.js"></script>
```

### EXAMPLE:

```
<script src="https://code.jquery.com/jquery-3.7.1.min.js" integrity="sha256-/JqT3SQfawRcv/BIHPThkBvs0OEvtFFmqPF/lYI/Cxo=" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/gh/zahiruddinnorzain/wikipedia-api@v1.0.0/wikipedia-api.js"></script>

<p id="wiki"></p>

<script>
var result = wikipedia_api('mahathir mohamad','ms','wiki');
</script>
```
```
Language:
ms = Bahasa Melayu
en = English
```
by kepaknaga@gmail.com