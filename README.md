# Site Admin Menu #
Swaps out the admin navigation menu for different roles.

## Usage ##
Set the machine name of the menu to use and the permission to check against to determine which to show.

	<?php 
	// machine name of the menu to use for site admins
	$site_admin_menu = 'owner';
	// permission to check against to determine whether to load the system admin menu or 
	// the custom site admin menu
	$permission = 'administer content types';
	?>