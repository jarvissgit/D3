#1 Nested Selections
--------------------
d3.select('h1.main-title').text('Gapminder World: China');

var parent_el = d3.select('#header-logo');

parent_el.select('img');

parent_el.select('img').attr('src');

parent_el.select('img').attr('alt','Udacity');

d3.select('.img').attr('alt','logo');

d3.select('.navbar-brand.logo img').attr('alt', 'logo');

d3.select('#header-logo img').attr('src','./assets/udacity_white.png');


