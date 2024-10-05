---
layout: page
title: "BOSS (In development, not released yet)"
permalink: /projects/breakable-glass-advanced
---

<link rel="stylesheet" href="{{ '/assets/css/stylesNew.css' | prepend: site.baseurl }}">


# Breakable Objects Slicing System

## Summary

Procedural mesh fraction system based on iterative mesh slicing which can be used as a Destruction System or as a
Slicer


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

## Slicer Features

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
