---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
#  image_fullwidth: header_unsplash_12.jpg
#  image_fullwidth: header-trucks.jpg
  image_fullwidth: squadvehicles.jpg
widget1:
  title: "Learn More"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: widget-1-302x182.jpg
  text: 'Learn about the services and abilities of TCRS.'
widget2:
  title: "Donate"
  url: '/donate'
  text: 'TCRS funds primarily come from personal donations, grants, and community supports.'
  image: donation.jpg
#  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Join Us"
  url: '/volunteer'
  image: training-group-photo.jpg
  text: 'TCRS is always looking for new members who are interested in helping the community.'
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
#callforaction:
#  url: https://tcrs.emassistant.net
#  text: Inform me about new updates and features ›
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
