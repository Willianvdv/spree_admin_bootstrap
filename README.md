Spree Admin Bootstrap
=====================

Spree 1-3-stable admin Bootstrap theme.

Installation
-----------
- Add to Gemfile:
```
gem 'spree_admin_bootstrap', :github => 'oxpeck/spree_admin_bootstrap'
```

- Run:
```
$ bundle exec rails g spree_admin_bootstrap:install
```

Features
-----------
- Full rework of the Spree Admin with Twitter Bootstrap
- Added features to the admin
- Fixed/tuned some Javascript work in app\views\spree\admin\prototypes\select.js.erb (only select text types)
- Fixed bug which didn't show states on new order in app\views\spree\admin\shared\_address_form.html.erb, added Javascript for this fix (same file)

Screenshots
-----------

### Products
![image](screens/screen1.png)

### Edit product
![image](screens/screen2.png)


### Edit product images
![image](screens/screen4.png)

### New order
![image](screens/screen3.png)


### General settings
![image](screens/screen5.png)
