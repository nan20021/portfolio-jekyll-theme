---
layout: page
title: About
permalink: /about
---

#Jacob's Portfolio
Isn't it great.

# Portfolio Jekyll Theme

<div id="chart"></div>
<script src="https://cdn.plot.ly/plotly-latest.min.js"></script>
<script>
  const trace = { x:[10,20,30], y:[4,9,16], mode:'lines+markers', type:'scatter' };
  const layout = { title:'Jekyll Embedded Chart' };
  Plotly.newPlot('chart',[trace], layout);
</script>

This is a personal portfolio theme that I built from the ground up, using the [DevTips Starter Kit](http://devtipsstarterkit.com/) as a foundation for starting, and following closely the amazing tutorial by [Travis Neilson over at DevTips](https://www.youtube.com/watch?v=T6jKLsxbFg4&list=PL0CB3OvPhDA_STygmp3sDenx3UpdOMk7P). You can [check out the demo](lenpaul.github.io/portfolio-jekyll-theme/), and [fork the repository](https://github.com/LeNPaul/portfolio-jekyll-theme/fork), to get started.
