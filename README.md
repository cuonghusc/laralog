<img src="https://raw.githubusercontent.com/ARCANEDEV/LogViewer/master/_screenshots/1-dashboard.jpg">

#Step 1
```composer require arcanedev/log-viewer```

#Step 2
- Open your ```.env``` file and change the ```LOG_CHANNEL``` value to daily rather than stack.
- Just to make sure it automatically published run the following command – ```php artisan log-viewer:publish```

#Step 3
Navigate to your ```localhost/log-viewer```
