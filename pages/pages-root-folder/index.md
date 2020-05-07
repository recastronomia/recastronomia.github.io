---
#
# Use the widgets beneath and the content will be
# inserted automatically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header.png
widget1:
  title: "¿Quienes somos?"
  url: '/info/nosotros'
  image: dia_reca.jpg
  text: 'RECA es una asociación que busca crear y mantener vínculos fuertes entre los estudiantes de astronomía de Colombia.'
widget2:
  title: "¿Quién eres tú?"
  url: '/censo'
  image: censo_virtual.jpg
  text: 'Ayudanos a conocer, re-conocer y ubicar a los estudiantes de RECA. Si eres colombiano y estas proyectandote profesionalmente en astronomía por favor llena nuestro censo electronico.'
widget3:
  title: "¡Únete a nuestra comunidad en Slack!"
  url: 'https://join.slack.com/t/recastronomia/shared_invite/zt-dyks4zz6-kLfGl_4QPXLETtxn~DaFAQ'
  image: slack.jpg
  text: 'Conéctate con todos los estudiantes colombianos de astronomía del país y del exterior. Encontrarás diferentes canales para consejos, noticias, eventos y más.'
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
#  url: https://join.slack.com/t/recastronomia/shared_invite/zt-dyks4zz6-kLfGl_4QPXLETtxn~DaFAQ
#  text: ¡Unete a nuestro Slack! 
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
