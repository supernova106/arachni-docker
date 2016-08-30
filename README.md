#Description
- Arachni docker in action

#Usage
```
docker run -it -v $PWD/reports:/home/ubuntu/reports <docker_registry>/arachni:cli_scanner <endpoint> --report-save-path /home/ubuntu/reports/<report_name>.afr
docker run -it -v $PWD/reports:/home/ubuntu/reports <docker_registry>/arachni:cli_reporter /home/ubuntu/reports/<report_name>.afr --reporter=html:outfile=/home/ubuntu/reports/<report_name>.html.zip
```
