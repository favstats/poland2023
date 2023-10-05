---
format:
  html:
    theme: lumen
---


<style>
    body .main-container {
        max-width: 1920px !important;
    }
</style>






::: {.cell-output-display}
```{=html}
<style>
#overlay {
  position: fixed;
  display: none;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba(0,0,0,0.5);
  z-index: 2;
  cursor: pointer;
  text-align: center;
  padding-top: 10%;
}

#text {
  position: relative;
  top: 50%;
  left: 50%;
  font-size: 20px;
  color: black;
  transform: translate(-50%,-50%);
  -ms-transform: translate(-50%,-50%);
  background-color: white;
  padding: 20px;
  border-radius: 10px;
  width: 50%;
}
</style>

<div id="overlay" onclick="off()">
  <div id="text">
    <img src="wtm_logo_2020.png" alt="Logo" style="width:150px;height:150px;">
    <h2>Welcome to the 2023 Polish Election Dashboard</h2>
    <p>This dashboard aggregates data from the <a href="https://www.facebook.com/ads/library/" target="_blank">Meta Ad Library</a> to show how citizens are targeted during the 2023 Polish parliamentary election.</p>
    <p>If you want to know more about Who Targets Me and our work on ad transparency, visit us on <a href="https://www.whotargets.me/" target="_blank">whotargets.me</a>!</p>
  </div>
</div>

<script>
window.onload = function() {
  var popupLastShown = localStorage.getItem("popupLastShown");
  var now = new Date().getTime();

  if (!popupLastShown || now - popupLastShown > 60*60*1000) {  // 60*60*1000 milliseconds = 1 hour
    document.getElementById("overlay").style.display = "block";
    localStorage.setItem("popupLastShown", now);
  }
}

function off() {
  document.getElementById("overlay").style.display = "none";
}
</script>
```
:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::

::: {.cell}

:::



# 2023 Polish parliamentary election

This section shows *total* and *daily spending* of political parties in the run-up to the 2023 Polish parliamentary election for the latest available data.

# Topline Statistics

::: {.panel-tabset}


## <img src="img/meta.svg" height="24px"> Meta


::: {.panel-tabset}

### Sep 3rd - Oct 2nd 2023 (Last 30 days)


In total, political parties spend zł2,991,812 and ran 12481 ads on Meta in this period.



::: {.cell}
::: {.cell-output-display}
```{=html}
<div id="lpjlbekzvf" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>@import url("https://fonts.googleapis.com/css2?family=Chivo:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");
#lpjlbekzvf table {
  font-family: Chivo, system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#lpjlbekzvf thead, #lpjlbekzvf tbody, #lpjlbekzvf tfoot, #lpjlbekzvf tr, #lpjlbekzvf td, #lpjlbekzvf th {
  border-style: none;
}

#lpjlbekzvf p {
  margin: 0;
  padding: 0;
}

#lpjlbekzvf .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: 300;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: none;
  border-top-width: 3px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#lpjlbekzvf .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#lpjlbekzvf .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#lpjlbekzvf .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#lpjlbekzvf .gt_heading {
  background-color: #FFFFFF;
  text-align: left;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#lpjlbekzvf .gt_bottom_border {
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#lpjlbekzvf .gt_col_headings {
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #000000;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#lpjlbekzvf .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: normal;
  text-transform: uppercase;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#lpjlbekzvf .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: normal;
  text-transform: uppercase;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#lpjlbekzvf .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#lpjlbekzvf .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#lpjlbekzvf .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #000000;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#lpjlbekzvf .gt_spanner_row {
  border-bottom-style: hidden;
}

#lpjlbekzvf .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  text-transform: uppercase;
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #000000;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#lpjlbekzvf .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #000000;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #FFFFFF;
  vertical-align: middle;
}

#lpjlbekzvf .gt_from_md > :first-child {
  margin-top: 0;
}

#lpjlbekzvf .gt_from_md > :last-child {
  margin-bottom: 0;
}

#lpjlbekzvf .gt_row {
  padding-top: 3px;
  padding-bottom: 3px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#lpjlbekzvf .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  text-transform: uppercase;
  border-right-style: solid;
  border-right-width: 0px;
  border-right-color: #FFFFFF;
  padding-left: 5px;
  padding-right: 5px;
}

#lpjlbekzvf .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#lpjlbekzvf .gt_row_group_first td {
  border-top-width: 2px;
}

#lpjlbekzvf .gt_row_group_first th {
  border-top-width: 2px;
}

#lpjlbekzvf .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#lpjlbekzvf .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#lpjlbekzvf .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#lpjlbekzvf .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#lpjlbekzvf .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#lpjlbekzvf .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#lpjlbekzvf .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}

#lpjlbekzvf .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#lpjlbekzvf .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#lpjlbekzvf .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#lpjlbekzvf .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#lpjlbekzvf .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#lpjlbekzvf .gt_sourcenote {
  font-size: 12px;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#lpjlbekzvf .gt_left {
  text-align: left;
}

#lpjlbekzvf .gt_center {
  text-align: center;
}

#lpjlbekzvf .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#lpjlbekzvf .gt_font_normal {
  font-weight: normal;
}

#lpjlbekzvf .gt_font_bold {
  font-weight: bold;
}

#lpjlbekzvf .gt_font_italic {
  font-style: italic;
}

#lpjlbekzvf .gt_super {
  font-size: 65%;
}

#lpjlbekzvf .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#lpjlbekzvf .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#lpjlbekzvf .gt_indent_1 {
  text-indent: 5px;
}

#lpjlbekzvf .gt_indent_2 {
  text-indent: 10px;
}

#lpjlbekzvf .gt_indent_3 {
  text-indent: 15px;
}

#lpjlbekzvf .gt_indent_4 {
  text-indent: 20px;
}

#lpjlbekzvf .gt_indent_5 {
  text-indent: 25px;
}

tbody tr:last-child {
  border-bottom: 2px solid #ffffff00;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id=""></th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Number of Advertisers">Number of Advertisers</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Top Spenders">Top Spenders</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Number of Ads">Number of Ads</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Total Spend">Total Spend</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><th id="stub_1_1" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>ZP</p>
</div></th>
<td headers="stub_1_1 Number of Advertisers" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #263778;"><div class='gt_from_md'><p>195</p>
</div></td>
<td headers="stub_1_1 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Prawo i Sprawiedliwość (zł680,056)<br>2. Mateusz Morawiecki (zł113,896)<br>3. Rafał Romanowski - Poseł na Sejm RP (zł14,094)</p>
</div></td>
<td headers="stub_1_1 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>3,635</p>
</div></td>
<td headers="stub_1_1 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł1,055,579</p>
</div></td></tr>
    <tr><th id="stub_1_2" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>KO</p>
</div></th>
<td headers="stub_1_2 Number of Advertisers" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #f68f2d;"><div class='gt_from_md'><p>238</p>
</div></td>
<td headers="stub_1_2 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Platforma Obywatelska (zł641,546)<br>2. Paweł Olszewski (zł20,658)<br>3. Katarzyna Stachowicz - Osoba Publiczna (zł15,678)</p>
</div></td>
<td headers="stub_1_2 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>3,467</p>
</div></td>
<td headers="stub_1_2 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł1,012,335</p>
</div></td></tr>
    <tr><th id="stub_1_3" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>LEW</p>
</div></th>
<td headers="stub_1_3 Number of Advertisers" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #851a64;"><div class='gt_from_md'><p>89</p>
</div></td>
<td headers="stub_1_3 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Lewica (zł268,107)<br>2. Maciej Gdula (zł11,348)<br>3. Tomasz Trela (zł8,549)</p>
</div></td>
<td headers="stub_1_3 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>2,319</p>
</div></td>
<td headers="stub_1_3 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł415,778</p>
</div></td></tr>
    <tr><th id="stub_1_4" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>TD</p>
</div></th>
<td headers="stub_1_4 Number of Advertisers" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #3db53a;"><div class='gt_from_md'><p>150</p>
</div></td>
<td headers="stub_1_4 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Polska 2050 (zł24,155)<br>2. Rafał Komarewicz - Przewodniczący Rady Miasta Krakowa (zł17,228)<br>3. Władysław Kosiniak-Kamysz (zł16,546)</p>
</div></td>
<td headers="stub_1_4 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>2,373</p>
</div></td>
<td headers="stub_1_4 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł366,409</p>
</div></td></tr>
    <tr><th id="stub_1_5" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>BS</p>
</div></th>
<td headers="stub_1_5 Number of Advertisers" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #e6001a;"><div class='gt_from_md'><p>22</p>
</div></td>
<td headers="stub_1_5 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Piotr Koszarek - do Sejmu (zł13,450)<br>2. Bezpartyjni Samorządowcy (zł6,591)<br>3. Michał Rado (zł6,319)</p>
</div></td>
<td headers="stub_1_5 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>196</p>
</div></td>
<td headers="stub_1_5 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł71,578</p>
</div></td></tr>
    <tr><th id="stub_1_6" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>KWIN</p>
</div></th>
<td headers="stub_1_6 Number of Advertisers" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #122746;"><div class='gt_from_md'><p>43</p>
</div></td>
<td headers="stub_1_6 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Konfederacja (zł29,399)<br>2. Patryk Marjan (zł5,552)<br>3. Stanisław Derehajło (zł5,069)</p>
</div></td>
<td headers="stub_1_6 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>301</p>
</div></td>
<td headers="stub_1_6 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł65,014</p>
</div></td></tr>
    <tr><th id="stub_1_7" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>LIB</p>
</div></th>
<td headers="stub_1_7 Number of Advertisers" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #ffd900;"><div class='gt_from_md'><p>2</p>
</div></td>
<td headers="stub_1_7 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Paweł Tanajno Polska Liberalna Strajk Przedsiębiorców (zł3,134)<br>2. Marcin Koza Shogun (zł1,985)</p>
</div></td>
<td headers="stub_1_7 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>190</p>
</div></td>
<td headers="stub_1_7 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł5,119</p>
</div></td></tr>
  </tbody>
  
  
</table>
</div>
```
:::
:::





### Sep 26th - Oct 2nd 2023 (Last 7 days)

In total, political parties spend zł1,108,707 and ran 6230 ads on Meta in this period.




::: {.cell}
::: {.cell-output-display}
```{=html}
<div id="hgmkmgxvxc" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>@import url("https://fonts.googleapis.com/css2?family=Chivo:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");
#hgmkmgxvxc table {
  font-family: Chivo, system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#hgmkmgxvxc thead, #hgmkmgxvxc tbody, #hgmkmgxvxc tfoot, #hgmkmgxvxc tr, #hgmkmgxvxc td, #hgmkmgxvxc th {
  border-style: none;
}

#hgmkmgxvxc p {
  margin: 0;
  padding: 0;
}

#hgmkmgxvxc .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: 300;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: none;
  border-top-width: 3px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#hgmkmgxvxc .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#hgmkmgxvxc .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#hgmkmgxvxc .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#hgmkmgxvxc .gt_heading {
  background-color: #FFFFFF;
  text-align: left;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#hgmkmgxvxc .gt_bottom_border {
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#hgmkmgxvxc .gt_col_headings {
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #000000;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#hgmkmgxvxc .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: normal;
  text-transform: uppercase;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#hgmkmgxvxc .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: normal;
  text-transform: uppercase;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#hgmkmgxvxc .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#hgmkmgxvxc .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#hgmkmgxvxc .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #000000;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#hgmkmgxvxc .gt_spanner_row {
  border-bottom-style: hidden;
}

#hgmkmgxvxc .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  text-transform: uppercase;
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #000000;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#hgmkmgxvxc .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #000000;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #FFFFFF;
  vertical-align: middle;
}

#hgmkmgxvxc .gt_from_md > :first-child {
  margin-top: 0;
}

#hgmkmgxvxc .gt_from_md > :last-child {
  margin-bottom: 0;
}

#hgmkmgxvxc .gt_row {
  padding-top: 3px;
  padding-bottom: 3px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#hgmkmgxvxc .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  text-transform: uppercase;
  border-right-style: solid;
  border-right-width: 0px;
  border-right-color: #FFFFFF;
  padding-left: 5px;
  padding-right: 5px;
}

#hgmkmgxvxc .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#hgmkmgxvxc .gt_row_group_first td {
  border-top-width: 2px;
}

#hgmkmgxvxc .gt_row_group_first th {
  border-top-width: 2px;
}

#hgmkmgxvxc .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#hgmkmgxvxc .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#hgmkmgxvxc .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#hgmkmgxvxc .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#hgmkmgxvxc .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#hgmkmgxvxc .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#hgmkmgxvxc .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}

#hgmkmgxvxc .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#hgmkmgxvxc .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#hgmkmgxvxc .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#hgmkmgxvxc .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#hgmkmgxvxc .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#hgmkmgxvxc .gt_sourcenote {
  font-size: 12px;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#hgmkmgxvxc .gt_left {
  text-align: left;
}

#hgmkmgxvxc .gt_center {
  text-align: center;
}

#hgmkmgxvxc .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#hgmkmgxvxc .gt_font_normal {
  font-weight: normal;
}

#hgmkmgxvxc .gt_font_bold {
  font-weight: bold;
}

#hgmkmgxvxc .gt_font_italic {
  font-style: italic;
}

#hgmkmgxvxc .gt_super {
  font-size: 65%;
}

#hgmkmgxvxc .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#hgmkmgxvxc .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#hgmkmgxvxc .gt_indent_1 {
  text-indent: 5px;
}

#hgmkmgxvxc .gt_indent_2 {
  text-indent: 10px;
}

#hgmkmgxvxc .gt_indent_3 {
  text-indent: 15px;
}

#hgmkmgxvxc .gt_indent_4 {
  text-indent: 20px;
}

#hgmkmgxvxc .gt_indent_5 {
  text-indent: 25px;
}

tbody tr:last-child {
  border-bottom: 2px solid #ffffff00;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id=""></th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Number of Advertisers">Number of Advertisers</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Top Spenders">Top Spenders</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Number of Ads">Number of Ads</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Total Spend">Total Spend</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><th id="stub_1_1" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>ZP</p>
</div></th>
<td headers="stub_1_1 Number of Advertisers" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #263778;"><div class='gt_from_md'><p>163</p>
</div></td>
<td headers="stub_1_1 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Prawo i Sprawiedliwość (zł224,445)<br>2. Mateusz Morawiecki (zł56,653)<br>3. Jarosław Sellin - oficjalna strona (zł4,829)</p>
</div></td>
<td headers="stub_1_1 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>1,823</p>
</div></td>
<td headers="stub_1_1 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł390,321</p>
</div></td></tr>
    <tr><th id="stub_1_2" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>KO</p>
</div></th>
<td headers="stub_1_2 Number of Advertisers" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #f68f2d;"><div class='gt_from_md'><p>199</p>
</div></td>
<td headers="stub_1_2 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Platforma Obywatelska (zł167,097)<br>2. Katarzyna Stachowicz - Osoba Publiczna (zł13,187)<br>3. Radosław Sikorski (zł10,431)</p>
</div></td>
<td headers="stub_1_2 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>1,628</p>
</div></td>
<td headers="stub_1_2 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł320,810</p>
</div></td></tr>
    <tr><th id="stub_1_3" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>LEW</p>
</div></th>
<td headers="stub_1_3 Number of Advertisers" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #851a64;"><div class='gt_from_md'><p>85</p>
</div></td>
<td headers="stub_1_3 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Lewica (zł126,926)<br>2. Maciej Gdula (zł6,928)<br>3. Tomasz Trela (zł3,284)</p>
</div></td>
<td headers="stub_1_3 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>1,222</p>
</div></td>
<td headers="stub_1_3 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł190,672</p>
</div></td></tr>
    <tr><th id="stub_1_4" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>TD</p>
</div></th>
<td headers="stub_1_4 Number of Advertisers" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #3db53a;"><div class='gt_from_md'><p>135</p>
</div></td>
<td headers="stub_1_4 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Polska 2050 (zł16,661)<br>2. Rafał Komarewicz - Przewodniczący Rady Miasta Krakowa (zł5,522)<br>3. Piotr Dasios (zł4,913)</p>
</div></td>
<td headers="stub_1_4 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>1,264</p>
</div></td>
<td headers="stub_1_4 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł147,641</p>
</div></td></tr>
    <tr><th id="stub_1_5" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>BS</p>
</div></th>
<td headers="stub_1_5 Number of Advertisers" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #e6001a;"><div class='gt_from_md'><p>20</p>
</div></td>
<td headers="stub_1_5 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Bezpartyjni Samorządowcy (zł6,591)<br>2. Piotr Koszarek - do Sejmu (zł4,215)<br>3. Michał Rado (zł3,915)</p>
</div></td>
<td headers="stub_1_5 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>140</p>
</div></td>
<td headers="stub_1_5 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł37,436</p>
</div></td></tr>
    <tr><th id="stub_1_6" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>KWIN</p>
</div></th>
<td headers="stub_1_6 Number of Advertisers" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #122746;"><div class='gt_from_md'><p>34</p>
</div></td>
<td headers="stub_1_6 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Konfederacja (zł6,045)<br>2. Stanisław Derehajło (zł3,228)<br>3. Patryk Marjan (zł1,412)</p>
</div></td>
<td headers="stub_1_6 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>144</p>
</div></td>
<td headers="stub_1_6 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł21,265</p>
</div></td></tr>
    <tr><th id="stub_1_7" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>LIB</p>
</div></th>
<td headers="stub_1_7 Number of Advertisers" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #ffd900;"><div class='gt_from_md'><p>2</p>
</div></td>
<td headers="stub_1_7 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Marcin Koza Shogun (zł462)<br>2. Paweł Tanajno Polska Liberalna Strajk Przedsiębiorców (zł100)</p>
</div></td>
<td headers="stub_1_7 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>9</p>
</div></td>
<td headers="stub_1_7 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł562</p>
</div></td></tr>
  </tbody>
  
  
</table>
</div>
```
:::
:::


::: 






## ![](img/g.svg) Google





::: {.cell}

:::

::: {.cell}

:::



::: {.panel-tabset}



### Sep 3rd - Oct 2nd 2023 (Last 30 days)


In total, political parties spent zł4,425,000 and ran 3787 ad copies on Google in this timeframe.


::: {.cell}
::: {.cell-output-display}
```{=html}
<div id="igkowwyvxl" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>@import url("https://fonts.googleapis.com/css2?family=Chivo:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");
#igkowwyvxl table {
  font-family: Chivo, system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#igkowwyvxl thead, #igkowwyvxl tbody, #igkowwyvxl tfoot, #igkowwyvxl tr, #igkowwyvxl td, #igkowwyvxl th {
  border-style: none;
}

#igkowwyvxl p {
  margin: 0;
  padding: 0;
}

#igkowwyvxl .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: 300;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: none;
  border-top-width: 3px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#igkowwyvxl .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#igkowwyvxl .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#igkowwyvxl .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#igkowwyvxl .gt_heading {
  background-color: #FFFFFF;
  text-align: left;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#igkowwyvxl .gt_bottom_border {
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#igkowwyvxl .gt_col_headings {
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #000000;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#igkowwyvxl .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: normal;
  text-transform: uppercase;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#igkowwyvxl .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: normal;
  text-transform: uppercase;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#igkowwyvxl .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#igkowwyvxl .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#igkowwyvxl .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #000000;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#igkowwyvxl .gt_spanner_row {
  border-bottom-style: hidden;
}

#igkowwyvxl .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  text-transform: uppercase;
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #000000;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#igkowwyvxl .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #000000;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #FFFFFF;
  vertical-align: middle;
}

#igkowwyvxl .gt_from_md > :first-child {
  margin-top: 0;
}

#igkowwyvxl .gt_from_md > :last-child {
  margin-bottom: 0;
}

#igkowwyvxl .gt_row {
  padding-top: 3px;
  padding-bottom: 3px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#igkowwyvxl .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  text-transform: uppercase;
  border-right-style: solid;
  border-right-width: 0px;
  border-right-color: #FFFFFF;
  padding-left: 5px;
  padding-right: 5px;
}

#igkowwyvxl .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#igkowwyvxl .gt_row_group_first td {
  border-top-width: 2px;
}

#igkowwyvxl .gt_row_group_first th {
  border-top-width: 2px;
}

#igkowwyvxl .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#igkowwyvxl .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#igkowwyvxl .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#igkowwyvxl .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#igkowwyvxl .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#igkowwyvxl .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#igkowwyvxl .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}

#igkowwyvxl .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#igkowwyvxl .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#igkowwyvxl .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#igkowwyvxl .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#igkowwyvxl .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#igkowwyvxl .gt_sourcenote {
  font-size: 12px;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#igkowwyvxl .gt_left {
  text-align: left;
}

#igkowwyvxl .gt_center {
  text-align: center;
}

#igkowwyvxl .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#igkowwyvxl .gt_font_normal {
  font-weight: normal;
}

#igkowwyvxl .gt_font_bold {
  font-weight: bold;
}

#igkowwyvxl .gt_font_italic {
  font-style: italic;
}

#igkowwyvxl .gt_super {
  font-size: 65%;
}

#igkowwyvxl .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#igkowwyvxl .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#igkowwyvxl .gt_indent_1 {
  text-indent: 5px;
}

#igkowwyvxl .gt_indent_2 {
  text-indent: 10px;
}

#igkowwyvxl .gt_indent_3 {
  text-indent: 15px;
}

#igkowwyvxl .gt_indent_4 {
  text-indent: 20px;
}

#igkowwyvxl .gt_indent_5 {
  text-indent: 25px;
}

tbody tr:last-child {
  border-bottom: 2px solid #ffffff00;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id=""></th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Number of Ads">Number of Ads</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Top Spenders">Top Spenders</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Total Spend">Total Spend</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><th id="stub_1_1" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>ZP</p>
</div></th>
<td headers="stub_1_1 Number of Ads" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #263778;"><div class='gt_from_md'><p>861</p>
</div></td>
<td headers="stub_1_1 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Komitet Wyborczy Prawo i Sprawiedliwość (zł3,155,500)<br>2. KW PRAWO I SPRAWIEDLIWOŚĆ (zł3,000)<br>3. Lendo Andrzej Skrętowski (zł1,250)</p>
</div></td>
<td headers="stub_1_1 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł3,159,750</p>
</div></td></tr>
    <tr><th id="stub_1_2" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>KO</p>
</div></th>
<td headers="stub_1_2 Number of Ads" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #f68f2d;"><div class='gt_from_md'><p>719</p>
</div></td>
<td headers="stub_1_2 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. KOALICYJNY KOMITET WYBORCZY KOALICJA OBYWATELSKA PO .N IPL ZIELONI (zł825,750)<br>2. Platforma Obywatelska RP (zł267,250)<br>3. BUSINESS TAILORS SPÓŁKA Z OGRANICZONĄ ODPOWIEDZIALNOŚCIĄ (zł2,750)</p>
</div></td>
<td headers="stub_1_2 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł1,095,750</p>
</div></td></tr>
    <tr><th id="stub_1_3" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>LEW</p>
</div></th>
<td headers="stub_1_3 Number of Ads" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #851a64;"><div class='gt_from_md'><p>1,699</p>
</div></td>
<td headers="stub_1_3 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Komitet Wyborczy Nowa Lewica (zł99,250)<br>2. KW Nowa Lewica (zł1,500)<br>3. NOWA LEWICA (zł750)</p>
</div></td>
<td headers="stub_1_3 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł101,500</p>
</div></td></tr>
    <tr><th id="stub_1_4" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>KWIN</p>
</div></th>
<td headers="stub_1_4 Number of Ads" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #122746;"><div class='gt_from_md'><p>149</p>
</div></td>
<td headers="stub_1_4 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Komitet Wyborczy Konfederacja Wolność i Niepodległość (zł37,500)</p>
</div></td>
<td headers="stub_1_4 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł37,500</p>
</div></td></tr>
    <tr><th id="stub_1_5" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>TD</p>
</div></th>
<td headers="stub_1_5 Number of Ads" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #3db53a;"><div class='gt_from_md'><p>153</p>
</div></td>
<td headers="stub_1_5 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. KKW TRZECIA DROGA PSL-PL2050 SZYMONA HOŁOWNI (zł11,250)<br>2. KKW TRZECIA DROGA PKOALICYJNY KOMITET WYBORCZY TRZECIA DROGA POLSKA 2050 SZYMONA HOŁOWNI - POLSKIE STRONNICTWO LUDOWESL-PL2050 SZYMONA HOŁOWNI. (zł3,250)<br>3. POLSKA 2050 (zł1,000)</p>
</div></td>
<td headers="stub_1_5 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł15,500</p>
</div></td></tr>
    <tr><th id="stub_1_6" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>BS</p>
</div></th>
<td headers="stub_1_6 Number of Ads" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #e6001a;"><div class='gt_from_md'><p>206</p>
</div></td>
<td headers="stub_1_6 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. KW Bezpartyjni Samorządowcy (zł15,000)</p>
</div></td>
<td headers="stub_1_6 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł15,000</p>
</div></td></tr>
  </tbody>
  
  
</table>
</div>
```
:::
:::


### Sep 26th - Oct 2nd 2023 (Last 7 days)

In total, political parties spent zł915,000 and ran 3212 ad copies on Google in this timeframe.



::: {.cell}
::: {.cell-output-display}
```{=html}
<div id="ykkixwgimq" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>@import url("https://fonts.googleapis.com/css2?family=Chivo:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");
#ykkixwgimq table {
  font-family: Chivo, system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#ykkixwgimq thead, #ykkixwgimq tbody, #ykkixwgimq tfoot, #ykkixwgimq tr, #ykkixwgimq td, #ykkixwgimq th {
  border-style: none;
}

#ykkixwgimq p {
  margin: 0;
  padding: 0;
}

#ykkixwgimq .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: 300;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: none;
  border-top-width: 3px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#ykkixwgimq .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#ykkixwgimq .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#ykkixwgimq .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#ykkixwgimq .gt_heading {
  background-color: #FFFFFF;
  text-align: left;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#ykkixwgimq .gt_bottom_border {
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#ykkixwgimq .gt_col_headings {
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #000000;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#ykkixwgimq .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: normal;
  text-transform: uppercase;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#ykkixwgimq .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: normal;
  text-transform: uppercase;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#ykkixwgimq .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#ykkixwgimq .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#ykkixwgimq .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #000000;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#ykkixwgimq .gt_spanner_row {
  border-bottom-style: hidden;
}

#ykkixwgimq .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  text-transform: uppercase;
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #000000;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#ykkixwgimq .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #000000;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #FFFFFF;
  vertical-align: middle;
}

#ykkixwgimq .gt_from_md > :first-child {
  margin-top: 0;
}

#ykkixwgimq .gt_from_md > :last-child {
  margin-bottom: 0;
}

#ykkixwgimq .gt_row {
  padding-top: 3px;
  padding-bottom: 3px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#ykkixwgimq .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  text-transform: uppercase;
  border-right-style: solid;
  border-right-width: 0px;
  border-right-color: #FFFFFF;
  padding-left: 5px;
  padding-right: 5px;
}

#ykkixwgimq .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#ykkixwgimq .gt_row_group_first td {
  border-top-width: 2px;
}

#ykkixwgimq .gt_row_group_first th {
  border-top-width: 2px;
}

#ykkixwgimq .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#ykkixwgimq .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#ykkixwgimq .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#ykkixwgimq .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#ykkixwgimq .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#ykkixwgimq .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#ykkixwgimq .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}

#ykkixwgimq .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#ykkixwgimq .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#ykkixwgimq .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#ykkixwgimq .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#ykkixwgimq .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#ykkixwgimq .gt_sourcenote {
  font-size: 12px;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#ykkixwgimq .gt_left {
  text-align: left;
}

#ykkixwgimq .gt_center {
  text-align: center;
}

#ykkixwgimq .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#ykkixwgimq .gt_font_normal {
  font-weight: normal;
}

#ykkixwgimq .gt_font_bold {
  font-weight: bold;
}

#ykkixwgimq .gt_font_italic {
  font-style: italic;
}

#ykkixwgimq .gt_super {
  font-size: 65%;
}

#ykkixwgimq .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#ykkixwgimq .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#ykkixwgimq .gt_indent_1 {
  text-indent: 5px;
}

#ykkixwgimq .gt_indent_2 {
  text-indent: 10px;
}

#ykkixwgimq .gt_indent_3 {
  text-indent: 15px;
}

#ykkixwgimq .gt_indent_4 {
  text-indent: 20px;
}

#ykkixwgimq .gt_indent_5 {
  text-indent: 25px;
}

tbody tr:last-child {
  border-bottom: 2px solid #ffffff00;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id=""></th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Number of Ads">Number of Ads</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Top Spenders">Top Spenders</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Total Spend">Total Spend</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><th id="stub_1_1" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>ZP</p>
</div></th>
<td headers="stub_1_1 Number of Ads" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #263778;"><div class='gt_from_md'><p>645</p>
</div></td>
<td headers="stub_1_1 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Komitet Wyborczy Prawo i Sprawiedliwość (zł625,250)<br>2. KW PRAWO I SPRAWIEDLIWOŚĆ (zł3,000)<br>3. Lendo Andrzej Skrętowski (zł1,250)</p>
</div></td>
<td headers="stub_1_1 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł629,500</p>
</div></td></tr>
    <tr><th id="stub_1_2" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>KO</p>
</div></th>
<td headers="stub_1_2 Number of Ads" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #f68f2d;"><div class='gt_from_md'><p>537</p>
</div></td>
<td headers="stub_1_2 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. KOALICYJNY KOMITET WYBORCZY KOALICJA OBYWATELSKA PO .N IPL ZIELONI (zł164,000)<br>2. BUSINESS TAILORS SPÓŁKA Z OGRANICZONĄ ODPOWIEDZIALNOŚCIĄ (zł2,750)<br>3. Platforma Obywatelska RP (zł250)</p>
</div></td>
<td headers="stub_1_2 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł167,000</p>
</div></td></tr>
    <tr><th id="stub_1_3" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>LEW</p>
</div></th>
<td headers="stub_1_3 Number of Ads" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #851a64;"><div class='gt_from_md'><p>1,572</p>
</div></td>
<td headers="stub_1_3 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Komitet Wyborczy Nowa Lewica (zł67,750)<br>2. KW Nowa Lewica (zł750)<br>3. NOWA LEWICA (zł500)</p>
</div></td>
<td headers="stub_1_3 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł69,000</p>
</div></td></tr>
    <tr><th id="stub_1_4" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>KWIN</p>
</div></th>
<td headers="stub_1_4 Number of Ads" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #122746;"><div class='gt_from_md'><p>137</p>
</div></td>
<td headers="stub_1_4 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. Komitet Wyborczy Konfederacja Wolność i Niepodległość (zł25,500)</p>
</div></td>
<td headers="stub_1_4 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł25,500</p>
</div></td></tr>
    <tr><th id="stub_1_5" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>BS</p>
</div></th>
<td headers="stub_1_5 Number of Ads" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #e6001a;"><div class='gt_from_md'><p>199</p>
</div></td>
<td headers="stub_1_5 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. KW Bezpartyjni Samorządowcy (zł12,250)</p>
</div></td>
<td headers="stub_1_5 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł12,250</p>
</div></td></tr>
    <tr><th id="stub_1_6" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>TD</p>
</div></th>
<td headers="stub_1_6 Number of Ads" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #3db53a;"><div class='gt_from_md'><p>122</p>
</div></td>
<td headers="stub_1_6 Top Spenders" class="gt_row gt_center"><div class='gt_from_md'><p><br>1. KKW TRZECIA DROGA PSL-PL2050 SZYMONA HOŁOWNI (zł8,500)<br>2. KKW TRZECIA DROGA PKOALICYJNY KOMITET WYBORCZY TRZECIA DROGA POLSKA 2050 SZYMONA HOŁOWNI - POLSKIE STRONNICTWO LUDOWESL-PL2050 SZYMONA HOŁOWNI. (zł2,500)<br>3. POLSKA 2050 (zł750)</p>
</div></td>
<td headers="stub_1_6 Total Spend" class="gt_row gt_center"><div class='gt_from_md'><p>zł11,750</p>
</div></td></tr>
  </tbody>
  
  
</table>
</div>
```
:::
:::



::: 

## `<svg aria-hidden="true" role="img" viewBox="0 0 448 512" style="height:1em;width:0.88em;vertical-align:-0.125em;margin-left:auto;margin-right:auto;font-size:inherit;fill:lightblue;overflow:visible;position:relative;"><path d="M349.4 44.6c5.9-13.7 1.5-29.7-10.6-38.5s-28.6-8-39.9 1.8l-256 224c-10 8.8-13.6 22.9-8.9 35.3S50.7 288 64 288H175.5L98.6 467.4c-5.9 13.7-1.5 29.7 10.6 38.5s28.6 8 39.9-1.8l256-224c10-8.8 13.6-22.9 8.9-35.3s-16.6-20.7-30-20.7H272.5L349.4 44.6z"/></svg>`{=html} Combined




::: {.cell}

:::

::: {.cell}

:::



::: {.panel-tabset}



### Sep 3rd - Oct 2nd 2023 (Last 30 days)


In total, political parties spent zł7,416,812 and ran 16268 ad copies on digital platforms in this timeframe.


::: {.cell}
::: {.cell-output-display}
```{=html}
<div id="uiqxwnilxy" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>@import url("https://fonts.googleapis.com/css2?family=Chivo:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");
#uiqxwnilxy table {
  font-family: Chivo, system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#uiqxwnilxy thead, #uiqxwnilxy tbody, #uiqxwnilxy tfoot, #uiqxwnilxy tr, #uiqxwnilxy td, #uiqxwnilxy th {
  border-style: none;
}

#uiqxwnilxy p {
  margin: 0;
  padding: 0;
}

#uiqxwnilxy .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: 300;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: none;
  border-top-width: 3px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#uiqxwnilxy .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#uiqxwnilxy .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#uiqxwnilxy .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#uiqxwnilxy .gt_heading {
  background-color: #FFFFFF;
  text-align: left;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#uiqxwnilxy .gt_bottom_border {
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#uiqxwnilxy .gt_col_headings {
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #000000;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#uiqxwnilxy .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: normal;
  text-transform: uppercase;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#uiqxwnilxy .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: normal;
  text-transform: uppercase;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#uiqxwnilxy .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#uiqxwnilxy .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#uiqxwnilxy .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #000000;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#uiqxwnilxy .gt_spanner_row {
  border-bottom-style: hidden;
}

#uiqxwnilxy .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  text-transform: uppercase;
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #000000;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#uiqxwnilxy .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #000000;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #FFFFFF;
  vertical-align: middle;
}

#uiqxwnilxy .gt_from_md > :first-child {
  margin-top: 0;
}

#uiqxwnilxy .gt_from_md > :last-child {
  margin-bottom: 0;
}

#uiqxwnilxy .gt_row {
  padding-top: 3px;
  padding-bottom: 3px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#uiqxwnilxy .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  text-transform: uppercase;
  border-right-style: solid;
  border-right-width: 0px;
  border-right-color: #FFFFFF;
  padding-left: 5px;
  padding-right: 5px;
}

#uiqxwnilxy .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#uiqxwnilxy .gt_row_group_first td {
  border-top-width: 2px;
}

#uiqxwnilxy .gt_row_group_first th {
  border-top-width: 2px;
}

#uiqxwnilxy .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#uiqxwnilxy .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#uiqxwnilxy .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#uiqxwnilxy .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#uiqxwnilxy .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#uiqxwnilxy .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#uiqxwnilxy .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}

#uiqxwnilxy .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#uiqxwnilxy .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#uiqxwnilxy .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#uiqxwnilxy .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#uiqxwnilxy .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#uiqxwnilxy .gt_sourcenote {
  font-size: 12px;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#uiqxwnilxy .gt_left {
  text-align: left;
}

#uiqxwnilxy .gt_center {
  text-align: center;
}

#uiqxwnilxy .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#uiqxwnilxy .gt_font_normal {
  font-weight: normal;
}

#uiqxwnilxy .gt_font_bold {
  font-weight: bold;
}

#uiqxwnilxy .gt_font_italic {
  font-style: italic;
}

#uiqxwnilxy .gt_super {
  font-size: 65%;
}

#uiqxwnilxy .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#uiqxwnilxy .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#uiqxwnilxy .gt_indent_1 {
  text-indent: 5px;
}

#uiqxwnilxy .gt_indent_2 {
  text-indent: 10px;
}

#uiqxwnilxy .gt_indent_3 {
  text-indent: 15px;
}

#uiqxwnilxy .gt_indent_4 {
  text-indent: 20px;
}

#uiqxwnilxy .gt_indent_5 {
  text-indent: 25px;
}

tbody tr:last-child {
  border-bottom: 2px solid #ffffff00;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id=""></th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Total Spend">Total Spend</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Number of Ads">Number of Ads</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><th id="stub_1_1" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>ZP</p>
</div></th>
<td headers="stub_1_1 Total Spend" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #263778;"><div class='gt_from_md'><p>zł4,215,329</p>
</div></td>
<td headers="stub_1_1 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>4496</p>
</div></td></tr>
    <tr><th id="stub_1_2" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>KO</p>
</div></th>
<td headers="stub_1_2 Total Spend" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #f68f2d;"><div class='gt_from_md'><p>zł2,108,085</p>
</div></td>
<td headers="stub_1_2 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>4186</p>
</div></td></tr>
    <tr><th id="stub_1_3" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>LEW</p>
</div></th>
<td headers="stub_1_3 Total Spend" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #851a64;"><div class='gt_from_md'><p>zł517,278</p>
</div></td>
<td headers="stub_1_3 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>4018</p>
</div></td></tr>
    <tr><th id="stub_1_4" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>TD</p>
</div></th>
<td headers="stub_1_4 Total Spend" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #3db53a;"><div class='gt_from_md'><p>zł381,909</p>
</div></td>
<td headers="stub_1_4 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>2526</p>
</div></td></tr>
    <tr><th id="stub_1_5" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>KWIN</p>
</div></th>
<td headers="stub_1_5 Total Spend" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #122746;"><div class='gt_from_md'><p>zł102,514</p>
</div></td>
<td headers="stub_1_5 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>450</p>
</div></td></tr>
    <tr><th id="stub_1_6" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>BS</p>
</div></th>
<td headers="stub_1_6 Total Spend" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #e6001a;"><div class='gt_from_md'><p>zł86,578</p>
</div></td>
<td headers="stub_1_6 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>402</p>
</div></td></tr>
    <tr><th id="stub_1_7" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>LIB</p>
</div></th>
<td headers="stub_1_7 Total Spend" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #ffd900;"><div class='gt_from_md'><p>zł5,119</p>
</div></td>
<td headers="stub_1_7 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>190</p>
</div></td></tr>
  </tbody>
  
  
</table>
</div>
```
:::
:::


### Sep 26th - Oct 2nd 2023 (Last 7 days)

In total, political parties spent zł2,023,707 and ran 9442 ads on digital platforms in this timeframe.



::: {.cell}
::: {.cell-output-display}
```{=html}
<div id="gnnwbnouni" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>@import url("https://fonts.googleapis.com/css2?family=Chivo:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");
#gnnwbnouni table {
  font-family: Chivo, system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#gnnwbnouni thead, #gnnwbnouni tbody, #gnnwbnouni tfoot, #gnnwbnouni tr, #gnnwbnouni td, #gnnwbnouni th {
  border-style: none;
}

#gnnwbnouni p {
  margin: 0;
  padding: 0;
}

#gnnwbnouni .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: 300;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: none;
  border-top-width: 3px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#gnnwbnouni .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#gnnwbnouni .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#gnnwbnouni .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#gnnwbnouni .gt_heading {
  background-color: #FFFFFF;
  text-align: left;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#gnnwbnouni .gt_bottom_border {
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#gnnwbnouni .gt_col_headings {
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #000000;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#gnnwbnouni .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: normal;
  text-transform: uppercase;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#gnnwbnouni .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: normal;
  text-transform: uppercase;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#gnnwbnouni .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#gnnwbnouni .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#gnnwbnouni .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #000000;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#gnnwbnouni .gt_spanner_row {
  border-bottom-style: hidden;
}

#gnnwbnouni .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  text-transform: uppercase;
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #000000;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#gnnwbnouni .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  border-top-style: none;
  border-top-width: 2px;
  border-top-color: #000000;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  border-bottom-color: #FFFFFF;
  vertical-align: middle;
}

#gnnwbnouni .gt_from_md > :first-child {
  margin-top: 0;
}

#gnnwbnouni .gt_from_md > :last-child {
  margin-bottom: 0;
}

#gnnwbnouni .gt_row {
  padding-top: 3px;
  padding-bottom: 3px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#gnnwbnouni .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 80%;
  font-weight: bolder;
  text-transform: uppercase;
  border-right-style: solid;
  border-right-width: 0px;
  border-right-color: #FFFFFF;
  padding-left: 5px;
  padding-right: 5px;
}

#gnnwbnouni .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#gnnwbnouni .gt_row_group_first td {
  border-top-width: 2px;
}

#gnnwbnouni .gt_row_group_first th {
  border-top-width: 2px;
}

#gnnwbnouni .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#gnnwbnouni .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#gnnwbnouni .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#gnnwbnouni .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#gnnwbnouni .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#gnnwbnouni .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#gnnwbnouni .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}

#gnnwbnouni .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#gnnwbnouni .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#gnnwbnouni .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#gnnwbnouni .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#gnnwbnouni .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#gnnwbnouni .gt_sourcenote {
  font-size: 12px;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#gnnwbnouni .gt_left {
  text-align: left;
}

#gnnwbnouni .gt_center {
  text-align: center;
}

#gnnwbnouni .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#gnnwbnouni .gt_font_normal {
  font-weight: normal;
}

#gnnwbnouni .gt_font_bold {
  font-weight: bold;
}

#gnnwbnouni .gt_font_italic {
  font-style: italic;
}

#gnnwbnouni .gt_super {
  font-size: 65%;
}

#gnnwbnouni .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#gnnwbnouni .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#gnnwbnouni .gt_indent_1 {
  text-indent: 5px;
}

#gnnwbnouni .gt_indent_2 {
  text-indent: 10px;
}

#gnnwbnouni .gt_indent_3 {
  text-indent: 15px;
}

#gnnwbnouni .gt_indent_4 {
  text-indent: 20px;
}

#gnnwbnouni .gt_indent_5 {
  text-indent: 25px;
}

tbody tr:last-child {
  border-bottom: 2px solid #ffffff00;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id=""></th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Total Spend">Total Spend</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_center" rowspan="1" colspan="1" style="border-top-width: 0px; border-top-style: solid; border-top-color: black;" scope="col" id="Number of Ads">Number of Ads</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><th id="stub_1_1" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>ZP</p>
</div></th>
<td headers="stub_1_1 Total Spend" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #263778;"><div class='gt_from_md'><p>zł1,019,821</p>
</div></td>
<td headers="stub_1_1 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>2468</p>
</div></td></tr>
    <tr><th id="stub_1_2" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>KO</p>
</div></th>
<td headers="stub_1_2 Total Spend" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #f68f2d;"><div class='gt_from_md'><p>zł487,810</p>
</div></td>
<td headers="stub_1_2 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>2165</p>
</div></td></tr>
    <tr><th id="stub_1_3" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>LEW</p>
</div></th>
<td headers="stub_1_3 Total Spend" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #851a64;"><div class='gt_from_md'><p>zł259,672</p>
</div></td>
<td headers="stub_1_3 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>2794</p>
</div></td></tr>
    <tr><th id="stub_1_4" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>TD</p>
</div></th>
<td headers="stub_1_4 Total Spend" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #3db53a;"><div class='gt_from_md'><p>zł159,391</p>
</div></td>
<td headers="stub_1_4 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>1386</p>
</div></td></tr>
    <tr><th id="stub_1_5" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>BS</p>
</div></th>
<td headers="stub_1_5 Total Spend" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #e6001a;"><div class='gt_from_md'><p>zł49,686</p>
</div></td>
<td headers="stub_1_5 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>339</p>
</div></td></tr>
    <tr><th id="stub_1_6" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>KWIN</p>
</div></th>
<td headers="stub_1_6 Total Spend" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #122746;"><div class='gt_from_md'><p>zł46,765</p>
</div></td>
<td headers="stub_1_6 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>281</p>
</div></td></tr>
    <tr><th id="stub_1_7" scope="row" class="gt_row gt_center gt_stub"><div class='gt_from_md'><p>LIB</p>
</div></th>
<td headers="stub_1_7 Total Spend" class="gt_row gt_center" style="border-left-width: 18.5px; border-left-style: solid; border-left-color: #ffd900;"><div class='gt_from_md'><p>zł562</p>
</div></td>
<td headers="stub_1_7 Number of Ads" class="gt_row gt_center"><div class='gt_from_md'><p>9</p>
</div></td></tr>
  </tbody>
  
  
</table>
</div>
```
:::
:::




::: 

::: 



# Spending over Time

Daily spending estimates might not be entirely accurate as reporting granularity differs (e.g. on Google minimum amounts of 50 Euro are displayed). For total estimates refer to the spending in the section above.


::: {.panel-tabset}


## <img src="img/meta.svg" height="24px"> Meta



::: {.panel-tabset}


### Cumulative


::: {.cell}

:::

::: {.cell}
::: {.cell-output-display}
```{=html}
<div class="highchart html-widget html-fill-item-overflow-hidden html-fill-item" id="htmlwidget-20168e88a51a7f48dc76" style="width:100%;height:480px;"></div>
<script type="application/json" data-for="htmlwidget-20168e88a51a7f48dc76">{"x":{"hc_opts":{"chart":{"reflow":true},"title":{"text":null},"yAxis":{"title":{"text":"Daily Spend"},"type":"linear"},"credits":{"enabled":false},"exporting":{"enabled":false},"boost":{"enabled":false},"plotOptions":{"series":{"label":{"enabled":false},"turboThreshold":0,"showInLegend":true},"treemap":{"layoutAlgorithm":"squarified"},"scatter":{"marker":{"symbol":"circle"}},"area":{"stacking":"normal","lineWidth":1,"marker":{"enabled":false}}},"series":[{"name":"BS","data":[{"date_produced":"2023-08-31","party":"BS","spend":119330,"total_spend":177481,"colors":"#e6001a","Date":"2023-08-31","Daily_Diff":145,"Daily Spend":290,"x":1693440000000,"y":290,"fill":"#e6001a"},{"date_produced":"2023-09-01","party":"BS","spend":119457,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-01","Daily_Diff":127,"Daily Spend":417,"x":1693526400000,"y":417,"fill":"#e6001a"},{"date_produced":"2023-09-02","party":"BS","spend":119584,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-02","Daily_Diff":127,"Daily Spend":544,"x":1693612800000,"y":544,"fill":"#e6001a"},{"date_produced":"2023-09-03","party":"BS","spend":119699,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-03","Daily_Diff":115,"Daily Spend":659,"x":1693699200000,"y":659,"fill":"#e6001a"},{"date_produced":"2023-09-04","party":"BS","spend":119820,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-04","Daily_Diff":121,"Daily Spend":780,"x":1693785600000,"y":780,"fill":"#e6001a"},{"date_produced":"2023-09-05","party":"BS","spend":120253,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-05","Daily_Diff":433,"Daily Spend":1213,"x":1693872000000,"y":1213,"fill":"#e6001a"},{"date_produced":"2023-09-06","party":"BS","spend":120618,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-06","Daily_Diff":365,"Daily Spend":1578,"x":1693958400000,"y":1578,"fill":"#e6001a"},{"date_produced":"2023-09-07","party":"BS","spend":120965,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-07","Daily_Diff":347,"Daily Spend":1925,"x":1694044800000,"y":1925,"fill":"#e6001a"},{"date_produced":"2023-09-08","party":"BS","spend":121532,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-08","Daily_Diff":567,"Daily Spend":2492,"x":1694131200000,"y":2492,"fill":"#e6001a"},{"date_produced":"2023-09-09","party":"BS","spend":121977,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-09","Daily_Diff":445,"Daily Spend":2937,"x":1694217600000,"y":2937,"fill":"#e6001a"},{"date_produced":"2023-09-10","party":"BS","spend":122234,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-10","Daily_Diff":257,"Daily Spend":3194,"x":1694304000000,"y":3194,"fill":"#e6001a"},{"date_produced":"2023-09-11","party":"BS","spend":122555,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-11","Daily_Diff":321,"Daily Spend":3515,"x":1694390400000,"y":3515,"fill":"#e6001a"},{"date_produced":"2023-09-12","party":"BS","spend":122835,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-12","Daily_Diff":280,"Daily Spend":3795,"x":1694476800000,"y":3795,"fill":"#e6001a"},{"date_produced":"2023-09-13","party":"BS","spend":123194,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-13","Daily_Diff":359,"Daily Spend":4154,"x":1694563200000,"y":4154,"fill":"#e6001a"},{"date_produced":"2023-09-14","party":"BS","spend":123763,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-14","Daily_Diff":569,"Daily Spend":4723,"x":1694649600000,"y":4723,"fill":"#e6001a"},{"date_produced":"2023-09-15","party":"BS","spend":124589,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-15","Daily_Diff":826,"Daily Spend":5549,"x":1694736000000,"y":5549,"fill":"#e6001a"},{"date_produced":"2023-09-16","party":"BS","spend":126164,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-16","Daily_Diff":1575,"Daily Spend":7124,"x":1694822400000,"y":7124,"fill":"#e6001a"},{"date_produced":"2023-09-17","party":"BS","spend":128246,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-17","Daily_Diff":2082,"Daily Spend":9206,"x":1694908800000,"y":9206,"fill":"#e6001a"},{"date_produced":"2023-09-18","party":"BS","spend":129843,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-18","Daily_Diff":1597,"Daily Spend":10803,"x":1694995200000,"y":10803,"fill":"#e6001a"},{"date_produced":"2023-09-19","party":"BS","spend":131975,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-19","Daily_Diff":2132,"Daily Spend":12935,"x":1695081600000,"y":12935,"fill":"#e6001a"},{"date_produced":"2023-09-20","party":"BS","spend":134417,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-20","Daily_Diff":2442,"Daily Spend":15377,"x":1695168000000,"y":15377,"fill":"#e6001a"},{"date_produced":"2023-09-21","party":"BS","spend":137261,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-21","Daily_Diff":2844,"Daily Spend":18221,"x":1695254400000,"y":18221,"fill":"#e6001a"},{"date_produced":"2023-09-22","party":"BS","spend":140607,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-22","Daily_Diff":3346,"Daily Spend":21567,"x":1695340800000,"y":21567,"fill":"#e6001a"},{"date_produced":"2023-09-23","party":"BS","spend":144945,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-23","Daily_Diff":4338,"Daily Spend":25905,"x":1695427200000,"y":25905,"fill":"#e6001a"},{"date_produced":"2023-09-24","party":"BS","spend":149547,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-24","Daily_Diff":4602,"Daily Spend":30507,"x":1695513600000,"y":30507,"fill":"#e6001a"},{"date_produced":"2023-09-25","party":"BS","spend":153687,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-25","Daily_Diff":4140,"Daily Spend":34647,"x":1695600000000,"y":34647,"fill":"#e6001a"},{"date_produced":"2023-09-26","party":"BS","spend":158167,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-26","Daily_Diff":4480,"Daily Spend":39127,"x":1695686400000,"y":39127,"fill":"#e6001a"},{"date_produced":"2023-09-27","party":"BS","spend":162241,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-27","Daily_Diff":4074,"Daily Spend":43201,"x":1695772800000,"y":43201,"fill":"#e6001a"},{"date_produced":"2023-09-28","party":"BS","spend":166309,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-28","Daily_Diff":4068,"Daily Spend":47269,"x":1695859200000,"y":47269,"fill":"#e6001a"},{"date_produced":"2023-09-29","party":"BS","spend":171077,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-29","Daily_Diff":4768,"Daily Spend":52037,"x":1695945600000,"y":52037,"fill":"#e6001a"},{"date_produced":"2023-09-30","party":"BS","spend":177481,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-30","Daily_Diff":6404,"Daily Spend":58441,"x":1696032000000,"y":58441,"fill":"#e6001a"}],"type":"area"},{"name":"LIB","data":[{"date_produced":"2023-08-31","party":"LIB","spend":424791,"total_spend":431261,"colors":"#ffd900","Date":"2023-08-31","Daily_Diff":780,"Daily Spend":1560,"x":1693440000000,"y":1560,"fill":"#ffd900"},{"date_produced":"2023-09-01","party":"LIB","spend":425481,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-01","Daily_Diff":690,"Daily Spend":2250,"x":1693526400000,"y":2250,"fill":"#ffd900"},{"date_produced":"2023-09-02","party":"LIB","spend":426279,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-02","Daily_Diff":798,"Daily Spend":3048,"x":1693612800000,"y":3048,"fill":"#ffd900"},{"date_produced":"2023-09-03","party":"LIB","spend":427180,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-03","Daily_Diff":901,"Daily Spend":3949,"x":1693699200000,"y":3949,"fill":"#ffd900"},{"date_produced":"2023-09-04","party":"LIB","spend":427954,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-04","Daily_Diff":774,"Daily Spend":4723,"x":1693785600000,"y":4723,"fill":"#ffd900"},{"date_produced":"2023-09-05","party":"LIB","spend":428612,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-05","Daily_Diff":658,"Daily Spend":5381,"x":1693872000000,"y":5381,"fill":"#ffd900"},{"date_produced":"2023-09-06","party":"LIB","spend":429201,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-06","Daily_Diff":589,"Daily Spend":5970,"x":1693958400000,"y":5970,"fill":"#ffd900"},{"date_produced":"2023-09-07","party":"LIB","spend":429530,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-07","Daily_Diff":329,"Daily Spend":6299,"x":1694044800000,"y":6299,"fill":"#ffd900"},{"date_produced":"2023-09-08","party":"LIB","spend":429599,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-08","Daily_Diff":69,"Daily Spend":6368,"x":1694131200000,"y":6368,"fill":"#ffd900"},{"date_produced":"2023-09-09","party":"LIB","spend":429675,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-09","Daily_Diff":76,"Daily Spend":6444,"x":1694217600000,"y":6444,"fill":"#ffd900"},{"date_produced":"2023-09-10","party":"LIB","spend":429761,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-10","Daily_Diff":86,"Daily Spend":6530,"x":1694304000000,"y":6530,"fill":"#ffd900"},{"date_produced":"2023-09-11","party":"LIB","spend":429840,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-11","Daily_Diff":79,"Daily Spend":6609,"x":1694390400000,"y":6609,"fill":"#ffd900"},{"date_produced":"2023-09-12","party":"LIB","spend":429918,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-12","Daily_Diff":78,"Daily Spend":6687,"x":1694476800000,"y":6687,"fill":"#ffd900"},{"date_produced":"2023-09-13","party":"LIB","spend":429995,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-13","Daily_Diff":77,"Daily Spend":6764,"x":1694563200000,"y":6764,"fill":"#ffd900"},{"date_produced":"2023-09-14","party":"LIB","spend":430070,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-14","Daily_Diff":75,"Daily Spend":6839,"x":1694649600000,"y":6839,"fill":"#ffd900"},{"date_produced":"2023-09-15","party":"LIB","spend":430143,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-15","Daily_Diff":73,"Daily Spend":6912,"x":1694736000000,"y":6912,"fill":"#ffd900"},{"date_produced":"2023-09-16","party":"LIB","spend":430220,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-16","Daily_Diff":77,"Daily Spend":6989,"x":1694822400000,"y":6989,"fill":"#ffd900"},{"date_produced":"2023-09-17","party":"LIB","spend":430312,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-17","Daily_Diff":92,"Daily Spend":7081,"x":1694908800000,"y":7081,"fill":"#ffd900"},{"date_produced":"2023-09-18","party":"LIB","spend":430401,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-18","Daily_Diff":89,"Daily Spend":7170,"x":1694995200000,"y":7170,"fill":"#ffd900"},{"date_produced":"2023-09-19","party":"LIB","spend":430498,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-19","Daily_Diff":97,"Daily Spend":7267,"x":1695081600000,"y":7267,"fill":"#ffd900"},{"date_produced":"2023-09-20","party":"LIB","spend":430582,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-20","Daily_Diff":84,"Daily Spend":7351,"x":1695168000000,"y":7351,"fill":"#ffd900"},{"date_produced":"2023-09-21","party":"LIB","spend":430666,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-21","Daily_Diff":84,"Daily Spend":7435,"x":1695254400000,"y":7435,"fill":"#ffd900"},{"date_produced":"2023-09-22","party":"LIB","spend":430735,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-22","Daily_Diff":69,"Daily Spend":7504,"x":1695340800000,"y":7504,"fill":"#ffd900"},{"date_produced":"2023-09-23","party":"LIB","spend":430799,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-23","Daily_Diff":64,"Daily Spend":7568,"x":1695427200000,"y":7568,"fill":"#ffd900"},{"date_produced":"2023-09-24","party":"LIB","spend":430870,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-24","Daily_Diff":71,"Daily Spend":7639,"x":1695513600000,"y":7639,"fill":"#ffd900"},{"date_produced":"2023-09-25","party":"LIB","spend":430937,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-25","Daily_Diff":67,"Daily Spend":7706,"x":1695600000000,"y":7706,"fill":"#ffd900"},{"date_produced":"2023-09-26","party":"LIB","spend":431004,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-26","Daily_Diff":67,"Daily Spend":7773,"x":1695686400000,"y":7773,"fill":"#ffd900"},{"date_produced":"2023-09-27","party":"LIB","spend":431071,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-27","Daily_Diff":67,"Daily Spend":7840,"x":1695772800000,"y":7840,"fill":"#ffd900"},{"date_produced":"2023-09-28","party":"LIB","spend":431134,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-28","Daily_Diff":63,"Daily Spend":7903,"x":1695859200000,"y":7903,"fill":"#ffd900"},{"date_produced":"2023-09-29","party":"LIB","spend":431196,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-29","Daily_Diff":62,"Daily Spend":7965,"x":1695945600000,"y":7965,"fill":"#ffd900"},{"date_produced":"2023-09-30","party":"LIB","spend":431261,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-30","Daily_Diff":65,"Daily Spend":8030,"x":1696032000000,"y":8030,"fill":"#ffd900"}],"type":"area"},{"name":"KWIN","data":[{"date_produced":"2023-08-31","party":"KWIN","spend":440998,"total_spend":501716,"colors":"#122746","Date":"2023-08-31","Daily_Diff":228,"Daily Spend":456,"x":1693440000000,"y":456,"fill":"#122746"},{"date_produced":"2023-09-01","party":"KWIN","spend":441599,"total_spend":501716,"colors":"#122746","Date":"2023-09-01","Daily_Diff":601,"Daily Spend":1057,"x":1693526400000,"y":1057,"fill":"#122746"},{"date_produced":"2023-09-02","party":"KWIN","spend":442193,"total_spend":501716,"colors":"#122746","Date":"2023-09-02","Daily_Diff":594,"Daily Spend":1651,"x":1693612800000,"y":1651,"fill":"#122746"},{"date_produced":"2023-09-03","party":"KWIN","spend":442390,"total_spend":501716,"colors":"#122746","Date":"2023-09-03","Daily_Diff":197,"Daily Spend":1848,"x":1693699200000,"y":1848,"fill":"#122746"},{"date_produced":"2023-09-04","party":"KWIN","spend":442647,"total_spend":501716,"colors":"#122746","Date":"2023-09-04","Daily_Diff":257,"Daily Spend":2105,"x":1693785600000,"y":2105,"fill":"#122746"},{"date_produced":"2023-09-05","party":"KWIN","spend":442969,"total_spend":501716,"colors":"#122746","Date":"2023-09-05","Daily_Diff":322,"Daily Spend":2427,"x":1693872000000,"y":2427,"fill":"#122746"},{"date_produced":"2023-09-06","party":"KWIN","spend":443963,"total_spend":501716,"colors":"#122746","Date":"2023-09-06","Daily_Diff":994,"Daily Spend":3421,"x":1693958400000,"y":3421,"fill":"#122746"},{"date_produced":"2023-09-07","party":"KWIN","spend":444891,"total_spend":501716,"colors":"#122746","Date":"2023-09-07","Daily_Diff":928,"Daily Spend":4349,"x":1694044800000,"y":4349,"fill":"#122746"},{"date_produced":"2023-09-08","party":"KWIN","spend":445420,"total_spend":501716,"colors":"#122746","Date":"2023-09-08","Daily_Diff":529,"Daily Spend":4878,"x":1694131200000,"y":4878,"fill":"#122746"},{"date_produced":"2023-09-09","party":"KWIN","spend":446474,"total_spend":501716,"colors":"#122746","Date":"2023-09-09","Daily_Diff":1054,"Daily Spend":5932,"x":1694217600000,"y":5932,"fill":"#122746"},{"date_produced":"2023-09-10","party":"KWIN","spend":447109,"total_spend":501716,"colors":"#122746","Date":"2023-09-10","Daily_Diff":635,"Daily Spend":6567,"x":1694304000000,"y":6567,"fill":"#122746"},{"date_produced":"2023-09-11","party":"KWIN","spend":447729,"total_spend":501716,"colors":"#122746","Date":"2023-09-11","Daily_Diff":620,"Daily Spend":7187,"x":1694390400000,"y":7187,"fill":"#122746"},{"date_produced":"2023-09-12","party":"KWIN","spend":447922,"total_spend":501716,"colors":"#122746","Date":"2023-09-12","Daily_Diff":193,"Daily Spend":7380,"x":1694476800000,"y":7380,"fill":"#122746"},{"date_produced":"2023-09-13","party":"KWIN","spend":448569,"total_spend":501716,"colors":"#122746","Date":"2023-09-13","Daily_Diff":647,"Daily Spend":8027,"x":1694563200000,"y":8027,"fill":"#122746"},{"date_produced":"2023-09-14","party":"KWIN","spend":449883,"total_spend":501716,"colors":"#122746","Date":"2023-09-14","Daily_Diff":1314,"Daily Spend":9341,"x":1694649600000,"y":9341,"fill":"#122746"},{"date_produced":"2023-09-15","party":"KWIN","spend":451296,"total_spend":501716,"colors":"#122746","Date":"2023-09-15","Daily_Diff":1413,"Daily Spend":10754,"x":1694736000000,"y":10754,"fill":"#122746"},{"date_produced":"2023-09-16","party":"KWIN","spend":452749,"total_spend":501716,"colors":"#122746","Date":"2023-09-16","Daily_Diff":1453,"Daily Spend":12207,"x":1694822400000,"y":12207,"fill":"#122746"},{"date_produced":"2023-09-17","party":"KWIN","spend":454931,"total_spend":501716,"colors":"#122746","Date":"2023-09-17","Daily_Diff":2182,"Daily Spend":14389,"x":1694908800000,"y":14389,"fill":"#122746"},{"date_produced":"2023-09-18","party":"KWIN","spend":458491,"total_spend":501716,"colors":"#122746","Date":"2023-09-18","Daily_Diff":3560,"Daily Spend":17949,"x":1694995200000,"y":17949,"fill":"#122746"},{"date_produced":"2023-09-19","party":"KWIN","spend":461951,"total_spend":501716,"colors":"#122746","Date":"2023-09-19","Daily_Diff":3460,"Daily Spend":21409,"x":1695081600000,"y":21409,"fill":"#122746"},{"date_produced":"2023-09-20","party":"KWIN","spend":465261,"total_spend":501716,"colors":"#122746","Date":"2023-09-20","Daily_Diff":3310,"Daily Spend":24719,"x":1695168000000,"y":24719,"fill":"#122746"},{"date_produced":"2023-09-21","party":"KWIN","spend":468535,"total_spend":501716,"colors":"#122746","Date":"2023-09-21","Daily_Diff":3274,"Daily Spend":27993,"x":1695254400000,"y":27993,"fill":"#122746"},{"date_produced":"2023-09-22","party":"KWIN","spend":472242,"total_spend":501716,"colors":"#122746","Date":"2023-09-22","Daily_Diff":3707,"Daily Spend":31700,"x":1695340800000,"y":31700,"fill":"#122746"},{"date_produced":"2023-09-23","party":"KWIN","spend":477337,"total_spend":501716,"colors":"#122746","Date":"2023-09-23","Daily_Diff":5095,"Daily Spend":36795,"x":1695427200000,"y":36795,"fill":"#122746"},{"date_produced":"2023-09-24","party":"KWIN","spend":482327,"total_spend":501716,"colors":"#122746","Date":"2023-09-24","Daily_Diff":4990,"Daily Spend":41785,"x":1695513600000,"y":41785,"fill":"#122746"},{"date_produced":"2023-09-25","party":"KWIN","spend":486077,"total_spend":501716,"colors":"#122746","Date":"2023-09-25","Daily_Diff":3750,"Daily Spend":45535,"x":1695600000000,"y":45535,"fill":"#122746"},{"date_produced":"2023-09-26","party":"KWIN","spend":489928,"total_spend":501716,"colors":"#122746","Date":"2023-09-26","Daily_Diff":3851,"Daily Spend":49386,"x":1695686400000,"y":49386,"fill":"#122746"},{"date_produced":"2023-09-27","party":"KWIN","spend":493814,"total_spend":501716,"colors":"#122746","Date":"2023-09-27","Daily_Diff":3886,"Daily Spend":53272,"x":1695772800000,"y":53272,"fill":"#122746"},{"date_produced":"2023-09-28","party":"KWIN","spend":496736,"total_spend":501716,"colors":"#122746","Date":"2023-09-28","Daily_Diff":2922,"Daily Spend":56194,"x":1695859200000,"y":56194,"fill":"#122746"},{"date_produced":"2023-09-29","party":"KWIN","spend":499417,"total_spend":501716,"colors":"#122746","Date":"2023-09-29","Daily_Diff":2681,"Daily Spend":58875,"x":1695945600000,"y":58875,"fill":"#122746"},{"date_produced":"2023-09-30","party":"KWIN","spend":501716,"total_spend":501716,"colors":"#122746","Date":"2023-09-30","Daily_Diff":2299,"Daily Spend":61174,"x":1696032000000,"y":61174,"fill":"#122746"}],"type":"area"},{"name":"LEW","data":[{"date_produced":"2023-08-31","party":"LEW","spend":659011,"total_spend":996334,"colors":"#851a64","Date":"2023-08-31","Daily_Diff":1314,"Daily Spend":2628,"x":1693440000000,"y":2628,"fill":"#851a64"},{"date_produced":"2023-09-01","party":"LEW","spend":660622,"total_spend":996334,"colors":"#851a64","Date":"2023-09-01","Daily_Diff":1611,"Daily Spend":4239,"x":1693526400000,"y":4239,"fill":"#851a64"},{"date_produced":"2023-09-02","party":"LEW","spend":661895,"total_spend":996334,"colors":"#851a64","Date":"2023-09-02","Daily_Diff":1273,"Daily Spend":5512,"x":1693612800000,"y":5512,"fill":"#851a64"},{"date_produced":"2023-09-03","party":"LEW","spend":663135,"total_spend":996334,"colors":"#851a64","Date":"2023-09-03","Daily_Diff":1240,"Daily Spend":6752,"x":1693699200000,"y":6752,"fill":"#851a64"},{"date_produced":"2023-09-04","party":"LEW","spend":664421,"total_spend":996334,"colors":"#851a64","Date":"2023-09-04","Daily_Diff":1286,"Daily Spend":8038,"x":1693785600000,"y":8038,"fill":"#851a64"},{"date_produced":"2023-09-05","party":"LEW","spend":665931,"total_spend":996334,"colors":"#851a64","Date":"2023-09-05","Daily_Diff":1510,"Daily Spend":9548,"x":1693872000000,"y":9548,"fill":"#851a64"},{"date_produced":"2023-09-06","party":"LEW","spend":668005,"total_spend":996334,"colors":"#851a64","Date":"2023-09-06","Daily_Diff":2074,"Daily Spend":11622,"x":1693958400000,"y":11622,"fill":"#851a64"},{"date_produced":"2023-09-07","party":"LEW","spend":670431,"total_spend":996334,"colors":"#851a64","Date":"2023-09-07","Daily_Diff":2426,"Daily Spend":14048,"x":1694044800000,"y":14048,"fill":"#851a64"},{"date_produced":"2023-09-08","party":"LEW","spend":673692,"total_spend":996334,"colors":"#851a64","Date":"2023-09-08","Daily_Diff":3261,"Daily Spend":17309,"x":1694131200000,"y":17309,"fill":"#851a64"},{"date_produced":"2023-09-09","party":"LEW","spend":677688,"total_spend":996334,"colors":"#851a64","Date":"2023-09-09","Daily_Diff":3996,"Daily Spend":21305,"x":1694217600000,"y":21305,"fill":"#851a64"},{"date_produced":"2023-09-10","party":"LEW","spend":684134,"total_spend":996334,"colors":"#851a64","Date":"2023-09-10","Daily_Diff":6446,"Daily Spend":27751,"x":1694304000000,"y":27751,"fill":"#851a64"},{"date_produced":"2023-09-11","party":"LEW","spend":691032,"total_spend":996334,"colors":"#851a64","Date":"2023-09-11","Daily_Diff":6898,"Daily Spend":34649,"x":1694390400000,"y":34649,"fill":"#851a64"},{"date_produced":"2023-09-12","party":"LEW","spend":698556,"total_spend":996334,"colors":"#851a64","Date":"2023-09-12","Daily_Diff":7524,"Daily Spend":42173,"x":1694476800000,"y":42173,"fill":"#851a64"},{"date_produced":"2023-09-13","party":"LEW","spend":707824,"total_spend":996334,"colors":"#851a64","Date":"2023-09-13","Daily_Diff":9268,"Daily Spend":51441,"x":1694563200000,"y":51441,"fill":"#851a64"},{"date_produced":"2023-09-14","party":"LEW","spend":719854,"total_spend":996334,"colors":"#851a64","Date":"2023-09-14","Daily_Diff":12030,"Daily Spend":63471,"x":1694649600000,"y":63471,"fill":"#851a64"},{"date_produced":"2023-09-15","party":"LEW","spend":731859,"total_spend":996334,"colors":"#851a64","Date":"2023-09-15","Daily_Diff":12005,"Daily Spend":75476,"x":1694736000000,"y":75476,"fill":"#851a64"},{"date_produced":"2023-09-16","party":"LEW","spend":744041,"total_spend":996334,"colors":"#851a64","Date":"2023-09-16","Daily_Diff":12182,"Daily Spend":87658,"x":1694822400000,"y":87658,"fill":"#851a64"},{"date_produced":"2023-09-17","party":"LEW","spend":756772,"total_spend":996334,"colors":"#851a64","Date":"2023-09-17","Daily_Diff":12731,"Daily Spend":100389,"x":1694908800000,"y":100389,"fill":"#851a64"},{"date_produced":"2023-09-18","party":"LEW","spend":769557,"total_spend":996334,"colors":"#851a64","Date":"2023-09-18","Daily_Diff":12785,"Daily Spend":113174,"x":1694995200000,"y":113174,"fill":"#851a64"},{"date_produced":"2023-09-19","party":"LEW","spend":782428,"total_spend":996334,"colors":"#851a64","Date":"2023-09-19","Daily_Diff":12871,"Daily Spend":126045,"x":1695081600000,"y":126045,"fill":"#851a64"},{"date_produced":"2023-09-20","party":"LEW","spend":798900,"total_spend":996334,"colors":"#851a64","Date":"2023-09-20","Daily_Diff":16472,"Daily Spend":142517,"x":1695168000000,"y":142517,"fill":"#851a64"},{"date_produced":"2023-09-21","party":"LEW","spend":816446,"total_spend":996334,"colors":"#851a64","Date":"2023-09-21","Daily_Diff":17546,"Daily Spend":160063,"x":1695254400000,"y":160063,"fill":"#851a64"},{"date_produced":"2023-09-22","party":"LEW","spend":834010,"total_spend":996334,"colors":"#851a64","Date":"2023-09-22","Daily_Diff":17564,"Daily Spend":177627,"x":1695340800000,"y":177627,"fill":"#851a64"},{"date_produced":"2023-09-23","party":"LEW","spend":851701,"total_spend":996334,"colors":"#851a64","Date":"2023-09-23","Daily_Diff":17691,"Daily Spend":195318,"x":1695427200000,"y":195318,"fill":"#851a64"},{"date_produced":"2023-09-24","party":"LEW","spend":869607,"total_spend":996334,"colors":"#851a64","Date":"2023-09-24","Daily_Diff":17906,"Daily Spend":213224,"x":1695513600000,"y":213224,"fill":"#851a64"},{"date_produced":"2023-09-25","party":"LEW","spend":886865,"total_spend":996334,"colors":"#851a64","Date":"2023-09-25","Daily_Diff":17258,"Daily Spend":230482,"x":1695600000000,"y":230482,"fill":"#851a64"},{"date_produced":"2023-09-26","party":"LEW","spend":904838,"total_spend":996334,"colors":"#851a64","Date":"2023-09-26","Daily_Diff":17973,"Daily Spend":248455,"x":1695686400000,"y":248455,"fill":"#851a64"},{"date_produced":"2023-09-27","party":"LEW","spend":923429,"total_spend":996334,"colors":"#851a64","Date":"2023-09-27","Daily_Diff":18591,"Daily Spend":267046,"x":1695772800000,"y":267046,"fill":"#851a64"},{"date_produced":"2023-09-28","party":"LEW","spend":945711,"total_spend":996334,"colors":"#851a64","Date":"2023-09-28","Daily_Diff":22282,"Daily Spend":289328,"x":1695859200000,"y":289328,"fill":"#851a64"},{"date_produced":"2023-09-29","party":"LEW","spend":968248,"total_spend":996334,"colors":"#851a64","Date":"2023-09-29","Daily_Diff":22537,"Daily Spend":311865,"x":1695945600000,"y":311865,"fill":"#851a64"},{"date_produced":"2023-09-30","party":"LEW","spend":996334,"total_spend":996334,"colors":"#851a64","Date":"2023-09-30","Daily_Diff":28086,"Daily Spend":339951,"x":1696032000000,"y":339951,"fill":"#851a64"}],"type":"area"},{"name":"TD","data":[{"date_produced":"2023-08-31","party":"TD","spend":995112,"total_spend":1317825,"colors":"#3db53a","Date":"2023-08-31","Daily_Diff":1407,"Daily Spend":2814,"x":1693440000000,"y":2814,"fill":"#3db53a"},{"date_produced":"2023-09-01","party":"TD","spend":995863,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-01","Daily_Diff":751,"Daily Spend":3565,"x":1693526400000,"y":3565,"fill":"#3db53a"},{"date_produced":"2023-09-02","party":"TD","spend":996908,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-02","Daily_Diff":1045,"Daily Spend":4610,"x":1693612800000,"y":4610,"fill":"#3db53a"},{"date_produced":"2023-09-03","party":"TD","spend":999040,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-03","Daily_Diff":2132,"Daily Spend":6742,"x":1693699200000,"y":6742,"fill":"#3db53a"},{"date_produced":"2023-09-04","party":"TD","spend":1000994,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-04","Daily_Diff":1954,"Daily Spend":8696,"x":1693785600000,"y":8696,"fill":"#3db53a"},{"date_produced":"2023-09-05","party":"TD","spend":1003103,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-05","Daily_Diff":2109,"Daily Spend":10805,"x":1693872000000,"y":10805,"fill":"#3db53a"},{"date_produced":"2023-09-06","party":"TD","spend":1005525,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-06","Daily_Diff":2422,"Daily Spend":13227,"x":1693958400000,"y":13227,"fill":"#3db53a"},{"date_produced":"2023-09-07","party":"TD","spend":1007761,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-07","Daily_Diff":2236,"Daily Spend":15463,"x":1694044800000,"y":15463,"fill":"#3db53a"},{"date_produced":"2023-09-08","party":"TD","spend":1010861,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-08","Daily_Diff":3100,"Daily Spend":18563,"x":1694131200000,"y":18563,"fill":"#3db53a"},{"date_produced":"2023-09-09","party":"TD","spend":1014863,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-09","Daily_Diff":4002,"Daily Spend":22565,"x":1694217600000,"y":22565,"fill":"#3db53a"},{"date_produced":"2023-09-10","party":"TD","spend":1020674,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-10","Daily_Diff":5811,"Daily Spend":28376,"x":1694304000000,"y":28376,"fill":"#3db53a"},{"date_produced":"2023-09-11","party":"TD","spend":1026466,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-11","Daily_Diff":5792,"Daily Spend":34168,"x":1694390400000,"y":34168,"fill":"#3db53a"},{"date_produced":"2023-09-12","party":"TD","spend":1036098,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-12","Daily_Diff":9632,"Daily Spend":43800,"x":1694476800000,"y":43800,"fill":"#3db53a"},{"date_produced":"2023-09-13","party":"TD","spend":1045240,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-13","Daily_Diff":9142,"Daily Spend":52942,"x":1694563200000,"y":52942,"fill":"#3db53a"},{"date_produced":"2023-09-14","party":"TD","spend":1057602,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-14","Daily_Diff":12362,"Daily Spend":65304,"x":1694649600000,"y":65304,"fill":"#3db53a"},{"date_produced":"2023-09-15","party":"TD","spend":1071808,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-15","Daily_Diff":14206,"Daily Spend":79510,"x":1694736000000,"y":79510,"fill":"#3db53a"},{"date_produced":"2023-09-16","party":"TD","spend":1086385,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-16","Daily_Diff":14577,"Daily Spend":94087,"x":1694822400000,"y":94087,"fill":"#3db53a"},{"date_produced":"2023-09-17","party":"TD","spend":1102731,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-17","Daily_Diff":16346,"Daily Spend":110433,"x":1694908800000,"y":110433,"fill":"#3db53a"},{"date_produced":"2023-09-18","party":"TD","spend":1112527,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-18","Daily_Diff":9796,"Daily Spend":120229,"x":1694995200000,"y":120229,"fill":"#3db53a"},{"date_produced":"2023-09-19","party":"TD","spend":1125041,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-19","Daily_Diff":12514,"Daily Spend":132743,"x":1695081600000,"y":132743,"fill":"#3db53a"},{"date_produced":"2023-09-20","party":"TD","spend":1137904,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-20","Daily_Diff":12863,"Daily Spend":145606,"x":1695168000000,"y":145606,"fill":"#3db53a"},{"date_produced":"2023-09-21","party":"TD","spend":1152425,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-21","Daily_Diff":14521,"Daily Spend":160127,"x":1695254400000,"y":160127,"fill":"#3db53a"},{"date_produced":"2023-09-22","party":"TD","spend":1167291,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-22","Daily_Diff":14866,"Daily Spend":174993,"x":1695340800000,"y":174993,"fill":"#3db53a"},{"date_produced":"2023-09-23","party":"TD","spend":1184077,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-23","Daily_Diff":16786,"Daily Spend":191779,"x":1695427200000,"y":191779,"fill":"#3db53a"},{"date_produced":"2023-09-24","party":"TD","spend":1200616,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-24","Daily_Diff":16539,"Daily Spend":208318,"x":1695513600000,"y":208318,"fill":"#3db53a"},{"date_produced":"2023-09-25","party":"TD","spend":1215202,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-25","Daily_Diff":14586,"Daily Spend":222904,"x":1695600000000,"y":222904,"fill":"#3db53a"},{"date_produced":"2023-09-26","party":"TD","spend":1231881,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-26","Daily_Diff":16679,"Daily Spend":239583,"x":1695686400000,"y":239583,"fill":"#3db53a"},{"date_produced":"2023-09-27","party":"TD","spend":1249586,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-27","Daily_Diff":17705,"Daily Spend":257288,"x":1695772800000,"y":257288,"fill":"#3db53a"},{"date_produced":"2023-09-28","party":"TD","spend":1271742,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-28","Daily_Diff":22156,"Daily Spend":279444,"x":1695859200000,"y":279444,"fill":"#3db53a"},{"date_produced":"2023-09-29","party":"TD","spend":1292142,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-29","Daily_Diff":20400,"Daily Spend":299844,"x":1695945600000,"y":299844,"fill":"#3db53a"},{"date_produced":"2023-09-30","party":"TD","spend":1317825,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-30","Daily_Diff":25683,"Daily Spend":325527,"x":1696032000000,"y":325527,"fill":"#3db53a"}],"type":"area"},{"name":"ZP","data":[{"date_produced":"2023-08-31","party":"ZP","spend":2699853,"total_spend":3623296,"colors":"#263778","Date":"2023-08-31","Daily_Diff":17220,"Daily Spend":34440,"x":1693440000000,"y":34440,"fill":"#263778"},{"date_produced":"2023-09-01","party":"ZP","spend":2716188,"total_spend":3623296,"colors":"#263778","Date":"2023-09-01","Daily_Diff":16335,"Daily Spend":50775,"x":1693526400000,"y":50775,"fill":"#263778"},{"date_produced":"2023-09-02","party":"ZP","spend":2733671,"total_spend":3623296,"colors":"#263778","Date":"2023-09-02","Daily_Diff":17483,"Daily Spend":68258,"x":1693612800000,"y":68258,"fill":"#263778"},{"date_produced":"2023-09-03","party":"ZP","spend":2750868,"total_spend":3623296,"colors":"#263778","Date":"2023-09-03","Daily_Diff":17197,"Daily Spend":85455,"x":1693699200000,"y":85455,"fill":"#263778"},{"date_produced":"2023-09-04","party":"ZP","spend":2765899,"total_spend":3623296,"colors":"#263778","Date":"2023-09-04","Daily_Diff":15031,"Daily Spend":100486,"x":1693785600000,"y":100486,"fill":"#263778"},{"date_produced":"2023-09-05","party":"ZP","spend":2781913,"total_spend":3623296,"colors":"#263778","Date":"2023-09-05","Daily_Diff":16014,"Daily Spend":116500,"x":1693872000000,"y":116500,"fill":"#263778"},{"date_produced":"2023-09-06","party":"ZP","spend":2797814,"total_spend":3623296,"colors":"#263778","Date":"2023-09-06","Daily_Diff":15901,"Daily Spend":132401,"x":1693958400000,"y":132401,"fill":"#263778"},{"date_produced":"2023-09-07","party":"ZP","spend":2813932,"total_spend":3623296,"colors":"#263778","Date":"2023-09-07","Daily_Diff":16118,"Daily Spend":148519,"x":1694044800000,"y":148519,"fill":"#263778"},{"date_produced":"2023-09-08","party":"ZP","spend":2828967,"total_spend":3623296,"colors":"#263778","Date":"2023-09-08","Daily_Diff":15035,"Daily Spend":163554,"x":1694131200000,"y":163554,"fill":"#263778"},{"date_produced":"2023-09-09","party":"ZP","spend":2847756,"total_spend":3623296,"colors":"#263778","Date":"2023-09-09","Daily_Diff":18789,"Daily Spend":182343,"x":1694217600000,"y":182343,"fill":"#263778"},{"date_produced":"2023-09-10","party":"ZP","spend":2904668,"total_spend":3623296,"colors":"#263778","Date":"2023-09-10","Daily_Diff":56912,"Daily Spend":239255,"x":1694304000000,"y":239255,"fill":"#263778"},{"date_produced":"2023-09-11","party":"ZP","spend":2936738,"total_spend":3623296,"colors":"#263778","Date":"2023-09-11","Daily_Diff":32070,"Daily Spend":271325,"x":1694390400000,"y":271325,"fill":"#263778"},{"date_produced":"2023-09-12","party":"ZP","spend":2957740,"total_spend":3623296,"colors":"#263778","Date":"2023-09-12","Daily_Diff":21002,"Daily Spend":292327,"x":1694476800000,"y":292327,"fill":"#263778"},{"date_produced":"2023-09-13","party":"ZP","spend":2976869,"total_spend":3623296,"colors":"#263778","Date":"2023-09-13","Daily_Diff":19129,"Daily Spend":311456,"x":1694563200000,"y":311456,"fill":"#263778"},{"date_produced":"2023-09-14","party":"ZP","spend":3005210,"total_spend":3623296,"colors":"#263778","Date":"2023-09-14","Daily_Diff":28341,"Daily Spend":339797,"x":1694649600000,"y":339797,"fill":"#263778"},{"date_produced":"2023-09-15","party":"ZP","spend":3031351,"total_spend":3623296,"colors":"#263778","Date":"2023-09-15","Daily_Diff":26141,"Daily Spend":365938,"x":1694736000000,"y":365938,"fill":"#263778"},{"date_produced":"2023-09-16","party":"ZP","spend":3057334,"total_spend":3623296,"colors":"#263778","Date":"2023-09-16","Daily_Diff":25983,"Daily Spend":391921,"x":1694822400000,"y":391921,"fill":"#263778"},{"date_produced":"2023-09-17","party":"ZP","spend":3099697,"total_spend":3623296,"colors":"#263778","Date":"2023-09-17","Daily_Diff":42363,"Daily Spend":434284,"x":1694908800000,"y":434284,"fill":"#263778"},{"date_produced":"2023-09-18","party":"ZP","spend":3130372,"total_spend":3623296,"colors":"#263778","Date":"2023-09-18","Daily_Diff":30675,"Daily Spend":464959,"x":1694995200000,"y":464959,"fill":"#263778"},{"date_produced":"2023-09-19","party":"ZP","spend":3164610,"total_spend":3623296,"colors":"#263778","Date":"2023-09-19","Daily_Diff":34238,"Daily Spend":499197,"x":1695081600000,"y":499197,"fill":"#263778"},{"date_produced":"2023-09-20","party":"ZP","spend":3204143,"total_spend":3623296,"colors":"#263778","Date":"2023-09-20","Daily_Diff":39533,"Daily Spend":538730,"x":1695168000000,"y":538730,"fill":"#263778"},{"date_produced":"2023-09-21","party":"ZP","spend":3244566,"total_spend":3623296,"colors":"#263778","Date":"2023-09-21","Daily_Diff":40423,"Daily Spend":579153,"x":1695254400000,"y":579153,"fill":"#263778"},{"date_produced":"2023-09-22","party":"ZP","spend":3287368,"total_spend":3623296,"colors":"#263778","Date":"2023-09-22","Daily_Diff":42802,"Daily Spend":621955,"x":1695340800000,"y":621955,"fill":"#263778"},{"date_produced":"2023-09-23","party":"ZP","spend":3324710,"total_spend":3623296,"colors":"#263778","Date":"2023-09-23","Daily_Diff":37342,"Daily Spend":659297,"x":1695427200000,"y":659297,"fill":"#263778"},{"date_produced":"2023-09-24","party":"ZP","spend":3364489,"total_spend":3623296,"colors":"#263778","Date":"2023-09-24","Daily_Diff":39779,"Daily Spend":699076,"x":1695513600000,"y":699076,"fill":"#263778"},{"date_produced":"2023-09-25","party":"ZP","spend":3403564,"total_spend":3623296,"colors":"#263778","Date":"2023-09-25","Daily_Diff":39075,"Daily Spend":738151,"x":1695600000000,"y":738151,"fill":"#263778"},{"date_produced":"2023-09-26","party":"ZP","spend":3444898,"total_spend":3623296,"colors":"#263778","Date":"2023-09-26","Daily_Diff":41334,"Daily Spend":779485,"x":1695686400000,"y":779485,"fill":"#263778"},{"date_produced":"2023-09-27","party":"ZP","spend":3485830,"total_spend":3623296,"colors":"#263778","Date":"2023-09-27","Daily_Diff":40932,"Daily Spend":820417,"x":1695772800000,"y":820417,"fill":"#263778"},{"date_produced":"2023-09-28","party":"ZP","spend":3526634,"total_spend":3623296,"colors":"#263778","Date":"2023-09-28","Daily_Diff":40804,"Daily Spend":861221,"x":1695859200000,"y":861221,"fill":"#263778"},{"date_produced":"2023-09-29","party":"ZP","spend":3569761,"total_spend":3623296,"colors":"#263778","Date":"2023-09-29","Daily_Diff":43127,"Daily Spend":904348,"x":1695945600000,"y":904348,"fill":"#263778"},{"date_produced":"2023-09-30","party":"ZP","spend":3623296,"total_spend":3623296,"colors":"#263778","Date":"2023-09-30","Daily_Diff":53535,"Daily Spend":957883,"x":1696032000000,"y":957883,"fill":"#263778"}],"type":"area"},{"name":"KO","data":[{"date_produced":"2023-08-31","party":"KO","spend":3779758,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-08-31","Daily_Diff":7773,"Daily Spend":15546,"x":1693440000000,"y":15546,"fill":"#f68f2d"},{"date_produced":"2023-09-01","party":"KO","spend":3787592,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-01","Daily_Diff":7834,"Daily Spend":23380,"x":1693526400000,"y":23380,"fill":"#f68f2d"},{"date_produced":"2023-09-02","party":"KO","spend":3797609,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-02","Daily_Diff":10017,"Daily Spend":33397,"x":1693612800000,"y":33397,"fill":"#f68f2d"},{"date_produced":"2023-09-03","party":"KO","spend":3809315,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-03","Daily_Diff":11706,"Daily Spend":45103,"x":1693699200000,"y":45103,"fill":"#f68f2d"},{"date_produced":"2023-09-04","party":"KO","spend":3820429,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-04","Daily_Diff":11114,"Daily Spend":56217,"x":1693785600000,"y":56217,"fill":"#f68f2d"},{"date_produced":"2023-09-05","party":"KO","spend":3832529,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-05","Daily_Diff":12100,"Daily Spend":68317,"x":1693872000000,"y":68317,"fill":"#f68f2d"},{"date_produced":"2023-09-06","party":"KO","spend":3848389,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-06","Daily_Diff":15860,"Daily Spend":84177,"x":1693958400000,"y":84177,"fill":"#f68f2d"},{"date_produced":"2023-09-07","party":"KO","spend":3870804,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-07","Daily_Diff":22415,"Daily Spend":106592,"x":1694044800000,"y":106592,"fill":"#f68f2d"},{"date_produced":"2023-09-08","party":"KO","spend":3899086,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-08","Daily_Diff":28282,"Daily Spend":134874,"x":1694131200000,"y":134874,"fill":"#f68f2d"},{"date_produced":"2023-09-09","party":"KO","spend":3935721,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-09","Daily_Diff":36635,"Daily Spend":171509,"x":1694217600000,"y":171509,"fill":"#f68f2d"},{"date_produced":"2023-09-10","party":"KO","spend":3960969,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-10","Daily_Diff":25248,"Daily Spend":196757,"x":1694304000000,"y":196757,"fill":"#f68f2d"},{"date_produced":"2023-09-11","party":"KO","spend":4007548,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-11","Daily_Diff":46579,"Daily Spend":243336,"x":1694390400000,"y":243336,"fill":"#f68f2d"},{"date_produced":"2023-09-12","party":"KO","spend":4064063,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-12","Daily_Diff":56515,"Daily Spend":299851,"x":1694476800000,"y":299851,"fill":"#f68f2d"},{"date_produced":"2023-09-13","party":"KO","spend":4091221,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-13","Daily_Diff":27158,"Daily Spend":327009,"x":1694563200000,"y":327009,"fill":"#f68f2d"},{"date_produced":"2023-09-14","party":"KO","spend":4108923,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-14","Daily_Diff":17702,"Daily Spend":344711,"x":1694649600000,"y":344711,"fill":"#f68f2d"},{"date_produced":"2023-09-15","party":"KO","spend":4146178,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-15","Daily_Diff":37255,"Daily Spend":381966,"x":1694736000000,"y":381966,"fill":"#f68f2d"},{"date_produced":"2023-09-16","party":"KO","spend":4193090,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-16","Daily_Diff":46912,"Daily Spend":428878,"x":1694822400000,"y":428878,"fill":"#f68f2d"},{"date_produced":"2023-09-17","party":"KO","spend":4245037,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-17","Daily_Diff":51947,"Daily Spend":480825,"x":1694908800000,"y":480825,"fill":"#f68f2d"},{"date_produced":"2023-09-18","party":"KO","spend":4267848,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-18","Daily_Diff":22811,"Daily Spend":503636,"x":1694995200000,"y":503636,"fill":"#f68f2d"},{"date_produced":"2023-09-19","party":"KO","spend":4298801,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-19","Daily_Diff":30953,"Daily Spend":534589,"x":1695081600000,"y":534589,"fill":"#f68f2d"},{"date_produced":"2023-09-20","party":"KO","spend":4332691,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-20","Daily_Diff":33890,"Daily Spend":568479,"x":1695168000000,"y":568479,"fill":"#f68f2d"},{"date_produced":"2023-09-21","party":"KO","spend":4364023,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-21","Daily_Diff":31332,"Daily Spend":599811,"x":1695254400000,"y":599811,"fill":"#f68f2d"},{"date_produced":"2023-09-22","party":"KO","spend":4396097,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-22","Daily_Diff":32074,"Daily Spend":631885,"x":1695340800000,"y":631885,"fill":"#f68f2d"},{"date_produced":"2023-09-23","party":"KO","spend":4426724,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-23","Daily_Diff":30627,"Daily Spend":662512,"x":1695427200000,"y":662512,"fill":"#f68f2d"},{"date_produced":"2023-09-24","party":"KO","spend":4459900,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-24","Daily_Diff":33176,"Daily Spend":695688,"x":1695513600000,"y":695688,"fill":"#f68f2d"},{"date_produced":"2023-09-25","party":"KO","spend":4488640,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-25","Daily_Diff":28740,"Daily Spend":724428,"x":1695600000000,"y":724428,"fill":"#f68f2d"},{"date_produced":"2023-09-26","party":"KO","spend":4517969,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-26","Daily_Diff":29329,"Daily Spend":753757,"x":1695686400000,"y":753757,"fill":"#f68f2d"},{"date_produced":"2023-09-27","party":"KO","spend":4558151,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-27","Daily_Diff":40182,"Daily Spend":793939,"x":1695772800000,"y":793939,"fill":"#f68f2d"},{"date_produced":"2023-09-28","party":"KO","spend":4616145,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-28","Daily_Diff":57994,"Daily Spend":851933,"x":1695859200000,"y":851933,"fill":"#f68f2d"},{"date_produced":"2023-09-29","party":"KO","spend":4685722,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-29","Daily_Diff":69577,"Daily Spend":921510,"x":1695945600000,"y":921510,"fill":"#f68f2d"},{"date_produced":"2023-09-30","party":"KO","spend":4740486,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-30","Daily_Diff":54764,"Daily Spend":976274,"x":1696032000000,"y":976274,"fill":"#f68f2d"}],"type":"area"}],"xAxis":{"type":"datetime","title":{"text":"Date"},"categories":null},"colors":["#e6001a","#ffd900","#122746","#851a64","#3db53a","#263778","#f68f2d"],"tooltip":{"shared":true,"positioner":"function (labelWidth, labelHeight, point) {\n        return { x: 200, y: this.chart.plotTop };\n    }"}},"theme":{"chart":{"backgroundColor":"transparent"},"colors":["#7cb5ec","#434348","#90ed7d","#f7a35c","#8085e9","#f15c80","#e4d354","#2b908f","#f45b5b","#91e8e1"]},"conf_opts":{"global":{"Date":null,"VMLRadialGradientURL":"http =//code.highcharts.com/list(version)/gfx/vml-radial-gradient.png","canvasToolsURL":"http =//code.highcharts.com/list(version)/modules/canvas-tools.js","getTimezoneOffset":null,"timezoneOffset":0,"useUTC":true},"lang":{"contextButtonTitle":"Chart context menu","decimalPoint":".","downloadCSV":"Download CSV","downloadJPEG":"Download JPEG image","downloadPDF":"Download PDF document","downloadPNG":"Download PNG image","downloadSVG":"Download SVG vector image","downloadXLS":"Download XLS","drillUpText":"◁ Back to {series.name}","exitFullscreen":"Exit from full screen","exportData":{"annotationHeader":"Annotations","categoryDatetimeHeader":"DateTime","categoryHeader":"Category"},"hideData":"Hide data table","invalidDate":null,"loading":"Loading...","months":["January","February","March","April","May","June","July","August","September","October","November","December"],"noData":"No data to display","numericSymbolMagnitude":1000,"numericSymbols":["k","M","G","T","P","E"],"printChart":"Print chart","resetZoom":"Reset zoom","resetZoomTitle":"Reset zoom level 1:1","shortMonths":["Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"],"shortWeekdays":["Sat","Sun","Mon","Tue","Wed","Thu","Fri"],"thousandsSep":" ","viewData":"View data table","viewFullscreen":"View in full screen","weekdays":["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday"]}},"type":"chart","fonts":[],"debug":false},"evals":["hc_opts.tooltip.positioner"],"jsHooks":[]}</script>
```
:::
:::




### Daily




::: {.cell}
::: {.cell-output-display}
```{=html}
<div class="highchart html-widget html-fill-item-overflow-hidden html-fill-item" id="htmlwidget-92bc795d690144569ca4" style="width:100%;height:480px;"></div>
<script type="application/json" data-for="htmlwidget-92bc795d690144569ca4">{"x":{"hc_opts":{"chart":{"reflow":true},"title":{"text":null},"yAxis":{"title":{"text":"Daily Spend"},"type":"linear"},"credits":{"enabled":false},"exporting":{"enabled":false},"boost":{"enabled":false},"plotOptions":{"series":{"label":{"enabled":false},"turboThreshold":0,"showInLegend":true},"treemap":{"layoutAlgorithm":"squarified"},"scatter":{"marker":{"symbol":"circle"}},"area":{"stacking":"normal","lineWidth":1,"marker":{"enabled":false}}},"series":[{"name":"BS","data":[{"date_produced":"2023-08-31","party":"BS","spend":119330,"total_spend":177481,"colors":"#e6001a","Date":"2023-08-31","Daily Spend":145,"x":1693440000000,"y":145,"fill":"#e6001a"},{"date_produced":"2023-09-01","party":"BS","spend":119457,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-01","Daily Spend":127,"x":1693526400000,"y":127,"fill":"#e6001a"},{"date_produced":"2023-09-02","party":"BS","spend":119584,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-02","Daily Spend":127,"x":1693612800000,"y":127,"fill":"#e6001a"},{"date_produced":"2023-09-03","party":"BS","spend":119699,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-03","Daily Spend":115,"x":1693699200000,"y":115,"fill":"#e6001a"},{"date_produced":"2023-09-04","party":"BS","spend":119820,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-04","Daily Spend":121,"x":1693785600000,"y":121,"fill":"#e6001a"},{"date_produced":"2023-09-05","party":"BS","spend":120253,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-05","Daily Spend":433,"x":1693872000000,"y":433,"fill":"#e6001a"},{"date_produced":"2023-09-06","party":"BS","spend":120618,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-06","Daily Spend":365,"x":1693958400000,"y":365,"fill":"#e6001a"},{"date_produced":"2023-09-07","party":"BS","spend":120965,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-07","Daily Spend":347,"x":1694044800000,"y":347,"fill":"#e6001a"},{"date_produced":"2023-09-08","party":"BS","spend":121532,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-08","Daily Spend":567,"x":1694131200000,"y":567,"fill":"#e6001a"},{"date_produced":"2023-09-09","party":"BS","spend":121977,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-09","Daily Spend":445,"x":1694217600000,"y":445,"fill":"#e6001a"},{"date_produced":"2023-09-10","party":"BS","spend":122234,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-10","Daily Spend":257,"x":1694304000000,"y":257,"fill":"#e6001a"},{"date_produced":"2023-09-11","party":"BS","spend":122555,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-11","Daily Spend":321,"x":1694390400000,"y":321,"fill":"#e6001a"},{"date_produced":"2023-09-12","party":"BS","spend":122835,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-12","Daily Spend":280,"x":1694476800000,"y":280,"fill":"#e6001a"},{"date_produced":"2023-09-13","party":"BS","spend":123194,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-13","Daily Spend":359,"x":1694563200000,"y":359,"fill":"#e6001a"},{"date_produced":"2023-09-14","party":"BS","spend":123763,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-14","Daily Spend":569,"x":1694649600000,"y":569,"fill":"#e6001a"},{"date_produced":"2023-09-15","party":"BS","spend":124589,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-15","Daily Spend":826,"x":1694736000000,"y":826,"fill":"#e6001a"},{"date_produced":"2023-09-16","party":"BS","spend":126164,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-16","Daily Spend":1575,"x":1694822400000,"y":1575,"fill":"#e6001a"},{"date_produced":"2023-09-17","party":"BS","spend":128246,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-17","Daily Spend":2082,"x":1694908800000,"y":2082,"fill":"#e6001a"},{"date_produced":"2023-09-18","party":"BS","spend":129843,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-18","Daily Spend":1597,"x":1694995200000,"y":1597,"fill":"#e6001a"},{"date_produced":"2023-09-19","party":"BS","spend":131975,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-19","Daily Spend":2132,"x":1695081600000,"y":2132,"fill":"#e6001a"},{"date_produced":"2023-09-20","party":"BS","spend":134417,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-20","Daily Spend":2442,"x":1695168000000,"y":2442,"fill":"#e6001a"},{"date_produced":"2023-09-21","party":"BS","spend":137261,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-21","Daily Spend":2844,"x":1695254400000,"y":2844,"fill":"#e6001a"},{"date_produced":"2023-09-22","party":"BS","spend":140607,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-22","Daily Spend":3346,"x":1695340800000,"y":3346,"fill":"#e6001a"},{"date_produced":"2023-09-23","party":"BS","spend":144945,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-23","Daily Spend":4338,"x":1695427200000,"y":4338,"fill":"#e6001a"},{"date_produced":"2023-09-24","party":"BS","spend":149547,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-24","Daily Spend":4602,"x":1695513600000,"y":4602,"fill":"#e6001a"},{"date_produced":"2023-09-25","party":"BS","spend":153687,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-25","Daily Spend":4140,"x":1695600000000,"y":4140,"fill":"#e6001a"},{"date_produced":"2023-09-26","party":"BS","spend":158167,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-26","Daily Spend":4480,"x":1695686400000,"y":4480,"fill":"#e6001a"},{"date_produced":"2023-09-27","party":"BS","spend":162241,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-27","Daily Spend":4074,"x":1695772800000,"y":4074,"fill":"#e6001a"},{"date_produced":"2023-09-28","party":"BS","spend":166309,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-28","Daily Spend":4068,"x":1695859200000,"y":4068,"fill":"#e6001a"},{"date_produced":"2023-09-29","party":"BS","spend":171077,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-29","Daily Spend":4768,"x":1695945600000,"y":4768,"fill":"#e6001a"},{"date_produced":"2023-09-30","party":"BS","spend":177481,"total_spend":177481,"colors":"#e6001a","Date":"2023-09-30","Daily Spend":6404,"x":1696032000000,"y":6404,"fill":"#e6001a"}],"type":"area"},{"name":"LIB","data":[{"date_produced":"2023-08-31","party":"LIB","spend":424791,"total_spend":431261,"colors":"#ffd900","Date":"2023-08-31","Daily Spend":780,"x":1693440000000,"y":780,"fill":"#ffd900"},{"date_produced":"2023-09-01","party":"LIB","spend":425481,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-01","Daily Spend":690,"x":1693526400000,"y":690,"fill":"#ffd900"},{"date_produced":"2023-09-02","party":"LIB","spend":426279,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-02","Daily Spend":798,"x":1693612800000,"y":798,"fill":"#ffd900"},{"date_produced":"2023-09-03","party":"LIB","spend":427180,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-03","Daily Spend":901,"x":1693699200000,"y":901,"fill":"#ffd900"},{"date_produced":"2023-09-04","party":"LIB","spend":427954,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-04","Daily Spend":774,"x":1693785600000,"y":774,"fill":"#ffd900"},{"date_produced":"2023-09-05","party":"LIB","spend":428612,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-05","Daily Spend":658,"x":1693872000000,"y":658,"fill":"#ffd900"},{"date_produced":"2023-09-06","party":"LIB","spend":429201,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-06","Daily Spend":589,"x":1693958400000,"y":589,"fill":"#ffd900"},{"date_produced":"2023-09-07","party":"LIB","spend":429530,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-07","Daily Spend":329,"x":1694044800000,"y":329,"fill":"#ffd900"},{"date_produced":"2023-09-08","party":"LIB","spend":429599,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-08","Daily Spend":69,"x":1694131200000,"y":69,"fill":"#ffd900"},{"date_produced":"2023-09-09","party":"LIB","spend":429675,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-09","Daily Spend":76,"x":1694217600000,"y":76,"fill":"#ffd900"},{"date_produced":"2023-09-10","party":"LIB","spend":429761,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-10","Daily Spend":86,"x":1694304000000,"y":86,"fill":"#ffd900"},{"date_produced":"2023-09-11","party":"LIB","spend":429840,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-11","Daily Spend":79,"x":1694390400000,"y":79,"fill":"#ffd900"},{"date_produced":"2023-09-12","party":"LIB","spend":429918,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-12","Daily Spend":78,"x":1694476800000,"y":78,"fill":"#ffd900"},{"date_produced":"2023-09-13","party":"LIB","spend":429995,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-13","Daily Spend":77,"x":1694563200000,"y":77,"fill":"#ffd900"},{"date_produced":"2023-09-14","party":"LIB","spend":430070,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-14","Daily Spend":75,"x":1694649600000,"y":75,"fill":"#ffd900"},{"date_produced":"2023-09-15","party":"LIB","spend":430143,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-15","Daily Spend":73,"x":1694736000000,"y":73,"fill":"#ffd900"},{"date_produced":"2023-09-16","party":"LIB","spend":430220,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-16","Daily Spend":77,"x":1694822400000,"y":77,"fill":"#ffd900"},{"date_produced":"2023-09-17","party":"LIB","spend":430312,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-17","Daily Spend":92,"x":1694908800000,"y":92,"fill":"#ffd900"},{"date_produced":"2023-09-18","party":"LIB","spend":430401,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-18","Daily Spend":89,"x":1694995200000,"y":89,"fill":"#ffd900"},{"date_produced":"2023-09-19","party":"LIB","spend":430498,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-19","Daily Spend":97,"x":1695081600000,"y":97,"fill":"#ffd900"},{"date_produced":"2023-09-20","party":"LIB","spend":430582,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-20","Daily Spend":84,"x":1695168000000,"y":84,"fill":"#ffd900"},{"date_produced":"2023-09-21","party":"LIB","spend":430666,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-21","Daily Spend":84,"x":1695254400000,"y":84,"fill":"#ffd900"},{"date_produced":"2023-09-22","party":"LIB","spend":430735,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-22","Daily Spend":69,"x":1695340800000,"y":69,"fill":"#ffd900"},{"date_produced":"2023-09-23","party":"LIB","spend":430799,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-23","Daily Spend":64,"x":1695427200000,"y":64,"fill":"#ffd900"},{"date_produced":"2023-09-24","party":"LIB","spend":430870,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-24","Daily Spend":71,"x":1695513600000,"y":71,"fill":"#ffd900"},{"date_produced":"2023-09-25","party":"LIB","spend":430937,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-25","Daily Spend":67,"x":1695600000000,"y":67,"fill":"#ffd900"},{"date_produced":"2023-09-26","party":"LIB","spend":431004,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-26","Daily Spend":67,"x":1695686400000,"y":67,"fill":"#ffd900"},{"date_produced":"2023-09-27","party":"LIB","spend":431071,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-27","Daily Spend":67,"x":1695772800000,"y":67,"fill":"#ffd900"},{"date_produced":"2023-09-28","party":"LIB","spend":431134,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-28","Daily Spend":63,"x":1695859200000,"y":63,"fill":"#ffd900"},{"date_produced":"2023-09-29","party":"LIB","spend":431196,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-29","Daily Spend":62,"x":1695945600000,"y":62,"fill":"#ffd900"},{"date_produced":"2023-09-30","party":"LIB","spend":431261,"total_spend":431261,"colors":"#ffd900","Date":"2023-09-30","Daily Spend":65,"x":1696032000000,"y":65,"fill":"#ffd900"}],"type":"area"},{"name":"KWIN","data":[{"date_produced":"2023-08-31","party":"KWIN","spend":440998,"total_spend":501716,"colors":"#122746","Date":"2023-08-31","Daily Spend":228,"x":1693440000000,"y":228,"fill":"#122746"},{"date_produced":"2023-09-01","party":"KWIN","spend":441599,"total_spend":501716,"colors":"#122746","Date":"2023-09-01","Daily Spend":601,"x":1693526400000,"y":601,"fill":"#122746"},{"date_produced":"2023-09-02","party":"KWIN","spend":442193,"total_spend":501716,"colors":"#122746","Date":"2023-09-02","Daily Spend":594,"x":1693612800000,"y":594,"fill":"#122746"},{"date_produced":"2023-09-03","party":"KWIN","spend":442390,"total_spend":501716,"colors":"#122746","Date":"2023-09-03","Daily Spend":197,"x":1693699200000,"y":197,"fill":"#122746"},{"date_produced":"2023-09-04","party":"KWIN","spend":442647,"total_spend":501716,"colors":"#122746","Date":"2023-09-04","Daily Spend":257,"x":1693785600000,"y":257,"fill":"#122746"},{"date_produced":"2023-09-05","party":"KWIN","spend":442969,"total_spend":501716,"colors":"#122746","Date":"2023-09-05","Daily Spend":322,"x":1693872000000,"y":322,"fill":"#122746"},{"date_produced":"2023-09-06","party":"KWIN","spend":443963,"total_spend":501716,"colors":"#122746","Date":"2023-09-06","Daily Spend":994,"x":1693958400000,"y":994,"fill":"#122746"},{"date_produced":"2023-09-07","party":"KWIN","spend":444891,"total_spend":501716,"colors":"#122746","Date":"2023-09-07","Daily Spend":928,"x":1694044800000,"y":928,"fill":"#122746"},{"date_produced":"2023-09-08","party":"KWIN","spend":445420,"total_spend":501716,"colors":"#122746","Date":"2023-09-08","Daily Spend":529,"x":1694131200000,"y":529,"fill":"#122746"},{"date_produced":"2023-09-09","party":"KWIN","spend":446474,"total_spend":501716,"colors":"#122746","Date":"2023-09-09","Daily Spend":1054,"x":1694217600000,"y":1054,"fill":"#122746"},{"date_produced":"2023-09-10","party":"KWIN","spend":447109,"total_spend":501716,"colors":"#122746","Date":"2023-09-10","Daily Spend":635,"x":1694304000000,"y":635,"fill":"#122746"},{"date_produced":"2023-09-11","party":"KWIN","spend":447729,"total_spend":501716,"colors":"#122746","Date":"2023-09-11","Daily Spend":620,"x":1694390400000,"y":620,"fill":"#122746"},{"date_produced":"2023-09-12","party":"KWIN","spend":447922,"total_spend":501716,"colors":"#122746","Date":"2023-09-12","Daily Spend":193,"x":1694476800000,"y":193,"fill":"#122746"},{"date_produced":"2023-09-13","party":"KWIN","spend":448569,"total_spend":501716,"colors":"#122746","Date":"2023-09-13","Daily Spend":647,"x":1694563200000,"y":647,"fill":"#122746"},{"date_produced":"2023-09-14","party":"KWIN","spend":449883,"total_spend":501716,"colors":"#122746","Date":"2023-09-14","Daily Spend":1314,"x":1694649600000,"y":1314,"fill":"#122746"},{"date_produced":"2023-09-15","party":"KWIN","spend":451296,"total_spend":501716,"colors":"#122746","Date":"2023-09-15","Daily Spend":1413,"x":1694736000000,"y":1413,"fill":"#122746"},{"date_produced":"2023-09-16","party":"KWIN","spend":452749,"total_spend":501716,"colors":"#122746","Date":"2023-09-16","Daily Spend":1453,"x":1694822400000,"y":1453,"fill":"#122746"},{"date_produced":"2023-09-17","party":"KWIN","spend":454931,"total_spend":501716,"colors":"#122746","Date":"2023-09-17","Daily Spend":2182,"x":1694908800000,"y":2182,"fill":"#122746"},{"date_produced":"2023-09-18","party":"KWIN","spend":458491,"total_spend":501716,"colors":"#122746","Date":"2023-09-18","Daily Spend":3560,"x":1694995200000,"y":3560,"fill":"#122746"},{"date_produced":"2023-09-19","party":"KWIN","spend":461951,"total_spend":501716,"colors":"#122746","Date":"2023-09-19","Daily Spend":3460,"x":1695081600000,"y":3460,"fill":"#122746"},{"date_produced":"2023-09-20","party":"KWIN","spend":465261,"total_spend":501716,"colors":"#122746","Date":"2023-09-20","Daily Spend":3310,"x":1695168000000,"y":3310,"fill":"#122746"},{"date_produced":"2023-09-21","party":"KWIN","spend":468535,"total_spend":501716,"colors":"#122746","Date":"2023-09-21","Daily Spend":3274,"x":1695254400000,"y":3274,"fill":"#122746"},{"date_produced":"2023-09-22","party":"KWIN","spend":472242,"total_spend":501716,"colors":"#122746","Date":"2023-09-22","Daily Spend":3707,"x":1695340800000,"y":3707,"fill":"#122746"},{"date_produced":"2023-09-23","party":"KWIN","spend":477337,"total_spend":501716,"colors":"#122746","Date":"2023-09-23","Daily Spend":5095,"x":1695427200000,"y":5095,"fill":"#122746"},{"date_produced":"2023-09-24","party":"KWIN","spend":482327,"total_spend":501716,"colors":"#122746","Date":"2023-09-24","Daily Spend":4990,"x":1695513600000,"y":4990,"fill":"#122746"},{"date_produced":"2023-09-25","party":"KWIN","spend":486077,"total_spend":501716,"colors":"#122746","Date":"2023-09-25","Daily Spend":3750,"x":1695600000000,"y":3750,"fill":"#122746"},{"date_produced":"2023-09-26","party":"KWIN","spend":489928,"total_spend":501716,"colors":"#122746","Date":"2023-09-26","Daily Spend":3851,"x":1695686400000,"y":3851,"fill":"#122746"},{"date_produced":"2023-09-27","party":"KWIN","spend":493814,"total_spend":501716,"colors":"#122746","Date":"2023-09-27","Daily Spend":3886,"x":1695772800000,"y":3886,"fill":"#122746"},{"date_produced":"2023-09-28","party":"KWIN","spend":496736,"total_spend":501716,"colors":"#122746","Date":"2023-09-28","Daily Spend":2922,"x":1695859200000,"y":2922,"fill":"#122746"},{"date_produced":"2023-09-29","party":"KWIN","spend":499417,"total_spend":501716,"colors":"#122746","Date":"2023-09-29","Daily Spend":2681,"x":1695945600000,"y":2681,"fill":"#122746"},{"date_produced":"2023-09-30","party":"KWIN","spend":501716,"total_spend":501716,"colors":"#122746","Date":"2023-09-30","Daily Spend":2299,"x":1696032000000,"y":2299,"fill":"#122746"}],"type":"area"},{"name":"LEW","data":[{"date_produced":"2023-08-31","party":"LEW","spend":659011,"total_spend":996334,"colors":"#851a64","Date":"2023-08-31","Daily Spend":1314,"x":1693440000000,"y":1314,"fill":"#851a64"},{"date_produced":"2023-09-01","party":"LEW","spend":660622,"total_spend":996334,"colors":"#851a64","Date":"2023-09-01","Daily Spend":1611,"x":1693526400000,"y":1611,"fill":"#851a64"},{"date_produced":"2023-09-02","party":"LEW","spend":661895,"total_spend":996334,"colors":"#851a64","Date":"2023-09-02","Daily Spend":1273,"x":1693612800000,"y":1273,"fill":"#851a64"},{"date_produced":"2023-09-03","party":"LEW","spend":663135,"total_spend":996334,"colors":"#851a64","Date":"2023-09-03","Daily Spend":1240,"x":1693699200000,"y":1240,"fill":"#851a64"},{"date_produced":"2023-09-04","party":"LEW","spend":664421,"total_spend":996334,"colors":"#851a64","Date":"2023-09-04","Daily Spend":1286,"x":1693785600000,"y":1286,"fill":"#851a64"},{"date_produced":"2023-09-05","party":"LEW","spend":665931,"total_spend":996334,"colors":"#851a64","Date":"2023-09-05","Daily Spend":1510,"x":1693872000000,"y":1510,"fill":"#851a64"},{"date_produced":"2023-09-06","party":"LEW","spend":668005,"total_spend":996334,"colors":"#851a64","Date":"2023-09-06","Daily Spend":2074,"x":1693958400000,"y":2074,"fill":"#851a64"},{"date_produced":"2023-09-07","party":"LEW","spend":670431,"total_spend":996334,"colors":"#851a64","Date":"2023-09-07","Daily Spend":2426,"x":1694044800000,"y":2426,"fill":"#851a64"},{"date_produced":"2023-09-08","party":"LEW","spend":673692,"total_spend":996334,"colors":"#851a64","Date":"2023-09-08","Daily Spend":3261,"x":1694131200000,"y":3261,"fill":"#851a64"},{"date_produced":"2023-09-09","party":"LEW","spend":677688,"total_spend":996334,"colors":"#851a64","Date":"2023-09-09","Daily Spend":3996,"x":1694217600000,"y":3996,"fill":"#851a64"},{"date_produced":"2023-09-10","party":"LEW","spend":684134,"total_spend":996334,"colors":"#851a64","Date":"2023-09-10","Daily Spend":6446,"x":1694304000000,"y":6446,"fill":"#851a64"},{"date_produced":"2023-09-11","party":"LEW","spend":691032,"total_spend":996334,"colors":"#851a64","Date":"2023-09-11","Daily Spend":6898,"x":1694390400000,"y":6898,"fill":"#851a64"},{"date_produced":"2023-09-12","party":"LEW","spend":698556,"total_spend":996334,"colors":"#851a64","Date":"2023-09-12","Daily Spend":7524,"x":1694476800000,"y":7524,"fill":"#851a64"},{"date_produced":"2023-09-13","party":"LEW","spend":707824,"total_spend":996334,"colors":"#851a64","Date":"2023-09-13","Daily Spend":9268,"x":1694563200000,"y":9268,"fill":"#851a64"},{"date_produced":"2023-09-14","party":"LEW","spend":719854,"total_spend":996334,"colors":"#851a64","Date":"2023-09-14","Daily Spend":12030,"x":1694649600000,"y":12030,"fill":"#851a64"},{"date_produced":"2023-09-15","party":"LEW","spend":731859,"total_spend":996334,"colors":"#851a64","Date":"2023-09-15","Daily Spend":12005,"x":1694736000000,"y":12005,"fill":"#851a64"},{"date_produced":"2023-09-16","party":"LEW","spend":744041,"total_spend":996334,"colors":"#851a64","Date":"2023-09-16","Daily Spend":12182,"x":1694822400000,"y":12182,"fill":"#851a64"},{"date_produced":"2023-09-17","party":"LEW","spend":756772,"total_spend":996334,"colors":"#851a64","Date":"2023-09-17","Daily Spend":12731,"x":1694908800000,"y":12731,"fill":"#851a64"},{"date_produced":"2023-09-18","party":"LEW","spend":769557,"total_spend":996334,"colors":"#851a64","Date":"2023-09-18","Daily Spend":12785,"x":1694995200000,"y":12785,"fill":"#851a64"},{"date_produced":"2023-09-19","party":"LEW","spend":782428,"total_spend":996334,"colors":"#851a64","Date":"2023-09-19","Daily Spend":12871,"x":1695081600000,"y":12871,"fill":"#851a64"},{"date_produced":"2023-09-20","party":"LEW","spend":798900,"total_spend":996334,"colors":"#851a64","Date":"2023-09-20","Daily Spend":16472,"x":1695168000000,"y":16472,"fill":"#851a64"},{"date_produced":"2023-09-21","party":"LEW","spend":816446,"total_spend":996334,"colors":"#851a64","Date":"2023-09-21","Daily Spend":17546,"x":1695254400000,"y":17546,"fill":"#851a64"},{"date_produced":"2023-09-22","party":"LEW","spend":834010,"total_spend":996334,"colors":"#851a64","Date":"2023-09-22","Daily Spend":17564,"x":1695340800000,"y":17564,"fill":"#851a64"},{"date_produced":"2023-09-23","party":"LEW","spend":851701,"total_spend":996334,"colors":"#851a64","Date":"2023-09-23","Daily Spend":17691,"x":1695427200000,"y":17691,"fill":"#851a64"},{"date_produced":"2023-09-24","party":"LEW","spend":869607,"total_spend":996334,"colors":"#851a64","Date":"2023-09-24","Daily Spend":17906,"x":1695513600000,"y":17906,"fill":"#851a64"},{"date_produced":"2023-09-25","party":"LEW","spend":886865,"total_spend":996334,"colors":"#851a64","Date":"2023-09-25","Daily Spend":17258,"x":1695600000000,"y":17258,"fill":"#851a64"},{"date_produced":"2023-09-26","party":"LEW","spend":904838,"total_spend":996334,"colors":"#851a64","Date":"2023-09-26","Daily Spend":17973,"x":1695686400000,"y":17973,"fill":"#851a64"},{"date_produced":"2023-09-27","party":"LEW","spend":923429,"total_spend":996334,"colors":"#851a64","Date":"2023-09-27","Daily Spend":18591,"x":1695772800000,"y":18591,"fill":"#851a64"},{"date_produced":"2023-09-28","party":"LEW","spend":945711,"total_spend":996334,"colors":"#851a64","Date":"2023-09-28","Daily Spend":22282,"x":1695859200000,"y":22282,"fill":"#851a64"},{"date_produced":"2023-09-29","party":"LEW","spend":968248,"total_spend":996334,"colors":"#851a64","Date":"2023-09-29","Daily Spend":22537,"x":1695945600000,"y":22537,"fill":"#851a64"},{"date_produced":"2023-09-30","party":"LEW","spend":996334,"total_spend":996334,"colors":"#851a64","Date":"2023-09-30","Daily Spend":28086,"x":1696032000000,"y":28086,"fill":"#851a64"}],"type":"area"},{"name":"TD","data":[{"date_produced":"2023-08-31","party":"TD","spend":995112,"total_spend":1317825,"colors":"#3db53a","Date":"2023-08-31","Daily Spend":1407,"x":1693440000000,"y":1407,"fill":"#3db53a"},{"date_produced":"2023-09-01","party":"TD","spend":995863,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-01","Daily Spend":751,"x":1693526400000,"y":751,"fill":"#3db53a"},{"date_produced":"2023-09-02","party":"TD","spend":996908,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-02","Daily Spend":1045,"x":1693612800000,"y":1045,"fill":"#3db53a"},{"date_produced":"2023-09-03","party":"TD","spend":999040,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-03","Daily Spend":2132,"x":1693699200000,"y":2132,"fill":"#3db53a"},{"date_produced":"2023-09-04","party":"TD","spend":1000994,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-04","Daily Spend":1954,"x":1693785600000,"y":1954,"fill":"#3db53a"},{"date_produced":"2023-09-05","party":"TD","spend":1003103,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-05","Daily Spend":2109,"x":1693872000000,"y":2109,"fill":"#3db53a"},{"date_produced":"2023-09-06","party":"TD","spend":1005525,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-06","Daily Spend":2422,"x":1693958400000,"y":2422,"fill":"#3db53a"},{"date_produced":"2023-09-07","party":"TD","spend":1007761,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-07","Daily Spend":2236,"x":1694044800000,"y":2236,"fill":"#3db53a"},{"date_produced":"2023-09-08","party":"TD","spend":1010861,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-08","Daily Spend":3100,"x":1694131200000,"y":3100,"fill":"#3db53a"},{"date_produced":"2023-09-09","party":"TD","spend":1014863,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-09","Daily Spend":4002,"x":1694217600000,"y":4002,"fill":"#3db53a"},{"date_produced":"2023-09-10","party":"TD","spend":1020674,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-10","Daily Spend":5811,"x":1694304000000,"y":5811,"fill":"#3db53a"},{"date_produced":"2023-09-11","party":"TD","spend":1026466,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-11","Daily Spend":5792,"x":1694390400000,"y":5792,"fill":"#3db53a"},{"date_produced":"2023-09-12","party":"TD","spend":1036098,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-12","Daily Spend":9632,"x":1694476800000,"y":9632,"fill":"#3db53a"},{"date_produced":"2023-09-13","party":"TD","spend":1045240,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-13","Daily Spend":9142,"x":1694563200000,"y":9142,"fill":"#3db53a"},{"date_produced":"2023-09-14","party":"TD","spend":1057602,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-14","Daily Spend":12362,"x":1694649600000,"y":12362,"fill":"#3db53a"},{"date_produced":"2023-09-15","party":"TD","spend":1071808,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-15","Daily Spend":14206,"x":1694736000000,"y":14206,"fill":"#3db53a"},{"date_produced":"2023-09-16","party":"TD","spend":1086385,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-16","Daily Spend":14577,"x":1694822400000,"y":14577,"fill":"#3db53a"},{"date_produced":"2023-09-17","party":"TD","spend":1102731,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-17","Daily Spend":16346,"x":1694908800000,"y":16346,"fill":"#3db53a"},{"date_produced":"2023-09-18","party":"TD","spend":1112527,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-18","Daily Spend":9796,"x":1694995200000,"y":9796,"fill":"#3db53a"},{"date_produced":"2023-09-19","party":"TD","spend":1125041,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-19","Daily Spend":12514,"x":1695081600000,"y":12514,"fill":"#3db53a"},{"date_produced":"2023-09-20","party":"TD","spend":1137904,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-20","Daily Spend":12863,"x":1695168000000,"y":12863,"fill":"#3db53a"},{"date_produced":"2023-09-21","party":"TD","spend":1152425,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-21","Daily Spend":14521,"x":1695254400000,"y":14521,"fill":"#3db53a"},{"date_produced":"2023-09-22","party":"TD","spend":1167291,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-22","Daily Spend":14866,"x":1695340800000,"y":14866,"fill":"#3db53a"},{"date_produced":"2023-09-23","party":"TD","spend":1184077,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-23","Daily Spend":16786,"x":1695427200000,"y":16786,"fill":"#3db53a"},{"date_produced":"2023-09-24","party":"TD","spend":1200616,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-24","Daily Spend":16539,"x":1695513600000,"y":16539,"fill":"#3db53a"},{"date_produced":"2023-09-25","party":"TD","spend":1215202,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-25","Daily Spend":14586,"x":1695600000000,"y":14586,"fill":"#3db53a"},{"date_produced":"2023-09-26","party":"TD","spend":1231881,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-26","Daily Spend":16679,"x":1695686400000,"y":16679,"fill":"#3db53a"},{"date_produced":"2023-09-27","party":"TD","spend":1249586,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-27","Daily Spend":17705,"x":1695772800000,"y":17705,"fill":"#3db53a"},{"date_produced":"2023-09-28","party":"TD","spend":1271742,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-28","Daily Spend":22156,"x":1695859200000,"y":22156,"fill":"#3db53a"},{"date_produced":"2023-09-29","party":"TD","spend":1292142,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-29","Daily Spend":20400,"x":1695945600000,"y":20400,"fill":"#3db53a"},{"date_produced":"2023-09-30","party":"TD","spend":1317825,"total_spend":1317825,"colors":"#3db53a","Date":"2023-09-30","Daily Spend":25683,"x":1696032000000,"y":25683,"fill":"#3db53a"}],"type":"area"},{"name":"ZP","data":[{"date_produced":"2023-08-31","party":"ZP","spend":2699853,"total_spend":3623296,"colors":"#263778","Date":"2023-08-31","Daily Spend":17220,"x":1693440000000,"y":17220,"fill":"#263778"},{"date_produced":"2023-09-01","party":"ZP","spend":2716188,"total_spend":3623296,"colors":"#263778","Date":"2023-09-01","Daily Spend":16335,"x":1693526400000,"y":16335,"fill":"#263778"},{"date_produced":"2023-09-02","party":"ZP","spend":2733671,"total_spend":3623296,"colors":"#263778","Date":"2023-09-02","Daily Spend":17483,"x":1693612800000,"y":17483,"fill":"#263778"},{"date_produced":"2023-09-03","party":"ZP","spend":2750868,"total_spend":3623296,"colors":"#263778","Date":"2023-09-03","Daily Spend":17197,"x":1693699200000,"y":17197,"fill":"#263778"},{"date_produced":"2023-09-04","party":"ZP","spend":2765899,"total_spend":3623296,"colors":"#263778","Date":"2023-09-04","Daily Spend":15031,"x":1693785600000,"y":15031,"fill":"#263778"},{"date_produced":"2023-09-05","party":"ZP","spend":2781913,"total_spend":3623296,"colors":"#263778","Date":"2023-09-05","Daily Spend":16014,"x":1693872000000,"y":16014,"fill":"#263778"},{"date_produced":"2023-09-06","party":"ZP","spend":2797814,"total_spend":3623296,"colors":"#263778","Date":"2023-09-06","Daily Spend":15901,"x":1693958400000,"y":15901,"fill":"#263778"},{"date_produced":"2023-09-07","party":"ZP","spend":2813932,"total_spend":3623296,"colors":"#263778","Date":"2023-09-07","Daily Spend":16118,"x":1694044800000,"y":16118,"fill":"#263778"},{"date_produced":"2023-09-08","party":"ZP","spend":2828967,"total_spend":3623296,"colors":"#263778","Date":"2023-09-08","Daily Spend":15035,"x":1694131200000,"y":15035,"fill":"#263778"},{"date_produced":"2023-09-09","party":"ZP","spend":2847756,"total_spend":3623296,"colors":"#263778","Date":"2023-09-09","Daily Spend":18789,"x":1694217600000,"y":18789,"fill":"#263778"},{"date_produced":"2023-09-10","party":"ZP","spend":2904668,"total_spend":3623296,"colors":"#263778","Date":"2023-09-10","Daily Spend":56912,"x":1694304000000,"y":56912,"fill":"#263778"},{"date_produced":"2023-09-11","party":"ZP","spend":2936738,"total_spend":3623296,"colors":"#263778","Date":"2023-09-11","Daily Spend":32070,"x":1694390400000,"y":32070,"fill":"#263778"},{"date_produced":"2023-09-12","party":"ZP","spend":2957740,"total_spend":3623296,"colors":"#263778","Date":"2023-09-12","Daily Spend":21002,"x":1694476800000,"y":21002,"fill":"#263778"},{"date_produced":"2023-09-13","party":"ZP","spend":2976869,"total_spend":3623296,"colors":"#263778","Date":"2023-09-13","Daily Spend":19129,"x":1694563200000,"y":19129,"fill":"#263778"},{"date_produced":"2023-09-14","party":"ZP","spend":3005210,"total_spend":3623296,"colors":"#263778","Date":"2023-09-14","Daily Spend":28341,"x":1694649600000,"y":28341,"fill":"#263778"},{"date_produced":"2023-09-15","party":"ZP","spend":3031351,"total_spend":3623296,"colors":"#263778","Date":"2023-09-15","Daily Spend":26141,"x":1694736000000,"y":26141,"fill":"#263778"},{"date_produced":"2023-09-16","party":"ZP","spend":3057334,"total_spend":3623296,"colors":"#263778","Date":"2023-09-16","Daily Spend":25983,"x":1694822400000,"y":25983,"fill":"#263778"},{"date_produced":"2023-09-17","party":"ZP","spend":3099697,"total_spend":3623296,"colors":"#263778","Date":"2023-09-17","Daily Spend":42363,"x":1694908800000,"y":42363,"fill":"#263778"},{"date_produced":"2023-09-18","party":"ZP","spend":3130372,"total_spend":3623296,"colors":"#263778","Date":"2023-09-18","Daily Spend":30675,"x":1694995200000,"y":30675,"fill":"#263778"},{"date_produced":"2023-09-19","party":"ZP","spend":3164610,"total_spend":3623296,"colors":"#263778","Date":"2023-09-19","Daily Spend":34238,"x":1695081600000,"y":34238,"fill":"#263778"},{"date_produced":"2023-09-20","party":"ZP","spend":3204143,"total_spend":3623296,"colors":"#263778","Date":"2023-09-20","Daily Spend":39533,"x":1695168000000,"y":39533,"fill":"#263778"},{"date_produced":"2023-09-21","party":"ZP","spend":3244566,"total_spend":3623296,"colors":"#263778","Date":"2023-09-21","Daily Spend":40423,"x":1695254400000,"y":40423,"fill":"#263778"},{"date_produced":"2023-09-22","party":"ZP","spend":3287368,"total_spend":3623296,"colors":"#263778","Date":"2023-09-22","Daily Spend":42802,"x":1695340800000,"y":42802,"fill":"#263778"},{"date_produced":"2023-09-23","party":"ZP","spend":3324710,"total_spend":3623296,"colors":"#263778","Date":"2023-09-23","Daily Spend":37342,"x":1695427200000,"y":37342,"fill":"#263778"},{"date_produced":"2023-09-24","party":"ZP","spend":3364489,"total_spend":3623296,"colors":"#263778","Date":"2023-09-24","Daily Spend":39779,"x":1695513600000,"y":39779,"fill":"#263778"},{"date_produced":"2023-09-25","party":"ZP","spend":3403564,"total_spend":3623296,"colors":"#263778","Date":"2023-09-25","Daily Spend":39075,"x":1695600000000,"y":39075,"fill":"#263778"},{"date_produced":"2023-09-26","party":"ZP","spend":3444898,"total_spend":3623296,"colors":"#263778","Date":"2023-09-26","Daily Spend":41334,"x":1695686400000,"y":41334,"fill":"#263778"},{"date_produced":"2023-09-27","party":"ZP","spend":3485830,"total_spend":3623296,"colors":"#263778","Date":"2023-09-27","Daily Spend":40932,"x":1695772800000,"y":40932,"fill":"#263778"},{"date_produced":"2023-09-28","party":"ZP","spend":3526634,"total_spend":3623296,"colors":"#263778","Date":"2023-09-28","Daily Spend":40804,"x":1695859200000,"y":40804,"fill":"#263778"},{"date_produced":"2023-09-29","party":"ZP","spend":3569761,"total_spend":3623296,"colors":"#263778","Date":"2023-09-29","Daily Spend":43127,"x":1695945600000,"y":43127,"fill":"#263778"},{"date_produced":"2023-09-30","party":"ZP","spend":3623296,"total_spend":3623296,"colors":"#263778","Date":"2023-09-30","Daily Spend":53535,"x":1696032000000,"y":53535,"fill":"#263778"}],"type":"area"},{"name":"KO","data":[{"date_produced":"2023-08-31","party":"KO","spend":3779758,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-08-31","Daily Spend":7773,"x":1693440000000,"y":7773,"fill":"#f68f2d"},{"date_produced":"2023-09-01","party":"KO","spend":3787592,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-01","Daily Spend":7834,"x":1693526400000,"y":7834,"fill":"#f68f2d"},{"date_produced":"2023-09-02","party":"KO","spend":3797609,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-02","Daily Spend":10017,"x":1693612800000,"y":10017,"fill":"#f68f2d"},{"date_produced":"2023-09-03","party":"KO","spend":3809315,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-03","Daily Spend":11706,"x":1693699200000,"y":11706,"fill":"#f68f2d"},{"date_produced":"2023-09-04","party":"KO","spend":3820429,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-04","Daily Spend":11114,"x":1693785600000,"y":11114,"fill":"#f68f2d"},{"date_produced":"2023-09-05","party":"KO","spend":3832529,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-05","Daily Spend":12100,"x":1693872000000,"y":12100,"fill":"#f68f2d"},{"date_produced":"2023-09-06","party":"KO","spend":3848389,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-06","Daily Spend":15860,"x":1693958400000,"y":15860,"fill":"#f68f2d"},{"date_produced":"2023-09-07","party":"KO","spend":3870804,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-07","Daily Spend":22415,"x":1694044800000,"y":22415,"fill":"#f68f2d"},{"date_produced":"2023-09-08","party":"KO","spend":3899086,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-08","Daily Spend":28282,"x":1694131200000,"y":28282,"fill":"#f68f2d"},{"date_produced":"2023-09-09","party":"KO","spend":3935721,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-09","Daily Spend":36635,"x":1694217600000,"y":36635,"fill":"#f68f2d"},{"date_produced":"2023-09-10","party":"KO","spend":3960969,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-10","Daily Spend":25248,"x":1694304000000,"y":25248,"fill":"#f68f2d"},{"date_produced":"2023-09-11","party":"KO","spend":4007548,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-11","Daily Spend":46579,"x":1694390400000,"y":46579,"fill":"#f68f2d"},{"date_produced":"2023-09-12","party":"KO","spend":4064063,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-12","Daily Spend":56515,"x":1694476800000,"y":56515,"fill":"#f68f2d"},{"date_produced":"2023-09-13","party":"KO","spend":4091221,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-13","Daily Spend":27158,"x":1694563200000,"y":27158,"fill":"#f68f2d"},{"date_produced":"2023-09-14","party":"KO","spend":4108923,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-14","Daily Spend":17702,"x":1694649600000,"y":17702,"fill":"#f68f2d"},{"date_produced":"2023-09-15","party":"KO","spend":4146178,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-15","Daily Spend":37255,"x":1694736000000,"y":37255,"fill":"#f68f2d"},{"date_produced":"2023-09-16","party":"KO","spend":4193090,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-16","Daily Spend":46912,"x":1694822400000,"y":46912,"fill":"#f68f2d"},{"date_produced":"2023-09-17","party":"KO","spend":4245037,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-17","Daily Spend":51947,"x":1694908800000,"y":51947,"fill":"#f68f2d"},{"date_produced":"2023-09-18","party":"KO","spend":4267848,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-18","Daily Spend":22811,"x":1694995200000,"y":22811,"fill":"#f68f2d"},{"date_produced":"2023-09-19","party":"KO","spend":4298801,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-19","Daily Spend":30953,"x":1695081600000,"y":30953,"fill":"#f68f2d"},{"date_produced":"2023-09-20","party":"KO","spend":4332691,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-20","Daily Spend":33890,"x":1695168000000,"y":33890,"fill":"#f68f2d"},{"date_produced":"2023-09-21","party":"KO","spend":4364023,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-21","Daily Spend":31332,"x":1695254400000,"y":31332,"fill":"#f68f2d"},{"date_produced":"2023-09-22","party":"KO","spend":4396097,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-22","Daily Spend":32074,"x":1695340800000,"y":32074,"fill":"#f68f2d"},{"date_produced":"2023-09-23","party":"KO","spend":4426724,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-23","Daily Spend":30627,"x":1695427200000,"y":30627,"fill":"#f68f2d"},{"date_produced":"2023-09-24","party":"KO","spend":4459900,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-24","Daily Spend":33176,"x":1695513600000,"y":33176,"fill":"#f68f2d"},{"date_produced":"2023-09-25","party":"KO","spend":4488640,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-25","Daily Spend":28740,"x":1695600000000,"y":28740,"fill":"#f68f2d"},{"date_produced":"2023-09-26","party":"KO","spend":4517969,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-26","Daily Spend":29329,"x":1695686400000,"y":29329,"fill":"#f68f2d"},{"date_produced":"2023-09-27","party":"KO","spend":4558151,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-27","Daily Spend":40182,"x":1695772800000,"y":40182,"fill":"#f68f2d"},{"date_produced":"2023-09-28","party":"KO","spend":4616145,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-28","Daily Spend":57994,"x":1695859200000,"y":57994,"fill":"#f68f2d"},{"date_produced":"2023-09-29","party":"KO","spend":4685722,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-29","Daily Spend":69577,"x":1695945600000,"y":69577,"fill":"#f68f2d"},{"date_produced":"2023-09-30","party":"KO","spend":4740486,"total_spend":4740486,"colors":"#f68f2d","Date":"2023-09-30","Daily Spend":54764,"x":1696032000000,"y":54764,"fill":"#f68f2d"}],"type":"area"}],"xAxis":{"type":"datetime","title":{"text":"Date"},"categories":null},"colors":["#e6001a","#ffd900","#122746","#851a64","#3db53a","#263778","#f68f2d"],"tooltip":{"shared":true,"positioner":"function (labelWidth, labelHeight, point) {\n        return { x: 200, y: this.chart.plotTop };\n    }"}},"theme":{"chart":{"backgroundColor":"transparent"},"colors":["#7cb5ec","#434348","#90ed7d","#f7a35c","#8085e9","#f15c80","#e4d354","#2b908f","#f45b5b","#91e8e1"]},"conf_opts":{"global":{"Date":null,"VMLRadialGradientURL":"http =//code.highcharts.com/list(version)/gfx/vml-radial-gradient.png","canvasToolsURL":"http =//code.highcharts.com/list(version)/modules/canvas-tools.js","getTimezoneOffset":null,"timezoneOffset":0,"useUTC":true},"lang":{"contextButtonTitle":"Chart context menu","decimalPoint":".","downloadCSV":"Download CSV","downloadJPEG":"Download JPEG image","downloadPDF":"Download PDF document","downloadPNG":"Download PNG image","downloadSVG":"Download SVG vector image","downloadXLS":"Download XLS","drillUpText":"◁ Back to {series.name}","exitFullscreen":"Exit from full screen","exportData":{"annotationHeader":"Annotations","categoryDatetimeHeader":"DateTime","categoryHeader":"Category"},"hideData":"Hide data table","invalidDate":null,"loading":"Loading...","months":["January","February","March","April","May","June","July","August","September","October","November","December"],"noData":"No data to display","numericSymbolMagnitude":1000,"numericSymbols":["k","M","G","T","P","E"],"printChart":"Print chart","resetZoom":"Reset zoom","resetZoomTitle":"Reset zoom level 1:1","shortMonths":["Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"],"shortWeekdays":["Sat","Sun","Mon","Tue","Wed","Thu","Fri"],"thousandsSep":" ","viewData":"View data table","viewFullscreen":"View in full screen","weekdays":["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday"]}},"type":"chart","fonts":[],"debug":false},"evals":["hc_opts.tooltip.positioner"],"jsHooks":[]}</script>
```
:::
:::


::: 



## ![](img/g.svg) Google


::: {.panel-tabset}



### Cumulative


::: {.cell}
::: {.cell-output-display}
```{=html}
<div class="highchart html-widget html-fill-item-overflow-hidden html-fill-item" id="htmlwidget-8e0f7e497d861588f560" style="width:100%;height:480px;"></div>
<script type="application/json" data-for="htmlwidget-8e0f7e497d861588f560">{"x":{"hc_opts":{"chart":{"reflow":true},"title":{"text":null},"yAxis":{"title":{"text":"Daily Spend"},"type":"linear"},"credits":{"enabled":false},"exporting":{"enabled":false},"boost":{"enabled":false},"plotOptions":{"series":{"label":{"enabled":false},"turboThreshold":0,"showInLegend":true},"treemap":{"layoutAlgorithm":"squarified"},"scatter":{"marker":{"symbol":"circle"}},"area":{"stacking":"normal","lineWidth":1,"marker":{"enabled":false}}},"series":[{"name":"TD","data":[{"date_produced":"2023-09-01","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-01","x":1693526400000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-02","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-02","x":1693612800000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-03","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-03","x":1693699200000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-04","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-04","x":1693785600000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-05","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-05","x":1693872000000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-06","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-06","x":1693958400000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-07","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-07","x":1694044800000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-08","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-08","x":1694131200000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-09","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-09","x":1694217600000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-10","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-10","x":1694304000000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-11","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-11","x":1694390400000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-12","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-12","x":1694476800000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-13","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-13","x":1694563200000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-14","party":"TD","spend":250,"total_spend":2750,"colors":"#3db53a","Daily Spend":250,"Date":"2023-09-14","x":1694649600000,"y":250,"fill":"#3db53a"},{"date_produced":"2023-09-15","party":"TD","spend":500,"total_spend":2750,"colors":"#3db53a","Daily Spend":500,"Date":"2023-09-15","x":1694736000000,"y":500,"fill":"#3db53a"},{"date_produced":"2023-09-16","party":"TD","spend":750,"total_spend":2750,"colors":"#3db53a","Daily Spend":750,"Date":"2023-09-16","x":1694822400000,"y":750,"fill":"#3db53a"},{"date_produced":"2023-09-17","party":"TD","spend":1250,"total_spend":2750,"colors":"#3db53a","Daily Spend":1250,"Date":"2023-09-17","x":1694908800000,"y":1250,"fill":"#3db53a"},{"date_produced":"2023-09-18","party":"TD","spend":2250,"total_spend":2750,"colors":"#3db53a","Daily Spend":2250,"Date":"2023-09-18","x":1694995200000,"y":2250,"fill":"#3db53a"},{"date_produced":"2023-09-19","party":"TD","spend":3250,"total_spend":2750,"colors":"#3db53a","Daily Spend":3250,"Date":"2023-09-19","x":1695081600000,"y":3250,"fill":"#3db53a"},{"date_produced":"2023-09-20","party":"TD","spend":5000,"total_spend":2750,"colors":"#3db53a","Daily Spend":5000,"Date":"2023-09-20","x":1695168000000,"y":5000,"fill":"#3db53a"},{"date_produced":"2023-09-21","party":"TD","spend":6250,"total_spend":2750,"colors":"#3db53a","Daily Spend":6250,"Date":"2023-09-21","x":1695254400000,"y":6250,"fill":"#3db53a"},{"date_produced":"2023-09-22","party":"TD","spend":7750,"total_spend":2750,"colors":"#3db53a","Daily Spend":7750,"Date":"2023-09-22","x":1695340800000,"y":7750,"fill":"#3db53a"},{"date_produced":"2023-09-23","party":"TD","spend":9250,"total_spend":2750,"colors":"#3db53a","Daily Spend":9250,"Date":"2023-09-23","x":1695427200000,"y":9250,"fill":"#3db53a"},{"date_produced":"2023-09-24","party":"TD","spend":10750,"total_spend":2750,"colors":"#3db53a","Daily Spend":10750,"Date":"2023-09-24","x":1695513600000,"y":10750,"fill":"#3db53a"},{"date_produced":"2023-09-25","party":"TD","spend":13000,"total_spend":2750,"colors":"#3db53a","Daily Spend":13000,"Date":"2023-09-25","x":1695600000000,"y":13000,"fill":"#3db53a"},{"date_produced":"2023-09-26","party":"TD","spend":15250,"total_spend":2750,"colors":"#3db53a","Daily Spend":15250,"Date":"2023-09-26","x":1695686400000,"y":15250,"fill":"#3db53a"},{"date_produced":"2023-09-27","party":"TD","spend":18000,"total_spend":2750,"colors":"#3db53a","Daily Spend":18000,"Date":"2023-09-27","x":1695772800000,"y":18000,"fill":"#3db53a"},{"date_produced":"2023-09-28","party":"TD","spend":20000,"total_spend":2750,"colors":"#3db53a","Daily Spend":20000,"Date":"2023-09-28","x":1695859200000,"y":20000,"fill":"#3db53a"},{"date_produced":"2023-09-29","party":"TD","spend":21250,"total_spend":2750,"colors":"#3db53a","Daily Spend":21250,"Date":"2023-09-29","x":1695945600000,"y":21250,"fill":"#3db53a"},{"date_produced":"2023-09-30","party":"TD","spend":22250,"total_spend":2750,"colors":"#3db53a","Daily Spend":22250,"Date":"2023-09-30","x":1696032000000,"y":22250,"fill":"#3db53a"},{"date_produced":"2023-10-01","party":"TD","spend":24000,"total_spend":2750,"colors":"#3db53a","Daily Spend":24000,"Date":"2023-10-01","x":1696118400000,"y":24000,"fill":"#3db53a"},{"date_produced":"2023-10-02","party":"TD","spend":26000,"total_spend":2750,"colors":"#3db53a","Daily Spend":26000,"Date":"2023-10-02","x":1696204800000,"y":26000,"fill":"#3db53a"}],"type":"area"},{"name":"BS","data":[{"date_produced":"2023-09-01","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-01","x":1693526400000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-02","party":"BS","spend":500,"total_spend":4000,"colors":"#e6001a","Daily Spend":500,"Date":"2023-09-02","x":1693612800000,"y":500,"fill":"#e6001a"},{"date_produced":"2023-09-03","party":"BS","spend":750,"total_spend":4000,"colors":"#e6001a","Daily Spend":750,"Date":"2023-09-03","x":1693699200000,"y":750,"fill":"#e6001a"},{"date_produced":"2023-09-04","party":"BS","spend":1000,"total_spend":4000,"colors":"#e6001a","Daily Spend":1000,"Date":"2023-09-04","x":1693785600000,"y":1000,"fill":"#e6001a"},{"date_produced":"2023-09-05","party":"BS","spend":1250,"total_spend":4000,"colors":"#e6001a","Daily Spend":1250,"Date":"2023-09-05","x":1693872000000,"y":1250,"fill":"#e6001a"},{"date_produced":"2023-09-06","party":"BS","spend":1500,"total_spend":4000,"colors":"#e6001a","Daily Spend":1500,"Date":"2023-09-06","x":1693958400000,"y":1500,"fill":"#e6001a"},{"date_produced":"2023-09-07","party":"BS","spend":1750,"total_spend":4000,"colors":"#e6001a","Daily Spend":1750,"Date":"2023-09-07","x":1694044800000,"y":1750,"fill":"#e6001a"},{"date_produced":"2023-09-08","party":"BS","spend":2000,"total_spend":4000,"colors":"#e6001a","Daily Spend":2000,"Date":"2023-09-08","x":1694131200000,"y":2000,"fill":"#e6001a"},{"date_produced":"2023-09-09","party":"BS","spend":2250,"total_spend":4000,"colors":"#e6001a","Daily Spend":2250,"Date":"2023-09-09","x":1694217600000,"y":2250,"fill":"#e6001a"},{"date_produced":"2023-09-10","party":"BS","spend":2500,"total_spend":4000,"colors":"#e6001a","Daily Spend":2500,"Date":"2023-09-10","x":1694304000000,"y":2500,"fill":"#e6001a"},{"date_produced":"2023-09-11","party":"BS","spend":2750,"total_spend":4000,"colors":"#e6001a","Daily Spend":2750,"Date":"2023-09-11","x":1694390400000,"y":2750,"fill":"#e6001a"},{"date_produced":"2023-09-12","party":"BS","spend":3000,"total_spend":4000,"colors":"#e6001a","Daily Spend":3000,"Date":"2023-09-12","x":1694476800000,"y":3000,"fill":"#e6001a"},{"date_produced":"2023-09-13","party":"BS","spend":3250,"total_spend":4000,"colors":"#e6001a","Daily Spend":3250,"Date":"2023-09-13","x":1694563200000,"y":3250,"fill":"#e6001a"},{"date_produced":"2023-09-14","party":"BS","spend":3500,"total_spend":4000,"colors":"#e6001a","Daily Spend":3500,"Date":"2023-09-14","x":1694649600000,"y":3500,"fill":"#e6001a"},{"date_produced":"2023-09-15","party":"BS","spend":3750,"total_spend":4000,"colors":"#e6001a","Daily Spend":3750,"Date":"2023-09-15","x":1694736000000,"y":3750,"fill":"#e6001a"},{"date_produced":"2023-09-16","party":"BS","spend":4000,"total_spend":4000,"colors":"#e6001a","Daily Spend":4000,"Date":"2023-09-16","x":1694822400000,"y":4000,"fill":"#e6001a"},{"date_produced":"2023-09-17","party":"BS","spend":4250,"total_spend":4000,"colors":"#e6001a","Daily Spend":4250,"Date":"2023-09-17","x":1694908800000,"y":4250,"fill":"#e6001a"},{"date_produced":"2023-09-18","party":"BS","spend":4500,"total_spend":4000,"colors":"#e6001a","Daily Spend":4500,"Date":"2023-09-18","x":1694995200000,"y":4500,"fill":"#e6001a"},{"date_produced":"2023-09-19","party":"BS","spend":5000,"total_spend":4000,"colors":"#e6001a","Daily Spend":5000,"Date":"2023-09-19","x":1695081600000,"y":5000,"fill":"#e6001a"},{"date_produced":"2023-09-20","party":"BS","spend":6000,"total_spend":4000,"colors":"#e6001a","Daily Spend":6000,"Date":"2023-09-20","x":1695168000000,"y":6000,"fill":"#e6001a"},{"date_produced":"2023-09-21","party":"BS","spend":7500,"total_spend":4000,"colors":"#e6001a","Daily Spend":7500,"Date":"2023-09-21","x":1695254400000,"y":7500,"fill":"#e6001a"},{"date_produced":"2023-09-22","party":"BS","spend":9000,"total_spend":4000,"colors":"#e6001a","Daily Spend":9000,"Date":"2023-09-22","x":1695340800000,"y":9000,"fill":"#e6001a"},{"date_produced":"2023-09-23","party":"BS","spend":10500,"total_spend":4000,"colors":"#e6001a","Daily Spend":10500,"Date":"2023-09-23","x":1695427200000,"y":10500,"fill":"#e6001a"},{"date_produced":"2023-09-24","party":"BS","spend":12000,"total_spend":4000,"colors":"#e6001a","Daily Spend":12000,"Date":"2023-09-24","x":1695513600000,"y":12000,"fill":"#e6001a"},{"date_produced":"2023-09-25","party":"BS","spend":13500,"total_spend":4000,"colors":"#e6001a","Daily Spend":13500,"Date":"2023-09-25","x":1695600000000,"y":13500,"fill":"#e6001a"},{"date_produced":"2023-09-26","party":"BS","spend":14750,"total_spend":4000,"colors":"#e6001a","Daily Spend":14750,"Date":"2023-09-26","x":1695686400000,"y":14750,"fill":"#e6001a"},{"date_produced":"2023-09-27","party":"BS","spend":16250,"total_spend":4000,"colors":"#e6001a","Daily Spend":16250,"Date":"2023-09-27","x":1695772800000,"y":16250,"fill":"#e6001a"},{"date_produced":"2023-09-28","party":"BS","spend":19500,"total_spend":4000,"colors":"#e6001a","Daily Spend":19500,"Date":"2023-09-28","x":1695859200000,"y":19500,"fill":"#e6001a"},{"date_produced":"2023-09-29","party":"BS","spend":22500,"total_spend":4000,"colors":"#e6001a","Daily Spend":22500,"Date":"2023-09-29","x":1695945600000,"y":22500,"fill":"#e6001a"},{"date_produced":"2023-09-30","party":"BS","spend":24000,"total_spend":4000,"colors":"#e6001a","Daily Spend":24000,"Date":"2023-09-30","x":1696032000000,"y":24000,"fill":"#e6001a"},{"date_produced":"2023-10-01","party":"BS","spend":27000,"total_spend":4000,"colors":"#e6001a","Daily Spend":27000,"Date":"2023-10-01","x":1696118400000,"y":27000,"fill":"#e6001a"},{"date_produced":"2023-10-02","party":"BS","spend":31000,"total_spend":4000,"colors":"#e6001a","Daily Spend":31000,"Date":"2023-10-02","x":1696204800000,"y":31000,"fill":"#e6001a"}],"type":"area"},{"name":"KWIN","data":[{"date_produced":"2023-09-01","party":"KWIN","spend":0,"total_spend":8500,"colors":"#122746","Daily Spend":0,"Date":"2023-09-01","x":1693526400000,"y":0,"fill":"#122746"},{"date_produced":"2023-09-02","party":"KWIN","spend":0,"total_spend":8500,"colors":"#122746","Daily Spend":0,"Date":"2023-09-02","x":1693612800000,"y":0,"fill":"#122746"},{"date_produced":"2023-09-03","party":"KWIN","spend":0,"total_spend":8500,"colors":"#122746","Daily Spend":0,"Date":"2023-09-03","x":1693699200000,"y":0,"fill":"#122746"},{"date_produced":"2023-09-04","party":"KWIN","spend":0,"total_spend":8500,"colors":"#122746","Daily Spend":0,"Date":"2023-09-04","x":1693785600000,"y":0,"fill":"#122746"},{"date_produced":"2023-09-05","party":"KWIN","spend":750,"total_spend":8500,"colors":"#122746","Daily Spend":750,"Date":"2023-09-05","x":1693872000000,"y":750,"fill":"#122746"},{"date_produced":"2023-09-06","party":"KWIN","spend":6750,"total_spend":8500,"colors":"#122746","Daily Spend":6750,"Date":"2023-09-06","x":1693958400000,"y":6750,"fill":"#122746"},{"date_produced":"2023-09-07","party":"KWIN","spend":9750,"total_spend":8500,"colors":"#122746","Daily Spend":9750,"Date":"2023-09-07","x":1694044800000,"y":9750,"fill":"#122746"},{"date_produced":"2023-09-08","party":"KWIN","spend":10000,"total_spend":8500,"colors":"#122746","Daily Spend":10000,"Date":"2023-09-08","x":1694131200000,"y":10000,"fill":"#122746"},{"date_produced":"2023-09-09","party":"KWIN","spend":10250,"total_spend":8500,"colors":"#122746","Daily Spend":10250,"Date":"2023-09-09","x":1694217600000,"y":10250,"fill":"#122746"},{"date_produced":"2023-09-10","party":"KWIN","spend":10500,"total_spend":8500,"colors":"#122746","Daily Spend":10500,"Date":"2023-09-10","x":1694304000000,"y":10500,"fill":"#122746"},{"date_produced":"2023-09-11","party":"KWIN","spend":11000,"total_spend":8500,"colors":"#122746","Daily Spend":11000,"Date":"2023-09-11","x":1694390400000,"y":11000,"fill":"#122746"},{"date_produced":"2023-09-12","party":"KWIN","spend":11250,"total_spend":8500,"colors":"#122746","Daily Spend":11250,"Date":"2023-09-12","x":1694476800000,"y":11250,"fill":"#122746"},{"date_produced":"2023-09-13","party":"KWIN","spend":11500,"total_spend":8500,"colors":"#122746","Daily Spend":11500,"Date":"2023-09-13","x":1694563200000,"y":11500,"fill":"#122746"},{"date_produced":"2023-09-14","party":"KWIN","spend":11750,"total_spend":8500,"colors":"#122746","Daily Spend":11750,"Date":"2023-09-14","x":1694649600000,"y":11750,"fill":"#122746"},{"date_produced":"2023-09-15","party":"KWIN","spend":12000,"total_spend":8500,"colors":"#122746","Daily Spend":12000,"Date":"2023-09-15","x":1694736000000,"y":12000,"fill":"#122746"},{"date_produced":"2023-09-16","party":"KWIN","spend":12250,"total_spend":8500,"colors":"#122746","Daily Spend":12250,"Date":"2023-09-16","x":1694822400000,"y":12250,"fill":"#122746"},{"date_produced":"2023-09-17","party":"KWIN","spend":12500,"total_spend":8500,"colors":"#122746","Daily Spend":12500,"Date":"2023-09-17","x":1694908800000,"y":12500,"fill":"#122746"},{"date_produced":"2023-09-18","party":"KWIN","spend":12750,"total_spend":8500,"colors":"#122746","Daily Spend":12750,"Date":"2023-09-18","x":1694995200000,"y":12750,"fill":"#122746"},{"date_produced":"2023-09-19","party":"KWIN","spend":13000,"total_spend":8500,"colors":"#122746","Daily Spend":13000,"Date":"2023-09-19","x":1695081600000,"y":13000,"fill":"#122746"},{"date_produced":"2023-09-20","party":"KWIN","spend":14250,"total_spend":8500,"colors":"#122746","Daily Spend":14250,"Date":"2023-09-20","x":1695168000000,"y":14250,"fill":"#122746"},{"date_produced":"2023-09-21","party":"KWIN","spend":15750,"total_spend":8500,"colors":"#122746","Daily Spend":15750,"Date":"2023-09-21","x":1695254400000,"y":15750,"fill":"#122746"},{"date_produced":"2023-09-22","party":"KWIN","spend":16500,"total_spend":8500,"colors":"#122746","Daily Spend":16500,"Date":"2023-09-22","x":1695340800000,"y":16500,"fill":"#122746"},{"date_produced":"2023-09-23","party":"KWIN","spend":20750,"total_spend":8500,"colors":"#122746","Daily Spend":20750,"Date":"2023-09-23","x":1695427200000,"y":20750,"fill":"#122746"},{"date_produced":"2023-09-24","party":"KWIN","spend":24000,"total_spend":8500,"colors":"#122746","Daily Spend":24000,"Date":"2023-09-24","x":1695513600000,"y":24000,"fill":"#122746"},{"date_produced":"2023-09-25","party":"KWIN","spend":26250,"total_spend":8500,"colors":"#122746","Daily Spend":26250,"Date":"2023-09-25","x":1695600000000,"y":26250,"fill":"#122746"},{"date_produced":"2023-09-26","party":"KWIN","spend":34750,"total_spend":8500,"colors":"#122746","Daily Spend":34750,"Date":"2023-09-26","x":1695686400000,"y":34750,"fill":"#122746"},{"date_produced":"2023-09-27","party":"KWIN","spend":39250,"total_spend":8500,"colors":"#122746","Daily Spend":39250,"Date":"2023-09-27","x":1695772800000,"y":39250,"fill":"#122746"},{"date_produced":"2023-09-28","party":"KWIN","spend":43500,"total_spend":8500,"colors":"#122746","Daily Spend":43500,"Date":"2023-09-28","x":1695859200000,"y":43500,"fill":"#122746"},{"date_produced":"2023-09-29","party":"KWIN","spend":50500,"total_spend":8500,"colors":"#122746","Daily Spend":50500,"Date":"2023-09-29","x":1695945600000,"y":50500,"fill":"#122746"},{"date_produced":"2023-09-30","party":"KWIN","spend":58750,"total_spend":8500,"colors":"#122746","Daily Spend":58750,"Date":"2023-09-30","x":1696032000000,"y":58750,"fill":"#122746"},{"date_produced":"2023-10-01","party":"KWIN","spend":63250,"total_spend":8500,"colors":"#122746","Daily Spend":63250,"Date":"2023-10-01","x":1696118400000,"y":63250,"fill":"#122746"},{"date_produced":"2023-10-02","party":"KWIN","spend":67250,"total_spend":8500,"colors":"#122746","Daily Spend":67250,"Date":"2023-10-02","x":1696204800000,"y":67250,"fill":"#122746"}],"type":"area"},{"name":"LEW","data":[{"date_produced":"2023-09-01","party":"LEW","spend":250,"total_spend":14250,"colors":"#851a64","Daily Spend":250,"Date":"2023-09-01","x":1693526400000,"y":250,"fill":"#851a64"},{"date_produced":"2023-09-02","party":"LEW","spend":500,"total_spend":14250,"colors":"#851a64","Daily Spend":500,"Date":"2023-09-02","x":1693612800000,"y":500,"fill":"#851a64"},{"date_produced":"2023-09-03","party":"LEW","spend":750,"total_spend":14250,"colors":"#851a64","Daily Spend":750,"Date":"2023-09-03","x":1693699200000,"y":750,"fill":"#851a64"},{"date_produced":"2023-09-04","party":"LEW","spend":1000,"total_spend":14250,"colors":"#851a64","Daily Spend":1000,"Date":"2023-09-04","x":1693785600000,"y":1000,"fill":"#851a64"},{"date_produced":"2023-09-05","party":"LEW","spend":1250,"total_spend":14250,"colors":"#851a64","Daily Spend":1250,"Date":"2023-09-05","x":1693872000000,"y":1250,"fill":"#851a64"},{"date_produced":"2023-09-06","party":"LEW","spend":1500,"total_spend":14250,"colors":"#851a64","Daily Spend":1500,"Date":"2023-09-06","x":1693958400000,"y":1500,"fill":"#851a64"},{"date_produced":"2023-09-07","party":"LEW","spend":1750,"total_spend":14250,"colors":"#851a64","Daily Spend":1750,"Date":"2023-09-07","x":1694044800000,"y":1750,"fill":"#851a64"},{"date_produced":"2023-09-08","party":"LEW","spend":2000,"total_spend":14250,"colors":"#851a64","Daily Spend":2000,"Date":"2023-09-08","x":1694131200000,"y":2000,"fill":"#851a64"},{"date_produced":"2023-09-09","party":"LEW","spend":2250,"total_spend":14250,"colors":"#851a64","Daily Spend":2250,"Date":"2023-09-09","x":1694217600000,"y":2250,"fill":"#851a64"},{"date_produced":"2023-09-10","party":"LEW","spend":2500,"total_spend":14250,"colors":"#851a64","Daily Spend":2500,"Date":"2023-09-10","x":1694304000000,"y":2500,"fill":"#851a64"},{"date_produced":"2023-09-11","party":"LEW","spend":2750,"total_spend":14250,"colors":"#851a64","Daily Spend":2750,"Date":"2023-09-11","x":1694390400000,"y":2750,"fill":"#851a64"},{"date_produced":"2023-09-12","party":"LEW","spend":3000,"total_spend":14250,"colors":"#851a64","Daily Spend":3000,"Date":"2023-09-12","x":1694476800000,"y":3000,"fill":"#851a64"},{"date_produced":"2023-09-13","party":"LEW","spend":8000,"total_spend":14250,"colors":"#851a64","Daily Spend":8000,"Date":"2023-09-13","x":1694563200000,"y":8000,"fill":"#851a64"},{"date_produced":"2023-09-14","party":"LEW","spend":10750,"total_spend":14250,"colors":"#851a64","Daily Spend":10750,"Date":"2023-09-14","x":1694649600000,"y":10750,"fill":"#851a64"},{"date_produced":"2023-09-15","party":"LEW","spend":13500,"total_spend":14250,"colors":"#851a64","Daily Spend":13500,"Date":"2023-09-15","x":1694736000000,"y":13500,"fill":"#851a64"},{"date_produced":"2023-09-16","party":"LEW","spend":16500,"total_spend":14250,"colors":"#851a64","Daily Spend":16500,"Date":"2023-09-16","x":1694822400000,"y":16500,"fill":"#851a64"},{"date_produced":"2023-09-17","party":"LEW","spend":20000,"total_spend":14250,"colors":"#851a64","Daily Spend":20000,"Date":"2023-09-17","x":1694908800000,"y":20000,"fill":"#851a64"},{"date_produced":"2023-09-18","party":"LEW","spend":23500,"total_spend":14250,"colors":"#851a64","Daily Spend":23500,"Date":"2023-09-18","x":1694995200000,"y":23500,"fill":"#851a64"},{"date_produced":"2023-09-19","party":"LEW","spend":26750,"total_spend":14250,"colors":"#851a64","Daily Spend":26750,"Date":"2023-09-19","x":1695081600000,"y":26750,"fill":"#851a64"},{"date_produced":"2023-09-20","party":"LEW","spend":34750,"total_spend":14250,"colors":"#851a64","Daily Spend":34750,"Date":"2023-09-20","x":1695168000000,"y":34750,"fill":"#851a64"},{"date_produced":"2023-09-21","party":"LEW","spend":42250,"total_spend":14250,"colors":"#851a64","Daily Spend":42250,"Date":"2023-09-21","x":1695254400000,"y":42250,"fill":"#851a64"},{"date_produced":"2023-09-22","party":"LEW","spend":52000,"total_spend":14250,"colors":"#851a64","Daily Spend":52000,"Date":"2023-09-22","x":1695340800000,"y":52000,"fill":"#851a64"},{"date_produced":"2023-09-23","party":"LEW","spend":62750,"total_spend":14250,"colors":"#851a64","Daily Spend":62750,"Date":"2023-09-23","x":1695427200000,"y":62750,"fill":"#851a64"},{"date_produced":"2023-09-24","party":"LEW","spend":73000,"total_spend":14250,"colors":"#851a64","Daily Spend":73000,"Date":"2023-09-24","x":1695513600000,"y":73000,"fill":"#851a64"},{"date_produced":"2023-09-25","party":"LEW","spend":80500,"total_spend":14250,"colors":"#851a64","Daily Spend":80500,"Date":"2023-09-25","x":1695600000000,"y":80500,"fill":"#851a64"},{"date_produced":"2023-09-26","party":"LEW","spend":91250,"total_spend":14250,"colors":"#851a64","Daily Spend":91250,"Date":"2023-09-26","x":1695686400000,"y":91250,"fill":"#851a64"},{"date_produced":"2023-09-27","party":"LEW","spend":105500,"total_spend":14250,"colors":"#851a64","Daily Spend":105500,"Date":"2023-09-27","x":1695772800000,"y":105500,"fill":"#851a64"},{"date_produced":"2023-09-28","party":"LEW","spend":112500,"total_spend":14250,"colors":"#851a64","Daily Spend":112500,"Date":"2023-09-28","x":1695859200000,"y":112500,"fill":"#851a64"},{"date_produced":"2023-09-29","party":"LEW","spend":121250,"total_spend":14250,"colors":"#851a64","Daily Spend":121250,"Date":"2023-09-29","x":1695945600000,"y":121250,"fill":"#851a64"},{"date_produced":"2023-09-30","party":"LEW","spend":130250,"total_spend":14250,"colors":"#851a64","Daily Spend":130250,"Date":"2023-09-30","x":1696032000000,"y":130250,"fill":"#851a64"},{"date_produced":"2023-10-01","party":"LEW","spend":138500,"total_spend":14250,"colors":"#851a64","Daily Spend":138500,"Date":"2023-10-01","x":1696118400000,"y":138500,"fill":"#851a64"},{"date_produced":"2023-10-02","party":"LEW","spend":148500,"total_spend":14250,"colors":"#851a64","Daily Spend":148500,"Date":"2023-10-02","x":1696204800000,"y":148500,"fill":"#851a64"}],"type":"area"},{"name":"KO","data":[{"date_produced":"2023-09-01","party":"KO","spend":3000,"total_spend":123750,"colors":"#f68f2d","Daily Spend":3000,"Date":"2023-09-01","x":1693526400000,"y":3000,"fill":"#f68f2d"},{"date_produced":"2023-09-02","party":"KO","spend":6250,"total_spend":123750,"colors":"#f68f2d","Daily Spend":6250,"Date":"2023-09-02","x":1693612800000,"y":6250,"fill":"#f68f2d"},{"date_produced":"2023-09-03","party":"KO","spend":9750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":9750,"Date":"2023-09-03","x":1693699200000,"y":9750,"fill":"#f68f2d"},{"date_produced":"2023-09-04","party":"KO","spend":11750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":11750,"Date":"2023-09-04","x":1693785600000,"y":11750,"fill":"#f68f2d"},{"date_produced":"2023-09-05","party":"KO","spend":13500,"total_spend":123750,"colors":"#f68f2d","Daily Spend":13500,"Date":"2023-09-05","x":1693872000000,"y":13500,"fill":"#f68f2d"},{"date_produced":"2023-09-06","party":"KO","spend":23250,"total_spend":123750,"colors":"#f68f2d","Daily Spend":23250,"Date":"2023-09-06","x":1693958400000,"y":23250,"fill":"#f68f2d"},{"date_produced":"2023-09-07","party":"KO","spend":42500,"total_spend":123750,"colors":"#f68f2d","Daily Spend":42500,"Date":"2023-09-07","x":1694044800000,"y":42500,"fill":"#f68f2d"},{"date_produced":"2023-09-08","party":"KO","spend":78750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":78750,"Date":"2023-09-08","x":1694131200000,"y":78750,"fill":"#f68f2d"},{"date_produced":"2023-09-09","party":"KO","spend":119000,"total_spend":123750,"colors":"#f68f2d","Daily Spend":119000,"Date":"2023-09-09","x":1694217600000,"y":119000,"fill":"#f68f2d"},{"date_produced":"2023-09-10","party":"KO","spend":161750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":161750,"Date":"2023-09-10","x":1694304000000,"y":161750,"fill":"#f68f2d"},{"date_produced":"2023-09-11","party":"KO","spend":246250,"total_spend":123750,"colors":"#f68f2d","Daily Spend":246250,"Date":"2023-09-11","x":1694390400000,"y":246250,"fill":"#f68f2d"},{"date_produced":"2023-09-12","party":"KO","spend":299000,"total_spend":123750,"colors":"#f68f2d","Daily Spend":299000,"Date":"2023-09-12","x":1694476800000,"y":299000,"fill":"#f68f2d"},{"date_produced":"2023-09-13","party":"KO","spend":351250,"total_spend":123750,"colors":"#f68f2d","Daily Spend":351250,"Date":"2023-09-13","x":1694563200000,"y":351250,"fill":"#f68f2d"},{"date_produced":"2023-09-14","party":"KO","spend":392500,"total_spend":123750,"colors":"#f68f2d","Daily Spend":392500,"Date":"2023-09-14","x":1694649600000,"y":392500,"fill":"#f68f2d"},{"date_produced":"2023-09-15","party":"KO","spend":486000,"total_spend":123750,"colors":"#f68f2d","Daily Spend":486000,"Date":"2023-09-15","x":1694736000000,"y":486000,"fill":"#f68f2d"},{"date_produced":"2023-09-16","party":"KO","spend":581500,"total_spend":123750,"colors":"#f68f2d","Daily Spend":581500,"Date":"2023-09-16","x":1694822400000,"y":581500,"fill":"#f68f2d"},{"date_produced":"2023-09-17","party":"KO","spend":705250,"total_spend":123750,"colors":"#f68f2d","Daily Spend":705250,"Date":"2023-09-17","x":1694908800000,"y":705250,"fill":"#f68f2d"},{"date_produced":"2023-09-18","party":"KO","spend":807000,"total_spend":123750,"colors":"#f68f2d","Daily Spend":807000,"Date":"2023-09-18","x":1694995200000,"y":807000,"fill":"#f68f2d"},{"date_produced":"2023-09-19","party":"KO","spend":838750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":838750,"Date":"2023-09-19","x":1695081600000,"y":838750,"fill":"#f68f2d"},{"date_produced":"2023-09-20","party":"KO","spend":887750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":887750,"Date":"2023-09-20","x":1695168000000,"y":887750,"fill":"#f68f2d"},{"date_produced":"2023-09-21","party":"KO","spend":916500,"total_spend":123750,"colors":"#f68f2d","Daily Spend":916500,"Date":"2023-09-21","x":1695254400000,"y":916500,"fill":"#f68f2d"},{"date_produced":"2023-09-22","party":"KO","spend":945000,"total_spend":123750,"colors":"#f68f2d","Daily Spend":945000,"Date":"2023-09-22","x":1695340800000,"y":945000,"fill":"#f68f2d"},{"date_produced":"2023-09-23","party":"KO","spend":963750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":963750,"Date":"2023-09-23","x":1695427200000,"y":963750,"fill":"#f68f2d"},{"date_produced":"2023-09-24","party":"KO","spend":981750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":981750,"Date":"2023-09-24","x":1695513600000,"y":981750,"fill":"#f68f2d"},{"date_produced":"2023-09-25","party":"KO","spend":1004500,"total_spend":123750,"colors":"#f68f2d","Daily Spend":1004500,"Date":"2023-09-25","x":1695600000000,"y":1004500,"fill":"#f68f2d"},{"date_produced":"2023-09-26","party":"KO","spend":1026500,"total_spend":123750,"colors":"#f68f2d","Daily Spend":1026500,"Date":"2023-09-26","x":1695686400000,"y":1026500,"fill":"#f68f2d"},{"date_produced":"2023-09-27","party":"KO","spend":1049750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":1049750,"Date":"2023-09-27","x":1695772800000,"y":1049750,"fill":"#f68f2d"},{"date_produced":"2023-09-28","party":"KO","spend":1068750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":1068750,"Date":"2023-09-28","x":1695859200000,"y":1068750,"fill":"#f68f2d"},{"date_produced":"2023-09-29","party":"KO","spend":1099250,"total_spend":123750,"colors":"#f68f2d","Daily Spend":1099250,"Date":"2023-09-29","x":1695945600000,"y":1099250,"fill":"#f68f2d"},{"date_produced":"2023-09-30","party":"KO","spend":1112500,"total_spend":123750,"colors":"#f68f2d","Daily Spend":1112500,"Date":"2023-09-30","x":1696032000000,"y":1112500,"fill":"#f68f2d"},{"date_produced":"2023-10-01","party":"KO","spend":1114500,"total_spend":123750,"colors":"#f68f2d","Daily Spend":1114500,"Date":"2023-10-01","x":1696118400000,"y":1114500,"fill":"#f68f2d"},{"date_produced":"2023-10-02","party":"KO","spend":1117250,"total_spend":123750,"colors":"#f68f2d","Daily Spend":1117250,"Date":"2023-10-02","x":1696204800000,"y":1117250,"fill":"#f68f2d"}],"type":"area"},{"name":"ZP","data":[{"date_produced":"2023-09-01","party":"ZP","spend":117500,"total_spend":135750,"colors":"#263778","Daily Spend":117500,"Date":"2023-09-01","x":1693526400000,"y":117500,"fill":"#263778"},{"date_produced":"2023-09-02","party":"ZP","spend":221750,"total_spend":135750,"colors":"#263778","Daily Spend":221750,"Date":"2023-09-02","x":1693612800000,"y":221750,"fill":"#263778"},{"date_produced":"2023-09-03","party":"ZP","spend":336500,"total_spend":135750,"colors":"#263778","Daily Spend":336500,"Date":"2023-09-03","x":1693699200000,"y":336500,"fill":"#263778"},{"date_produced":"2023-09-04","party":"ZP","spend":448500,"total_spend":135750,"colors":"#263778","Daily Spend":448500,"Date":"2023-09-04","x":1693785600000,"y":448500,"fill":"#263778"},{"date_produced":"2023-09-05","party":"ZP","spend":560750,"total_spend":135750,"colors":"#263778","Daily Spend":560750,"Date":"2023-09-05","x":1693872000000,"y":560750,"fill":"#263778"},{"date_produced":"2023-09-06","party":"ZP","spend":683500,"total_spend":135750,"colors":"#263778","Daily Spend":683500,"Date":"2023-09-06","x":1693958400000,"y":683500,"fill":"#263778"},{"date_produced":"2023-09-07","party":"ZP","spend":792750,"total_spend":135750,"colors":"#263778","Daily Spend":792750,"Date":"2023-09-07","x":1694044800000,"y":792750,"fill":"#263778"},{"date_produced":"2023-09-08","party":"ZP","spend":915250,"total_spend":135750,"colors":"#263778","Daily Spend":915250,"Date":"2023-09-08","x":1694131200000,"y":915250,"fill":"#263778"},{"date_produced":"2023-09-09","party":"ZP","spend":1039000,"total_spend":135750,"colors":"#263778","Daily Spend":1039000,"Date":"2023-09-09","x":1694217600000,"y":1039000,"fill":"#263778"},{"date_produced":"2023-09-10","party":"ZP","spend":1137500,"total_spend":135750,"colors":"#263778","Daily Spend":1137500,"Date":"2023-09-10","x":1694304000000,"y":1137500,"fill":"#263778"},{"date_produced":"2023-09-11","party":"ZP","spend":1255250,"total_spend":135750,"colors":"#263778","Daily Spend":1255250,"Date":"2023-09-11","x":1694390400000,"y":1255250,"fill":"#263778"},{"date_produced":"2023-09-12","party":"ZP","spend":1362250,"total_spend":135750,"colors":"#263778","Daily Spend":1362250,"Date":"2023-09-12","x":1694476800000,"y":1362250,"fill":"#263778"},{"date_produced":"2023-09-13","party":"ZP","spend":1470500,"total_spend":135750,"colors":"#263778","Daily Spend":1470500,"Date":"2023-09-13","x":1694563200000,"y":1470500,"fill":"#263778"},{"date_produced":"2023-09-14","party":"ZP","spend":1606250,"total_spend":135750,"colors":"#263778","Daily Spend":1606250,"Date":"2023-09-14","x":1694649600000,"y":1606250,"fill":"#263778"},{"date_produced":"2023-09-15","party":"ZP","spend":1681750,"total_spend":135750,"colors":"#263778","Daily Spend":1681750,"Date":"2023-09-15","x":1694736000000,"y":1681750,"fill":"#263778"},{"date_produced":"2023-09-16","party":"ZP","spend":1749500,"total_spend":135750,"colors":"#263778","Daily Spend":1749500,"Date":"2023-09-16","x":1694822400000,"y":1749500,"fill":"#263778"},{"date_produced":"2023-09-17","party":"ZP","spend":1836750,"total_spend":135750,"colors":"#263778","Daily Spend":1836750,"Date":"2023-09-17","x":1694908800000,"y":1836750,"fill":"#263778"},{"date_produced":"2023-09-18","party":"ZP","spend":1939750,"total_spend":135750,"colors":"#263778","Daily Spend":1939750,"Date":"2023-09-18","x":1694995200000,"y":1939750,"fill":"#263778"},{"date_produced":"2023-09-19","party":"ZP","spend":2058750,"total_spend":135750,"colors":"#263778","Daily Spend":2058750,"Date":"2023-09-19","x":1695081600000,"y":2058750,"fill":"#263778"},{"date_produced":"2023-09-20","party":"ZP","spend":2128750,"total_spend":135750,"colors":"#263778","Daily Spend":2128750,"Date":"2023-09-20","x":1695168000000,"y":2128750,"fill":"#263778"},{"date_produced":"2023-09-21","party":"ZP","spend":2220000,"total_spend":135750,"colors":"#263778","Daily Spend":2220000,"Date":"2023-09-21","x":1695254400000,"y":2220000,"fill":"#263778"},{"date_produced":"2023-09-22","party":"ZP","spend":2310250,"total_spend":135750,"colors":"#263778","Daily Spend":2310250,"Date":"2023-09-22","x":1695340800000,"y":2310250,"fill":"#263778"},{"date_produced":"2023-09-23","party":"ZP","spend":2404250,"total_spend":135750,"colors":"#263778","Daily Spend":2404250,"Date":"2023-09-23","x":1695427200000,"y":2404250,"fill":"#263778"},{"date_produced":"2023-09-24","party":"ZP","spend":2494000,"total_spend":135750,"colors":"#263778","Daily Spend":2494000,"Date":"2023-09-24","x":1695513600000,"y":2494000,"fill":"#263778"},{"date_produced":"2023-09-25","party":"ZP","spend":2583750,"total_spend":135750,"colors":"#263778","Daily Spend":2583750,"Date":"2023-09-25","x":1695600000000,"y":2583750,"fill":"#263778"},{"date_produced":"2023-09-26","party":"ZP","spend":2668750,"total_spend":135750,"colors":"#263778","Daily Spend":2668750,"Date":"2023-09-26","x":1695686400000,"y":2668750,"fill":"#263778"},{"date_produced":"2023-09-27","party":"ZP","spend":2753750,"total_spend":135750,"colors":"#263778","Daily Spend":2753750,"Date":"2023-09-27","x":1695772800000,"y":2753750,"fill":"#263778"},{"date_produced":"2023-09-28","party":"ZP","spend":2828250,"total_spend":135750,"colors":"#263778","Daily Spend":2828250,"Date":"2023-09-28","x":1695859200000,"y":2828250,"fill":"#263778"},{"date_produced":"2023-09-29","party":"ZP","spend":2902000,"total_spend":135750,"colors":"#263778","Daily Spend":2902000,"Date":"2023-09-29","x":1695945600000,"y":2902000,"fill":"#263778"},{"date_produced":"2023-09-30","party":"ZP","spend":2967500,"total_spend":135750,"colors":"#263778","Daily Spend":2967500,"Date":"2023-09-30","x":1696032000000,"y":2967500,"fill":"#263778"},{"date_produced":"2023-10-01","party":"ZP","spend":3055250,"total_spend":135750,"colors":"#263778","Daily Spend":3055250,"Date":"2023-10-01","x":1696118400000,"y":3055250,"fill":"#263778"},{"date_produced":"2023-10-02","party":"ZP","spend":3140000,"total_spend":135750,"colors":"#263778","Daily Spend":3140000,"Date":"2023-10-02","x":1696204800000,"y":3140000,"fill":"#263778"}],"type":"area"}],"xAxis":{"type":"datetime","title":{"text":"Date"},"categories":null},"colors":["#3db53a","#e6001a","#122746","#851a64","#f68f2d","#263778"],"tooltip":{"shared":true,"positioner":"function (labelWidth, labelHeight, point) {\n        return { x: 200, y: this.chart.plotTop };\n    }"}},"theme":{"chart":{"backgroundColor":"transparent"},"colors":["#7cb5ec","#434348","#90ed7d","#f7a35c","#8085e9","#f15c80","#e4d354","#2b908f","#f45b5b","#91e8e1"]},"conf_opts":{"global":{"Date":null,"VMLRadialGradientURL":"http =//code.highcharts.com/list(version)/gfx/vml-radial-gradient.png","canvasToolsURL":"http =//code.highcharts.com/list(version)/modules/canvas-tools.js","getTimezoneOffset":null,"timezoneOffset":0,"useUTC":true},"lang":{"contextButtonTitle":"Chart context menu","decimalPoint":".","downloadCSV":"Download CSV","downloadJPEG":"Download JPEG image","downloadPDF":"Download PDF document","downloadPNG":"Download PNG image","downloadSVG":"Download SVG vector image","downloadXLS":"Download XLS","drillUpText":"◁ Back to {series.name}","exitFullscreen":"Exit from full screen","exportData":{"annotationHeader":"Annotations","categoryDatetimeHeader":"DateTime","categoryHeader":"Category"},"hideData":"Hide data table","invalidDate":null,"loading":"Loading...","months":["January","February","March","April","May","June","July","August","September","October","November","December"],"noData":"No data to display","numericSymbolMagnitude":1000,"numericSymbols":["k","M","G","T","P","E"],"printChart":"Print chart","resetZoom":"Reset zoom","resetZoomTitle":"Reset zoom level 1:1","shortMonths":["Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"],"shortWeekdays":["Sat","Sun","Mon","Tue","Wed","Thu","Fri"],"thousandsSep":" ","viewData":"View data table","viewFullscreen":"View in full screen","weekdays":["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday"]}},"type":"chart","fonts":[],"debug":false},"evals":["hc_opts.tooltip.positioner"],"jsHooks":[]}</script>
```
:::
:::





### Daily


::: {.cell}
::: {.cell-output-display}
```{=html}
<div class="highchart html-widget html-fill-item-overflow-hidden html-fill-item" id="htmlwidget-1daccc7d6fcf54064988" style="width:100%;height:480px;"></div>
<script type="application/json" data-for="htmlwidget-1daccc7d6fcf54064988">{"x":{"hc_opts":{"chart":{"reflow":true},"title":{"text":null},"yAxis":{"title":{"text":"Daily Spend"},"type":"linear"},"credits":{"enabled":false},"exporting":{"enabled":false},"boost":{"enabled":false},"plotOptions":{"series":{"label":{"enabled":false},"turboThreshold":0,"showInLegend":true},"treemap":{"layoutAlgorithm":"squarified"},"scatter":{"marker":{"symbol":"circle"}},"area":{"stacking":"normal","lineWidth":1,"marker":{"enabled":false}}},"series":[{"name":"TD","data":[{"date_produced":"2023-09-01","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-01","x":1693526400000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-02","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-02","x":1693612800000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-03","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-03","x":1693699200000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-04","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-04","x":1693785600000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-05","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-05","x":1693872000000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-06","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-06","x":1693958400000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-07","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-07","x":1694044800000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-08","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-08","x":1694131200000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-09","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-09","x":1694217600000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-10","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-10","x":1694304000000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-11","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-11","x":1694390400000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-12","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-12","x":1694476800000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-13","party":"TD","spend":0,"total_spend":2750,"colors":"#3db53a","Daily Spend":0,"Date":"2023-09-13","x":1694563200000,"y":0,"fill":"#3db53a"},{"date_produced":"2023-09-14","party":"TD","spend":250,"total_spend":2750,"colors":"#3db53a","Daily Spend":250,"Date":"2023-09-14","x":1694649600000,"y":250,"fill":"#3db53a"},{"date_produced":"2023-09-15","party":"TD","spend":250,"total_spend":2750,"colors":"#3db53a","Daily Spend":250,"Date":"2023-09-15","x":1694736000000,"y":250,"fill":"#3db53a"},{"date_produced":"2023-09-16","party":"TD","spend":250,"total_spend":2750,"colors":"#3db53a","Daily Spend":250,"Date":"2023-09-16","x":1694822400000,"y":250,"fill":"#3db53a"},{"date_produced":"2023-09-17","party":"TD","spend":500,"total_spend":2750,"colors":"#3db53a","Daily Spend":500,"Date":"2023-09-17","x":1694908800000,"y":500,"fill":"#3db53a"},{"date_produced":"2023-09-18","party":"TD","spend":1000,"total_spend":2750,"colors":"#3db53a","Daily Spend":1000,"Date":"2023-09-18","x":1694995200000,"y":1000,"fill":"#3db53a"},{"date_produced":"2023-09-19","party":"TD","spend":1000,"total_spend":2750,"colors":"#3db53a","Daily Spend":1000,"Date":"2023-09-19","x":1695081600000,"y":1000,"fill":"#3db53a"},{"date_produced":"2023-09-20","party":"TD","spend":1750,"total_spend":2750,"colors":"#3db53a","Daily Spend":1750,"Date":"2023-09-20","x":1695168000000,"y":1750,"fill":"#3db53a"},{"date_produced":"2023-09-21","party":"TD","spend":1250,"total_spend":2750,"colors":"#3db53a","Daily Spend":1250,"Date":"2023-09-21","x":1695254400000,"y":1250,"fill":"#3db53a"},{"date_produced":"2023-09-22","party":"TD","spend":1500,"total_spend":2750,"colors":"#3db53a","Daily Spend":1500,"Date":"2023-09-22","x":1695340800000,"y":1500,"fill":"#3db53a"},{"date_produced":"2023-09-23","party":"TD","spend":1500,"total_spend":2750,"colors":"#3db53a","Daily Spend":1500,"Date":"2023-09-23","x":1695427200000,"y":1500,"fill":"#3db53a"},{"date_produced":"2023-09-24","party":"TD","spend":1500,"total_spend":2750,"colors":"#3db53a","Daily Spend":1500,"Date":"2023-09-24","x":1695513600000,"y":1500,"fill":"#3db53a"},{"date_produced":"2023-09-25","party":"TD","spend":2250,"total_spend":2750,"colors":"#3db53a","Daily Spend":2250,"Date":"2023-09-25","x":1695600000000,"y":2250,"fill":"#3db53a"},{"date_produced":"2023-09-26","party":"TD","spend":2250,"total_spend":2750,"colors":"#3db53a","Daily Spend":2250,"Date":"2023-09-26","x":1695686400000,"y":2250,"fill":"#3db53a"},{"date_produced":"2023-09-27","party":"TD","spend":2750,"total_spend":2750,"colors":"#3db53a","Daily Spend":2750,"Date":"2023-09-27","x":1695772800000,"y":2750,"fill":"#3db53a"},{"date_produced":"2023-09-28","party":"TD","spend":2000,"total_spend":2750,"colors":"#3db53a","Daily Spend":2000,"Date":"2023-09-28","x":1695859200000,"y":2000,"fill":"#3db53a"},{"date_produced":"2023-09-29","party":"TD","spend":1250,"total_spend":2750,"colors":"#3db53a","Daily Spend":1250,"Date":"2023-09-29","x":1695945600000,"y":1250,"fill":"#3db53a"},{"date_produced":"2023-09-30","party":"TD","spend":1000,"total_spend":2750,"colors":"#3db53a","Daily Spend":1000,"Date":"2023-09-30","x":1696032000000,"y":1000,"fill":"#3db53a"},{"date_produced":"2023-10-01","party":"TD","spend":1750,"total_spend":2750,"colors":"#3db53a","Daily Spend":1750,"Date":"2023-10-01","x":1696118400000,"y":1750,"fill":"#3db53a"},{"date_produced":"2023-10-02","party":"TD","spend":2000,"total_spend":2750,"colors":"#3db53a","Daily Spend":2000,"Date":"2023-10-02","x":1696204800000,"y":2000,"fill":"#3db53a"}],"type":"area"},{"name":"BS","data":[{"date_produced":"2023-09-01","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-01","x":1693526400000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-02","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-02","x":1693612800000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-03","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-03","x":1693699200000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-04","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-04","x":1693785600000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-05","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-05","x":1693872000000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-06","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-06","x":1693958400000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-07","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-07","x":1694044800000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-08","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-08","x":1694131200000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-09","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-09","x":1694217600000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-10","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-10","x":1694304000000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-11","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-11","x":1694390400000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-12","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-12","x":1694476800000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-13","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-13","x":1694563200000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-14","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-14","x":1694649600000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-15","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-15","x":1694736000000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-16","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-16","x":1694822400000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-17","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-17","x":1694908800000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-18","party":"BS","spend":250,"total_spend":4000,"colors":"#e6001a","Daily Spend":250,"Date":"2023-09-18","x":1694995200000,"y":250,"fill":"#e6001a"},{"date_produced":"2023-09-19","party":"BS","spend":500,"total_spend":4000,"colors":"#e6001a","Daily Spend":500,"Date":"2023-09-19","x":1695081600000,"y":500,"fill":"#e6001a"},{"date_produced":"2023-09-20","party":"BS","spend":1000,"total_spend":4000,"colors":"#e6001a","Daily Spend":1000,"Date":"2023-09-20","x":1695168000000,"y":1000,"fill":"#e6001a"},{"date_produced":"2023-09-21","party":"BS","spend":1500,"total_spend":4000,"colors":"#e6001a","Daily Spend":1500,"Date":"2023-09-21","x":1695254400000,"y":1500,"fill":"#e6001a"},{"date_produced":"2023-09-22","party":"BS","spend":1500,"total_spend":4000,"colors":"#e6001a","Daily Spend":1500,"Date":"2023-09-22","x":1695340800000,"y":1500,"fill":"#e6001a"},{"date_produced":"2023-09-23","party":"BS","spend":1500,"total_spend":4000,"colors":"#e6001a","Daily Spend":1500,"Date":"2023-09-23","x":1695427200000,"y":1500,"fill":"#e6001a"},{"date_produced":"2023-09-24","party":"BS","spend":1500,"total_spend":4000,"colors":"#e6001a","Daily Spend":1500,"Date":"2023-09-24","x":1695513600000,"y":1500,"fill":"#e6001a"},{"date_produced":"2023-09-25","party":"BS","spend":1500,"total_spend":4000,"colors":"#e6001a","Daily Spend":1500,"Date":"2023-09-25","x":1695600000000,"y":1500,"fill":"#e6001a"},{"date_produced":"2023-09-26","party":"BS","spend":1250,"total_spend":4000,"colors":"#e6001a","Daily Spend":1250,"Date":"2023-09-26","x":1695686400000,"y":1250,"fill":"#e6001a"},{"date_produced":"2023-09-27","party":"BS","spend":1500,"total_spend":4000,"colors":"#e6001a","Daily Spend":1500,"Date":"2023-09-27","x":1695772800000,"y":1500,"fill":"#e6001a"},{"date_produced":"2023-09-28","party":"BS","spend":3250,"total_spend":4000,"colors":"#e6001a","Daily Spend":3250,"Date":"2023-09-28","x":1695859200000,"y":3250,"fill":"#e6001a"},{"date_produced":"2023-09-29","party":"BS","spend":3000,"total_spend":4000,"colors":"#e6001a","Daily Spend":3000,"Date":"2023-09-29","x":1695945600000,"y":3000,"fill":"#e6001a"},{"date_produced":"2023-09-30","party":"BS","spend":1500,"total_spend":4000,"colors":"#e6001a","Daily Spend":1500,"Date":"2023-09-30","x":1696032000000,"y":1500,"fill":"#e6001a"},{"date_produced":"2023-10-01","party":"BS","spend":3000,"total_spend":4000,"colors":"#e6001a","Daily Spend":3000,"Date":"2023-10-01","x":1696118400000,"y":3000,"fill":"#e6001a"},{"date_produced":"2023-10-02","party":"BS","spend":4000,"total_spend":4000,"colors":"#e6001a","Daily Spend":4000,"Date":"2023-10-02","x":1696204800000,"y":4000,"fill":"#e6001a"}],"type":"area"},{"name":"KWIN","data":[{"date_produced":"2023-09-01","party":"KWIN","spend":0,"total_spend":8500,"colors":"#122746","Daily Spend":0,"Date":"2023-09-01","x":1693526400000,"y":0,"fill":"#122746"},{"date_produced":"2023-09-02","party":"KWIN","spend":0,"total_spend":8500,"colors":"#122746","Daily Spend":0,"Date":"2023-09-02","x":1693612800000,"y":0,"fill":"#122746"},{"date_produced":"2023-09-03","party":"KWIN","spend":0,"total_spend":8500,"colors":"#122746","Daily Spend":0,"Date":"2023-09-03","x":1693699200000,"y":0,"fill":"#122746"},{"date_produced":"2023-09-04","party":"KWIN","spend":0,"total_spend":8500,"colors":"#122746","Daily Spend":0,"Date":"2023-09-04","x":1693785600000,"y":0,"fill":"#122746"},{"date_produced":"2023-09-05","party":"KWIN","spend":750,"total_spend":8500,"colors":"#122746","Daily Spend":750,"Date":"2023-09-05","x":1693872000000,"y":750,"fill":"#122746"},{"date_produced":"2023-09-06","party":"KWIN","spend":6000,"total_spend":8500,"colors":"#122746","Daily Spend":6000,"Date":"2023-09-06","x":1693958400000,"y":6000,"fill":"#122746"},{"date_produced":"2023-09-07","party":"KWIN","spend":3000,"total_spend":8500,"colors":"#122746","Daily Spend":3000,"Date":"2023-09-07","x":1694044800000,"y":3000,"fill":"#122746"},{"date_produced":"2023-09-08","party":"KWIN","spend":250,"total_spend":8500,"colors":"#122746","Daily Spend":250,"Date":"2023-09-08","x":1694131200000,"y":250,"fill":"#122746"},{"date_produced":"2023-09-09","party":"KWIN","spend":250,"total_spend":8500,"colors":"#122746","Daily Spend":250,"Date":"2023-09-09","x":1694217600000,"y":250,"fill":"#122746"},{"date_produced":"2023-09-10","party":"KWIN","spend":250,"total_spend":8500,"colors":"#122746","Daily Spend":250,"Date":"2023-09-10","x":1694304000000,"y":250,"fill":"#122746"},{"date_produced":"2023-09-11","party":"KWIN","spend":500,"total_spend":8500,"colors":"#122746","Daily Spend":500,"Date":"2023-09-11","x":1694390400000,"y":500,"fill":"#122746"},{"date_produced":"2023-09-12","party":"KWIN","spend":250,"total_spend":8500,"colors":"#122746","Daily Spend":250,"Date":"2023-09-12","x":1694476800000,"y":250,"fill":"#122746"},{"date_produced":"2023-09-13","party":"KWIN","spend":250,"total_spend":8500,"colors":"#122746","Daily Spend":250,"Date":"2023-09-13","x":1694563200000,"y":250,"fill":"#122746"},{"date_produced":"2023-09-14","party":"KWIN","spend":250,"total_spend":8500,"colors":"#122746","Daily Spend":250,"Date":"2023-09-14","x":1694649600000,"y":250,"fill":"#122746"},{"date_produced":"2023-09-15","party":"KWIN","spend":250,"total_spend":8500,"colors":"#122746","Daily Spend":250,"Date":"2023-09-15","x":1694736000000,"y":250,"fill":"#122746"},{"date_produced":"2023-09-16","party":"KWIN","spend":250,"total_spend":8500,"colors":"#122746","Daily Spend":250,"Date":"2023-09-16","x":1694822400000,"y":250,"fill":"#122746"},{"date_produced":"2023-09-17","party":"KWIN","spend":250,"total_spend":8500,"colors":"#122746","Daily Spend":250,"Date":"2023-09-17","x":1694908800000,"y":250,"fill":"#122746"},{"date_produced":"2023-09-18","party":"KWIN","spend":250,"total_spend":8500,"colors":"#122746","Daily Spend":250,"Date":"2023-09-18","x":1694995200000,"y":250,"fill":"#122746"},{"date_produced":"2023-09-19","party":"KWIN","spend":250,"total_spend":8500,"colors":"#122746","Daily Spend":250,"Date":"2023-09-19","x":1695081600000,"y":250,"fill":"#122746"},{"date_produced":"2023-09-20","party":"KWIN","spend":1250,"total_spend":8500,"colors":"#122746","Daily Spend":1250,"Date":"2023-09-20","x":1695168000000,"y":1250,"fill":"#122746"},{"date_produced":"2023-09-21","party":"KWIN","spend":1500,"total_spend":8500,"colors":"#122746","Daily Spend":1500,"Date":"2023-09-21","x":1695254400000,"y":1500,"fill":"#122746"},{"date_produced":"2023-09-22","party":"KWIN","spend":750,"total_spend":8500,"colors":"#122746","Daily Spend":750,"Date":"2023-09-22","x":1695340800000,"y":750,"fill":"#122746"},{"date_produced":"2023-09-23","party":"KWIN","spend":4250,"total_spend":8500,"colors":"#122746","Daily Spend":4250,"Date":"2023-09-23","x":1695427200000,"y":4250,"fill":"#122746"},{"date_produced":"2023-09-24","party":"KWIN","spend":3250,"total_spend":8500,"colors":"#122746","Daily Spend":3250,"Date":"2023-09-24","x":1695513600000,"y":3250,"fill":"#122746"},{"date_produced":"2023-09-25","party":"KWIN","spend":2250,"total_spend":8500,"colors":"#122746","Daily Spend":2250,"Date":"2023-09-25","x":1695600000000,"y":2250,"fill":"#122746"},{"date_produced":"2023-09-26","party":"KWIN","spend":8500,"total_spend":8500,"colors":"#122746","Daily Spend":8500,"Date":"2023-09-26","x":1695686400000,"y":8500,"fill":"#122746"},{"date_produced":"2023-09-27","party":"KWIN","spend":4500,"total_spend":8500,"colors":"#122746","Daily Spend":4500,"Date":"2023-09-27","x":1695772800000,"y":4500,"fill":"#122746"},{"date_produced":"2023-09-28","party":"KWIN","spend":4250,"total_spend":8500,"colors":"#122746","Daily Spend":4250,"Date":"2023-09-28","x":1695859200000,"y":4250,"fill":"#122746"},{"date_produced":"2023-09-29","party":"KWIN","spend":7000,"total_spend":8500,"colors":"#122746","Daily Spend":7000,"Date":"2023-09-29","x":1695945600000,"y":7000,"fill":"#122746"},{"date_produced":"2023-09-30","party":"KWIN","spend":8250,"total_spend":8500,"colors":"#122746","Daily Spend":8250,"Date":"2023-09-30","x":1696032000000,"y":8250,"fill":"#122746"},{"date_produced":"2023-10-01","party":"KWIN","spend":4500,"total_spend":8500,"colors":"#122746","Daily Spend":4500,"Date":"2023-10-01","x":1696118400000,"y":4500,"fill":"#122746"},{"date_produced":"2023-10-02","party":"KWIN","spend":4000,"total_spend":8500,"colors":"#122746","Daily Spend":4000,"Date":"2023-10-02","x":1696204800000,"y":4000,"fill":"#122746"}],"type":"area"},{"name":"LEW","data":[{"date_produced":"2023-09-01","party":"LEW","spend":250,"total_spend":14250,"colors":"#851a64","Daily Spend":250,"Date":"2023-09-01","x":1693526400000,"y":250,"fill":"#851a64"},{"date_produced":"2023-09-02","party":"LEW","spend":250,"total_spend":14250,"colors":"#851a64","Daily Spend":250,"Date":"2023-09-02","x":1693612800000,"y":250,"fill":"#851a64"},{"date_produced":"2023-09-03","party":"LEW","spend":250,"total_spend":14250,"colors":"#851a64","Daily Spend":250,"Date":"2023-09-03","x":1693699200000,"y":250,"fill":"#851a64"},{"date_produced":"2023-09-04","party":"LEW","spend":250,"total_spend":14250,"colors":"#851a64","Daily Spend":250,"Date":"2023-09-04","x":1693785600000,"y":250,"fill":"#851a64"},{"date_produced":"2023-09-05","party":"LEW","spend":250,"total_spend":14250,"colors":"#851a64","Daily Spend":250,"Date":"2023-09-05","x":1693872000000,"y":250,"fill":"#851a64"},{"date_produced":"2023-09-06","party":"LEW","spend":250,"total_spend":14250,"colors":"#851a64","Daily Spend":250,"Date":"2023-09-06","x":1693958400000,"y":250,"fill":"#851a64"},{"date_produced":"2023-09-07","party":"LEW","spend":250,"total_spend":14250,"colors":"#851a64","Daily Spend":250,"Date":"2023-09-07","x":1694044800000,"y":250,"fill":"#851a64"},{"date_produced":"2023-09-08","party":"LEW","spend":250,"total_spend":14250,"colors":"#851a64","Daily Spend":250,"Date":"2023-09-08","x":1694131200000,"y":250,"fill":"#851a64"},{"date_produced":"2023-09-09","party":"LEW","spend":250,"total_spend":14250,"colors":"#851a64","Daily Spend":250,"Date":"2023-09-09","x":1694217600000,"y":250,"fill":"#851a64"},{"date_produced":"2023-09-10","party":"LEW","spend":250,"total_spend":14250,"colors":"#851a64","Daily Spend":250,"Date":"2023-09-10","x":1694304000000,"y":250,"fill":"#851a64"},{"date_produced":"2023-09-11","party":"LEW","spend":250,"total_spend":14250,"colors":"#851a64","Daily Spend":250,"Date":"2023-09-11","x":1694390400000,"y":250,"fill":"#851a64"},{"date_produced":"2023-09-12","party":"LEW","spend":250,"total_spend":14250,"colors":"#851a64","Daily Spend":250,"Date":"2023-09-12","x":1694476800000,"y":250,"fill":"#851a64"},{"date_produced":"2023-09-13","party":"LEW","spend":5000,"total_spend":14250,"colors":"#851a64","Daily Spend":5000,"Date":"2023-09-13","x":1694563200000,"y":5000,"fill":"#851a64"},{"date_produced":"2023-09-14","party":"LEW","spend":2750,"total_spend":14250,"colors":"#851a64","Daily Spend":2750,"Date":"2023-09-14","x":1694649600000,"y":2750,"fill":"#851a64"},{"date_produced":"2023-09-15","party":"LEW","spend":2750,"total_spend":14250,"colors":"#851a64","Daily Spend":2750,"Date":"2023-09-15","x":1694736000000,"y":2750,"fill":"#851a64"},{"date_produced":"2023-09-16","party":"LEW","spend":3000,"total_spend":14250,"colors":"#851a64","Daily Spend":3000,"Date":"2023-09-16","x":1694822400000,"y":3000,"fill":"#851a64"},{"date_produced":"2023-09-17","party":"LEW","spend":3500,"total_spend":14250,"colors":"#851a64","Daily Spend":3500,"Date":"2023-09-17","x":1694908800000,"y":3500,"fill":"#851a64"},{"date_produced":"2023-09-18","party":"LEW","spend":3500,"total_spend":14250,"colors":"#851a64","Daily Spend":3500,"Date":"2023-09-18","x":1694995200000,"y":3500,"fill":"#851a64"},{"date_produced":"2023-09-19","party":"LEW","spend":3250,"total_spend":14250,"colors":"#851a64","Daily Spend":3250,"Date":"2023-09-19","x":1695081600000,"y":3250,"fill":"#851a64"},{"date_produced":"2023-09-20","party":"LEW","spend":8000,"total_spend":14250,"colors":"#851a64","Daily Spend":8000,"Date":"2023-09-20","x":1695168000000,"y":8000,"fill":"#851a64"},{"date_produced":"2023-09-21","party":"LEW","spend":7500,"total_spend":14250,"colors":"#851a64","Daily Spend":7500,"Date":"2023-09-21","x":1695254400000,"y":7500,"fill":"#851a64"},{"date_produced":"2023-09-22","party":"LEW","spend":9750,"total_spend":14250,"colors":"#851a64","Daily Spend":9750,"Date":"2023-09-22","x":1695340800000,"y":9750,"fill":"#851a64"},{"date_produced":"2023-09-23","party":"LEW","spend":10750,"total_spend":14250,"colors":"#851a64","Daily Spend":10750,"Date":"2023-09-23","x":1695427200000,"y":10750,"fill":"#851a64"},{"date_produced":"2023-09-24","party":"LEW","spend":10250,"total_spend":14250,"colors":"#851a64","Daily Spend":10250,"Date":"2023-09-24","x":1695513600000,"y":10250,"fill":"#851a64"},{"date_produced":"2023-09-25","party":"LEW","spend":7500,"total_spend":14250,"colors":"#851a64","Daily Spend":7500,"Date":"2023-09-25","x":1695600000000,"y":7500,"fill":"#851a64"},{"date_produced":"2023-09-26","party":"LEW","spend":10750,"total_spend":14250,"colors":"#851a64","Daily Spend":10750,"Date":"2023-09-26","x":1695686400000,"y":10750,"fill":"#851a64"},{"date_produced":"2023-09-27","party":"LEW","spend":14250,"total_spend":14250,"colors":"#851a64","Daily Spend":14250,"Date":"2023-09-27","x":1695772800000,"y":14250,"fill":"#851a64"},{"date_produced":"2023-09-28","party":"LEW","spend":7000,"total_spend":14250,"colors":"#851a64","Daily Spend":7000,"Date":"2023-09-28","x":1695859200000,"y":7000,"fill":"#851a64"},{"date_produced":"2023-09-29","party":"LEW","spend":8750,"total_spend":14250,"colors":"#851a64","Daily Spend":8750,"Date":"2023-09-29","x":1695945600000,"y":8750,"fill":"#851a64"},{"date_produced":"2023-09-30","party":"LEW","spend":9000,"total_spend":14250,"colors":"#851a64","Daily Spend":9000,"Date":"2023-09-30","x":1696032000000,"y":9000,"fill":"#851a64"},{"date_produced":"2023-10-01","party":"LEW","spend":8250,"total_spend":14250,"colors":"#851a64","Daily Spend":8250,"Date":"2023-10-01","x":1696118400000,"y":8250,"fill":"#851a64"},{"date_produced":"2023-10-02","party":"LEW","spend":10000,"total_spend":14250,"colors":"#851a64","Daily Spend":10000,"Date":"2023-10-02","x":1696204800000,"y":10000,"fill":"#851a64"}],"type":"area"},{"name":"KO","data":[{"date_produced":"2023-09-01","party":"KO","spend":3000,"total_spend":123750,"colors":"#f68f2d","Daily Spend":3000,"Date":"2023-09-01","x":1693526400000,"y":3000,"fill":"#f68f2d"},{"date_produced":"2023-09-02","party":"KO","spend":3250,"total_spend":123750,"colors":"#f68f2d","Daily Spend":3250,"Date":"2023-09-02","x":1693612800000,"y":3250,"fill":"#f68f2d"},{"date_produced":"2023-09-03","party":"KO","spend":3500,"total_spend":123750,"colors":"#f68f2d","Daily Spend":3500,"Date":"2023-09-03","x":1693699200000,"y":3500,"fill":"#f68f2d"},{"date_produced":"2023-09-04","party":"KO","spend":2000,"total_spend":123750,"colors":"#f68f2d","Daily Spend":2000,"Date":"2023-09-04","x":1693785600000,"y":2000,"fill":"#f68f2d"},{"date_produced":"2023-09-05","party":"KO","spend":1750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":1750,"Date":"2023-09-05","x":1693872000000,"y":1750,"fill":"#f68f2d"},{"date_produced":"2023-09-06","party":"KO","spend":9750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":9750,"Date":"2023-09-06","x":1693958400000,"y":9750,"fill":"#f68f2d"},{"date_produced":"2023-09-07","party":"KO","spend":19250,"total_spend":123750,"colors":"#f68f2d","Daily Spend":19250,"Date":"2023-09-07","x":1694044800000,"y":19250,"fill":"#f68f2d"},{"date_produced":"2023-09-08","party":"KO","spend":36250,"total_spend":123750,"colors":"#f68f2d","Daily Spend":36250,"Date":"2023-09-08","x":1694131200000,"y":36250,"fill":"#f68f2d"},{"date_produced":"2023-09-09","party":"KO","spend":40250,"total_spend":123750,"colors":"#f68f2d","Daily Spend":40250,"Date":"2023-09-09","x":1694217600000,"y":40250,"fill":"#f68f2d"},{"date_produced":"2023-09-10","party":"KO","spend":42750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":42750,"Date":"2023-09-10","x":1694304000000,"y":42750,"fill":"#f68f2d"},{"date_produced":"2023-09-11","party":"KO","spend":84500,"total_spend":123750,"colors":"#f68f2d","Daily Spend":84500,"Date":"2023-09-11","x":1694390400000,"y":84500,"fill":"#f68f2d"},{"date_produced":"2023-09-12","party":"KO","spend":52750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":52750,"Date":"2023-09-12","x":1694476800000,"y":52750,"fill":"#f68f2d"},{"date_produced":"2023-09-13","party":"KO","spend":52250,"total_spend":123750,"colors":"#f68f2d","Daily Spend":52250,"Date":"2023-09-13","x":1694563200000,"y":52250,"fill":"#f68f2d"},{"date_produced":"2023-09-14","party":"KO","spend":41250,"total_spend":123750,"colors":"#f68f2d","Daily Spend":41250,"Date":"2023-09-14","x":1694649600000,"y":41250,"fill":"#f68f2d"},{"date_produced":"2023-09-15","party":"KO","spend":93500,"total_spend":123750,"colors":"#f68f2d","Daily Spend":93500,"Date":"2023-09-15","x":1694736000000,"y":93500,"fill":"#f68f2d"},{"date_produced":"2023-09-16","party":"KO","spend":95500,"total_spend":123750,"colors":"#f68f2d","Daily Spend":95500,"Date":"2023-09-16","x":1694822400000,"y":95500,"fill":"#f68f2d"},{"date_produced":"2023-09-17","party":"KO","spend":123750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":123750,"Date":"2023-09-17","x":1694908800000,"y":123750,"fill":"#f68f2d"},{"date_produced":"2023-09-18","party":"KO","spend":101750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":101750,"Date":"2023-09-18","x":1694995200000,"y":101750,"fill":"#f68f2d"},{"date_produced":"2023-09-19","party":"KO","spend":31750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":31750,"Date":"2023-09-19","x":1695081600000,"y":31750,"fill":"#f68f2d"},{"date_produced":"2023-09-20","party":"KO","spend":49000,"total_spend":123750,"colors":"#f68f2d","Daily Spend":49000,"Date":"2023-09-20","x":1695168000000,"y":49000,"fill":"#f68f2d"},{"date_produced":"2023-09-21","party":"KO","spend":28750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":28750,"Date":"2023-09-21","x":1695254400000,"y":28750,"fill":"#f68f2d"},{"date_produced":"2023-09-22","party":"KO","spend":28500,"total_spend":123750,"colors":"#f68f2d","Daily Spend":28500,"Date":"2023-09-22","x":1695340800000,"y":28500,"fill":"#f68f2d"},{"date_produced":"2023-09-23","party":"KO","spend":18750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":18750,"Date":"2023-09-23","x":1695427200000,"y":18750,"fill":"#f68f2d"},{"date_produced":"2023-09-24","party":"KO","spend":18000,"total_spend":123750,"colors":"#f68f2d","Daily Spend":18000,"Date":"2023-09-24","x":1695513600000,"y":18000,"fill":"#f68f2d"},{"date_produced":"2023-09-25","party":"KO","spend":22750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":22750,"Date":"2023-09-25","x":1695600000000,"y":22750,"fill":"#f68f2d"},{"date_produced":"2023-09-26","party":"KO","spend":22000,"total_spend":123750,"colors":"#f68f2d","Daily Spend":22000,"Date":"2023-09-26","x":1695686400000,"y":22000,"fill":"#f68f2d"},{"date_produced":"2023-09-27","party":"KO","spend":23250,"total_spend":123750,"colors":"#f68f2d","Daily Spend":23250,"Date":"2023-09-27","x":1695772800000,"y":23250,"fill":"#f68f2d"},{"date_produced":"2023-09-28","party":"KO","spend":19000,"total_spend":123750,"colors":"#f68f2d","Daily Spend":19000,"Date":"2023-09-28","x":1695859200000,"y":19000,"fill":"#f68f2d"},{"date_produced":"2023-09-29","party":"KO","spend":30500,"total_spend":123750,"colors":"#f68f2d","Daily Spend":30500,"Date":"2023-09-29","x":1695945600000,"y":30500,"fill":"#f68f2d"},{"date_produced":"2023-09-30","party":"KO","spend":13250,"total_spend":123750,"colors":"#f68f2d","Daily Spend":13250,"Date":"2023-09-30","x":1696032000000,"y":13250,"fill":"#f68f2d"},{"date_produced":"2023-10-01","party":"KO","spend":2000,"total_spend":123750,"colors":"#f68f2d","Daily Spend":2000,"Date":"2023-10-01","x":1696118400000,"y":2000,"fill":"#f68f2d"},{"date_produced":"2023-10-02","party":"KO","spend":2750,"total_spend":123750,"colors":"#f68f2d","Daily Spend":2750,"Date":"2023-10-02","x":1696204800000,"y":2750,"fill":"#f68f2d"}],"type":"area"},{"name":"ZP","data":[{"date_produced":"2023-09-01","party":"ZP","spend":117500,"total_spend":135750,"colors":"#263778","Daily Spend":117500,"Date":"2023-09-01","x":1693526400000,"y":117500,"fill":"#263778"},{"date_produced":"2023-09-02","party":"ZP","spend":104250,"total_spend":135750,"colors":"#263778","Daily Spend":104250,"Date":"2023-09-02","x":1693612800000,"y":104250,"fill":"#263778"},{"date_produced":"2023-09-03","party":"ZP","spend":114750,"total_spend":135750,"colors":"#263778","Daily Spend":114750,"Date":"2023-09-03","x":1693699200000,"y":114750,"fill":"#263778"},{"date_produced":"2023-09-04","party":"ZP","spend":112000,"total_spend":135750,"colors":"#263778","Daily Spend":112000,"Date":"2023-09-04","x":1693785600000,"y":112000,"fill":"#263778"},{"date_produced":"2023-09-05","party":"ZP","spend":112250,"total_spend":135750,"colors":"#263778","Daily Spend":112250,"Date":"2023-09-05","x":1693872000000,"y":112250,"fill":"#263778"},{"date_produced":"2023-09-06","party":"ZP","spend":122750,"total_spend":135750,"colors":"#263778","Daily Spend":122750,"Date":"2023-09-06","x":1693958400000,"y":122750,"fill":"#263778"},{"date_produced":"2023-09-07","party":"ZP","spend":109250,"total_spend":135750,"colors":"#263778","Daily Spend":109250,"Date":"2023-09-07","x":1694044800000,"y":109250,"fill":"#263778"},{"date_produced":"2023-09-08","party":"ZP","spend":122500,"total_spend":135750,"colors":"#263778","Daily Spend":122500,"Date":"2023-09-08","x":1694131200000,"y":122500,"fill":"#263778"},{"date_produced":"2023-09-09","party":"ZP","spend":123750,"total_spend":135750,"colors":"#263778","Daily Spend":123750,"Date":"2023-09-09","x":1694217600000,"y":123750,"fill":"#263778"},{"date_produced":"2023-09-10","party":"ZP","spend":98500,"total_spend":135750,"colors":"#263778","Daily Spend":98500,"Date":"2023-09-10","x":1694304000000,"y":98500,"fill":"#263778"},{"date_produced":"2023-09-11","party":"ZP","spend":117750,"total_spend":135750,"colors":"#263778","Daily Spend":117750,"Date":"2023-09-11","x":1694390400000,"y":117750,"fill":"#263778"},{"date_produced":"2023-09-12","party":"ZP","spend":107000,"total_spend":135750,"colors":"#263778","Daily Spend":107000,"Date":"2023-09-12","x":1694476800000,"y":107000,"fill":"#263778"},{"date_produced":"2023-09-13","party":"ZP","spend":108250,"total_spend":135750,"colors":"#263778","Daily Spend":108250,"Date":"2023-09-13","x":1694563200000,"y":108250,"fill":"#263778"},{"date_produced":"2023-09-14","party":"ZP","spend":135750,"total_spend":135750,"colors":"#263778","Daily Spend":135750,"Date":"2023-09-14","x":1694649600000,"y":135750,"fill":"#263778"},{"date_produced":"2023-09-15","party":"ZP","spend":75500,"total_spend":135750,"colors":"#263778","Daily Spend":75500,"Date":"2023-09-15","x":1694736000000,"y":75500,"fill":"#263778"},{"date_produced":"2023-09-16","party":"ZP","spend":67750,"total_spend":135750,"colors":"#263778","Daily Spend":67750,"Date":"2023-09-16","x":1694822400000,"y":67750,"fill":"#263778"},{"date_produced":"2023-09-17","party":"ZP","spend":87250,"total_spend":135750,"colors":"#263778","Daily Spend":87250,"Date":"2023-09-17","x":1694908800000,"y":87250,"fill":"#263778"},{"date_produced":"2023-09-18","party":"ZP","spend":103000,"total_spend":135750,"colors":"#263778","Daily Spend":103000,"Date":"2023-09-18","x":1694995200000,"y":103000,"fill":"#263778"},{"date_produced":"2023-09-19","party":"ZP","spend":119000,"total_spend":135750,"colors":"#263778","Daily Spend":119000,"Date":"2023-09-19","x":1695081600000,"y":119000,"fill":"#263778"},{"date_produced":"2023-09-20","party":"ZP","spend":70000,"total_spend":135750,"colors":"#263778","Daily Spend":70000,"Date":"2023-09-20","x":1695168000000,"y":70000,"fill":"#263778"},{"date_produced":"2023-09-21","party":"ZP","spend":91250,"total_spend":135750,"colors":"#263778","Daily Spend":91250,"Date":"2023-09-21","x":1695254400000,"y":91250,"fill":"#263778"},{"date_produced":"2023-09-22","party":"ZP","spend":90250,"total_spend":135750,"colors":"#263778","Daily Spend":90250,"Date":"2023-09-22","x":1695340800000,"y":90250,"fill":"#263778"},{"date_produced":"2023-09-23","party":"ZP","spend":94000,"total_spend":135750,"colors":"#263778","Daily Spend":94000,"Date":"2023-09-23","x":1695427200000,"y":94000,"fill":"#263778"},{"date_produced":"2023-09-24","party":"ZP","spend":89750,"total_spend":135750,"colors":"#263778","Daily Spend":89750,"Date":"2023-09-24","x":1695513600000,"y":89750,"fill":"#263778"},{"date_produced":"2023-09-25","party":"ZP","spend":89750,"total_spend":135750,"colors":"#263778","Daily Spend":89750,"Date":"2023-09-25","x":1695600000000,"y":89750,"fill":"#263778"},{"date_produced":"2023-09-26","party":"ZP","spend":85000,"total_spend":135750,"colors":"#263778","Daily Spend":85000,"Date":"2023-09-26","x":1695686400000,"y":85000,"fill":"#263778"},{"date_produced":"2023-09-27","party":"ZP","spend":85000,"total_spend":135750,"colors":"#263778","Daily Spend":85000,"Date":"2023-09-27","x":1695772800000,"y":85000,"fill":"#263778"},{"date_produced":"2023-09-28","party":"ZP","spend":74500,"total_spend":135750,"colors":"#263778","Daily Spend":74500,"Date":"2023-09-28","x":1695859200000,"y":74500,"fill":"#263778"},{"date_produced":"2023-09-29","party":"ZP","spend":73750,"total_spend":135750,"colors":"#263778","Daily Spend":73750,"Date":"2023-09-29","x":1695945600000,"y":73750,"fill":"#263778"},{"date_produced":"2023-09-30","party":"ZP","spend":65500,"total_spend":135750,"colors":"#263778","Daily Spend":65500,"Date":"2023-09-30","x":1696032000000,"y":65500,"fill":"#263778"},{"date_produced":"2023-10-01","party":"ZP","spend":87750,"total_spend":135750,"colors":"#263778","Daily Spend":87750,"Date":"2023-10-01","x":1696118400000,"y":87750,"fill":"#263778"},{"date_produced":"2023-10-02","party":"ZP","spend":84750,"total_spend":135750,"colors":"#263778","Daily Spend":84750,"Date":"2023-10-02","x":1696204800000,"y":84750,"fill":"#263778"}],"type":"area"}],"xAxis":{"type":"datetime","title":{"text":"Date"},"categories":null},"colors":["#3db53a","#e6001a","#122746","#851a64","#f68f2d","#263778"],"tooltip":{"shared":true,"positioner":"function (labelWidth, labelHeight, point) {\n        return { x: 200, y: this.chart.plotTop };\n    }"}},"theme":{"chart":{"backgroundColor":"transparent"},"colors":["#7cb5ec","#434348","#90ed7d","#f7a35c","#8085e9","#f15c80","#e4d354","#2b908f","#f45b5b","#91e8e1"]},"conf_opts":{"global":{"Date":null,"VMLRadialGradientURL":"http =//code.highcharts.com/list(version)/gfx/vml-radial-gradient.png","canvasToolsURL":"http =//code.highcharts.com/list(version)/modules/canvas-tools.js","getTimezoneOffset":null,"timezoneOffset":0,"useUTC":true},"lang":{"contextButtonTitle":"Chart context menu","decimalPoint":".","downloadCSV":"Download CSV","downloadJPEG":"Download JPEG image","downloadPDF":"Download PDF document","downloadPNG":"Download PNG image","downloadSVG":"Download SVG vector image","downloadXLS":"Download XLS","drillUpText":"◁ Back to {series.name}","exitFullscreen":"Exit from full screen","exportData":{"annotationHeader":"Annotations","categoryDatetimeHeader":"DateTime","categoryHeader":"Category"},"hideData":"Hide data table","invalidDate":null,"loading":"Loading...","months":["January","February","March","April","May","June","July","August","September","October","November","December"],"noData":"No data to display","numericSymbolMagnitude":1000,"numericSymbols":["k","M","G","T","P","E"],"printChart":"Print chart","resetZoom":"Reset zoom","resetZoomTitle":"Reset zoom level 1:1","shortMonths":["Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"],"shortWeekdays":["Sat","Sun","Mon","Tue","Wed","Thu","Fri"],"thousandsSep":" ","viewData":"View data table","viewFullscreen":"View in full screen","weekdays":["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday"]}},"type":"chart","fonts":[],"debug":false},"evals":["hc_opts.tooltip.positioner"],"jsHooks":[]}</script>
```
:::
:::





::: 



## `<svg aria-hidden="true" role="img" viewBox="0 0 448 512" style="height:1em;width:0.88em;vertical-align:-0.125em;margin-left:auto;margin-right:auto;font-size:inherit;fill:lightblue;overflow:visible;position:relative;"><path d="M349.4 44.6c5.9-13.7 1.5-29.7-10.6-38.5s-28.6-8-39.9 1.8l-256 224c-10 8.8-13.6 22.9-8.9 35.3S50.7 288 64 288H175.5L98.6 467.4c-5.9 13.7-1.5 29.7 10.6 38.5s28.6 8 39.9-1.8l256-224c10-8.8 13.6-22.9 8.9-35.3s-16.6-20.7-30-20.7H272.5L349.4 44.6z"/></svg>`{=html} Combined


::: {.panel-tabset}



### Cumulative


::: {.cell}
::: {.cell-output-display}
```{=html}
<div class="highchart html-widget html-fill-item-overflow-hidden html-fill-item" id="htmlwidget-bf6f7478d387390c2322" style="width:100%;height:480px;"></div>
<script type="application/json" data-for="htmlwidget-bf6f7478d387390c2322">{"x":{"hc_opts":{"chart":{"reflow":true},"title":{"text":null},"yAxis":{"title":{"text":"Daily Spend"},"type":"linear"},"credits":{"enabled":false},"exporting":{"enabled":false},"boost":{"enabled":false},"plotOptions":{"series":{"label":{"enabled":false},"turboThreshold":0,"showInLegend":true},"treemap":{"layoutAlgorithm":"squarified"},"scatter":{"marker":{"symbol":"circle"}},"area":{"stacking":"normal","lineWidth":1,"marker":{"enabled":false}}},"series":[{"name":"BS","data":[{"date_produced":"2023-08-31","party":"BS","colors":"#e6001a","spend":290,"Daily Spend":290,"Date":"2023-08-31","x":1693440000000,"y":290,"fill":"#e6001a"},{"date_produced":"2023-09-01","party":"BS","colors":"#e6001a","spend":667,"Daily Spend":667,"Date":"2023-09-01","x":1693526400000,"y":667,"fill":"#e6001a"},{"date_produced":"2023-09-02","party":"BS","colors":"#e6001a","spend":1044,"Daily Spend":1044,"Date":"2023-09-02","x":1693612800000,"y":1044,"fill":"#e6001a"},{"date_produced":"2023-09-03","party":"BS","colors":"#e6001a","spend":1409,"Daily Spend":1409,"Date":"2023-09-03","x":1693699200000,"y":1409,"fill":"#e6001a"},{"date_produced":"2023-09-04","party":"BS","colors":"#e6001a","spend":1780,"Daily Spend":1780,"Date":"2023-09-04","x":1693785600000,"y":1780,"fill":"#e6001a"},{"date_produced":"2023-09-05","party":"BS","colors":"#e6001a","spend":2463,"Daily Spend":2463,"Date":"2023-09-05","x":1693872000000,"y":2463,"fill":"#e6001a"},{"date_produced":"2023-09-06","party":"BS","colors":"#e6001a","spend":3078,"Daily Spend":3078,"Date":"2023-09-06","x":1693958400000,"y":3078,"fill":"#e6001a"},{"date_produced":"2023-09-07","party":"BS","colors":"#e6001a","spend":3675,"Daily Spend":3675,"Date":"2023-09-07","x":1694044800000,"y":3675,"fill":"#e6001a"},{"date_produced":"2023-09-08","party":"BS","colors":"#e6001a","spend":4492,"Daily Spend":4492,"Date":"2023-09-08","x":1694131200000,"y":4492,"fill":"#e6001a"},{"date_produced":"2023-09-09","party":"BS","colors":"#e6001a","spend":5187,"Daily Spend":5187,"Date":"2023-09-09","x":1694217600000,"y":5187,"fill":"#e6001a"},{"date_produced":"2023-09-10","party":"BS","colors":"#e6001a","spend":5694,"Daily Spend":5694,"Date":"2023-09-10","x":1694304000000,"y":5694,"fill":"#e6001a"},{"date_produced":"2023-09-11","party":"BS","colors":"#e6001a","spend":6265,"Daily Spend":6265,"Date":"2023-09-11","x":1694390400000,"y":6265,"fill":"#e6001a"},{"date_produced":"2023-09-12","party":"BS","colors":"#e6001a","spend":6795,"Daily Spend":6795,"Date":"2023-09-12","x":1694476800000,"y":6795,"fill":"#e6001a"},{"date_produced":"2023-09-13","party":"BS","colors":"#e6001a","spend":7404,"Daily Spend":7404,"Date":"2023-09-13","x":1694563200000,"y":7404,"fill":"#e6001a"},{"date_produced":"2023-09-14","party":"BS","colors":"#e6001a","spend":8223,"Daily Spend":8223,"Date":"2023-09-14","x":1694649600000,"y":8223,"fill":"#e6001a"},{"date_produced":"2023-09-15","party":"BS","colors":"#e6001a","spend":9299,"Daily Spend":9299,"Date":"2023-09-15","x":1694736000000,"y":9299,"fill":"#e6001a"},{"date_produced":"2023-09-16","party":"BS","colors":"#e6001a","spend":11124,"Daily Spend":11124,"Date":"2023-09-16","x":1694822400000,"y":11124,"fill":"#e6001a"},{"date_produced":"2023-09-17","party":"BS","colors":"#e6001a","spend":13456,"Daily Spend":13456,"Date":"2023-09-17","x":1694908800000,"y":13456,"fill":"#e6001a"},{"date_produced":"2023-09-18","party":"BS","colors":"#e6001a","spend":15303,"Daily Spend":15303,"Date":"2023-09-18","x":1694995200000,"y":15303,"fill":"#e6001a"},{"date_produced":"2023-09-19","party":"BS","colors":"#e6001a","spend":17935,"Daily Spend":17935,"Date":"2023-09-19","x":1695081600000,"y":17935,"fill":"#e6001a"},{"date_produced":"2023-09-20","party":"BS","colors":"#e6001a","spend":21377,"Daily Spend":21377,"Date":"2023-09-20","x":1695168000000,"y":21377,"fill":"#e6001a"},{"date_produced":"2023-09-21","party":"BS","colors":"#e6001a","spend":25721,"Daily Spend":25721,"Date":"2023-09-21","x":1695254400000,"y":25721,"fill":"#e6001a"},{"date_produced":"2023-09-22","party":"BS","colors":"#e6001a","spend":30567,"Daily Spend":30567,"Date":"2023-09-22","x":1695340800000,"y":30567,"fill":"#e6001a"},{"date_produced":"2023-09-23","party":"BS","colors":"#e6001a","spend":36405,"Daily Spend":36405,"Date":"2023-09-23","x":1695427200000,"y":36405,"fill":"#e6001a"},{"date_produced":"2023-09-24","party":"BS","colors":"#e6001a","spend":42507,"Daily Spend":42507,"Date":"2023-09-24","x":1695513600000,"y":42507,"fill":"#e6001a"},{"date_produced":"2023-09-25","party":"BS","colors":"#e6001a","spend":48147,"Daily Spend":48147,"Date":"2023-09-25","x":1695600000000,"y":48147,"fill":"#e6001a"},{"date_produced":"2023-09-26","party":"BS","colors":"#e6001a","spend":53877,"Daily Spend":53877,"Date":"2023-09-26","x":1695686400000,"y":53877,"fill":"#e6001a"},{"date_produced":"2023-09-27","party":"BS","colors":"#e6001a","spend":59451,"Daily Spend":59451,"Date":"2023-09-27","x":1695772800000,"y":59451,"fill":"#e6001a"},{"date_produced":"2023-09-28","party":"BS","colors":"#e6001a","spend":66769,"Daily Spend":66769,"Date":"2023-09-28","x":1695859200000,"y":66769,"fill":"#e6001a"},{"date_produced":"2023-09-29","party":"BS","colors":"#e6001a","spend":74537,"Daily Spend":74537,"Date":"2023-09-29","x":1695945600000,"y":74537,"fill":"#e6001a"},{"date_produced":"2023-09-30","party":"BS","colors":"#e6001a","spend":82441,"Daily Spend":82441,"Date":"2023-09-30","x":1696032000000,"y":82441,"fill":"#e6001a"}],"type":"area"},{"name":"LIB","data":[{"date_produced":"2023-08-31","party":"LIB","colors":"#ffd900","spend":1560,"Daily Spend":1560,"Date":"2023-08-31","x":1693440000000,"y":1560,"fill":"#ffd900"},{"date_produced":"2023-09-01","party":"LIB","colors":"#ffd900","spend":2250,"Daily Spend":2250,"Date":"2023-09-01","x":1693526400000,"y":2250,"fill":"#ffd900"},{"date_produced":"2023-09-02","party":"LIB","colors":"#ffd900","spend":3048,"Daily Spend":3048,"Date":"2023-09-02","x":1693612800000,"y":3048,"fill":"#ffd900"},{"date_produced":"2023-09-03","party":"LIB","colors":"#ffd900","spend":3949,"Daily Spend":3949,"Date":"2023-09-03","x":1693699200000,"y":3949,"fill":"#ffd900"},{"date_produced":"2023-09-04","party":"LIB","colors":"#ffd900","spend":4723,"Daily Spend":4723,"Date":"2023-09-04","x":1693785600000,"y":4723,"fill":"#ffd900"},{"date_produced":"2023-09-05","party":"LIB","colors":"#ffd900","spend":5381,"Daily Spend":5381,"Date":"2023-09-05","x":1693872000000,"y":5381,"fill":"#ffd900"},{"date_produced":"2023-09-06","party":"LIB","colors":"#ffd900","spend":5970,"Daily Spend":5970,"Date":"2023-09-06","x":1693958400000,"y":5970,"fill":"#ffd900"},{"date_produced":"2023-09-07","party":"LIB","colors":"#ffd900","spend":6299,"Daily Spend":6299,"Date":"2023-09-07","x":1694044800000,"y":6299,"fill":"#ffd900"},{"date_produced":"2023-09-08","party":"LIB","colors":"#ffd900","spend":6368,"Daily Spend":6368,"Date":"2023-09-08","x":1694131200000,"y":6368,"fill":"#ffd900"},{"date_produced":"2023-09-09","party":"LIB","colors":"#ffd900","spend":6444,"Daily Spend":6444,"Date":"2023-09-09","x":1694217600000,"y":6444,"fill":"#ffd900"},{"date_produced":"2023-09-10","party":"LIB","colors":"#ffd900","spend":6530,"Daily Spend":6530,"Date":"2023-09-10","x":1694304000000,"y":6530,"fill":"#ffd900"},{"date_produced":"2023-09-11","party":"LIB","colors":"#ffd900","spend":6609,"Daily Spend":6609,"Date":"2023-09-11","x":1694390400000,"y":6609,"fill":"#ffd900"},{"date_produced":"2023-09-12","party":"LIB","colors":"#ffd900","spend":6687,"Daily Spend":6687,"Date":"2023-09-12","x":1694476800000,"y":6687,"fill":"#ffd900"},{"date_produced":"2023-09-13","party":"LIB","colors":"#ffd900","spend":6764,"Daily Spend":6764,"Date":"2023-09-13","x":1694563200000,"y":6764,"fill":"#ffd900"},{"date_produced":"2023-09-14","party":"LIB","colors":"#ffd900","spend":6839,"Daily Spend":6839,"Date":"2023-09-14","x":1694649600000,"y":6839,"fill":"#ffd900"},{"date_produced":"2023-09-15","party":"LIB","colors":"#ffd900","spend":6912,"Daily Spend":6912,"Date":"2023-09-15","x":1694736000000,"y":6912,"fill":"#ffd900"},{"date_produced":"2023-09-16","party":"LIB","colors":"#ffd900","spend":6989,"Daily Spend":6989,"Date":"2023-09-16","x":1694822400000,"y":6989,"fill":"#ffd900"},{"date_produced":"2023-09-17","party":"LIB","colors":"#ffd900","spend":7081,"Daily Spend":7081,"Date":"2023-09-17","x":1694908800000,"y":7081,"fill":"#ffd900"},{"date_produced":"2023-09-18","party":"LIB","colors":"#ffd900","spend":7170,"Daily Spend":7170,"Date":"2023-09-18","x":1694995200000,"y":7170,"fill":"#ffd900"},{"date_produced":"2023-09-19","party":"LIB","colors":"#ffd900","spend":7267,"Daily Spend":7267,"Date":"2023-09-19","x":1695081600000,"y":7267,"fill":"#ffd900"},{"date_produced":"2023-09-20","party":"LIB","colors":"#ffd900","spend":7351,"Daily Spend":7351,"Date":"2023-09-20","x":1695168000000,"y":7351,"fill":"#ffd900"},{"date_produced":"2023-09-21","party":"LIB","colors":"#ffd900","spend":7435,"Daily Spend":7435,"Date":"2023-09-21","x":1695254400000,"y":7435,"fill":"#ffd900"},{"date_produced":"2023-09-22","party":"LIB","colors":"#ffd900","spend":7504,"Daily Spend":7504,"Date":"2023-09-22","x":1695340800000,"y":7504,"fill":"#ffd900"},{"date_produced":"2023-09-23","party":"LIB","colors":"#ffd900","spend":7568,"Daily Spend":7568,"Date":"2023-09-23","x":1695427200000,"y":7568,"fill":"#ffd900"},{"date_produced":"2023-09-24","party":"LIB","colors":"#ffd900","spend":7639,"Daily Spend":7639,"Date":"2023-09-24","x":1695513600000,"y":7639,"fill":"#ffd900"},{"date_produced":"2023-09-25","party":"LIB","colors":"#ffd900","spend":7706,"Daily Spend":7706,"Date":"2023-09-25","x":1695600000000,"y":7706,"fill":"#ffd900"},{"date_produced":"2023-09-26","party":"LIB","colors":"#ffd900","spend":7773,"Daily Spend":7773,"Date":"2023-09-26","x":1695686400000,"y":7773,"fill":"#ffd900"},{"date_produced":"2023-09-27","party":"LIB","colors":"#ffd900","spend":7840,"Daily Spend":7840,"Date":"2023-09-27","x":1695772800000,"y":7840,"fill":"#ffd900"},{"date_produced":"2023-09-28","party":"LIB","colors":"#ffd900","spend":7903,"Daily Spend":7903,"Date":"2023-09-28","x":1695859200000,"y":7903,"fill":"#ffd900"},{"date_produced":"2023-09-29","party":"LIB","colors":"#ffd900","spend":7965,"Daily Spend":7965,"Date":"2023-09-29","x":1695945600000,"y":7965,"fill":"#ffd900"},{"date_produced":"2023-09-30","party":"LIB","colors":"#ffd900","spend":8030,"Daily Spend":8030,"Date":"2023-09-30","x":1696032000000,"y":8030,"fill":"#ffd900"}],"type":"area"},{"name":"KWIN","data":[{"date_produced":"2023-08-31","party":"KWIN","colors":"#122746","spend":456,"Daily Spend":456,"Date":"2023-08-31","x":1693440000000,"y":456,"fill":"#122746"},{"date_produced":"2023-09-01","party":"KWIN","colors":"#122746","spend":1057,"Daily Spend":1057,"Date":"2023-09-01","x":1693526400000,"y":1057,"fill":"#122746"},{"date_produced":"2023-09-02","party":"KWIN","colors":"#122746","spend":1651,"Daily Spend":1651,"Date":"2023-09-02","x":1693612800000,"y":1651,"fill":"#122746"},{"date_produced":"2023-09-03","party":"KWIN","colors":"#122746","spend":1848,"Daily Spend":1848,"Date":"2023-09-03","x":1693699200000,"y":1848,"fill":"#122746"},{"date_produced":"2023-09-04","party":"KWIN","colors":"#122746","spend":2105,"Daily Spend":2105,"Date":"2023-09-04","x":1693785600000,"y":2105,"fill":"#122746"},{"date_produced":"2023-09-05","party":"KWIN","colors":"#122746","spend":3177,"Daily Spend":3177,"Date":"2023-09-05","x":1693872000000,"y":3177,"fill":"#122746"},{"date_produced":"2023-09-06","party":"KWIN","colors":"#122746","spend":10171,"Daily Spend":10171,"Date":"2023-09-06","x":1693958400000,"y":10171,"fill":"#122746"},{"date_produced":"2023-09-07","party":"KWIN","colors":"#122746","spend":14099,"Daily Spend":14099,"Date":"2023-09-07","x":1694044800000,"y":14099,"fill":"#122746"},{"date_produced":"2023-09-08","party":"KWIN","colors":"#122746","spend":14878,"Daily Spend":14878,"Date":"2023-09-08","x":1694131200000,"y":14878,"fill":"#122746"},{"date_produced":"2023-09-09","party":"KWIN","colors":"#122746","spend":16182,"Daily Spend":16182,"Date":"2023-09-09","x":1694217600000,"y":16182,"fill":"#122746"},{"date_produced":"2023-09-10","party":"KWIN","colors":"#122746","spend":17067,"Daily Spend":17067,"Date":"2023-09-10","x":1694304000000,"y":17067,"fill":"#122746"},{"date_produced":"2023-09-11","party":"KWIN","colors":"#122746","spend":18187,"Daily Spend":18187,"Date":"2023-09-11","x":1694390400000,"y":18187,"fill":"#122746"},{"date_produced":"2023-09-12","party":"KWIN","colors":"#122746","spend":18630,"Daily Spend":18630,"Date":"2023-09-12","x":1694476800000,"y":18630,"fill":"#122746"},{"date_produced":"2023-09-13","party":"KWIN","colors":"#122746","spend":19527,"Daily Spend":19527,"Date":"2023-09-13","x":1694563200000,"y":19527,"fill":"#122746"},{"date_produced":"2023-09-14","party":"KWIN","colors":"#122746","spend":21091,"Daily Spend":21091,"Date":"2023-09-14","x":1694649600000,"y":21091,"fill":"#122746"},{"date_produced":"2023-09-15","party":"KWIN","colors":"#122746","spend":22754,"Daily Spend":22754,"Date":"2023-09-15","x":1694736000000,"y":22754,"fill":"#122746"},{"date_produced":"2023-09-16","party":"KWIN","colors":"#122746","spend":24457,"Daily Spend":24457,"Date":"2023-09-16","x":1694822400000,"y":24457,"fill":"#122746"},{"date_produced":"2023-09-17","party":"KWIN","colors":"#122746","spend":26889,"Daily Spend":26889,"Date":"2023-09-17","x":1694908800000,"y":26889,"fill":"#122746"},{"date_produced":"2023-09-18","party":"KWIN","colors":"#122746","spend":30699,"Daily Spend":30699,"Date":"2023-09-18","x":1694995200000,"y":30699,"fill":"#122746"},{"date_produced":"2023-09-19","party":"KWIN","colors":"#122746","spend":34409,"Daily Spend":34409,"Date":"2023-09-19","x":1695081600000,"y":34409,"fill":"#122746"},{"date_produced":"2023-09-20","party":"KWIN","colors":"#122746","spend":38969,"Daily Spend":38969,"Date":"2023-09-20","x":1695168000000,"y":38969,"fill":"#122746"},{"date_produced":"2023-09-21","party":"KWIN","colors":"#122746","spend":43743,"Daily Spend":43743,"Date":"2023-09-21","x":1695254400000,"y":43743,"fill":"#122746"},{"date_produced":"2023-09-22","party":"KWIN","colors":"#122746","spend":48200,"Daily Spend":48200,"Date":"2023-09-22","x":1695340800000,"y":48200,"fill":"#122746"},{"date_produced":"2023-09-23","party":"KWIN","colors":"#122746","spend":57545,"Daily Spend":57545,"Date":"2023-09-23","x":1695427200000,"y":57545,"fill":"#122746"},{"date_produced":"2023-09-24","party":"KWIN","colors":"#122746","spend":65785,"Daily Spend":65785,"Date":"2023-09-24","x":1695513600000,"y":65785,"fill":"#122746"},{"date_produced":"2023-09-25","party":"KWIN","colors":"#122746","spend":71785,"Daily Spend":71785,"Date":"2023-09-25","x":1695600000000,"y":71785,"fill":"#122746"},{"date_produced":"2023-09-26","party":"KWIN","colors":"#122746","spend":84136,"Daily Spend":84136,"Date":"2023-09-26","x":1695686400000,"y":84136,"fill":"#122746"},{"date_produced":"2023-09-27","party":"KWIN","colors":"#122746","spend":92522,"Daily Spend":92522,"Date":"2023-09-27","x":1695772800000,"y":92522,"fill":"#122746"},{"date_produced":"2023-09-28","party":"KWIN","colors":"#122746","spend":99694,"Daily Spend":99694,"Date":"2023-09-28","x":1695859200000,"y":99694,"fill":"#122746"},{"date_produced":"2023-09-29","party":"KWIN","colors":"#122746","spend":109375,"Daily Spend":109375,"Date":"2023-09-29","x":1695945600000,"y":109375,"fill":"#122746"},{"date_produced":"2023-09-30","party":"KWIN","colors":"#122746","spend":119924,"Daily Spend":119924,"Date":"2023-09-30","x":1696032000000,"y":119924,"fill":"#122746"}],"type":"area"},{"name":"LEW","data":[{"date_produced":"2023-08-31","party":"LEW","colors":"#851a64","spend":2628,"Daily Spend":2628,"Date":"2023-08-31","x":1693440000000,"y":2628,"fill":"#851a64"},{"date_produced":"2023-09-01","party":"LEW","colors":"#851a64","spend":4489,"Daily Spend":4489,"Date":"2023-09-01","x":1693526400000,"y":4489,"fill":"#851a64"},{"date_produced":"2023-09-02","party":"LEW","colors":"#851a64","spend":6012,"Daily Spend":6012,"Date":"2023-09-02","x":1693612800000,"y":6012,"fill":"#851a64"},{"date_produced":"2023-09-03","party":"LEW","colors":"#851a64","spend":7502,"Daily Spend":7502,"Date":"2023-09-03","x":1693699200000,"y":7502,"fill":"#851a64"},{"date_produced":"2023-09-04","party":"LEW","colors":"#851a64","spend":9038,"Daily Spend":9038,"Date":"2023-09-04","x":1693785600000,"y":9038,"fill":"#851a64"},{"date_produced":"2023-09-05","party":"LEW","colors":"#851a64","spend":10798,"Daily Spend":10798,"Date":"2023-09-05","x":1693872000000,"y":10798,"fill":"#851a64"},{"date_produced":"2023-09-06","party":"LEW","colors":"#851a64","spend":13122,"Daily Spend":13122,"Date":"2023-09-06","x":1693958400000,"y":13122,"fill":"#851a64"},{"date_produced":"2023-09-07","party":"LEW","colors":"#851a64","spend":15798,"Daily Spend":15798,"Date":"2023-09-07","x":1694044800000,"y":15798,"fill":"#851a64"},{"date_produced":"2023-09-08","party":"LEW","colors":"#851a64","spend":19309,"Daily Spend":19309,"Date":"2023-09-08","x":1694131200000,"y":19309,"fill":"#851a64"},{"date_produced":"2023-09-09","party":"LEW","colors":"#851a64","spend":23555,"Daily Spend":23555,"Date":"2023-09-09","x":1694217600000,"y":23555,"fill":"#851a64"},{"date_produced":"2023-09-10","party":"LEW","colors":"#851a64","spend":30251,"Daily Spend":30251,"Date":"2023-09-10","x":1694304000000,"y":30251,"fill":"#851a64"},{"date_produced":"2023-09-11","party":"LEW","colors":"#851a64","spend":37399,"Daily Spend":37399,"Date":"2023-09-11","x":1694390400000,"y":37399,"fill":"#851a64"},{"date_produced":"2023-09-12","party":"LEW","colors":"#851a64","spend":45173,"Daily Spend":45173,"Date":"2023-09-12","x":1694476800000,"y":45173,"fill":"#851a64"},{"date_produced":"2023-09-13","party":"LEW","colors":"#851a64","spend":59441,"Daily Spend":59441,"Date":"2023-09-13","x":1694563200000,"y":59441,"fill":"#851a64"},{"date_produced":"2023-09-14","party":"LEW","colors":"#851a64","spend":74221,"Daily Spend":74221,"Date":"2023-09-14","x":1694649600000,"y":74221,"fill":"#851a64"},{"date_produced":"2023-09-15","party":"LEW","colors":"#851a64","spend":88976,"Daily Spend":88976,"Date":"2023-09-15","x":1694736000000,"y":88976,"fill":"#851a64"},{"date_produced":"2023-09-16","party":"LEW","colors":"#851a64","spend":104158,"Daily Spend":104158,"Date":"2023-09-16","x":1694822400000,"y":104158,"fill":"#851a64"},{"date_produced":"2023-09-17","party":"LEW","colors":"#851a64","spend":120389,"Daily Spend":120389,"Date":"2023-09-17","x":1694908800000,"y":120389,"fill":"#851a64"},{"date_produced":"2023-09-18","party":"LEW","colors":"#851a64","spend":136674,"Daily Spend":136674,"Date":"2023-09-18","x":1694995200000,"y":136674,"fill":"#851a64"},{"date_produced":"2023-09-19","party":"LEW","colors":"#851a64","spend":152795,"Daily Spend":152795,"Date":"2023-09-19","x":1695081600000,"y":152795,"fill":"#851a64"},{"date_produced":"2023-09-20","party":"LEW","colors":"#851a64","spend":177267,"Daily Spend":177267,"Date":"2023-09-20","x":1695168000000,"y":177267,"fill":"#851a64"},{"date_produced":"2023-09-21","party":"LEW","colors":"#851a64","spend":202313,"Daily Spend":202313,"Date":"2023-09-21","x":1695254400000,"y":202313,"fill":"#851a64"},{"date_produced":"2023-09-22","party":"LEW","colors":"#851a64","spend":229627,"Daily Spend":229627,"Date":"2023-09-22","x":1695340800000,"y":229627,"fill":"#851a64"},{"date_produced":"2023-09-23","party":"LEW","colors":"#851a64","spend":258068,"Daily Spend":258068,"Date":"2023-09-23","x":1695427200000,"y":258068,"fill":"#851a64"},{"date_produced":"2023-09-24","party":"LEW","colors":"#851a64","spend":286224,"Daily Spend":286224,"Date":"2023-09-24","x":1695513600000,"y":286224,"fill":"#851a64"},{"date_produced":"2023-09-25","party":"LEW","colors":"#851a64","spend":310982,"Daily Spend":310982,"Date":"2023-09-25","x":1695600000000,"y":310982,"fill":"#851a64"},{"date_produced":"2023-09-26","party":"LEW","colors":"#851a64","spend":339705,"Daily Spend":339705,"Date":"2023-09-26","x":1695686400000,"y":339705,"fill":"#851a64"},{"date_produced":"2023-09-27","party":"LEW","colors":"#851a64","spend":372546,"Daily Spend":372546,"Date":"2023-09-27","x":1695772800000,"y":372546,"fill":"#851a64"},{"date_produced":"2023-09-28","party":"LEW","colors":"#851a64","spend":401828,"Daily Spend":401828,"Date":"2023-09-28","x":1695859200000,"y":401828,"fill":"#851a64"},{"date_produced":"2023-09-29","party":"LEW","colors":"#851a64","spend":433115,"Daily Spend":433115,"Date":"2023-09-29","x":1695945600000,"y":433115,"fill":"#851a64"},{"date_produced":"2023-09-30","party":"LEW","colors":"#851a64","spend":470201,"Daily Spend":470201,"Date":"2023-09-30","x":1696032000000,"y":470201,"fill":"#851a64"}],"type":"area"},{"name":"TD","data":[{"date_produced":"2023-08-31","party":"TD","colors":"#3db53a","spend":2814,"Daily Spend":2814,"Date":"2023-08-31","x":1693440000000,"y":2814,"fill":"#3db53a"},{"date_produced":"2023-09-01","party":"TD","colors":"#3db53a","spend":3565,"Daily Spend":3565,"Date":"2023-09-01","x":1693526400000,"y":3565,"fill":"#3db53a"},{"date_produced":"2023-09-02","party":"TD","colors":"#3db53a","spend":4610,"Daily Spend":4610,"Date":"2023-09-02","x":1693612800000,"y":4610,"fill":"#3db53a"},{"date_produced":"2023-09-03","party":"TD","colors":"#3db53a","spend":6742,"Daily Spend":6742,"Date":"2023-09-03","x":1693699200000,"y":6742,"fill":"#3db53a"},{"date_produced":"2023-09-04","party":"TD","colors":"#3db53a","spend":8696,"Daily Spend":8696,"Date":"2023-09-04","x":1693785600000,"y":8696,"fill":"#3db53a"},{"date_produced":"2023-09-05","party":"TD","colors":"#3db53a","spend":10805,"Daily Spend":10805,"Date":"2023-09-05","x":1693872000000,"y":10805,"fill":"#3db53a"},{"date_produced":"2023-09-06","party":"TD","colors":"#3db53a","spend":13227,"Daily Spend":13227,"Date":"2023-09-06","x":1693958400000,"y":13227,"fill":"#3db53a"},{"date_produced":"2023-09-07","party":"TD","colors":"#3db53a","spend":15463,"Daily Spend":15463,"Date":"2023-09-07","x":1694044800000,"y":15463,"fill":"#3db53a"},{"date_produced":"2023-09-08","party":"TD","colors":"#3db53a","spend":18563,"Daily Spend":18563,"Date":"2023-09-08","x":1694131200000,"y":18563,"fill":"#3db53a"},{"date_produced":"2023-09-09","party":"TD","colors":"#3db53a","spend":22565,"Daily Spend":22565,"Date":"2023-09-09","x":1694217600000,"y":22565,"fill":"#3db53a"},{"date_produced":"2023-09-10","party":"TD","colors":"#3db53a","spend":28376,"Daily Spend":28376,"Date":"2023-09-10","x":1694304000000,"y":28376,"fill":"#3db53a"},{"date_produced":"2023-09-11","party":"TD","colors":"#3db53a","spend":34168,"Daily Spend":34168,"Date":"2023-09-11","x":1694390400000,"y":34168,"fill":"#3db53a"},{"date_produced":"2023-09-12","party":"TD","colors":"#3db53a","spend":43800,"Daily Spend":43800,"Date":"2023-09-12","x":1694476800000,"y":43800,"fill":"#3db53a"},{"date_produced":"2023-09-13","party":"TD","colors":"#3db53a","spend":52942,"Daily Spend":52942,"Date":"2023-09-13","x":1694563200000,"y":52942,"fill":"#3db53a"},{"date_produced":"2023-09-14","party":"TD","colors":"#3db53a","spend":65554,"Daily Spend":65554,"Date":"2023-09-14","x":1694649600000,"y":65554,"fill":"#3db53a"},{"date_produced":"2023-09-15","party":"TD","colors":"#3db53a","spend":80010,"Daily Spend":80010,"Date":"2023-09-15","x":1694736000000,"y":80010,"fill":"#3db53a"},{"date_produced":"2023-09-16","party":"TD","colors":"#3db53a","spend":94837,"Daily Spend":94837,"Date":"2023-09-16","x":1694822400000,"y":94837,"fill":"#3db53a"},{"date_produced":"2023-09-17","party":"TD","colors":"#3db53a","spend":111683,"Daily Spend":111683,"Date":"2023-09-17","x":1694908800000,"y":111683,"fill":"#3db53a"},{"date_produced":"2023-09-18","party":"TD","colors":"#3db53a","spend":122479,"Daily Spend":122479,"Date":"2023-09-18","x":1694995200000,"y":122479,"fill":"#3db53a"},{"date_produced":"2023-09-19","party":"TD","colors":"#3db53a","spend":135993,"Daily Spend":135993,"Date":"2023-09-19","x":1695081600000,"y":135993,"fill":"#3db53a"},{"date_produced":"2023-09-20","party":"TD","colors":"#3db53a","spend":150606,"Daily Spend":150606,"Date":"2023-09-20","x":1695168000000,"y":150606,"fill":"#3db53a"},{"date_produced":"2023-09-21","party":"TD","colors":"#3db53a","spend":166377,"Daily Spend":166377,"Date":"2023-09-21","x":1695254400000,"y":166377,"fill":"#3db53a"},{"date_produced":"2023-09-22","party":"TD","colors":"#3db53a","spend":182743,"Daily Spend":182743,"Date":"2023-09-22","x":1695340800000,"y":182743,"fill":"#3db53a"},{"date_produced":"2023-09-23","party":"TD","colors":"#3db53a","spend":201029,"Daily Spend":201029,"Date":"2023-09-23","x":1695427200000,"y":201029,"fill":"#3db53a"},{"date_produced":"2023-09-24","party":"TD","colors":"#3db53a","spend":219068,"Daily Spend":219068,"Date":"2023-09-24","x":1695513600000,"y":219068,"fill":"#3db53a"},{"date_produced":"2023-09-25","party":"TD","colors":"#3db53a","spend":235904,"Daily Spend":235904,"Date":"2023-09-25","x":1695600000000,"y":235904,"fill":"#3db53a"},{"date_produced":"2023-09-26","party":"TD","colors":"#3db53a","spend":254833,"Daily Spend":254833,"Date":"2023-09-26","x":1695686400000,"y":254833,"fill":"#3db53a"},{"date_produced":"2023-09-27","party":"TD","colors":"#3db53a","spend":275288,"Daily Spend":275288,"Date":"2023-09-27","x":1695772800000,"y":275288,"fill":"#3db53a"},{"date_produced":"2023-09-28","party":"TD","colors":"#3db53a","spend":299444,"Daily Spend":299444,"Date":"2023-09-28","x":1695859200000,"y":299444,"fill":"#3db53a"},{"date_produced":"2023-09-29","party":"TD","colors":"#3db53a","spend":321094,"Daily Spend":321094,"Date":"2023-09-29","x":1695945600000,"y":321094,"fill":"#3db53a"},{"date_produced":"2023-09-30","party":"TD","colors":"#3db53a","spend":347777,"Daily Spend":347777,"Date":"2023-09-30","x":1696032000000,"y":347777,"fill":"#3db53a"}],"type":"area"},{"name":"ZP","data":[{"date_produced":"2023-08-31","party":"ZP","colors":"#263778","spend":34440,"Daily Spend":34440,"Date":"2023-08-31","x":1693440000000,"y":34440,"fill":"#263778"},{"date_produced":"2023-09-01","party":"ZP","colors":"#263778","spend":168275,"Daily Spend":168275,"Date":"2023-09-01","x":1693526400000,"y":168275,"fill":"#263778"},{"date_produced":"2023-09-02","party":"ZP","colors":"#263778","spend":290008,"Daily Spend":290008,"Date":"2023-09-02","x":1693612800000,"y":290008,"fill":"#263778"},{"date_produced":"2023-09-03","party":"ZP","colors":"#263778","spend":421955,"Daily Spend":421955,"Date":"2023-09-03","x":1693699200000,"y":421955,"fill":"#263778"},{"date_produced":"2023-09-04","party":"ZP","colors":"#263778","spend":548986,"Daily Spend":548986,"Date":"2023-09-04","x":1693785600000,"y":548986,"fill":"#263778"},{"date_produced":"2023-09-05","party":"ZP","colors":"#263778","spend":677250,"Daily Spend":677250,"Date":"2023-09-05","x":1693872000000,"y":677250,"fill":"#263778"},{"date_produced":"2023-09-06","party":"ZP","colors":"#263778","spend":815901,"Daily Spend":815901,"Date":"2023-09-06","x":1693958400000,"y":815901,"fill":"#263778"},{"date_produced":"2023-09-07","party":"ZP","colors":"#263778","spend":941269,"Daily Spend":941269,"Date":"2023-09-07","x":1694044800000,"y":941269,"fill":"#263778"},{"date_produced":"2023-09-08","party":"ZP","colors":"#263778","spend":1078804,"Daily Spend":1078804,"Date":"2023-09-08","x":1694131200000,"y":1078804,"fill":"#263778"},{"date_produced":"2023-09-09","party":"ZP","colors":"#263778","spend":1221343,"Daily Spend":1221343,"Date":"2023-09-09","x":1694217600000,"y":1221343,"fill":"#263778"},{"date_produced":"2023-09-10","party":"ZP","colors":"#263778","spend":1376755,"Daily Spend":1376755,"Date":"2023-09-10","x":1694304000000,"y":1376755,"fill":"#263778"},{"date_produced":"2023-09-11","party":"ZP","colors":"#263778","spend":1526575,"Daily Spend":1526575,"Date":"2023-09-11","x":1694390400000,"y":1526575,"fill":"#263778"},{"date_produced":"2023-09-12","party":"ZP","colors":"#263778","spend":1654577,"Daily Spend":1654577,"Date":"2023-09-12","x":1694476800000,"y":1654577,"fill":"#263778"},{"date_produced":"2023-09-13","party":"ZP","colors":"#263778","spend":1781956,"Daily Spend":1781956,"Date":"2023-09-13","x":1694563200000,"y":1781956,"fill":"#263778"},{"date_produced":"2023-09-14","party":"ZP","colors":"#263778","spend":1946047,"Daily Spend":1946047,"Date":"2023-09-14","x":1694649600000,"y":1946047,"fill":"#263778"},{"date_produced":"2023-09-15","party":"ZP","colors":"#263778","spend":2047688,"Daily Spend":2047688,"Date":"2023-09-15","x":1694736000000,"y":2047688,"fill":"#263778"},{"date_produced":"2023-09-16","party":"ZP","colors":"#263778","spend":2141421,"Daily Spend":2141421,"Date":"2023-09-16","x":1694822400000,"y":2141421,"fill":"#263778"},{"date_produced":"2023-09-17","party":"ZP","colors":"#263778","spend":2271034,"Daily Spend":2271034,"Date":"2023-09-17","x":1694908800000,"y":2271034,"fill":"#263778"},{"date_produced":"2023-09-18","party":"ZP","colors":"#263778","spend":2404709,"Daily Spend":2404709,"Date":"2023-09-18","x":1694995200000,"y":2404709,"fill":"#263778"},{"date_produced":"2023-09-19","party":"ZP","colors":"#263778","spend":2557947,"Daily Spend":2557947,"Date":"2023-09-19","x":1695081600000,"y":2557947,"fill":"#263778"},{"date_produced":"2023-09-20","party":"ZP","colors":"#263778","spend":2667480,"Daily Spend":2667480,"Date":"2023-09-20","x":1695168000000,"y":2667480,"fill":"#263778"},{"date_produced":"2023-09-21","party":"ZP","colors":"#263778","spend":2799153,"Daily Spend":2799153,"Date":"2023-09-21","x":1695254400000,"y":2799153,"fill":"#263778"},{"date_produced":"2023-09-22","party":"ZP","colors":"#263778","spend":2932205,"Daily Spend":2932205,"Date":"2023-09-22","x":1695340800000,"y":2932205,"fill":"#263778"},{"date_produced":"2023-09-23","party":"ZP","colors":"#263778","spend":3063547,"Daily Spend":3063547,"Date":"2023-09-23","x":1695427200000,"y":3063547,"fill":"#263778"},{"date_produced":"2023-09-24","party":"ZP","colors":"#263778","spend":3193076,"Daily Spend":3193076,"Date":"2023-09-24","x":1695513600000,"y":3193076,"fill":"#263778"},{"date_produced":"2023-09-25","party":"ZP","colors":"#263778","spend":3321901,"Daily Spend":3321901,"Date":"2023-09-25","x":1695600000000,"y":3321901,"fill":"#263778"},{"date_produced":"2023-09-26","party":"ZP","colors":"#263778","spend":3448235,"Daily Spend":3448235,"Date":"2023-09-26","x":1695686400000,"y":3448235,"fill":"#263778"},{"date_produced":"2023-09-27","party":"ZP","colors":"#263778","spend":3574167,"Daily Spend":3574167,"Date":"2023-09-27","x":1695772800000,"y":3574167,"fill":"#263778"},{"date_produced":"2023-09-28","party":"ZP","colors":"#263778","spend":3689471,"Daily Spend":3689471,"Date":"2023-09-28","x":1695859200000,"y":3689471,"fill":"#263778"},{"date_produced":"2023-09-29","party":"ZP","colors":"#263778","spend":3806348,"Daily Spend":3806348,"Date":"2023-09-29","x":1695945600000,"y":3806348,"fill":"#263778"},{"date_produced":"2023-09-30","party":"ZP","colors":"#263778","spend":3925383,"Daily Spend":3925383,"Date":"2023-09-30","x":1696032000000,"y":3925383,"fill":"#263778"}],"type":"area"},{"name":"KO","data":[{"date_produced":"2023-08-31","party":"KO","colors":"#f68f2d","spend":15546,"Daily Spend":15546,"Date":"2023-08-31","x":1693440000000,"y":15546,"fill":"#f68f2d"},{"date_produced":"2023-09-01","party":"KO","colors":"#f68f2d","spend":26380,"Daily Spend":26380,"Date":"2023-09-01","x":1693526400000,"y":26380,"fill":"#f68f2d"},{"date_produced":"2023-09-02","party":"KO","colors":"#f68f2d","spend":39647,"Daily Spend":39647,"Date":"2023-09-02","x":1693612800000,"y":39647,"fill":"#f68f2d"},{"date_produced":"2023-09-03","party":"KO","colors":"#f68f2d","spend":54853,"Daily Spend":54853,"Date":"2023-09-03","x":1693699200000,"y":54853,"fill":"#f68f2d"},{"date_produced":"2023-09-04","party":"KO","colors":"#f68f2d","spend":67967,"Daily Spend":67967,"Date":"2023-09-04","x":1693785600000,"y":67967,"fill":"#f68f2d"},{"date_produced":"2023-09-05","party":"KO","colors":"#f68f2d","spend":81817,"Daily Spend":81817,"Date":"2023-09-05","x":1693872000000,"y":81817,"fill":"#f68f2d"},{"date_produced":"2023-09-06","party":"KO","colors":"#f68f2d","spend":107427,"Daily Spend":107427,"Date":"2023-09-06","x":1693958400000,"y":107427,"fill":"#f68f2d"},{"date_produced":"2023-09-07","party":"KO","colors":"#f68f2d","spend":149092,"Daily Spend":149092,"Date":"2023-09-07","x":1694044800000,"y":149092,"fill":"#f68f2d"},{"date_produced":"2023-09-08","party":"KO","colors":"#f68f2d","spend":213624,"Daily Spend":213624,"Date":"2023-09-08","x":1694131200000,"y":213624,"fill":"#f68f2d"},{"date_produced":"2023-09-09","party":"KO","colors":"#f68f2d","spend":290509,"Daily Spend":290509,"Date":"2023-09-09","x":1694217600000,"y":290509,"fill":"#f68f2d"},{"date_produced":"2023-09-10","party":"KO","colors":"#f68f2d","spend":358507,"Daily Spend":358507,"Date":"2023-09-10","x":1694304000000,"y":358507,"fill":"#f68f2d"},{"date_produced":"2023-09-11","party":"KO","colors":"#f68f2d","spend":489586,"Daily Spend":489586,"Date":"2023-09-11","x":1694390400000,"y":489586,"fill":"#f68f2d"},{"date_produced":"2023-09-12","party":"KO","colors":"#f68f2d","spend":598851,"Daily Spend":598851,"Date":"2023-09-12","x":1694476800000,"y":598851,"fill":"#f68f2d"},{"date_produced":"2023-09-13","party":"KO","colors":"#f68f2d","spend":678259,"Daily Spend":678259,"Date":"2023-09-13","x":1694563200000,"y":678259,"fill":"#f68f2d"},{"date_produced":"2023-09-14","party":"KO","colors":"#f68f2d","spend":737211,"Daily Spend":737211,"Date":"2023-09-14","x":1694649600000,"y":737211,"fill":"#f68f2d"},{"date_produced":"2023-09-15","party":"KO","colors":"#f68f2d","spend":867966,"Daily Spend":867966,"Date":"2023-09-15","x":1694736000000,"y":867966,"fill":"#f68f2d"},{"date_produced":"2023-09-16","party":"KO","colors":"#f68f2d","spend":1010378,"Daily Spend":1010378,"Date":"2023-09-16","x":1694822400000,"y":1010378,"fill":"#f68f2d"},{"date_produced":"2023-09-17","party":"KO","colors":"#f68f2d","spend":1186075,"Daily Spend":1186075,"Date":"2023-09-17","x":1694908800000,"y":1186075,"fill":"#f68f2d"},{"date_produced":"2023-09-18","party":"KO","colors":"#f68f2d","spend":1310636,"Daily Spend":1310636,"Date":"2023-09-18","x":1694995200000,"y":1310636,"fill":"#f68f2d"},{"date_produced":"2023-09-19","party":"KO","colors":"#f68f2d","spend":1373339,"Daily Spend":1373339,"Date":"2023-09-19","x":1695081600000,"y":1373339,"fill":"#f68f2d"},{"date_produced":"2023-09-20","party":"KO","colors":"#f68f2d","spend":1456229,"Daily Spend":1456229,"Date":"2023-09-20","x":1695168000000,"y":1456229,"fill":"#f68f2d"},{"date_produced":"2023-09-21","party":"KO","colors":"#f68f2d","spend":1516311,"Daily Spend":1516311,"Date":"2023-09-21","x":1695254400000,"y":1516311,"fill":"#f68f2d"},{"date_produced":"2023-09-22","party":"KO","colors":"#f68f2d","spend":1576885,"Daily Spend":1576885,"Date":"2023-09-22","x":1695340800000,"y":1576885,"fill":"#f68f2d"},{"date_produced":"2023-09-23","party":"KO","colors":"#f68f2d","spend":1626262,"Daily Spend":1626262,"Date":"2023-09-23","x":1695427200000,"y":1626262,"fill":"#f68f2d"},{"date_produced":"2023-09-24","party":"KO","colors":"#f68f2d","spend":1677438,"Daily Spend":1677438,"Date":"2023-09-24","x":1695513600000,"y":1677438,"fill":"#f68f2d"},{"date_produced":"2023-09-25","party":"KO","colors":"#f68f2d","spend":1728928,"Daily Spend":1728928,"Date":"2023-09-25","x":1695600000000,"y":1728928,"fill":"#f68f2d"},{"date_produced":"2023-09-26","party":"KO","colors":"#f68f2d","spend":1780257,"Daily Spend":1780257,"Date":"2023-09-26","x":1695686400000,"y":1780257,"fill":"#f68f2d"},{"date_produced":"2023-09-27","party":"KO","colors":"#f68f2d","spend":1843689,"Daily Spend":1843689,"Date":"2023-09-27","x":1695772800000,"y":1843689,"fill":"#f68f2d"},{"date_produced":"2023-09-28","party":"KO","colors":"#f68f2d","spend":1920683,"Daily Spend":1920683,"Date":"2023-09-28","x":1695859200000,"y":1920683,"fill":"#f68f2d"},{"date_produced":"2023-09-29","party":"KO","colors":"#f68f2d","spend":2020760,"Daily Spend":2020760,"Date":"2023-09-29","x":1695945600000,"y":2020760,"fill":"#f68f2d"},{"date_produced":"2023-09-30","party":"KO","colors":"#f68f2d","spend":2088774,"Daily Spend":2088774,"Date":"2023-09-30","x":1696032000000,"y":2088774,"fill":"#f68f2d"}],"type":"area"}],"xAxis":{"type":"datetime","title":{"text":"Date"},"categories":null},"colors":["#e6001a","#ffd900","#122746","#851a64","#3db53a","#263778","#f68f2d"],"tooltip":{"shared":true,"positioner":"function (labelWidth, labelHeight, point) {\n        return { x: 200, y: this.chart.plotTop };\n    }"}},"theme":{"chart":{"backgroundColor":"transparent"},"colors":["#7cb5ec","#434348","#90ed7d","#f7a35c","#8085e9","#f15c80","#e4d354","#2b908f","#f45b5b","#91e8e1"]},"conf_opts":{"global":{"Date":null,"VMLRadialGradientURL":"http =//code.highcharts.com/list(version)/gfx/vml-radial-gradient.png","canvasToolsURL":"http =//code.highcharts.com/list(version)/modules/canvas-tools.js","getTimezoneOffset":null,"timezoneOffset":0,"useUTC":true},"lang":{"contextButtonTitle":"Chart context menu","decimalPoint":".","downloadCSV":"Download CSV","downloadJPEG":"Download JPEG image","downloadPDF":"Download PDF document","downloadPNG":"Download PNG image","downloadSVG":"Download SVG vector image","downloadXLS":"Download XLS","drillUpText":"◁ Back to {series.name}","exitFullscreen":"Exit from full screen","exportData":{"annotationHeader":"Annotations","categoryDatetimeHeader":"DateTime","categoryHeader":"Category"},"hideData":"Hide data table","invalidDate":null,"loading":"Loading...","months":["January","February","March","April","May","June","July","August","September","October","November","December"],"noData":"No data to display","numericSymbolMagnitude":1000,"numericSymbols":["k","M","G","T","P","E"],"printChart":"Print chart","resetZoom":"Reset zoom","resetZoomTitle":"Reset zoom level 1:1","shortMonths":["Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"],"shortWeekdays":["Sat","Sun","Mon","Tue","Wed","Thu","Fri"],"thousandsSep":" ","viewData":"View data table","viewFullscreen":"View in full screen","weekdays":["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday"]}},"type":"chart","fonts":[],"debug":false},"evals":["hc_opts.tooltip.positioner"],"jsHooks":[]}</script>
```
:::
:::



### Daily


::: {.cell}
::: {.cell-output-display}
```{=html}
<div class="highchart html-widget html-fill-item-overflow-hidden html-fill-item" id="htmlwidget-ba5e46fdcdb8f04079d4" style="width:100%;height:480px;"></div>
<script type="application/json" data-for="htmlwidget-ba5e46fdcdb8f04079d4">{"x":{"hc_opts":{"chart":{"reflow":true},"title":{"text":null},"yAxis":{"title":{"text":"Daily Spend"},"type":"linear"},"credits":{"enabled":false},"exporting":{"enabled":false},"boost":{"enabled":false},"plotOptions":{"series":{"label":{"enabled":false},"turboThreshold":0,"showInLegend":true},"treemap":{"layoutAlgorithm":"squarified"},"scatter":{"marker":{"symbol":"circle"}},"area":{"stacking":"normal","lineWidth":1,"marker":{"enabled":false}}},"series":[{"name":"TD","data":[{"date_produced":"2023-08-31","party":"TD","colors":"#3db53a","spend":1407,"Daily Spend":1407,"Date":"2023-08-31","x":1693440000000,"y":1407,"fill":"#3db53a"},{"date_produced":"2023-09-01","party":"TD","colors":"#3db53a","spend":751,"Daily Spend":751,"Date":"2023-09-01","x":1693526400000,"y":751,"fill":"#3db53a"},{"date_produced":"2023-09-02","party":"TD","colors":"#3db53a","spend":1045,"Daily Spend":1045,"Date":"2023-09-02","x":1693612800000,"y":1045,"fill":"#3db53a"},{"date_produced":"2023-09-03","party":"TD","colors":"#3db53a","spend":2132,"Daily Spend":2132,"Date":"2023-09-03","x":1693699200000,"y":2132,"fill":"#3db53a"},{"date_produced":"2023-09-04","party":"TD","colors":"#3db53a","spend":1954,"Daily Spend":1954,"Date":"2023-09-04","x":1693785600000,"y":1954,"fill":"#3db53a"},{"date_produced":"2023-09-05","party":"TD","colors":"#3db53a","spend":2109,"Daily Spend":2109,"Date":"2023-09-05","x":1693872000000,"y":2109,"fill":"#3db53a"},{"date_produced":"2023-09-06","party":"TD","colors":"#3db53a","spend":2422,"Daily Spend":2422,"Date":"2023-09-06","x":1693958400000,"y":2422,"fill":"#3db53a"},{"date_produced":"2023-09-07","party":"TD","colors":"#3db53a","spend":2236,"Daily Spend":2236,"Date":"2023-09-07","x":1694044800000,"y":2236,"fill":"#3db53a"},{"date_produced":"2023-09-08","party":"TD","colors":"#3db53a","spend":3100,"Daily Spend":3100,"Date":"2023-09-08","x":1694131200000,"y":3100,"fill":"#3db53a"},{"date_produced":"2023-09-09","party":"TD","colors":"#3db53a","spend":4002,"Daily Spend":4002,"Date":"2023-09-09","x":1694217600000,"y":4002,"fill":"#3db53a"},{"date_produced":"2023-09-10","party":"TD","colors":"#3db53a","spend":5811,"Daily Spend":5811,"Date":"2023-09-10","x":1694304000000,"y":5811,"fill":"#3db53a"},{"date_produced":"2023-09-11","party":"TD","colors":"#3db53a","spend":5792,"Daily Spend":5792,"Date":"2023-09-11","x":1694390400000,"y":5792,"fill":"#3db53a"},{"date_produced":"2023-09-12","party":"TD","colors":"#3db53a","spend":9632,"Daily Spend":9632,"Date":"2023-09-12","x":1694476800000,"y":9632,"fill":"#3db53a"},{"date_produced":"2023-09-13","party":"TD","colors":"#3db53a","spend":9142,"Daily Spend":9142,"Date":"2023-09-13","x":1694563200000,"y":9142,"fill":"#3db53a"},{"date_produced":"2023-09-14","party":"TD","colors":"#3db53a","spend":12612,"Daily Spend":12612,"Date":"2023-09-14","x":1694649600000,"y":12612,"fill":"#3db53a"},{"date_produced":"2023-09-15","party":"TD","colors":"#3db53a","spend":14456,"Daily Spend":14456,"Date":"2023-09-15","x":1694736000000,"y":14456,"fill":"#3db53a"},{"date_produced":"2023-09-16","party":"TD","colors":"#3db53a","spend":14827,"Daily Spend":14827,"Date":"2023-09-16","x":1694822400000,"y":14827,"fill":"#3db53a"},{"date_produced":"2023-09-17","party":"TD","colors":"#3db53a","spend":16846,"Daily Spend":16846,"Date":"2023-09-17","x":1694908800000,"y":16846,"fill":"#3db53a"},{"date_produced":"2023-09-18","party":"TD","colors":"#3db53a","spend":10796,"Daily Spend":10796,"Date":"2023-09-18","x":1694995200000,"y":10796,"fill":"#3db53a"},{"date_produced":"2023-09-19","party":"TD","colors":"#3db53a","spend":13514,"Daily Spend":13514,"Date":"2023-09-19","x":1695081600000,"y":13514,"fill":"#3db53a"},{"date_produced":"2023-09-20","party":"TD","colors":"#3db53a","spend":14613,"Daily Spend":14613,"Date":"2023-09-20","x":1695168000000,"y":14613,"fill":"#3db53a"},{"date_produced":"2023-09-21","party":"TD","colors":"#3db53a","spend":15771,"Daily Spend":15771,"Date":"2023-09-21","x":1695254400000,"y":15771,"fill":"#3db53a"},{"date_produced":"2023-09-22","party":"TD","colors":"#3db53a","spend":16366,"Daily Spend":16366,"Date":"2023-09-22","x":1695340800000,"y":16366,"fill":"#3db53a"},{"date_produced":"2023-09-23","party":"TD","colors":"#3db53a","spend":18286,"Daily Spend":18286,"Date":"2023-09-23","x":1695427200000,"y":18286,"fill":"#3db53a"},{"date_produced":"2023-09-24","party":"TD","colors":"#3db53a","spend":18039,"Daily Spend":18039,"Date":"2023-09-24","x":1695513600000,"y":18039,"fill":"#3db53a"},{"date_produced":"2023-09-25","party":"TD","colors":"#3db53a","spend":16836,"Daily Spend":16836,"Date":"2023-09-25","x":1695600000000,"y":16836,"fill":"#3db53a"},{"date_produced":"2023-09-26","party":"TD","colors":"#3db53a","spend":18929,"Daily Spend":18929,"Date":"2023-09-26","x":1695686400000,"y":18929,"fill":"#3db53a"},{"date_produced":"2023-09-27","party":"TD","colors":"#3db53a","spend":20455,"Daily Spend":20455,"Date":"2023-09-27","x":1695772800000,"y":20455,"fill":"#3db53a"},{"date_produced":"2023-09-28","party":"TD","colors":"#3db53a","spend":24156,"Daily Spend":24156,"Date":"2023-09-28","x":1695859200000,"y":24156,"fill":"#3db53a"},{"date_produced":"2023-09-29","party":"TD","colors":"#3db53a","spend":21650,"Daily Spend":21650,"Date":"2023-09-29","x":1695945600000,"y":21650,"fill":"#3db53a"},{"date_produced":"2023-09-30","party":"TD","colors":"#3db53a","spend":26683,"Daily Spend":26683,"Date":"2023-09-30","x":1696032000000,"y":26683,"fill":"#3db53a"}],"type":"area"},{"name":"BS","data":[{"date_produced":"2023-08-31","party":"BS","colors":"#e6001a","spend":145,"Daily Spend":145,"Date":"2023-08-31","x":1693440000000,"y":145,"fill":"#e6001a"},{"date_produced":"2023-09-01","party":"BS","colors":"#e6001a","spend":377,"Daily Spend":377,"Date":"2023-09-01","x":1693526400000,"y":377,"fill":"#e6001a"},{"date_produced":"2023-09-02","party":"BS","colors":"#e6001a","spend":377,"Daily Spend":377,"Date":"2023-09-02","x":1693612800000,"y":377,"fill":"#e6001a"},{"date_produced":"2023-09-03","party":"BS","colors":"#e6001a","spend":365,"Daily Spend":365,"Date":"2023-09-03","x":1693699200000,"y":365,"fill":"#e6001a"},{"date_produced":"2023-09-04","party":"BS","colors":"#e6001a","spend":371,"Daily Spend":371,"Date":"2023-09-04","x":1693785600000,"y":371,"fill":"#e6001a"},{"date_produced":"2023-09-05","party":"BS","colors":"#e6001a","spend":683,"Daily Spend":683,"Date":"2023-09-05","x":1693872000000,"y":683,"fill":"#e6001a"},{"date_produced":"2023-09-06","party":"BS","colors":"#e6001a","spend":615,"Daily Spend":615,"Date":"2023-09-06","x":1693958400000,"y":615,"fill":"#e6001a"},{"date_produced":"2023-09-07","party":"BS","colors":"#e6001a","spend":597,"Daily Spend":597,"Date":"2023-09-07","x":1694044800000,"y":597,"fill":"#e6001a"},{"date_produced":"2023-09-08","party":"BS","colors":"#e6001a","spend":817,"Daily Spend":817,"Date":"2023-09-08","x":1694131200000,"y":817,"fill":"#e6001a"},{"date_produced":"2023-09-09","party":"BS","colors":"#e6001a","spend":695,"Daily Spend":695,"Date":"2023-09-09","x":1694217600000,"y":695,"fill":"#e6001a"},{"date_produced":"2023-09-10","party":"BS","colors":"#e6001a","spend":507,"Daily Spend":507,"Date":"2023-09-10","x":1694304000000,"y":507,"fill":"#e6001a"},{"date_produced":"2023-09-11","party":"BS","colors":"#e6001a","spend":571,"Daily Spend":571,"Date":"2023-09-11","x":1694390400000,"y":571,"fill":"#e6001a"},{"date_produced":"2023-09-12","party":"BS","colors":"#e6001a","spend":530,"Daily Spend":530,"Date":"2023-09-12","x":1694476800000,"y":530,"fill":"#e6001a"},{"date_produced":"2023-09-13","party":"BS","colors":"#e6001a","spend":609,"Daily Spend":609,"Date":"2023-09-13","x":1694563200000,"y":609,"fill":"#e6001a"},{"date_produced":"2023-09-14","party":"BS","colors":"#e6001a","spend":819,"Daily Spend":819,"Date":"2023-09-14","x":1694649600000,"y":819,"fill":"#e6001a"},{"date_produced":"2023-09-15","party":"BS","colors":"#e6001a","spend":1076,"Daily Spend":1076,"Date":"2023-09-15","x":1694736000000,"y":1076,"fill":"#e6001a"},{"date_produced":"2023-09-16","party":"BS","colors":"#e6001a","spend":1825,"Daily Spend":1825,"Date":"2023-09-16","x":1694822400000,"y":1825,"fill":"#e6001a"},{"date_produced":"2023-09-17","party":"BS","colors":"#e6001a","spend":2332,"Daily Spend":2332,"Date":"2023-09-17","x":1694908800000,"y":2332,"fill":"#e6001a"},{"date_produced":"2023-09-18","party":"BS","colors":"#e6001a","spend":1847,"Daily Spend":1847,"Date":"2023-09-18","x":1694995200000,"y":1847,"fill":"#e6001a"},{"date_produced":"2023-09-19","party":"BS","colors":"#e6001a","spend":2632,"Daily Spend":2632,"Date":"2023-09-19","x":1695081600000,"y":2632,"fill":"#e6001a"},{"date_produced":"2023-09-20","party":"BS","colors":"#e6001a","spend":3442,"Daily Spend":3442,"Date":"2023-09-20","x":1695168000000,"y":3442,"fill":"#e6001a"},{"date_produced":"2023-09-21","party":"BS","colors":"#e6001a","spend":4344,"Daily Spend":4344,"Date":"2023-09-21","x":1695254400000,"y":4344,"fill":"#e6001a"},{"date_produced":"2023-09-22","party":"BS","colors":"#e6001a","spend":4846,"Daily Spend":4846,"Date":"2023-09-22","x":1695340800000,"y":4846,"fill":"#e6001a"},{"date_produced":"2023-09-23","party":"BS","colors":"#e6001a","spend":5838,"Daily Spend":5838,"Date":"2023-09-23","x":1695427200000,"y":5838,"fill":"#e6001a"},{"date_produced":"2023-09-24","party":"BS","colors":"#e6001a","spend":6102,"Daily Spend":6102,"Date":"2023-09-24","x":1695513600000,"y":6102,"fill":"#e6001a"},{"date_produced":"2023-09-25","party":"BS","colors":"#e6001a","spend":5640,"Daily Spend":5640,"Date":"2023-09-25","x":1695600000000,"y":5640,"fill":"#e6001a"},{"date_produced":"2023-09-26","party":"BS","colors":"#e6001a","spend":5730,"Daily Spend":5730,"Date":"2023-09-26","x":1695686400000,"y":5730,"fill":"#e6001a"},{"date_produced":"2023-09-27","party":"BS","colors":"#e6001a","spend":5574,"Daily Spend":5574,"Date":"2023-09-27","x":1695772800000,"y":5574,"fill":"#e6001a"},{"date_produced":"2023-09-28","party":"BS","colors":"#e6001a","spend":7318,"Daily Spend":7318,"Date":"2023-09-28","x":1695859200000,"y":7318,"fill":"#e6001a"},{"date_produced":"2023-09-29","party":"BS","colors":"#e6001a","spend":7768,"Daily Spend":7768,"Date":"2023-09-29","x":1695945600000,"y":7768,"fill":"#e6001a"},{"date_produced":"2023-09-30","party":"BS","colors":"#e6001a","spend":7904,"Daily Spend":7904,"Date":"2023-09-30","x":1696032000000,"y":7904,"fill":"#e6001a"}],"type":"area"},{"name":"KWIN","data":[{"date_produced":"2023-08-31","party":"KWIN","colors":"#122746","spend":228,"Daily Spend":228,"Date":"2023-08-31","x":1693440000000,"y":228,"fill":"#122746"},{"date_produced":"2023-09-01","party":"KWIN","colors":"#122746","spend":601,"Daily Spend":601,"Date":"2023-09-01","x":1693526400000,"y":601,"fill":"#122746"},{"date_produced":"2023-09-02","party":"KWIN","colors":"#122746","spend":594,"Daily Spend":594,"Date":"2023-09-02","x":1693612800000,"y":594,"fill":"#122746"},{"date_produced":"2023-09-03","party":"KWIN","colors":"#122746","spend":197,"Daily Spend":197,"Date":"2023-09-03","x":1693699200000,"y":197,"fill":"#122746"},{"date_produced":"2023-09-04","party":"KWIN","colors":"#122746","spend":257,"Daily Spend":257,"Date":"2023-09-04","x":1693785600000,"y":257,"fill":"#122746"},{"date_produced":"2023-09-05","party":"KWIN","colors":"#122746","spend":1072,"Daily Spend":1072,"Date":"2023-09-05","x":1693872000000,"y":1072,"fill":"#122746"},{"date_produced":"2023-09-06","party":"KWIN","colors":"#122746","spend":6994,"Daily Spend":6994,"Date":"2023-09-06","x":1693958400000,"y":6994,"fill":"#122746"},{"date_produced":"2023-09-07","party":"KWIN","colors":"#122746","spend":3928,"Daily Spend":3928,"Date":"2023-09-07","x":1694044800000,"y":3928,"fill":"#122746"},{"date_produced":"2023-09-08","party":"KWIN","colors":"#122746","spend":779,"Daily Spend":779,"Date":"2023-09-08","x":1694131200000,"y":779,"fill":"#122746"},{"date_produced":"2023-09-09","party":"KWIN","colors":"#122746","spend":1304,"Daily Spend":1304,"Date":"2023-09-09","x":1694217600000,"y":1304,"fill":"#122746"},{"date_produced":"2023-09-10","party":"KWIN","colors":"#122746","spend":885,"Daily Spend":885,"Date":"2023-09-10","x":1694304000000,"y":885,"fill":"#122746"},{"date_produced":"2023-09-11","party":"KWIN","colors":"#122746","spend":1120,"Daily Spend":1120,"Date":"2023-09-11","x":1694390400000,"y":1120,"fill":"#122746"},{"date_produced":"2023-09-12","party":"KWIN","colors":"#122746","spend":443,"Daily Spend":443,"Date":"2023-09-12","x":1694476800000,"y":443,"fill":"#122746"},{"date_produced":"2023-09-13","party":"KWIN","colors":"#122746","spend":897,"Daily Spend":897,"Date":"2023-09-13","x":1694563200000,"y":897,"fill":"#122746"},{"date_produced":"2023-09-14","party":"KWIN","colors":"#122746","spend":1564,"Daily Spend":1564,"Date":"2023-09-14","x":1694649600000,"y":1564,"fill":"#122746"},{"date_produced":"2023-09-15","party":"KWIN","colors":"#122746","spend":1663,"Daily Spend":1663,"Date":"2023-09-15","x":1694736000000,"y":1663,"fill":"#122746"},{"date_produced":"2023-09-16","party":"KWIN","colors":"#122746","spend":1703,"Daily Spend":1703,"Date":"2023-09-16","x":1694822400000,"y":1703,"fill":"#122746"},{"date_produced":"2023-09-17","party":"KWIN","colors":"#122746","spend":2432,"Daily Spend":2432,"Date":"2023-09-17","x":1694908800000,"y":2432,"fill":"#122746"},{"date_produced":"2023-09-18","party":"KWIN","colors":"#122746","spend":3810,"Daily Spend":3810,"Date":"2023-09-18","x":1694995200000,"y":3810,"fill":"#122746"},{"date_produced":"2023-09-19","party":"KWIN","colors":"#122746","spend":3710,"Daily Spend":3710,"Date":"2023-09-19","x":1695081600000,"y":3710,"fill":"#122746"},{"date_produced":"2023-09-20","party":"KWIN","colors":"#122746","spend":4560,"Daily Spend":4560,"Date":"2023-09-20","x":1695168000000,"y":4560,"fill":"#122746"},{"date_produced":"2023-09-21","party":"KWIN","colors":"#122746","spend":4774,"Daily Spend":4774,"Date":"2023-09-21","x":1695254400000,"y":4774,"fill":"#122746"},{"date_produced":"2023-09-22","party":"KWIN","colors":"#122746","spend":4457,"Daily Spend":4457,"Date":"2023-09-22","x":1695340800000,"y":4457,"fill":"#122746"},{"date_produced":"2023-09-23","party":"KWIN","colors":"#122746","spend":9345,"Daily Spend":9345,"Date":"2023-09-23","x":1695427200000,"y":9345,"fill":"#122746"},{"date_produced":"2023-09-24","party":"KWIN","colors":"#122746","spend":8240,"Daily Spend":8240,"Date":"2023-09-24","x":1695513600000,"y":8240,"fill":"#122746"},{"date_produced":"2023-09-25","party":"KWIN","colors":"#122746","spend":6000,"Daily Spend":6000,"Date":"2023-09-25","x":1695600000000,"y":6000,"fill":"#122746"},{"date_produced":"2023-09-26","party":"KWIN","colors":"#122746","spend":12351,"Daily Spend":12351,"Date":"2023-09-26","x":1695686400000,"y":12351,"fill":"#122746"},{"date_produced":"2023-09-27","party":"KWIN","colors":"#122746","spend":8386,"Daily Spend":8386,"Date":"2023-09-27","x":1695772800000,"y":8386,"fill":"#122746"},{"date_produced":"2023-09-28","party":"KWIN","colors":"#122746","spend":7172,"Daily Spend":7172,"Date":"2023-09-28","x":1695859200000,"y":7172,"fill":"#122746"},{"date_produced":"2023-09-29","party":"KWIN","colors":"#122746","spend":9681,"Daily Spend":9681,"Date":"2023-09-29","x":1695945600000,"y":9681,"fill":"#122746"},{"date_produced":"2023-09-30","party":"KWIN","colors":"#122746","spend":10549,"Daily Spend":10549,"Date":"2023-09-30","x":1696032000000,"y":10549,"fill":"#122746"}],"type":"area"},{"name":"LEW","data":[{"date_produced":"2023-08-31","party":"LEW","colors":"#851a64","spend":1314,"Daily Spend":1314,"Date":"2023-08-31","x":1693440000000,"y":1314,"fill":"#851a64"},{"date_produced":"2023-09-01","party":"LEW","colors":"#851a64","spend":1861,"Daily Spend":1861,"Date":"2023-09-01","x":1693526400000,"y":1861,"fill":"#851a64"},{"date_produced":"2023-09-02","party":"LEW","colors":"#851a64","spend":1523,"Daily Spend":1523,"Date":"2023-09-02","x":1693612800000,"y":1523,"fill":"#851a64"},{"date_produced":"2023-09-03","party":"LEW","colors":"#851a64","spend":1490,"Daily Spend":1490,"Date":"2023-09-03","x":1693699200000,"y":1490,"fill":"#851a64"},{"date_produced":"2023-09-04","party":"LEW","colors":"#851a64","spend":1536,"Daily Spend":1536,"Date":"2023-09-04","x":1693785600000,"y":1536,"fill":"#851a64"},{"date_produced":"2023-09-05","party":"LEW","colors":"#851a64","spend":1760,"Daily Spend":1760,"Date":"2023-09-05","x":1693872000000,"y":1760,"fill":"#851a64"},{"date_produced":"2023-09-06","party":"LEW","colors":"#851a64","spend":2324,"Daily Spend":2324,"Date":"2023-09-06","x":1693958400000,"y":2324,"fill":"#851a64"},{"date_produced":"2023-09-07","party":"LEW","colors":"#851a64","spend":2676,"Daily Spend":2676,"Date":"2023-09-07","x":1694044800000,"y":2676,"fill":"#851a64"},{"date_produced":"2023-09-08","party":"LEW","colors":"#851a64","spend":3511,"Daily Spend":3511,"Date":"2023-09-08","x":1694131200000,"y":3511,"fill":"#851a64"},{"date_produced":"2023-09-09","party":"LEW","colors":"#851a64","spend":4246,"Daily Spend":4246,"Date":"2023-09-09","x":1694217600000,"y":4246,"fill":"#851a64"},{"date_produced":"2023-09-10","party":"LEW","colors":"#851a64","spend":6696,"Daily Spend":6696,"Date":"2023-09-10","x":1694304000000,"y":6696,"fill":"#851a64"},{"date_produced":"2023-09-11","party":"LEW","colors":"#851a64","spend":7148,"Daily Spend":7148,"Date":"2023-09-11","x":1694390400000,"y":7148,"fill":"#851a64"},{"date_produced":"2023-09-12","party":"LEW","colors":"#851a64","spend":7774,"Daily Spend":7774,"Date":"2023-09-12","x":1694476800000,"y":7774,"fill":"#851a64"},{"date_produced":"2023-09-13","party":"LEW","colors":"#851a64","spend":14268,"Daily Spend":14268,"Date":"2023-09-13","x":1694563200000,"y":14268,"fill":"#851a64"},{"date_produced":"2023-09-14","party":"LEW","colors":"#851a64","spend":14780,"Daily Spend":14780,"Date":"2023-09-14","x":1694649600000,"y":14780,"fill":"#851a64"},{"date_produced":"2023-09-15","party":"LEW","colors":"#851a64","spend":14755,"Daily Spend":14755,"Date":"2023-09-15","x":1694736000000,"y":14755,"fill":"#851a64"},{"date_produced":"2023-09-16","party":"LEW","colors":"#851a64","spend":15182,"Daily Spend":15182,"Date":"2023-09-16","x":1694822400000,"y":15182,"fill":"#851a64"},{"date_produced":"2023-09-17","party":"LEW","colors":"#851a64","spend":16231,"Daily Spend":16231,"Date":"2023-09-17","x":1694908800000,"y":16231,"fill":"#851a64"},{"date_produced":"2023-09-18","party":"LEW","colors":"#851a64","spend":16285,"Daily Spend":16285,"Date":"2023-09-18","x":1694995200000,"y":16285,"fill":"#851a64"},{"date_produced":"2023-09-19","party":"LEW","colors":"#851a64","spend":16121,"Daily Spend":16121,"Date":"2023-09-19","x":1695081600000,"y":16121,"fill":"#851a64"},{"date_produced":"2023-09-20","party":"LEW","colors":"#851a64","spend":24472,"Daily Spend":24472,"Date":"2023-09-20","x":1695168000000,"y":24472,"fill":"#851a64"},{"date_produced":"2023-09-21","party":"LEW","colors":"#851a64","spend":25046,"Daily Spend":25046,"Date":"2023-09-21","x":1695254400000,"y":25046,"fill":"#851a64"},{"date_produced":"2023-09-22","party":"LEW","colors":"#851a64","spend":27314,"Daily Spend":27314,"Date":"2023-09-22","x":1695340800000,"y":27314,"fill":"#851a64"},{"date_produced":"2023-09-23","party":"LEW","colors":"#851a64","spend":28441,"Daily Spend":28441,"Date":"2023-09-23","x":1695427200000,"y":28441,"fill":"#851a64"},{"date_produced":"2023-09-24","party":"LEW","colors":"#851a64","spend":28156,"Daily Spend":28156,"Date":"2023-09-24","x":1695513600000,"y":28156,"fill":"#851a64"},{"date_produced":"2023-09-25","party":"LEW","colors":"#851a64","spend":24758,"Daily Spend":24758,"Date":"2023-09-25","x":1695600000000,"y":24758,"fill":"#851a64"},{"date_produced":"2023-09-26","party":"LEW","colors":"#851a64","spend":28723,"Daily Spend":28723,"Date":"2023-09-26","x":1695686400000,"y":28723,"fill":"#851a64"},{"date_produced":"2023-09-27","party":"LEW","colors":"#851a64","spend":32841,"Daily Spend":32841,"Date":"2023-09-27","x":1695772800000,"y":32841,"fill":"#851a64"},{"date_produced":"2023-09-28","party":"LEW","colors":"#851a64","spend":29282,"Daily Spend":29282,"Date":"2023-09-28","x":1695859200000,"y":29282,"fill":"#851a64"},{"date_produced":"2023-09-29","party":"LEW","colors":"#851a64","spend":31287,"Daily Spend":31287,"Date":"2023-09-29","x":1695945600000,"y":31287,"fill":"#851a64"},{"date_produced":"2023-09-30","party":"LEW","colors":"#851a64","spend":37086,"Daily Spend":37086,"Date":"2023-09-30","x":1696032000000,"y":37086,"fill":"#851a64"}],"type":"area"},{"name":"KO","data":[{"date_produced":"2023-08-31","party":"KO","colors":"#f68f2d","spend":7773,"Daily Spend":7773,"Date":"2023-08-31","x":1693440000000,"y":7773,"fill":"#f68f2d"},{"date_produced":"2023-09-01","party":"KO","colors":"#f68f2d","spend":10834,"Daily Spend":10834,"Date":"2023-09-01","x":1693526400000,"y":10834,"fill":"#f68f2d"},{"date_produced":"2023-09-02","party":"KO","colors":"#f68f2d","spend":13267,"Daily Spend":13267,"Date":"2023-09-02","x":1693612800000,"y":13267,"fill":"#f68f2d"},{"date_produced":"2023-09-03","party":"KO","colors":"#f68f2d","spend":15206,"Daily Spend":15206,"Date":"2023-09-03","x":1693699200000,"y":15206,"fill":"#f68f2d"},{"date_produced":"2023-09-04","party":"KO","colors":"#f68f2d","spend":13114,"Daily Spend":13114,"Date":"2023-09-04","x":1693785600000,"y":13114,"fill":"#f68f2d"},{"date_produced":"2023-09-05","party":"KO","colors":"#f68f2d","spend":13850,"Daily Spend":13850,"Date":"2023-09-05","x":1693872000000,"y":13850,"fill":"#f68f2d"},{"date_produced":"2023-09-06","party":"KO","colors":"#f68f2d","spend":25610,"Daily Spend":25610,"Date":"2023-09-06","x":1693958400000,"y":25610,"fill":"#f68f2d"},{"date_produced":"2023-09-07","party":"KO","colors":"#f68f2d","spend":41665,"Daily Spend":41665,"Date":"2023-09-07","x":1694044800000,"y":41665,"fill":"#f68f2d"},{"date_produced":"2023-09-08","party":"KO","colors":"#f68f2d","spend":64532,"Daily Spend":64532,"Date":"2023-09-08","x":1694131200000,"y":64532,"fill":"#f68f2d"},{"date_produced":"2023-09-09","party":"KO","colors":"#f68f2d","spend":76885,"Daily Spend":76885,"Date":"2023-09-09","x":1694217600000,"y":76885,"fill":"#f68f2d"},{"date_produced":"2023-09-10","party":"KO","colors":"#f68f2d","spend":67998,"Daily Spend":67998,"Date":"2023-09-10","x":1694304000000,"y":67998,"fill":"#f68f2d"},{"date_produced":"2023-09-11","party":"KO","colors":"#f68f2d","spend":131079,"Daily Spend":131079,"Date":"2023-09-11","x":1694390400000,"y":131079,"fill":"#f68f2d"},{"date_produced":"2023-09-12","party":"KO","colors":"#f68f2d","spend":109265,"Daily Spend":109265,"Date":"2023-09-12","x":1694476800000,"y":109265,"fill":"#f68f2d"},{"date_produced":"2023-09-13","party":"KO","colors":"#f68f2d","spend":79408,"Daily Spend":79408,"Date":"2023-09-13","x":1694563200000,"y":79408,"fill":"#f68f2d"},{"date_produced":"2023-09-14","party":"KO","colors":"#f68f2d","spend":58952,"Daily Spend":58952,"Date":"2023-09-14","x":1694649600000,"y":58952,"fill":"#f68f2d"},{"date_produced":"2023-09-15","party":"KO","colors":"#f68f2d","spend":130755,"Daily Spend":130755,"Date":"2023-09-15","x":1694736000000,"y":130755,"fill":"#f68f2d"},{"date_produced":"2023-09-16","party":"KO","colors":"#f68f2d","spend":142412,"Daily Spend":142412,"Date":"2023-09-16","x":1694822400000,"y":142412,"fill":"#f68f2d"},{"date_produced":"2023-09-17","party":"KO","colors":"#f68f2d","spend":175697,"Daily Spend":175697,"Date":"2023-09-17","x":1694908800000,"y":175697,"fill":"#f68f2d"},{"date_produced":"2023-09-18","party":"KO","colors":"#f68f2d","spend":124561,"Daily Spend":124561,"Date":"2023-09-18","x":1694995200000,"y":124561,"fill":"#f68f2d"},{"date_produced":"2023-09-19","party":"KO","colors":"#f68f2d","spend":62703,"Daily Spend":62703,"Date":"2023-09-19","x":1695081600000,"y":62703,"fill":"#f68f2d"},{"date_produced":"2023-09-20","party":"KO","colors":"#f68f2d","spend":82890,"Daily Spend":82890,"Date":"2023-09-20","x":1695168000000,"y":82890,"fill":"#f68f2d"},{"date_produced":"2023-09-21","party":"KO","colors":"#f68f2d","spend":60082,"Daily Spend":60082,"Date":"2023-09-21","x":1695254400000,"y":60082,"fill":"#f68f2d"},{"date_produced":"2023-09-22","party":"KO","colors":"#f68f2d","spend":60574,"Daily Spend":60574,"Date":"2023-09-22","x":1695340800000,"y":60574,"fill":"#f68f2d"},{"date_produced":"2023-09-23","party":"KO","colors":"#f68f2d","spend":49377,"Daily Spend":49377,"Date":"2023-09-23","x":1695427200000,"y":49377,"fill":"#f68f2d"},{"date_produced":"2023-09-24","party":"KO","colors":"#f68f2d","spend":51176,"Daily Spend":51176,"Date":"2023-09-24","x":1695513600000,"y":51176,"fill":"#f68f2d"},{"date_produced":"2023-09-25","party":"KO","colors":"#f68f2d","spend":51490,"Daily Spend":51490,"Date":"2023-09-25","x":1695600000000,"y":51490,"fill":"#f68f2d"},{"date_produced":"2023-09-26","party":"KO","colors":"#f68f2d","spend":51329,"Daily Spend":51329,"Date":"2023-09-26","x":1695686400000,"y":51329,"fill":"#f68f2d"},{"date_produced":"2023-09-27","party":"KO","colors":"#f68f2d","spend":63432,"Daily Spend":63432,"Date":"2023-09-27","x":1695772800000,"y":63432,"fill":"#f68f2d"},{"date_produced":"2023-09-28","party":"KO","colors":"#f68f2d","spend":76994,"Daily Spend":76994,"Date":"2023-09-28","x":1695859200000,"y":76994,"fill":"#f68f2d"},{"date_produced":"2023-09-29","party":"KO","colors":"#f68f2d","spend":100077,"Daily Spend":100077,"Date":"2023-09-29","x":1695945600000,"y":100077,"fill":"#f68f2d"},{"date_produced":"2023-09-30","party":"KO","colors":"#f68f2d","spend":68014,"Daily Spend":68014,"Date":"2023-09-30","x":1696032000000,"y":68014,"fill":"#f68f2d"}],"type":"area"},{"name":"ZP","data":[{"date_produced":"2023-08-31","party":"ZP","colors":"#263778","spend":17220,"Daily Spend":17220,"Date":"2023-08-31","x":1693440000000,"y":17220,"fill":"#263778"},{"date_produced":"2023-09-01","party":"ZP","colors":"#263778","spend":133835,"Daily Spend":133835,"Date":"2023-09-01","x":1693526400000,"y":133835,"fill":"#263778"},{"date_produced":"2023-09-02","party":"ZP","colors":"#263778","spend":121733,"Daily Spend":121733,"Date":"2023-09-02","x":1693612800000,"y":121733,"fill":"#263778"},{"date_produced":"2023-09-03","party":"ZP","colors":"#263778","spend":131947,"Daily Spend":131947,"Date":"2023-09-03","x":1693699200000,"y":131947,"fill":"#263778"},{"date_produced":"2023-09-04","party":"ZP","colors":"#263778","spend":127031,"Daily Spend":127031,"Date":"2023-09-04","x":1693785600000,"y":127031,"fill":"#263778"},{"date_produced":"2023-09-05","party":"ZP","colors":"#263778","spend":128264,"Daily Spend":128264,"Date":"2023-09-05","x":1693872000000,"y":128264,"fill":"#263778"},{"date_produced":"2023-09-06","party":"ZP","colors":"#263778","spend":138651,"Daily Spend":138651,"Date":"2023-09-06","x":1693958400000,"y":138651,"fill":"#263778"},{"date_produced":"2023-09-07","party":"ZP","colors":"#263778","spend":125368,"Daily Spend":125368,"Date":"2023-09-07","x":1694044800000,"y":125368,"fill":"#263778"},{"date_produced":"2023-09-08","party":"ZP","colors":"#263778","spend":137535,"Daily Spend":137535,"Date":"2023-09-08","x":1694131200000,"y":137535,"fill":"#263778"},{"date_produced":"2023-09-09","party":"ZP","colors":"#263778","spend":142539,"Daily Spend":142539,"Date":"2023-09-09","x":1694217600000,"y":142539,"fill":"#263778"},{"date_produced":"2023-09-10","party":"ZP","colors":"#263778","spend":155412,"Daily Spend":155412,"Date":"2023-09-10","x":1694304000000,"y":155412,"fill":"#263778"},{"date_produced":"2023-09-11","party":"ZP","colors":"#263778","spend":149820,"Daily Spend":149820,"Date":"2023-09-11","x":1694390400000,"y":149820,"fill":"#263778"},{"date_produced":"2023-09-12","party":"ZP","colors":"#263778","spend":128002,"Daily Spend":128002,"Date":"2023-09-12","x":1694476800000,"y":128002,"fill":"#263778"},{"date_produced":"2023-09-13","party":"ZP","colors":"#263778","spend":127379,"Daily Spend":127379,"Date":"2023-09-13","x":1694563200000,"y":127379,"fill":"#263778"},{"date_produced":"2023-09-14","party":"ZP","colors":"#263778","spend":164091,"Daily Spend":164091,"Date":"2023-09-14","x":1694649600000,"y":164091,"fill":"#263778"},{"date_produced":"2023-09-15","party":"ZP","colors":"#263778","spend":101641,"Daily Spend":101641,"Date":"2023-09-15","x":1694736000000,"y":101641,"fill":"#263778"},{"date_produced":"2023-09-16","party":"ZP","colors":"#263778","spend":93733,"Daily Spend":93733,"Date":"2023-09-16","x":1694822400000,"y":93733,"fill":"#263778"},{"date_produced":"2023-09-17","party":"ZP","colors":"#263778","spend":129613,"Daily Spend":129613,"Date":"2023-09-17","x":1694908800000,"y":129613,"fill":"#263778"},{"date_produced":"2023-09-18","party":"ZP","colors":"#263778","spend":133675,"Daily Spend":133675,"Date":"2023-09-18","x":1694995200000,"y":133675,"fill":"#263778"},{"date_produced":"2023-09-19","party":"ZP","colors":"#263778","spend":153238,"Daily Spend":153238,"Date":"2023-09-19","x":1695081600000,"y":153238,"fill":"#263778"},{"date_produced":"2023-09-20","party":"ZP","colors":"#263778","spend":109533,"Daily Spend":109533,"Date":"2023-09-20","x":1695168000000,"y":109533,"fill":"#263778"},{"date_produced":"2023-09-21","party":"ZP","colors":"#263778","spend":131673,"Daily Spend":131673,"Date":"2023-09-21","x":1695254400000,"y":131673,"fill":"#263778"},{"date_produced":"2023-09-22","party":"ZP","colors":"#263778","spend":133052,"Daily Spend":133052,"Date":"2023-09-22","x":1695340800000,"y":133052,"fill":"#263778"},{"date_produced":"2023-09-23","party":"ZP","colors":"#263778","spend":131342,"Daily Spend":131342,"Date":"2023-09-23","x":1695427200000,"y":131342,"fill":"#263778"},{"date_produced":"2023-09-24","party":"ZP","colors":"#263778","spend":129529,"Daily Spend":129529,"Date":"2023-09-24","x":1695513600000,"y":129529,"fill":"#263778"},{"date_produced":"2023-09-25","party":"ZP","colors":"#263778","spend":128825,"Daily Spend":128825,"Date":"2023-09-25","x":1695600000000,"y":128825,"fill":"#263778"},{"date_produced":"2023-09-26","party":"ZP","colors":"#263778","spend":126334,"Daily Spend":126334,"Date":"2023-09-26","x":1695686400000,"y":126334,"fill":"#263778"},{"date_produced":"2023-09-27","party":"ZP","colors":"#263778","spend":125932,"Daily Spend":125932,"Date":"2023-09-27","x":1695772800000,"y":125932,"fill":"#263778"},{"date_produced":"2023-09-28","party":"ZP","colors":"#263778","spend":115304,"Daily Spend":115304,"Date":"2023-09-28","x":1695859200000,"y":115304,"fill":"#263778"},{"date_produced":"2023-09-29","party":"ZP","colors":"#263778","spend":116877,"Daily Spend":116877,"Date":"2023-09-29","x":1695945600000,"y":116877,"fill":"#263778"},{"date_produced":"2023-09-30","party":"ZP","colors":"#263778","spend":119035,"Daily Spend":119035,"Date":"2023-09-30","x":1696032000000,"y":119035,"fill":"#263778"}],"type":"area"},{"name":"LIB","data":[{"date_produced":"2023-08-31","party":"LIB","colors":"#ffd900","spend":780,"Daily Spend":780,"Date":"2023-08-31","x":1693440000000,"y":780,"fill":"#ffd900"},{"date_produced":"2023-09-01","party":"LIB","colors":"#ffd900","spend":690,"Daily Spend":690,"Date":"2023-09-01","x":1693526400000,"y":690,"fill":"#ffd900"},{"date_produced":"2023-09-02","party":"LIB","colors":"#ffd900","spend":798,"Daily Spend":798,"Date":"2023-09-02","x":1693612800000,"y":798,"fill":"#ffd900"},{"date_produced":"2023-09-03","party":"LIB","colors":"#ffd900","spend":901,"Daily Spend":901,"Date":"2023-09-03","x":1693699200000,"y":901,"fill":"#ffd900"},{"date_produced":"2023-09-04","party":"LIB","colors":"#ffd900","spend":774,"Daily Spend":774,"Date":"2023-09-04","x":1693785600000,"y":774,"fill":"#ffd900"},{"date_produced":"2023-09-05","party":"LIB","colors":"#ffd900","spend":658,"Daily Spend":658,"Date":"2023-09-05","x":1693872000000,"y":658,"fill":"#ffd900"},{"date_produced":"2023-09-06","party":"LIB","colors":"#ffd900","spend":589,"Daily Spend":589,"Date":"2023-09-06","x":1693958400000,"y":589,"fill":"#ffd900"},{"date_produced":"2023-09-07","party":"LIB","colors":"#ffd900","spend":329,"Daily Spend":329,"Date":"2023-09-07","x":1694044800000,"y":329,"fill":"#ffd900"},{"date_produced":"2023-09-08","party":"LIB","colors":"#ffd900","spend":69,"Daily Spend":69,"Date":"2023-09-08","x":1694131200000,"y":69,"fill":"#ffd900"},{"date_produced":"2023-09-09","party":"LIB","colors":"#ffd900","spend":76,"Daily Spend":76,"Date":"2023-09-09","x":1694217600000,"y":76,"fill":"#ffd900"},{"date_produced":"2023-09-10","party":"LIB","colors":"#ffd900","spend":86,"Daily Spend":86,"Date":"2023-09-10","x":1694304000000,"y":86,"fill":"#ffd900"},{"date_produced":"2023-09-11","party":"LIB","colors":"#ffd900","spend":79,"Daily Spend":79,"Date":"2023-09-11","x":1694390400000,"y":79,"fill":"#ffd900"},{"date_produced":"2023-09-12","party":"LIB","colors":"#ffd900","spend":78,"Daily Spend":78,"Date":"2023-09-12","x":1694476800000,"y":78,"fill":"#ffd900"},{"date_produced":"2023-09-13","party":"LIB","colors":"#ffd900","spend":77,"Daily Spend":77,"Date":"2023-09-13","x":1694563200000,"y":77,"fill":"#ffd900"},{"date_produced":"2023-09-14","party":"LIB","colors":"#ffd900","spend":75,"Daily Spend":75,"Date":"2023-09-14","x":1694649600000,"y":75,"fill":"#ffd900"},{"date_produced":"2023-09-15","party":"LIB","colors":"#ffd900","spend":73,"Daily Spend":73,"Date":"2023-09-15","x":1694736000000,"y":73,"fill":"#ffd900"},{"date_produced":"2023-09-16","party":"LIB","colors":"#ffd900","spend":77,"Daily Spend":77,"Date":"2023-09-16","x":1694822400000,"y":77,"fill":"#ffd900"},{"date_produced":"2023-09-17","party":"LIB","colors":"#ffd900","spend":92,"Daily Spend":92,"Date":"2023-09-17","x":1694908800000,"y":92,"fill":"#ffd900"},{"date_produced":"2023-09-18","party":"LIB","colors":"#ffd900","spend":89,"Daily Spend":89,"Date":"2023-09-18","x":1694995200000,"y":89,"fill":"#ffd900"},{"date_produced":"2023-09-19","party":"LIB","colors":"#ffd900","spend":97,"Daily Spend":97,"Date":"2023-09-19","x":1695081600000,"y":97,"fill":"#ffd900"},{"date_produced":"2023-09-20","party":"LIB","colors":"#ffd900","spend":84,"Daily Spend":84,"Date":"2023-09-20","x":1695168000000,"y":84,"fill":"#ffd900"},{"date_produced":"2023-09-21","party":"LIB","colors":"#ffd900","spend":84,"Daily Spend":84,"Date":"2023-09-21","x":1695254400000,"y":84,"fill":"#ffd900"},{"date_produced":"2023-09-22","party":"LIB","colors":"#ffd900","spend":69,"Daily Spend":69,"Date":"2023-09-22","x":1695340800000,"y":69,"fill":"#ffd900"},{"date_produced":"2023-09-23","party":"LIB","colors":"#ffd900","spend":64,"Daily Spend":64,"Date":"2023-09-23","x":1695427200000,"y":64,"fill":"#ffd900"},{"date_produced":"2023-09-24","party":"LIB","colors":"#ffd900","spend":71,"Daily Spend":71,"Date":"2023-09-24","x":1695513600000,"y":71,"fill":"#ffd900"},{"date_produced":"2023-09-25","party":"LIB","colors":"#ffd900","spend":67,"Daily Spend":67,"Date":"2023-09-25","x":1695600000000,"y":67,"fill":"#ffd900"},{"date_produced":"2023-09-26","party":"LIB","colors":"#ffd900","spend":67,"Daily Spend":67,"Date":"2023-09-26","x":1695686400000,"y":67,"fill":"#ffd900"},{"date_produced":"2023-09-27","party":"LIB","colors":"#ffd900","spend":67,"Daily Spend":67,"Date":"2023-09-27","x":1695772800000,"y":67,"fill":"#ffd900"},{"date_produced":"2023-09-28","party":"LIB","colors":"#ffd900","spend":63,"Daily Spend":63,"Date":"2023-09-28","x":1695859200000,"y":63,"fill":"#ffd900"},{"date_produced":"2023-09-29","party":"LIB","colors":"#ffd900","spend":62,"Daily Spend":62,"Date":"2023-09-29","x":1695945600000,"y":62,"fill":"#ffd900"},{"date_produced":"2023-09-30","party":"LIB","colors":"#ffd900","spend":65,"Daily Spend":65,"Date":"2023-09-30","x":1696032000000,"y":65,"fill":"#ffd900"}],"type":"area"}],"xAxis":{"type":"datetime","title":{"text":"Date"},"categories":null},"colors":["#3db53a","#e6001a","#122746","#851a64","#f68f2d","#263778","#ffd900"],"tooltip":{"shared":true,"positioner":"function (labelWidth, labelHeight, point) {\n        return { x: 200, y: this.chart.plotTop };\n    }"}},"theme":{"chart":{"backgroundColor":"transparent"},"colors":["#7cb5ec","#434348","#90ed7d","#f7a35c","#8085e9","#f15c80","#e4d354","#2b908f","#f45b5b","#91e8e1"]},"conf_opts":{"global":{"Date":null,"VMLRadialGradientURL":"http =//code.highcharts.com/list(version)/gfx/vml-radial-gradient.png","canvasToolsURL":"http =//code.highcharts.com/list(version)/modules/canvas-tools.js","getTimezoneOffset":null,"timezoneOffset":0,"useUTC":true},"lang":{"contextButtonTitle":"Chart context menu","decimalPoint":".","downloadCSV":"Download CSV","downloadJPEG":"Download JPEG image","downloadPDF":"Download PDF document","downloadPNG":"Download PNG image","downloadSVG":"Download SVG vector image","downloadXLS":"Download XLS","drillUpText":"◁ Back to {series.name}","exitFullscreen":"Exit from full screen","exportData":{"annotationHeader":"Annotations","categoryDatetimeHeader":"DateTime","categoryHeader":"Category"},"hideData":"Hide data table","invalidDate":null,"loading":"Loading...","months":["January","February","March","April","May","June","July","August","September","October","November","December"],"noData":"No data to display","numericSymbolMagnitude":1000,"numericSymbols":["k","M","G","T","P","E"],"printChart":"Print chart","resetZoom":"Reset zoom","resetZoomTitle":"Reset zoom level 1:1","shortMonths":["Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"],"shortWeekdays":["Sat","Sun","Mon","Tue","Wed","Thu","Fri"],"thousandsSep":" ","viewData":"View data table","viewFullscreen":"View in full screen","weekdays":["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday"]}},"type":"chart","fonts":[],"debug":false},"evals":["hc_opts.tooltip.positioner"],"jsHooks":[]}</script>
```
:::
:::




::: 


::: 



