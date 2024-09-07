---
description: EigenDB provides a robust REST API to perform various actions.
---

# EigenDB's REST API

{% swagger src="specs/openapi.yaml" path="/health" method="get" %}
[openapi.yaml](specs/openapi.yaml)
{% endswagger %}

{% swagger src="specs/openapi.yaml" path="/vector/insert" method="put" %}
[openapi.yaml](specs/openapi.yaml)
{% endswagger %}

{% swagger src="specs/openapi.yaml" path="/vector/bulk-insert" method="put" %}
[openapi.yaml](specs/openapi.yaml)
{% endswagger %}

{% swagger src="specs/openapi.yaml" path="/vector/search" method="get" %}
[openapi.yaml](specs/openapi.yaml)
{% endswagger %}

{% swagger src="specs/openapi.yaml" path="/update-config/persistence/time-interval" method="post" %}
[openapi.yaml](specs/openapi.yaml)
{% endswagger %}

{% swagger src="specs/openapi.yaml" path="/update-config/api/port" method="post" %}
[openapi.yaml](specs/openapi.yaml)
{% endswagger %}

{% swagger src="specs/openapi.yaml" path="/update-config/api/address" method="post" %}
[openapi.yaml](specs/openapi.yaml)
{% endswagger %}

{% swagger src="specs/openapi.yaml" path="/update-config/hnsw-params/similarity-metric" method="post" %}
[openapi.yaml](specs/openapi.yaml)
{% endswagger %}

{% swagger src="specs/openapi.yaml" path="/update-config/hnsw-params/vector-space-size" method="post" %}
[openapi.yaml](specs/openapi.yaml)
{% endswagger %}

{% swagger src="specs/openapi.yaml" path="/update-config/hnsw-params/m" method="post" %}
[openapi.yaml](specs/openapi.yaml)
{% endswagger %}

{% swagger src="specs/openapi.yaml" path="/update-config/hnsw-params/ef-construction" method="post" %}
[openapi.yaml](specs/openapi.yaml)
{% endswagger %}
