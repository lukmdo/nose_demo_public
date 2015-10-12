# nose_demo
Demo tests using Selenium and nose

### Run simple non-parallel test

```
nosetests --process-timeout=120 ./tests/web_driver_test1.py
```

### Run paralell tests

```
nosetests --processes=4 --process-timeout=120 ./tests/web_driver_test2.py
```
