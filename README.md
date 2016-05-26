Forked from https://github.com/jreinke/magento-admin-theme and update for private framework.

![Magento Admin Theme - Flat Gray](http://i.imgur.com/RZ5CjHA.png)

## Usage
Switch theme from in the footer.

You can also add a custom theme from Magento 1.9.x using theme.xml and a parent declaration. This has been added to the Flat Gray theme. When you create your own theme make sure to define a parent and define the new theme in a module configuration file as following:
```xml
<config>
	<adminhtml>
		<themes>
			<nashpharma module="bubble_admintheme">
	     		<label>NashPharma</label>
	 		</nashpharma>
		</themes>
	</adminhtml>
</config>
```

Less files are also added to be used with our private framework. Make sure your Less compiler picks up the files if you want to use them.