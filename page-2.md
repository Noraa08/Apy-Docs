# Page 2

{% swagger method="get" path="/santa" baseUrl="https://apy.willz.repl.co/image" summary="Santa" %}
{% swagger-description %}
Write a text on a letter for Ar
{% endswagger-description %}

{% swagger-parameter in="query" name="text" type="String" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```javascript
{
    // Response
}
```
{% endswagger-response %}

{% swagger-response status="400: Bad Request" description="" %}
```javascript
{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
