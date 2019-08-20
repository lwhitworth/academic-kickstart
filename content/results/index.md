+++
# Results
widget = "blank"
title = "Results"
+++
<script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script> 
# Results

{{< chart-age >}}
{{< chart-location >}}

**Age**
<div class="wrapper">
    <div id="one"><div id="age" style="width: 500px; height: 350px; display: inline-block"></div></div>
    <div id="two">{{< table-age >}}</div>
</div>

**Location**
<div class="wrapper">
    <div id="one"><div id="location" style="width: 500px; height: 700px; display: inline-block"></div></div>
    <div id="two">{{< table-location >}}</div>
</div>

{{< google-js >}}