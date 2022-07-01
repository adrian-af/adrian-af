# readMe
<style>
    #hiddenP
    {
        display: none;
    }
</style>
<p>:sparkles: Hola :sparkles:</p>
<p id="hiddenP">Párrafo</p>
<p onclick="show()">Párrafo2</p>

<script>
    function show()
    {
        var hiddenP = document.getElementByID("hiddenP");
        hiddenP.style.display = "block";
    }
</script>
