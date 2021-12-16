This repository contains [Questioning Authority](https://github.com/LD4P/qa_server) configuration files for Norwegian authority registries.

To start a local QA server:

    docker-compose up

Vocabularies:

ID | Name | Checks
--|--|--
bibbi | Bibbi authorities | http://localhost:3000/check_status?utf8=%E2%9C%93&authority=BIBBI&compare_with=&validation_type=all_checks
noraf | Norwegian authority file | TODO (not available as linked data?)
humord | Humord | TODO
ddc23no | Norwegian WebDewey | TODO
