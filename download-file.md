//nella HEAD dell'HTML
```
<script src="https://code.jquery.com/jquery-3.7.1.min.js" integrity="sha256-/JqT3SQfawRcv/BIHPThkBvs0OEvtFFmqPF/lYI/Cxo=" crossorigin="anonymous"></script>
```

//nel body dell'HTML
```
<a id="download">Scarica il PDF</a>

<script>
  $(document).ready(function() {
    $('a#download').attr({target: '_blank', href : 'file.pdf'})
  });
</script>
```
