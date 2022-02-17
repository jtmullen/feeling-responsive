---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: random
  title: "American Solar Challenge"
widget1:
  title: "American Solar Challenge"
  url: 'https://www.americansolarchallenge.org/about/american-solar-challenge/'
  text: 'The American Solar Challenge is a competition to design, build, and drive solar-powered cars in a cross-country time/distance rally event. Teams compete over a 1,500-2,000 mile course between multiple cities across the country. The event has had over two decades of organized events in North America.'
  image: logo.png
widget2:
  title: "Formula Sun Grand Prix"
  url: 'https://www.americansolarchallenge.org/about/formula-sun-grand-prix/'
  text: 'The Formula Sun Grand Prix is a track event that is held on grand prix or road style closed courses. This unique style of competition truly test the limits of solar cars in handling curves, braking, and acceleration. Strategy applied during these three day events is different than what is applied on the cross-country event.'
  image: "FSGP Color Logo.png"
widget3:
  title: "Support Our Events"
  url: 'https://www.paypal.com/donate?token=xVdCIZtRKnp_7iQF_5kteSTG6eqoNyW57mhHZMOWSvTc-jDskHuKvODuim7PuDrrMO3AKUkAXMwLDO9w'
  text: 'Donate Today or Support our events when you shop on <a href="https://smile.amazon.com/ch/27-1324770">Amazon Smile</a>'
  image: amazon_smile.png
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://jtmullen.github.io/feeling-responsive/events/2022/
  text: Register for the 2022 American Solar Challenge! ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
