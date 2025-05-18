# primerproyecto
Primero proyecto a realizar!

### Solicitar ejecución

```sh
curl -X POST "http://localhost:8080/api/v1/dags/{dag_id}/dagRuns" \
     -H "Content-Type: application/json" \
     --user "airflow:airflow" \
     -d '{
            "conf": {
              "file_name": "{filename}.xlsx",
            }
          }'
```
