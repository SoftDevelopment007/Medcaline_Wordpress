# Medcaline_Wordpress
This is customized web site for my source, it has uploaded in themedorest.
https://themeforest.net/item/medcaline-psychology-counseling-wordpress-theme/26747297

- install Xampp
- lunch Xampp(with appach, mysql)

- create db
 * open SQLyog
 * create new db named "wordpress_db"
 * db charset: "utf8"
 * db collation: "utf8_unicode_ci"
 
 - set up wp
 * unzip wordpress-5.5.zip in htdoc holder
 * http://localhost/wordpress/wp-admin/
 * change name "wp_config_sample.php" to "wp_config.php"
 
   db name: "wordpress_db"
   user: "root"
   password: ""
   
 - add theme "1_medcaline_update.zip"
   * http://localhost/wordpress/wp-admin/theme-install.php?browse=featured
   * appearance>add theme>upload theme>
   * Begin installing plugin
   * active plugin
   
 - add demo website by add theme "2_medcaline-child.zip"
   * http://localhost/wordpress/wp-admin/theme-install.php?browse=featured
   * appearance>add theme>upload theme>
   * Begin installing plugin
   * active plugin
  
  - you can check updated demo
   * http://localhost/wordpress/

  - add plugin to handle source
   * plugin - "All-in-One WP Migration"
