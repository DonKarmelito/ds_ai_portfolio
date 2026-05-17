# **Analiza danych Tytanik**

Poniżej prezentuję prostą analizę danych z katastrofy statku Tytanik. W tym projekcie znajdziesz kilka wniosków, obserwacji i ciekawostek dotyczących tego dramatyczne zdarzenia jakim bez wątpienia byłą katastrofa Tytanika. Projekt ten służył mi jako trening i nauka nowych umiejętności 

<a href="titanic.ipynb" class="md-button md-button--primary">Pobierz notebook!</a>

<iframe
    id="content"
    src="titanic.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>
