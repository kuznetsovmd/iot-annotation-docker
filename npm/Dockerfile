FROM node:alpine

WORKDIR /var/www/html

CMD    chown -R $(whoami) /var/www/html/public/js    \
    && chmod -R 0755 /var/www/html/public/js         \
    && chown -R $(whoami) /var/www/html/node_modules \
    && chmod -R 0755 /var/www/html/node_modules      \
    && npm install && npm run watch