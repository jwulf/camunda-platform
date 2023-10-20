# Multitenancy

To run multi-tenant:

```bash
docker compose -f docker-compose-multitenancy.yaml up
```

After it starts, you will get a bunch of errors in the connectors container: 

- Open Identity at [http://localhost:8084](http://localhost:8084/) and log in with demo / demo. 
- Go to Applications
- Choose Zeebe
- Click on Tenants
- Click on Add
- Add the Default tenant