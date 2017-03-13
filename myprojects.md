---
layout: gallery
title: My Projects
subtitle: These projects eat my spare time
css: "/css/materialize.css"
---


<div class="container center">
<div class="row">
  <form class="col s12">
	<div class="row">
	  <div class="input-field col s2">
		<!-- <i class="material-icons prefix">sort_by_alpha</i> -->
		<select id="gridsort">
		  <option value="name">Name</option>
		  <option value="author">Author</option>
		  <option value="stars" selected>Github stars</option>
		  <!-- <option value="stars">Github stars</option> -->
		</select>
		<label>Sort</label>
	  </div>
	  <div class="input-field col s2">
		<!-- <i class="material-icons prefix">search</i> -->
		<input type="text" id="textfilter" class="validate" placeholder="search name, author, description">
		<label>Text Filter</label>
	  </div>
	  <div class="input-field col s3">
		<!-- <i class="material-icons prefix">sort_by_alpha</i> -->
		<select id="authorfilter">
		  <option value="" selected>&nbsp;</option>
		  <!-- <option value="author">Author</option> -->
		</select>
		<label>Author Filter</label>
	  </div>
	  <div class="input-field col s3">
		<!-- <i class="material-icons prefix">sort_by_alpha</i> -->
		<select id="tagfilter">
		  <option value="" selected>&nbsp;</option>
		  <!-- <option value="author">Author</option> -->
		</select>
		<label>Tag Filter</label>
	  </div>
	  <div class="col s2">
		<div class="switch-label tooltipped" data-position="top" data-delay="10" data-tooltip="Show/hide widgets not yet on CRAN"><label>CRAN Only</label></div>
		<div class="switch cran-switch">
		  <label>
			<!-- Off -->
			<input id="crancheckbox" checked type="checkbox">
			<span class="lever"></span>
			<!-- On -->
		  </label>
		</div>
	  </div>
	</div>
  </form>
</div>
</div>

<div class="main-container">
	<div class="row" id="grid">

		<div class="card grid-item" data-author="zachcp">
		  <div class="card-image waves-effect waves-block waves-light">
			<div style="width:350px; height:300px; padding:3px;" class="valign-wrapper">
			<a href="https://zachcp.github.io/phylocanvas/">
			<img class="valign" src="
			
			  /img/404-southpark.jpg
			
			"></a>
			</div>
		  </div>
		  <div class="card-content widget-content">
			<a href="https://zachcp.github.io/phylocanvas/"><span class="card-title grey-text text-darken-4">phylocanvas</span></a>
			<p class="widget-shortdesc">An htmlwidgets binding for creating interactive phylogenetic trees.
		</p>
			<p class="widget-list-item"><i class="material-icons meta-bullet red-text">stop</i><span class="red-text">type:</span> <span class="widget-author widget-meta"><a href="https://github.com/zachcp">zachcp</a></span></p>
			<p class="widget-list-item"><i class="material-icons meta-bullet green-text">stop</i><span class="green-text">tags:</span> <span class="widget-tags widget-meta">phylogenetics, trees, biology</span></p>
			<p class="widget-list-item"><i class="material-icons meta-bullet blue-text">stop</i><span class="blue-text">libraries:</span> <span class="widget-jslibs widget-meta"><a href="https://github.com/phylocanvas">phylocanvas</a>
		</span></p>
			<!-- <div class="more-icon activator"><i class="material-icons right">more_vert</i></div> -->
			<div class="hidden widget-cran">true</div>
		  </div>
		  <div class="card-reveal" style="display: none; -webkit-transform: translateY(0px);">
			<span class="card-title grey-text text-darken-4">phylocanvas<i class="material-icons right">close</i></span>
			<p>(full meta data to go here)</p>
			</div>
		</div>
		
		<!-- second card -->
		
		<div class="card grid-item" data-author="dominik">
		  <div class="card-image waves-effect waves-block waves-light">
			<div style="width:350px; height:300px; padding:3px;" class="valign-wrapper">
			<a href="https://zachcp.github.io/phylocanvas/">
			<img class="valign" src="
			
			  /img/Unbenannt.png
			
			"></a>
			</div>
		  </div>
		  <div class="card-content widget-content">
			<a href="https://zachcp.github.io/phylocanvas/"><span class="card-title grey-text text-darken-4">Test</span></a>
			<p class="widget-shortdesc">Lorem Ipsum
		</p>
			<p class="widget-list-item"><i class="material-icons meta-bullet red-text">stop</i><span class="red-text">type:</span> <span class="widget-author widget-meta"><a href="https://github.com/zachcp">Dominik</a></span></p>
			<p class="widget-list-item"><i class="material-icons meta-bullet green-text">stop</i><span class="green-text">tags:</span> <span class="widget-tags widget-meta">phylogenetics, trees, test</span></p>
			<p class="widget-list-item"><i class="material-icons meta-bullet blue-text">stop</i><span class="blue-text">libraries:</span> <span class="widget-jslibs widget-meta"><a href="https://github.com/phylocanvas">aaa</a>
		</span></p>
			<!-- <div class="more-icon activator"><i class="material-icons right">more_vert</i></div> -->
			<div class="hidden widget-cran">true</div>
		  </div>
		  <div class="card-reveal" style="display: none; -webkit-transform: translateY(0px);">
			<span class="card-title grey-text text-darken-4">phylocanvas<i class="material-icons right">close</i></span>
			<p>(full meta data to go here)</p>
			</div>
		</div>
		
		<!-- third test card -->
		
		<div class="card grid-item" data-author="Michal">
		  <div class="card-image waves-effect waves-block waves-light">
			<div style="width:350px; height:300px; padding:3px;" class="valign-wrapper">
			<a href="https://zachcp.github.io/phylocanvas/">
			<img class="valign" src="
			
			  /img/404-southpark.jpg
			
			"></a>
			</div>
		  </div>
		  <div class="card-content widget-content">
			<a href="https://zachcp.github.io/phylocanvas/"><span class="card-title grey-text text-darken-4">Test</span></a>
			<p class="widget-shortdesc"> Let's check the linebreak and the container size.
		</p>
			<p class="widget-list-item"><i class="material-icons meta-bullet red-text">stop</i><span class="red-text">type:</span> <span class="widget-author widget-meta"><a href="https://github.com/zachcp">Michal</a></span></p>
			<p class="widget-list-item"><i class="material-icons meta-bullet green-text">stop</i><span class="green-text">tags:</span> <span class="widget-tags widget-meta">phylogenetics, trees, test</span></p>
			<p class="widget-list-item"><i class="material-icons meta-bullet blue-text">stop</i><span class="blue-text">libraries:</span> <span class="widget-jslibs widget-meta"><a href="https://github.com/phylocanvas">test</a>
		</span></p>
			<!-- <div class="more-icon activator"><i class="material-icons right">more_vert</i></div> -->
			<div class="hidden widget-cran">true</div>
		  </div>
		  <div class="card-reveal" style="display: none; -webkit-transform: translateY(0px);">
			<span class="card-title grey-text text-darken-4">phylocanvas<i class="material-icons right">close</i></span>
			<p>(full meta data to go here)</p>
			</div>
		</div>

	</div>

	<div class="row">
		<div class="col s12 m6">
		  <div class="card">
			<div class="card-image">
			  <img src="/img/sample-1.jpg">
			  <span class="card-title">Card Title</span>
			  <a class="btn-floating halfway-fab waves-effect waves-light red"><i class="material-icons">add</i></a>
			</div>
			<div class="card-content">
			  <p>I am a very simple card. I am good at containing small bits of information. I am convenient because I require little markup to use effectively.</p>
			</div>
		  </div>
		</div>
	</div>

	<div class="row">
		<div class="col s12 m6">
		  <div class="card">
			<div class="card-image">
			  <img src="https://dominikkoch.github.io/img/sample-1.jpg">
			  <span class="card-title">Card Title</span>
			  <a class="btn-floating halfway-fab waves-effect waves-light red"><i class="material-icons">add</i></a>
			</div>
			<div class="card-content">
			  <p>I am the second card. I am good at containing small bits of information. I am convenient because I require little markup to use effectively.</p>
			</div>
		  </div>
		</div>
	</div>

	<div class="row">
		<div class="col s12 m6">
		  <div class="card">
			<div class="card-image">
			  <img src="https://dominikkoch.github.io/img/sample-1.jpg">
			  <span class="card-title">Card Title</span>
			  <a class="btn-floating halfway-fab waves-effect waves-light red"><i class="material-icons">add</i></a>
			</div>
			<div class="card-content">
			  <p>I am the second card. I am good at containing small bits of information. I am convenient because I require little markup to use effectively.</p>
			</div>
		  </div>
		</div>
		
		<div class="col s12 m6">
		  <div class="card">
			<div class="card-image">
			  <img src="https://dominikkoch.github.io/img/sample-1.jpg">
			  <span class="card-title">Card Title</span>
			  <a class="btn-floating halfway-fab waves-effect waves-light red"><i class="material-icons">add</i></a>
			</div>
			<div class="card-content">
			  <p>I am the second card. I am good at containing small bits of information. I am convenient because I require little markup to use effectively.</p>
			</div>
		  </div>
		</div>
		
		<div class="col s12 m6">
		  <div class="card">
			<div class="card-image">
			  <img src="https://dominikkoch.github.io/img/sample-1.jpg">
			  <span class="card-title">Card Title</span>
			  <a class="btn-floating halfway-fab waves-effect waves-light red"><i class="material-icons">add</i></a>
			</div>
			<div class="card-content">
			  <p>I am the second card. I am good at containing small bits of information. I am convenient because I require little markup to use effectively.</p>
			</div>
		  </div>
		</div>
		
		<div class="col s12 m6">
		  <div class="card">
			<div class="card-image">
			  <img src="https://dominikkoch.github.io/img/sample-1.jpg">
			  <span class="card-title">Card Title</span>
			  <a class="btn-floating halfway-fab waves-effect waves-light red"><i class="material-icons">add</i></a>
			</div>
			<div class="card-content">
			  <p>I am the second card. I am good at containing small bits of information. I am convenient because I require little markup to use effectively.</p>
			</div>
		  </div>
		</div>
	</div>
</div>