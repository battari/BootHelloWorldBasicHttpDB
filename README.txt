** start console:

1. http://localhost:8080/h2-console (use jdbc:h2:mem:test_db as URL)
2. Set username and password: myuser/mypassword by running scripts
        -- mypassword: $2y$10$izRs7Fbw1ju33XNiYxfVIOKFlBtyul8bad4Mf6ualsD5PFqpgGiJW
        insert into USERS values('myuser', '$2y$10$izRs7Fbw1ju33XNiYxfVIOKFlBtyul8bad4Mf6ualsD5PFqpgGiJW', TRUE);

        insert into AUTHORITIES values('myuser', 'USER_ROLE');

        commit;

3. Go to URL: http://localhost:8080/boothello/welcome?to=Bob



