## S3 Storage Classes

| Storage Class | Designed for | Availability Zones | Min storage duration |
| --- | --- | --- | --- |
| S3 Standard | Frequently accessed data (more than once a month) with millisecond access | >= 3 | None |
| S3 Standard-IA | Long-lived, infrequently accessed data (once a month) with millisecond access | >= 3 | 30 days |
| S3 Intelligent-Tiering | Data with unknown, changing, or unpredictable access patterns | >= 3 | None |
| S3 One Zone-IA | Recreatable, infrequently accessed data (once a month) with millisecond access | 1 | 30 days |
| S3 Express One Zone | Single-digit millisecond data access for latency-sensitive applications within a single AWS Availability Zone | 1 | None |
