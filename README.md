# minio-compose
fast start minio server with docker-compose

create `.env` file:

```bash
### minio or s3 credentials
S3_KEY=85A8U57ZITLSLFBYKNCG
S3_SECRET=14MAuAetrv7y3E6zAuUOimXy5KYRqrZKw3cWuEe/
### port of local minio
MINIO_PORT=9000
```

Start all with:

```bash
docker-compose up -d
```
