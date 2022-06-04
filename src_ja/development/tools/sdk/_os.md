{% assign id =  include.os | downcase -%}
{% assign channels =  'stable beta' | split: ' ' -%}

<div id="{{id}}" class="tab-pane
  {%- if id == 'windows' %} active {% endif %}"
  role="tabpanel" aria-labelledby="{{id}}-tab" markdown="1">

{% for channel in channels -%}
## {{channel | capitalize }} channel ({{include.os}})

Select from the following scrollable list:

<div class="scrollable-table">
  <table id="downloads-{{id}}-{{channel}}" class="table table-striped">
  <thead><tr><th>Flutter version</th><th>Architecture</th><th>Ref</th><th class="date">Release Date</th><th>Dart version</th></tr></thead>
  <tr class="loading"><td colspan="5">Loading...</td></tr>
  </table>
</div>
{% endfor -%}

</div>
