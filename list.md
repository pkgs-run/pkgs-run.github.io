{% for image in img %}
    {% if image.path contains 'svg' %}
        <img src="{{ site.baseurl }}/img/{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}
