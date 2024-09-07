# EigenDB's REST API 

EigenDB provides a robust REST API to perform various actions. 

{% swagger src="specs/openapi.yaml" path="/health" method="get" %} specs/openapi.yaml {% endswagger %}

{% swagger src="specs/openapi.yaml" path="/vector/insert" method="put" %} specs/openapi.yaml {% endswagger %}

{% swagger src="specs/openapi.yaml" path="/vector/bulk-insert" method="put" %} specs/openapi.yaml {% endswagger %}

{% swagger src="specs/openapi.yaml" path="/vector/search" method="get" %} specs/openapi.yaml {% endswagger %}


{% swagger src="specs/openapi.yaml" path="/update-config/persistence/time-interval" method="post" %} specs/openapi.yaml {% endswagger %}


{% swagger src="specs/openapi.yaml" path="/update-config/api/port" method="post" %} specs/openapi.yaml {% endswagger %}

{% swagger src="specs/openapi.yaml" path="/update-config/api/address" method="post" %} specs/openapi.yaml {% endswagger %}


{% swagger src="specs/openapi.yaml" path="/update-config/hnsw-params/similarity-metric" method="post" %} specs/openapi.yaml {% endswagger %}

{% swagger src="specs/openapi.yaml" path="/update-config/hnsw-params/vector-space-size" method="post" %} specs/openapi.yaml {% endswagger %}

{% swagger src="specs/openapi.yaml" path="/update-config/hnsw-params/m" method="post" %} specs/openapi.yaml {% endswagger %}

{% swagger src="specs/openapi.yaml" path="/update-config/hnsw-params/ef-construction" method="post" %} specs/openapi.yaml {% endswagger %}


