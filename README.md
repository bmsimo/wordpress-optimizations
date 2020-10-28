# Wordpress Optimizations list

- Disable Emojis
- Disable wp-embed
- Disable jQuery
- Disable Woocommerce normal and inline styles/scripts in normal pages
- Create CriticalCSS using `html-critical-webpack-plugin`
- Enqueue the criticalCSS via functions.php
- Remove unused CSS using `purgecss-webpack-plugin`
