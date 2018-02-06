docker-allure2
==============

# How to use docker-allure2 image

Put the xunit xml file in "allure-report" directory.

```bash
docker run -it --rm -v $(pwd):/allure-report -w /output amitvyasbms/docker-allure2 allure generate /output/allure-report/ -o /output/allure-report/ --clean
```
