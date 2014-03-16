<p>
  Generates a link that will add (or replace) <code>&property=value</code>
  to the current request or will remove it if it's already there. Optionally
  instead of showing the actual value it is possible to show an icon. The icon
  is more appropriate when filtering by boolean properties.
</p>

<h5>Arguments</h5>
<dl>
  <dt>property</dt>
  <dd>The name of the entity's property.</dd>
  <dt>value</dt>
  <dd>
    The value to be applied to the filter.
  </dd>
  <dt>icon</dt>
  <dd>
    Optional name for the icon instead that will be shown instead of the value.
  </dd>
  <dt>ignore</dt>
  <dd>
    Optional list of arguments that will be ignored and removed from the
    generated request. Sometimes it is needed when in the original request the
    <code>cursor</code> is present and it will be invalid if some of the other
    arguments will have a different value.
  </dd>
</dl>

<div class="gi-callout gi-callout-info">
  <h4>Examples & Demo</h4>
  Check how it is used in
  <a href="https://github.com/gae-init/gae-init/blob/master/main/templates/user/user_list.html">user_list.html</a>
  and play with filters in
  <a href="https://gae-init.appspot.com/user/?order=-modified">User List</a>.
</div>
