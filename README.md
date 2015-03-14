# SCSSPHP for Kirby v2

This is a preprocessor for SCSS files. Built using the [scssphp library](https://github.com/leafo/scssphp) by Leaf Corcoran. This plugin will automatically process SCSS files.

1. Copy folder ‘scssphp’ inside ‘plugins’ to Kirby’s plugin folder.
2. Copy file ‘scss.php’ inside ‘snippet’ to Kirby’s snippet folder.
3. Call the snippet with <?php snippet('scss') ?> in your HTML head.
4. Create a folder ‘scss’ inside Kirby’s assets folder.
5. Create a file ‘style.scss’ and place it inside ‘assets/scss’.
6. Make sure a folder ‘css’ exists inside Kirby’s assets folder.