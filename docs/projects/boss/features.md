<link rel="stylesheet" href="{{ '/assets/css/stylesNew.css' | prepend: site.baseurl }}">

## General Features

<div class="features-grid">
  {% for feature in site.data.features_general %}
  <div class="feature-item">
    <img src="{{ feature.image }}" alt="{{ feature.title }} Image">
    <h3>{{ feature.title }}</h3>
    <ul>
      {% for item in feature.description %}
      <li>{{ item }}</li>
      {% endfor %}
    </ul>
  </div>
  {% endfor %}
</div>

## Slice Features

<div class="features-grid">
  {% for feature in site.data.features_slicer %}
  <div class="feature-item">
    <img src="{{ feature.image }}" alt="{{ feature.title }} Image">
    <h3>{{ feature.title }}</h3>
    <ul>
      {% for item in feature.description %}
      <li>{{ item }}</li>
      {% endfor %}
    </ul>
  </div>
  {% endfor %}
</div>
