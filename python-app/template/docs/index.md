# Documents for python-app

This application has two endpoints:
- `/api/v1/info`
- `/api/v1/healthz`

Here you could expand on what each of these endpoints do.

{% if values.use_any %}
${{ values.app_env }}
{% endif %}

# How to access the app?

You can access the app by accessing this URL: `${{ values.app_name }}-${{ values.app_env }}.test.com/api/v1/healthz` 
