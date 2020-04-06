# speedtest
![bla](https://github.com/FellipeBr/speedtest/workflows/Python%20application/badge.svg)

Network Speed Monitor written in Python used to populate grafana dashboard.




### Dependencies
- Python
- InfluxDB
- speedtest-cli

### Crontab
`*/10 * * * * python3 ./speedtest.py`