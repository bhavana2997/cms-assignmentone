<?php
/**
 * The base configuration for WordPress
 *
 * The wp-config.php creation script uses this file during the installation.
 * You don't have to use the web site, you can copy this file to "wp-config.php"
 * and fill in the values.
 *
 * This file contains the following configurations:
 *
 * * Database settings
 * * Secret keys
 * * Database table prefix
 * * Localized language
 * * ABSPATH
 *
 * @link https://wordpress.org/support/article/editing-wp-config-php/
 *
 * @package WordPress
 */

// ** Database settings - You can get this info from your web host ** //
/** The name of the database for WordPress */
define( 'DB_NAME', 'Bhavana200532256' );

/** Database username */
define( 'DB_USER', 'Bhavana200532256' );

/** Database password */
define( 'DB_PASSWORD', 'xyV23tZy-t' );

/** Database hostname */
define( 'DB_HOST', 'localhost' );

/** Database charset to use in creating database tables. */
define( 'DB_CHARSET', 'utf8' );

/** The database collate type. Don't change this if in doubt. */
define( 'DB_COLLATE', '' );

/**#@+
 * Authentication unique keys and salts.
 *
 * Change these to different unique phrases! You can generate these using
 * the {@link https://api.wordpress.org/secret-key/1.1/salt/ WordPress.org secret-key service}.
 *
 * You can change these at any point in time to invalidate all existing cookies.
 * This will force all users to have to log in again.
 *
 * @since 2.6.0
 */
define( 'AUTH_KEY',          'J@{QW2=zADwa7FVRDbvYB)tGKr?gh8j@2QRGA2s/fsS#C#=K&IY-r/,&1!Ah{wq!' );
define( 'SECURE_AUTH_KEY',   'g649m!ChTs7XKQLF.^V=!L:Kj@nv35np~>1G<7);RvpVp,Kvwjp2h^<#(Tlz}>lR' );
define( 'LOGGED_IN_KEY',     'be@4>3`g;!l5N9XY9.W!9^ByD0&sk:O_^]fAK!a:TeGjy.RW`u]`p9 d7/ nI$PT' );
define( 'NONCE_KEY',         '&gi%?xGrNld8]r<?x=%0s^#wI9/c#{b~i!OO6p {D:N0W^~}2uWAvthbdTcwL5(_' );
define( 'AUTH_SALT',         'dlmIX,iAWONDSx-:uNo_2dl>QHA1?_5qHHvnAc=iz]>83t>fLkI>u[0CK(w5Qbs/' );
define( 'SECURE_AUTH_SALT',  '^NE;rE^u-.} 468be6|j4QV<$U=@+af~&=i1wBR$q^ltGmw+%.5h%>7Xdx;xO9n(' );
define( 'LOGGED_IN_SALT',    'DQ|atTRJK6@zI//}pA0;x*.ZiSd@$Y68_:J=><=H/(>wiycf47#&Aq-RB_s@jHw!' );
define( 'NONCE_SALT',        'r1ZSuh`NP_T5`C5nXV z.3YdJEl]J276yKbir,f`m$V/EgQi!NA@u/ZW?LM9l6`#' );
define( 'WP_CACHE_KEY_SALT', ' *SC/yyQ<lvewfUTb Kg_y2jAXw_i@H{Mz!QsaGOLh2Z8K3:|R;}SE}*.=!vROt5' );


/**#@-*/

/**
 * WordPress database table prefix.
 *
 * You can have multiple installations in one database if you give each
 * a unique prefix. Only numbers, letters, and underscores please!
 */
$table_prefix = 'wp_';


/* Add any custom values between this line and the "stop editing" line. */



/**
 * For developers: WordPress debugging mode.
 *
 * Change this to true to enable the display of notices during development.
 * It is strongly recommended that plugin and theme developers use WP_DEBUG
 * in their development environments.
 *
 * For information on other constants that can be used for debugging,
 * visit the documentation.
 *
 * @link https://wordpress.org/support/article/debugging-in-wordpress/
 */
if ( ! defined( 'WP_DEBUG' ) ) {
	define( 'WP_DEBUG', false );
}

define( 'WP_ENVIRONMENT_TYPE', 'local' );
/* That's all, stop editing! Happy publishing. */

/** Absolute path to the WordPress directory. */
if ( ! defined( 'ABSPATH' ) ) {
	define( 'ABSPATH', __DIR__ . '/' );
}

/** Sets up WordPress vars and included files. */
require_once ABSPATH . 'wp-settings.php';
