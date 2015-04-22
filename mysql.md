### Start MySQL ###

    sudo /usr/local/mysql/bin/mysqld_safe

### Using pager ###

    mysql> pager more

### Edit previous query ###

    edit

### log what you are doing ###

    mysql> tee queries.log

### Get database size ###

    SELECT table_schema "Data Base Name",
    sum( data_length + index_length ) / 1024 / 1024 "Data Base Size in MB",
    sum( data_free )/ 1024 / 1024 "Free Space in MB"
    FROM information_schema.TABLES
    GROUP BY table_schema ;
