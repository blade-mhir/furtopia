FROM laravelsail/php74-composer:latest

# Copy existing application directory permissions
COPY --chown=sail:sail . /var/www/html

# Switch to the application directory
WORKDIR /var/www/html

# Start Laravel Sail
ENTRYPOINT ["/bin/sh", "-c", "while :; do sleep 3600; done"]
