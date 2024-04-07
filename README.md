Demostrates the error of

```
ERROR [o.j.p.JDBC_PING] JGRP000115: Could not open connection to database java.sql.SQLException: No suitable driver found for jdbc:postgresql://dbhost:5432/db
```

Steps to reproduce:

1. run `docker compose up -d`
2. check the container log for the `cache` container
