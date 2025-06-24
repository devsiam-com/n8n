# n8n

```bash
# Export CX-PG-LOCAL
curl -X POST http://localhost:5678/webhook-test/efddabb1-76a9-4fef-8795-dc6364618d34 \
     -H "Content-Type: application/json" \
     -d '{"message": "hello from button"}'
# Import CX-PG-LOCAL-TO-LOCAL
curl -X POST http://localhost:5678/webhook-test/e1a5edc2-f014-4e24-9cc3-b30807cfea42 \
     -H "Content-Type: application/json" \
     -d '{"message": "hello from button"}'
# CX-Client-Deduplicates
curl -X POST http://localhost:5678/webhook-test/de2b1307-1355-4812-b786-be67924440e2 \
     -H "Content-Type: application/json" \
     -d '{"message": "hello from button"}'
```