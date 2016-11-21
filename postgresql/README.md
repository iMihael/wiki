Show proccess list
> SELECT * FROM pg_stat_activity;

Terminate proccess by id
> SELECT pg_terminate_backend(1234)
