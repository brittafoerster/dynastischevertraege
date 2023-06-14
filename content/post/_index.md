---
title: "Verträge"
draft: false
layout: list

---





<h1>Dynastische Eheverträge der frühen Neuzeit</h1>

<h2> Suche </h2>

<form id="custom-search" name="custom-search" method="post" action="" onsubmit="customSearchResults(); return false;">
    <p>
    <input id="custom-search-field" type="text" name="search" value="" title="Search String" placeholder="SearchString">
    <!-- <input type="submit" value="Suchen"> -->
    </p>
    <!-- <p><em>durchsuchen:</em><br>
        <input type="checkbox"name="section[]" value="site" checked="checked"> alles<br>
        <input type="checkbox" name="section[]" value="post"> Blog<br>
        <input type="checkbox" name="section[]" value="other-section"> Other Section
    </p> -->
    <p>
        <input type="radio" name="option" value="AND" checked="checked"> UND-Suche<br>
        <input type="radio" name="option" value="OR"> ODER-Suche
    </p>
</form>

<div id="custom-search-results"></div>

<script>
// CUSTOM AREA
let params = {
    json_src       : '/index.json', // for multiple sources: comma separated list of JSONarrays
    minlength      : 3,
    defaultsearch  : 'AND',
    sort_date      : 'DESC',
    autocomplete   : 1, // 0: form needs a submit button
    section_search : 0, // 1: needs checkboxes with name="section[]"
    badwords       : 'und,oder,aber,wenn,also,der,die,das,den,dem,des,ein,eines,einer', //ignore this words
    json_wait      : '<p><em>Einen Moment bitte, Suche wird geladen...</em></p>',
    json_ready     : '<p><em>Bitte geben Sie einen Suchbegriff ein</em></p>',
    extern_icon    : ' (externer Link)', // marker for external links (optional)
    err_badstring  : '<p>Der Suchbegriff ist zu kurz!</p>',
    err_noresult   : '<p>Leider kein Suchergebnis. Bitte versuchen Sie es noch einmal.</p>',
    err_norequest  : '<p style="text-align: center; color:red;">Die Volltextsuche steht zur Zeit nicht zurVerfügung.</p>',
    err_filefailed : '<p style="text-align: center;color: red;">Eine Datei konnte nicht abgerufen werden.</p>',
    res_one_item   : '<p><em>[CNT] SUCHERGEBNIS</em></p>',
    res_more_items : '<p><em>[CNT] SUCHERGEBNISSE</em></p>',
    res_out_top    : '<ul>',
    res_out_bottom : '</ul>',
    res_item_tpl   : '<li><a href="[URL]">[TITLE]</a><br>[DATE]:[SUMMARY]<br><em>[SECTION][TAGS]</em></li>',
    add_searchlink : '<p><a href="https://duckduckgo.com/?q=site:yourdomain.com [QUERY]" target="_blank"><i>Nicht zufrieden mit den Suchergebnissen? Externe Suche via DuckDuckGo ...</i></a></p>'
};

// Translation of section name (optional)
let section_trans = {
    "post" : "Blog",
    // "other-section" : "Other Section"
};

let searchfield_weight = {
    "title"   : 5,
    "tags"    : 5,
    "summary" : 2,
    "content" : 1
};
// CUSTOM AREA END
</script>
<script type="text/javascript" src="/js/search.js"></script>


<h2> Besondere Epochen </h2>
{{<filterneuzeit>}}
{{<filter_romantik>}}
{{<filter_16Jh>}}
{{<filter_30Krieg>}}
{{<filter_aufklaerung>}}
{{<filter_Klassizismus>}}
{{<filterrenaissance>}}
{{<filter_rev>}}
{{<filter_Rokkoko>}}


<h2> Kategorien </h2>
{{<columns>}}
{{<details "Ratifikation, Bestätigungen, Genehmigungen erwähnt?" >}}
[Ja]({{<ref "/categories/ratifikationja">}}) 
[Nein]({{<ref "/categories/ratifikationnein">}}) {{</details >}}
<---> 
{{<details "Ständische Instanzen beteiligt?" >}}
[Ja]({{<ref "/categories/ständischja">}}) 
[Nein]({{<ref "/categories/ständischnein">}}) 
{{</details >}}
<---> 
{{<details "Textbezug zu vergangenen Ereignissen?" >}}
[Ja]({{<ref "/categories/textbezugja">}}) 
[Nein]({{<ref "/categories/textbezugnein">}}) 
{{</details >}}
{{</columns>}}

{{<columns>}}
{{<details "Verschiedenkonfessionelle Ehe?" >}}
[Ja]({{<ref "/categories/verschiedenkonfessionelle-eheja/">}}) 
[Nein]({{<ref "/categories/verschiedenkonfessionelle-ehenein/">}}) 
[unbekannt]({{<ref "/categories/verschiedenkonfessionelle-eheunbekannt/">}}) 
{{</details >}}
<---> 
{{<details "Eheschließung vollzogen?" >}}
[Ja]({{<ref "/categories/eheschließung-vollzogenja/">}}) 
[Nein]({{<ref "/categories/eheschließung-vollzogennein/">}}) 
{{</details >}}
<---> 
{{<details "Weitere Verträge" >}}
 [Nein]({{<ref "/categories/sonstigesnein">}}) 
 [Ja]({{<ref "/categories/sonstigesja">}}) 
{{</details >}}
{{</columns>}}

<br>




<h2> Alle Verträge (220)</h2>

[Download Alle Verträge (zip)](/vertraege/vertraege.zip)





