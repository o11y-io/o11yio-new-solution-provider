---
role: ui
artifact_id: opensearch-dashboards
version: 2.19.0
platform: docker
architecture: x64
slug: opensearch-dashboards-2.19.0-docker-x64
category: opensearch-dashboards
type: docker
inline_instructions:
- label: "Docker Hub"
  code: docker pull opensearchproject/opensearch-dashboards:2.19.0
  link:
    label: View on Docker Hub
    url: https://hub.docker.com/r/opensearchproject/opensearch-dashboards/tags?page=1&ordering=last_updated&name=2.19.0
- label: "Amazon ECR"
  code: docker pull public.ecr.aws/opensearchproject/opensearch-dashboards:2.19.0
  link:
    label: View on Amazon ECR
    url: https://gallery.ecr.aws/opensearchproject/opensearch-dashboards
---