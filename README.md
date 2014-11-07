ICI-Redirect
============

A simple but effective Drupal 7.x URL Router

The main goal of this module is to provide a simple and maintenable list of 301 Redirects for a series of legacy URL in a heavy SEO optimized website.


#How it works

The module hooks itself at the hook_boot() of Drupal so that it can start working at the early stages of the system bootstrap.

Contrary to the use of hook_init() it also works on cached pages.

#How it behaves

Very well indeed: it plays nice with [Global Redirect](https://www.drupal.org/project/globalredirect), [Redirect](https://www.drupal.org/project/redirect) and almost any other custom redirection method. Just keep attention to redirection loops.

#Fun Stuff

The module is named after my SEO's department collegues, or the old Italian House Tax.
