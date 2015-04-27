WordPress Ansible Role
=========

This role allows the installation of WordPress in a Docker container.

Requirements
------------

This role needs a MySQL or MariaDB database.

Role Variables
--------------

* wordpress_db_name: name of the database
* wordpress_db_username: username to use in the database connection
* wordpress_db_password: password to use in the database connection
* wordpress_db_host: host or IP address to connect to
* wordpress_test_http_endpoint: The tests will run against this endpoint
* wordpress_test_http_status_code: The HTTP code response
* wordpress_test_string: a string to search in the test response
* wordpress_version: Version of WordPress to install
* wordpress_plugins: List of plugins that must be installed
* wordpress_themes: List of themes that must be installed
* wordpress_adm_user: WordPress admin username
* wordpress_adm_mail: WordPress admin email address
* wordpress_adm_pass: WordPress admin password
* wordpress_name: Site name
* wordpress_fqdn: Full Qualified Domain Name used by the WordPress instance.

Dependencies
------------

None so far.

License
-------

BSD

