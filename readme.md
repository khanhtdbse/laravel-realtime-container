Laravel 5.4 sample kit. Up and running real-time websocket application with ease 

- Services:
    + nginx
    + mysql
    + php-fpm
    + redis queue 
    + laravel-echo
    + pusher broadcasting (using laravel-echo-server, socket.io)

- Setup:
    + git clone https://github.com/tranduykhanh/laravel-realtime-container
    + composer install
    + npm install && npm run dev
    + docker-compose up -d

- Check: Open 2 tabs on your browser
    + Tab 1: Open http://localhost
    + Tab 2: Open http://localhost/fire for fire event. Tab 1 will receive notification

That's it!