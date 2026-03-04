FROM httpd:2.4

# Remove default Apache content
RUN rm -rf /usr/local/apache2/htdocs/*

# Copy your website files into Apache public folder
COPY . /usr/local/apache2/htdocs/

# Make sure Apache listens on port 80
EXPOSE 80