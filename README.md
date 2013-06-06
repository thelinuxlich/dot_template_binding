dot_template_binding
====================

A template binding for doT.js + Knockout

How to use:

  <div data-bind="dotTemplate: 'script_id'"></div>
  
  <script id='script_id' type='text/html'>
    {{~it.$data.something_like_an_array :value:index }}
      <span>{{= value }}</span>
    {{~}}
  </script>
