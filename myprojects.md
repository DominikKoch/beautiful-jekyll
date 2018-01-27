---
layout: gallery
title: My projects
subtitle: A collection of nice visualisations, algorithms and useful code snippets
css: "/css/materialize.css"
---


<div class="container center filter">
<div class="row">
  <form class="col s12">
	<div class="row">
	  
	  <div class="input-field col s2">
		<!-- <i class="material-icons prefix">sort_by_alpha</i> -->
		<select id="gridsort">
		  <option value="name">Name</option>
		  <!-- <option value="author">Author</option> -->
		  <!-- <option value="stars" selected>Github stars</option> -->
		  <!-- <option value="stars">Github stars</option> -->
		</select>
		<label>Sort</label>
	  </div>
	  
	  <div class="input-field col s4">
		<!-- <i class="material-icons prefix">search</i> -->
		<input type="text" id="textfilter" class="validate" placeholder="name, tag, description">
		<label>Text Filter</label>
	  </div>
	  
	  <div class="input-field col s3">
		<!-- <i class="material-icons prefix">sort_by_alpha</i> -->
		<select id="authorfilter">
		  <option value="" selected>&nbsp;</option>
		  <!-- <option value="author">Author</option> -->
		</select>
		<label>Type Filter</label>
	  </div>
	  
	  <div class="input-field col s3">
		<!-- <i class="material-icons prefix">sort_by_alpha</i> -->
		<select id="tagfilter">
		  <option value="" selected>&nbsp;</option>
		  <!-- <option value="author">Author</option> -->
		</select>
		<label>Tag Filter</label>
	  </div>
	  
	</div>
  </form>
</div>
</div>

<div class="main-container">
	<div class="row" id="grid">

		<div class="card grid-item" data-author="christopher-gandrud">
		  <div class="card-image waves-effect waves-block waves-light">
			<div style="width:350px; height:300px; padding:3px;" class="valign-wrapper">
			<a href="https://christophergandrud.github.io/networkD3/#sankey">
			<img class="valign" src="
			
			  /img/sankey.png
			
			"></a>
			</div>
		  </div>
		  <div class="card-content widget-content">
			<a href="https://christophergandrud.github.io/networkD3/#sankey"><span class="card-title grey-text text-darken-4">Sankey Diagram</span></a>
			<p class="widget-shortdesc">Visualise path data in an interactive flow diagram.
		</p>
			<p class="widget-list-item"><i class="material-icons meta-bullet red-text">stop</i><span class="red-text">type:</span> <span class="widget-author widget-meta">Visualisation</span></p>
			<p class="widget-list-item"><i class="material-icons meta-bullet green-text">stop</i><span class="green-text">tags:</span> <span class="widget-tags widget-meta">network-graphs</span></p>
			<p class="widget-list-item"><i class="material-icons meta-bullet blue-text">stop</i><span class="blue-text">libraries:</span> <span class="widget-jslibs widget-meta">networkD3</span>
		</p>
			<!-- <div class="more-icon activator"><i class="material-icons right">more_vert</i></div> -->
			<div class="hidden widget-cran">true</div>
		  </div>
		  <div class="card-reveal" style="display: none; -webkit-transform: translateY(0px);">
			<span class="card-title grey-text text-darken-4">phylocanvas<i class="material-icons right">close</i></span>
			<p>(full meta data to go here)</p>
			</div>
		</div>
		
		<!-- second card -->
		
		<div class="card grid-item" data-author="dominik-koch">
		  <div class="card-image waves-effect waves-block waves-light">
			<div style="width:350px; height:300px; padding:3px;" class="valign-wrapper">
			<a href="https://dominikkoch.github.io/Calendar-Heatmap/">
			<img class="valign" src="
			
			  /img/calendarHeatmap.png
			
			"></a>
			</div>
		  </div>
		  <div class="card-content widget-content">
			<a href="https://dominikkoch.github.io/Calendar-Heatmap/"><span class="card-title grey-text text-darken-4">Calendar Heatmap</span></a>
			<p class="widget-shortdesc">Visualise time series data in calendar style.
		</p>
			<p class="widget-list-item"><i class="material-icons meta-bullet red-text">stop</i><span class="red-text">type:</span> <span class="widget-author widget-meta">Visualisation</span></p>
			<p class="widget-list-item"><i class="material-icons meta-bullet green-text">stop</i><span class="green-text">tags:</span> <span class="widget-tags widget-meta">time-series</span></p>
			<p class="widget-list-item"><i class="material-icons meta-bullet blue-text">stop</i><span class="blue-text">libraries:</span> <span class="widget-jslibs widget-meta">ggplot2</span>
		</p>
			<!-- <div class="more-icon activator"><i class="material-icons right">more_vert</i></div> -->
			<div class="hidden widget-cran">true</div>
		  </div>
		  <div class="card-reveal" style="display: none; -webkit-transform: translateY(0px);">
			<span class="card-title grey-text text-darken-4">Calendar Heatmap<i class="material-icons right">close</i></span>
			<p>(full meta data to go here)</p>
			</div>
		</div>
		
		<!-- third test card -->
		
		<div class="card grid-item" data-author="dominik-koch">
		  <div class="card-image waves-effect waves-block waves-light">
			<div style="width:350px; height:300px; padding:3px;" class="valign-wrapper">
			<a href="https://zachcp.github.io/phylocanvas/">
			<img class="valign" src="
			
			  /img/Global-Terrorism.jpg
			
			"></a>
			</div>
		  </div>
		  <div class="card-content widget-content">
			<a href="https://datascience42.shinyapps.io/terrorism/"><span class="card-title grey-text text-darken-4">Global Terrorism App</span></a>
			<p class="widget-shortdesc"> Highlight global terrorism on an interactive map.
		</p>
			<p class="widget-list-item"><i class="material-icons meta-bullet red-text">stop</i><span class="red-text">type:</span> <span class="widget-author widget-meta">Dashboard</span></p>
			<p class="widget-list-item"><i class="material-icons meta-bullet green-text">stop</i><span class="green-text">tags:</span> <span class="widget-tags widget-meta">maps,webGL-globe,time-series</span></p>
			<p class="widget-list-item"><i class="material-icons meta-bullet blue-text">stop</i><span class="blue-text">libraries:</span> <span class="widget-jslibs widget-meta">shiny,leaflet,shinyGlobe,timevis</span>
		</p>
			<!-- <div class="more-icon activator"><i class="material-icons right">more_vert</i></div> -->
			<div class="hidden widget-cran">true</div>
		  </div>
		  <div class="card-reveal" style="display: none; -webkit-transform: translateY(0px);">
			<span class="card-title grey-text text-darken-4">Global Terrorism App<i class="material-icons right">close</i></span>
			<p>(full meta data to go here)</p>
			</div>
		</div>

	</div>
</div>