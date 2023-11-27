# PCa-detection
Docker Images about Prostate Cancer (PCa) segmentation/detection

# Gland Segmentation
docker load -i pg_seg.tar.gz
docker run -v /path/to/your/data:/app/dataset /path/to/your/save_folder:/app/output pg_seg
