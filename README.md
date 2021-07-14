Frontent
    - Main Docker -------------------------------------------
        Laravel <---------------------------                |
            - DataBase                     |--> RabbitMQ    | (Internal API Call)
    - Admin Docker <------------------------                |
        Laravel <--------------------------------------------
            - DataBase