FROM matrixdotorg/synapse:v1.12.0
ARG PYTHON_VERSION=3.7
COPY  synapse-s3-storage-provider/s3_storage_provider.py /usr/local/lib/python3.6/site-packages/s3_storage_provider.py
COPY  synapse-s3-storage-provider/s3_storage_provider.py /usr/local/lib/python3.7/site-packages/s3_storage_provider.py
COPY  synapse-s3-storage-provider/scripts/s3_media_upload /usr/local/bin/s3_media_upload.py
