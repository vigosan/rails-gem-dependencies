rails-gem-dependencies Cookbook
===============================
Installs packages commonly required by rails gems

Usage
-----
#### rails-gem-dependencies::default

e.g.
Just include `rails-gem-dependencies` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[rails-gem-dependencies]"
  ]
}
```

Contributing
------------
1. Fork it (https://github.com/vigosan/rails-gem-dependencies)
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create a new Pull Request
