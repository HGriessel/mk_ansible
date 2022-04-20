# Mikenskiet Configuration

## Configurtion



You can run the main.yml for complete installation
Example Inventory File provided 
Global Vars that can be set example file provided all.example 


**database_user**:mysql_database_username  
**database_password**: **********  
**database_name**: mysql_database_name  
**root_password**: **********  
**app_root_directory**: /var/www/html/appname  
**virtualenv_name**: pythonvenv  
**static_dir**:  /some/path/static  
**app_name**: DjangoProjectName  
**nginx_path**: /etc/nginx/conf.d/  
**system_path**: /etc/systemd/system
**server_name**: app.domain.com


## Outstanding
improve inventory handling for use of remote database,worker services 