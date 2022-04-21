# Mikenskiet Configuration

## Configurtion



You can run the main.yml for complete installation
Example Inventory File provided 
Global Vars that can be set example file provided all.example 


**database_user**:mysql_database_username  
**database_name**: mysql_database_name  
**app_root_directory**: /var/www/html/appname  
**virtualenv_name**: pythonvenv  
**static_dir**:  /some/path/static  
**app_name**: DjangoProjectName  
**nginx_path**: /etc/nginx/conf.d/  
**system_path**: /etc/systemd/system
**server_name**: app.domain.com

#### Password variable retrieved from 
**database_password**: {{ vault_database_password }}  
**root_password**: {{ vault_root_password }}  



## Outstanding
improve inventory handling for use of remote database,worker services 
implement tags
