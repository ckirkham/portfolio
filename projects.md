---
layout: page
title: Projects
permalink: /projects
---

This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](http://jekyllrb.com/)

You can find the source code for the Jekyll new theme at:
{% include icon-github.html username="jglovier" %} /
[jekyll-new](https://github.com/jglovier/jekyll-new)

You can find the source code for Jekyll at
{% include icon-github.html username="jekyll" %} /
[jekyll](https://github.com/jekyll/jekyll)











<ul class="post-list">
    {% for projects in site.projects %}
      <li>
        <span class="post-meta">{{ projects.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ projects.url | prepend: site.baseurl }}">{{ projects.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>














<div id="projects">


	<div class="heading-section">
		<h1><a href="{{ post.url }}">{{ project.title }}</a></h1>
	</div>

	<section class="wrapper" style="background: white;">
		<ul id="blog">
			{% for project in site.projects %}
				<li>
					<small>Posted on </small>
					<small>{{ project.date | date: "%B %d, %Y" }}</small>
					<h1><a href="{{ post.url }}">{{ project.title }}</a></h1>
				</li>
				<hr>
		  	{% endfor %}
		</ul>
	</section>


	<!-- <div class="ctm-banner banner">
		<div class="heading-section">
			<div>
				<h1>Meerkat App</h1>
				<p>Meerkat app was a conceptual piece, created to work out the future stepping stones for the Compare the Market service proposition.</p>
				<button>
					<a href="{{ root }}/projects/2014-02-28-ctmconcept.html">View project</a>
				</button>
			</div>
		</div>
	</div>

	<div class="icarus-banner banner">
		<div class="heading-section">
			<div>
				<h1>Icarus Concierge</h1>
				<p>Icarus is an exclusive members concierge service that caters to high-quality lifestyle individuals.</p>
				<button>
					<a href="{{ root }}/projects/2014-02-23-icarus.html">View project</a>
				</button>
			</div>
		</div>
	</div>

	<div class="cd-banner banner">
		<div class="heading-section">
			<div>
				<h1>Chemist Direct</h1>
				<p>Case study of the Chemist Direct e-commerce site being re-built from the ground up for the responsive web, in a sprint led, agile workflow.</p>
				<button>
					<a href="{{ root }}/projects/2013-07-14-chemistdirect.html">View project</a>
				</button>
			</div>
		</div>
	</div>

	<div class="movements-banner banner">
		<div class="heading-section">
			<div>
				<h1>Movements</h1>
				<p>Movements is crowdsourcing human rights. It connects human rights activists in closed societies with those with skills to help them around the world.</p>
				<button>
					<a href="{{ root }}/projects/2014-06-21-movements.html">View project</a>
				</button>
			</div>
		</div>
	</div>

	<div class="rk-banner banner">
		<div class="heading-section">
			<div>
				<h1>Rival Kingdoms</h1>
				<p>Responsive &amp; interactive launch site for Rival Kingdoms, the new iOS MMO strategy game created by Space Ape games.</p>
				<button>
					<a href="{{ root }}/projects/2014-11-14-rivalkingdoms.html">View project</a>
				</button>
			</div>
		</div>
	</div>

	<div class="mb-banner banner">
		<div class="heading-section">
			<div>
				<h1>MightyBee</h1>
				<p>MightyBee is an organic coconut water brand dealing in London.</p>
				<button>
					<a href="{{ root }}/projects/2015-02-10-mightybee.html">View project</a>
				</button>
			</div>
		</div>
	</div> -->

</div>