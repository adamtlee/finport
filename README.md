# Finport (Legacy Stocker) 

Finport is an application to track stock listings using the IEX api
- db diagram: https://dbdiagram.io/d/60f84a004ed9be1c05d6ae06

## Instructions
Clone the repository:   
```
git clone https://github.com/adamtlee/stocker.git
```
cd into the directory: 
```
cd stocker/
```
install the gem dependencies:
```
bundle install
```
Run the existing migrations:
```
bundle exec rails db:migrate
```
install webpacker:
```
bundle exec rails webpacker:install
```
run the server: 
```
rails s 
```

## Resources
- IEX ruby client: https://github.com/dblock/iex-ruby-client
- IEX platform: https://iexcloud.io/
