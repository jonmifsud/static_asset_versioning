static_asset_versioning
=======================

Versioning extension for static assets in Symphony CMS

# Choose files to version

You can list file paths which needs to be versioned; the below is a template you can use to add settings.

###### STATIC_ASSET_VERSIONING ######
		'version-data' => array(
			'paths' =>  array(
				'js' => '/res/js',
				'css' => '/res/css'
			),
			'extensions' => 'js,css'
		),