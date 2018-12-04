### discovery Rules:
* **test_** file.py
* **test_** fun()

assert **verify-true**  - to throw an error


### running tests

command | description
--------|------------
`python -m -v test_file.py ` |  run with verbose
`pytest --collect-only ` |  available tests
`-rxs  ` |  why skipped?
`-k **fun** `| runs only tests with **fun** in name
`--capture=no ` | directs prints to stdout
`-m **xyz**  ` | runs only tests marked with **xyz**
`-m "not **xyz**" ` | runs only tests _not marked_ with **xyz**



### decorators
command | description
--------|------------
`@pytest.mark.**xyz**`   |  marks a test with **xyz**
`@pytest.mark.**xyz**`   |  marks a test with **xyz**
`@pytest.mark.**xyz**`   |  marks a test with **xyz**






# Timestamp
    import pandas as pd
    pd.Timestamp()
    pd.to_datetime()


![time comversion](https://i.stack.imgur.com/uiXQd.png "timestamp")
