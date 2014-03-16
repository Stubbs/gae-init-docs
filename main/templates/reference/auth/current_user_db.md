<p>
  Get the <code>User</code> entity model of the authenticated user if there is
  one, otherwise returns <code>None</code>.
  If you want to make sure that this function will return a <code>user_db</code>
  use one of the <a href="#decorator">decorators</a>.
</p>

<p>
  In templates you can get access to this variable through
  <code>&#123;&#123;current_user.user_db&#125;&#125;</code>. So if you would
  like to display the name of the currently signed in user somewhere you would use
  it like: <code>&#123;&#123;current_user.user_db.name&#125;&#125;</code>.
</p>
