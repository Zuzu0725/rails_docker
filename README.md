## Rails + MySQL のDocker環境です

## Railsのインストール方法
1. ```docker-compose run web rails new . --force --database=mysql```  
2. ```docker-compose build```  
3. ```database.yml のpasswordとhost記載```  
4. ```docker-compose run web rails db:create```  
5. ```docker-compose up -d```

# バージョン
Ruby 3.0.4  
Rails 6.1.4  
MySQL 8.0  
