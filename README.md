Infopanel
=========

Enterprise TV on Drupal sites

This is moduel for drupal7, that create html5 enterprise tv.

Installation:
=============

1. Download drupal/infopanel to your drupal site module folder.
2. Enabled module infopanel.
3. In drupal site: create conten type 'tv'
4. In drupal site: add field 'tvfile' as text for link to http://example.org/video.webm
5. In drupal site: add field 'tvfile_mp4' as text for link to http://example.org/video.mp4
6. In drupal site: add field 'frequency' as integer for set weight

Now you can add tv page and must set tvfile and tvfile_mp4

Goto http://example.com/infopanel/random

Goto http://example.com/infopanel/random/public/browser

Goto http://example.com/infopanel/random/public/fullscreen/browser

Optional:

You can add infoblock on any page:

1. In drupal site: create conten type 'infoblock'
2. publish block 'infoblock' on any address (example: 'infopanel/random')

Now you can add infoblock content as html-code for random view in block.
