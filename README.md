Install NGINX :
        =============
      apt-get update
      apt install nginx
      
      INSTALL NODE_JS :
      ================
      curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
      apt install -y nodejs
      
      INSTALL NPM:
      ==============
      apt install npm
      
      Pull the code from GITHUB
      =========================
      
     cd /var/www/html/
 
     git clone https://github.com/zelar-soft-todoapp/frontend.git
   
     npm run build
     npm install
     npm run build
     
     To open vi /etc/nginx/sites-available/default give the project path in server section
     ======================================================================================
     
     vi /etc/nginx/sites-available/default
     
     nginx -t  -----> to check syntax errors
     
     TO START NGINX SERVICE
     ======================
     service nginx restart
     
     
     
