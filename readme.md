# selenium-parallel-tests
Parallel test using selenium server grid
## Download Selenium Server Grid
1. Download jar file from following link https://www.selenium.dev/downloads/
2. Copy to your selected folder and execute following script in your shell
`java -jar selenium-server-standalone-3.141.59.jar`
3. Check it *localhost:4444*

## Install Packages
```
pip install pytest-xdist
pip install pytest-rerunfailures
pip install nose
pip install multiprocess
```

## Execute
Execute, just to start test session
`pytest -s`

## Test
`pytest -n 5`
or
`nosetests --processes=5`1