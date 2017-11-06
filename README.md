# resilient-software
Manage multi app on single condigniter instance 

********************************************************
APP = Name + instance + controller + function + Layout
********************************************************

Page = Auth + ipasport + register + new_account + center_layout
Data / parameters

Simplifier le déploiement/maintenance d'une application avec CI
On part d'une base avec template (ex inspinia) + lib et on peut mutualiser


********************************************************
Assets
********************************************************

/assets/theme/inspinia3/js
		
/assets/js/
	_Layouts/
		<layout>.js
	_Apps/
		<app_name>/
			<app_name>.js
			<app_name>_<inst>.js
			<controller>.js
			<controller>_<function>.js

/assets/css
	_Layouts/
		<layout>.css
	_Apps/
		<app_name>/
			<app_name>.js
			<app_name>_<inst1>.css
			<controller>.css
			<controller>_<function>.css

/img/
	_Layouts/
	_Apps/

********************************************************
Controller
********************************************************

/controller/
	<app_name>/
		<controller>.php


********************************************************
Config
********************************************************

/config/
	_Apps/
		<app_name>/
			<app_name>.php
			<app_name>_<inst>.php
	_Layouts
		<layout_name>.php

********************************************************
Views
********************************************************

/views/
	_Layouts
	_Common
	_Components

********************************************************
Librairies
********************************************************

/librairies/

********************************************************
Helper
********************************************************

/helper
