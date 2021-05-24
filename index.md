## Electoral Map

_Sourced from MIT Election Data and Science Lab, 2017 "U.S. President 1976 - 2020"_

<script src="https://www.example.com/javascripts/api/tableau-2.js"></script>
<div id="tableauViz"></div>
<script> function initializeViz() {
var placeholderDiv = document.getElementById("tableauViz");
var url = "https://public.tableau.com/views/ElectoralMap_16218468730270/Dashboard1?:language=en&:display_count=y&:origin=viz_share_link";
var options = {
 width: '600px',
 height: '600px',
 hideTabs: true,
 hideToolbar: true,
 };
viz = new tableau.Viz(placeholderDiv, url, options);
}

</script>
