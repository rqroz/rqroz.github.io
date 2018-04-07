---
layout: default
title: Digital Image Processing
permalink: "/DIP/"
---

<!-- <link rel="stylesheet" href="{{ "/assets/css/DIP/dipnav.css" | relative_url }}"> -->
<style>
.row {
    margin-left: 0;
    margin-right: 0;
}

#sidebar-wrapper {
  height: 100%;
  position: fixed;
  left: 0;
  right: 0;
  width: calc(25% - 15px);
  overflow-y: auto;
  background: #222 !important;
}

#page-content-wrapper {
  width: 100%;
  position: absolute;
  padding: 15px;
}
/* Sidebar Styles */

.sidebar-nav {
  top: 0;
  margin: 0;
  padding: 0;
  list-style: none;
  color: white;
}

.sidebar-nav li {
  text-indent: 20px;
  line-height: 40px;
}

.sidebar-nav li a {
  display: block;
  text-decoration: none;
  color: #828282;
}

.sidebar-nav li a:hover {
  text-decoration: none;
  color: #fff;
  background: rgba(130, 130, 130, 0.2);
}

.sidebar-nav li a:active, .sidebar-nav li a:focus {
  text-decoration: none;
}

@media (max-width: 992px){
  #sidebar-wrapper {
    display: none;
  }
}
</style>

<div class="row">
  {% include DIP/navigator.html %}
  <div class="col-md-9 col-md-offset-3">
    {% include DIP/content.html %}
  </div>
</div>
