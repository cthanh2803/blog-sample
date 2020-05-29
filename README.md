# README

This is a simple blog with some features like create a post, comment, registration...

# Install

Your computer has already installed Docker, docker-compose. If has not, please visit https://docs.docker.com/engine/install/

After that, please clone this repository and run this command. I'll guide you step by step:

- cd blog-sample
- docker-compose up
- docker-compose run web yarn install --check-files
- docker-compose run web rails db:create
- docker-compose run web rails db:migrate
- Ctrl + C
- docker-compose up

And please access localhost:3000 in your browser !!!!!

<!--       _
          \\.__(.)> (CAP CAP)
            \___)
     ~~~~~~~~~~~~~~~~~~-->
